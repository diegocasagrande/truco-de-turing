# Testes de performance

**Versão 1.2.0** · commit `8ddde7f-dirty` (com as mudanças ainda não registradas) · 10/11/2026, 23:42 (horário de Brasília)  
Ambiente: Node v22.23.4 · Chromium 153.0.8010.12 · Linux x64 · 2 núcleos

Tempos do motor de regras, dos oponentes, das dicas, da arte e do empacotamento no Node; tempo de carregamento, quadros por segundo, memória e tempo de resposta no navegador. Cada medida tem um limite; acima dele, o teste falha.

| Testes | Aprovados | Reprovados | Pulados | Duração |
|---:|---:|---:|---:|---:|
| 12 | 12 | 0 | 0 | 24,1 s |

Resultado em formato JUnit (para ferramentas de CI): [`resultado.junit.xml`](resultado.junit.xml).

## Medidas

| | Grupo | Medida | Valor | Limite | Observação |
|---|---|---|---:|---:|---|
| ✅ | Navegador | Tempo até o menu (WebGL) | 782 ms | ≤ 15.000 |  |
| ✅ | Navegador | Tempo até a mesa pronta (WebGL) | 6.223 ms | ≤ 15.000 |  |
| ✅ | Navegador | Quadros por segundo na mesa (WebGL) | 4,98 qps | ≥ 3,00 | WebGL por software (sem GPU no teste) |
| ✅ | Navegador | Memória JavaScript em uso (WebGL) | 32,95 MB | ≤ 400 |  |
| ✅ | Navegador | Resposta a uma jogada (WebGL) | 38,40 ms | ≤ 300 |  |
| ✅ | Navegador | Tempo até o menu (Canvas) | 290 ms | ≤ 15.000 |  |
| ✅ | Navegador | Tempo até a mesa pronta (Canvas) | 868 ms | ≤ 15.000 |  |
| ✅ | Navegador | Quadros por segundo na mesa (Canvas) | 60,45 qps | ≥ 20,00 | Chromium sem GPU |
| ✅ | Navegador | Memória JavaScript em uso (Canvas) | 22,74 MB | ≤ 400 |  |
| ✅ | Navegador | Resposta a uma jogada (Canvas) | 34,40 ms | ≤ 300 |  |
| ✅ | Node | pontuarRede | 10,26 µs por chamada | ≤ 200 |  |
| ✅ | Node | jogadasLegais | 15,02 µs por chamada | ≤ 300 |  |
| ✅ | Node | Mãos completas simuladas | 1.418 mãos/s | ≥ 150 |  |
| ✅ | Node | copiarMao | 67,65 µs por chamada | ≤ 300 |  |
| ✅ | Node | determinizar | 99,99 µs por chamada | ≤ 600 |  |
| ✅ | Node | Decisão gulosa | 0,21 ms | ≤ 60,00 | p95 0.3 ms |
| ✅ | Node | Simulações por decisão (Monte Carlo) | 240 partidas | ≥ 80,00 |  |
| ✅ | Node | Decisão do Monte Carlo | 45,29 ms | ≤ 1.500 | p95 46.7 ms |
| ✅ | Node | chanceDeVitoria (40 simulações) | 11,63 ms | ≤ 150 |  |
| ✅ | Node | escolherDicaDeJogo | 11,71 µs por chamada | ≤ 500 |  |
| ✅ | Node | Carta completa (densidade 2) | 14,84 ms | ≤ 120 |  |
| ✅ | Node | Carta da mesa (densidade 1,25) | 6,75 ms | ≤ 60,00 |  |
| ✅ | Node | Verso (densidade 2) | 0,38 ms | ≤ 120 |  |
| ✅ | Node | Fundo da mesa 1280×720 | 17,24 ms | ≤ 400 |  |
| ✅ | Node | Empacotamento (esbuild) | 200 ms | ≤ 8.000 |  |
| ✅ | Node | Tamanho do arquivo único | 593 KB | ≤ 700 |  |

Todas as medidas em [`medidas.json`](medidas.json). O Chromium dos testes não tem placa de vídeo: o WebGL é desenhado por software, por isso os quadros por segundo em WebGL ficam muito abaixo do que um aparelho de verdade alcança; a medida em Canvas mostra que a lógica do jogo não é o gargalo.

## `testes/performance/navegador.test.js`

| | Teste | Grupo | Duração |
|---|---|---|---:|
| ✅ | WebGL (padrão) | jogo no navegador | 13,5 s |
| ✅ | Canvas 2D | jogo no navegador | 5,7 s |

## `testes/performance/nucleo-e-arte.test.js`

| | Teste | Grupo | Duração |
|---|---|---|---:|
| ✅ | pontuar uma rede no meio da mão | motor de regras | 64 ms |
| ✅ | listar as jogadas legais | motor de regras | 80 ms |
| ✅ | mãos inteiras por segundo (jogadas aleatórias) | motor de regras | 1,5 s |
| ✅ | copiar e determinizar uma mão | motor de regras | 341 ms |
| ✅ | decisão do Gradiente Guloso | oponentes e dicas | 13 ms |
| ✅ | decisão do Mestre Monte Carlo (40 partidas simuladas por jogada) | oponentes e dicas | 363 ms |
| ✅ | chance de vitória com 40 simulações (dica do truco) | oponentes e dicas | 141 ms |
| ✅ | escolher a dica de jogo | oponentes e dicas | 28 ms |
| ✅ | desenhar cartas, versos e a mesa | arte procedural e empacotamento | 498 ms |
| ✅ | tempo de empacotamento e tamanho do arquivo único | arte procedural e empacotamento | 215 ms |

