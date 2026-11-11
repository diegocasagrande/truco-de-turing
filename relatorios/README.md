# Relatórios de testes

**Versão 1.2.0** · commit `8ddde7f-dirty` (com as mudanças ainda não registradas) · 10/11/2026, 23:42 (horário de Brasília)  
Ambiente: Node v22.23.4 · Chromium 153.0.8010.12 · Linux x64 · 2 núcleos

Gerado por `npm run relatorios` (`ferramentas/relatorios.js`).

## Resultado

| Suíte | Testes | Aprovados | Reprovados | Duração | Relatório |
|---|---:|---:|---:|---:|---|
| ✅ Testes de unidade | 311 | 311 | 0 | 57,2 s | [unidade/](unidade/README.md) |
| ✅ Testes de interface | 23 | 23 | 0 | 1240,3 s | [interface/](interface/README.md) |
| ✅ Testes de performance | 12 | 12 | 0 | 24,1 s | [performance/](performance/README.md) |

## Cobertura

| Linhas | Instruções | Ramos | Funções (todas) | Funções e métodos com nome |
|---:|---:|---:|---:|---:|
| 98,0% | 98,0% | 91,8% | 95,1% | 780 de 820 |

Detalhe por arquivo e por função em [cobertura/](cobertura/README.md).

## Destaques de performance

| Medida | Valor | Limite |
|---|---:|---:|
| Tempo até o menu (WebGL) | 782 ms | ≤ 15.000 |
| Quadros por segundo na mesa (Canvas) | 60,45 qps | ≥ 20,00 |
| Mãos completas simuladas | 1.418 mãos/s | ≥ 150 |
| Decisão gulosa | 0,21 ms | ≤ 60,00 |
| Simulações por decisão (Monte Carlo) | 240 partidas | ≥ 80,00 |
| Tamanho do arquivo único | 593 KB | ≤ 700 |

Todas as medidas em [performance/](performance/README.md).

## Como rodar

```bash
npm run testar              # unidade
npm run testar:interface    # interface (Chromium)
npm run testar:performance  # performance
npm run relatorios          # tudo + relatórios e cobertura
```
