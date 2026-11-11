# Cobertura dos testes

**Versão 1.2.0** · commit `8ddde7f-dirty` (com as mudanças ainda não registradas) · 10/11/2026, 23:42 (horário de Brasília)  
Ambiente: Node v22.23.4 · Chromium 153.0.8010.12 · Linux x64 · 2 núcleos

Cobertura medida pelo V8 nos testes de unidade (Node) e nos testes de interface (Chromium, com os módulos de `src/` servidos sem empacotar), juntada pelo c8. Ficam fora da conta só `ferramentas/relatorios.js` (o gerador destes relatórios, que é quem roda os testes) e `src/recursos/` (a foto embutida, sem código).

| | Linhas | Instruções | Ramos | Funções |
|---|---:|---:|---:|---:|
| **Total** | 98,0% | 98,0% | 91,8% | 95,1% |

**Funções e métodos com nome executados pelos testes: 780 de 820 (95,1%).** A coluna "Funções" acima conta também as funções anônimas (callbacks de eventos, de animações e de `map`/`filter`).

## Por arquivo

| Arquivo | Linhas | Ramos | Funções |
|---|---:|---:|---:|
| `ferramentas/documentar.js` | 100,0% | 88,6% | 100,0% |
| `ferramentas/empacotar.js` | 100,0% | 71,4% | 100,0% |
| `ferramentas/simular.js` | 94,3% | 80,0% | 100,0% |
| `ferramentas/versionar.js` | 100,0% | 87,0% | 100,0% |
| `src/aplicacao.js` | 100,0% | 87,8% | 100,0% |
| `src/arte/avatares.js` | 100,0% | 98,4% | 100,0% |
| `src/arte/botoes.js` | 100,0% | 76,5% | 100,0% |
| `src/arte/cartas.js` | 100,0% | 95,2% | 100,0% |
| `src/arte/cartasDeTerreno.js` | 100,0% | 94,7% | 100,0% |
| `src/arte/cenarios.js` | 100,0% | 98,0% | 100,0% |
| `src/arte/emblemas.js` | 100,0% | 100,0% | 100,0% |
| `src/arte/figuras.js` | 100,0% | 91,9% | 100,0% |
| `src/arte/icones.js` | 100,0% | 100,0% | 100,0% |
| `src/arte/mesas.js` | 100,0% | 94,7% | 100,0% |
| `src/arte/moldura.js` | 100,0% | 100,0% | 100,0% |
| `src/arte/paleta.js` | 100,0% | 100,0% | 100,0% |
| `src/arte/pincel.js` | 100,0% | 84,8% | 100,0% |
| `src/arte/retrato.js` | 100,0% | 88,2% | 100,0% |
| `src/arte/versos.js` | 100,0% | 96,0% | 100,0% |
| `src/cenas/CenaCarregamento.js` | 100,0% | 86,7% | 100,0% |
| `src/cenas/CenaMenu.js` | 100,0% | 90,9% | 100,0% |
| `src/cenas/mesa/CenaMesa.js` | 100,0% | 100,0% | 100,0% |
| `src/cenas/mesa/ambiente.js` | 100,0% | 78,1% | 100,0% |
| `src/cenas/mesa/cenario.js` | 100,0% | 95,0% | 82,8% |
| `src/cenas/mesa/desenho.js` | 99,2% | 94,4% | 100,0% |
| `src/cenas/mesa/dicas.js` | 98,8% | 58,3% | 100,0% |
| `src/cenas/mesa/efeitos.js` | 99,0% | 92,2% | 100,0% |
| `src/cenas/mesa/entrada.js` | 91,8% | 75,0% | 100,0% |
| `src/cenas/mesa/layout.js` | 100,0% | 96,7% | 90,0% |
| `src/cenas/mesa/online.js` | 95,3% | 85,5% | 92,8% |
| `src/cenas/mesa/paineis.js` | 98,6% | 72,0% | 100,0% |
| `src/cenas/mesa/resultado.js` | 100,0% | 85,1% | 100,0% |
| `src/cenas/mesa/truco.js` | 100,0% | 92,5% | 100,0% |
| `src/cenas/mesa/turnos.js` | 93,4% | 94,2% | 100,0% |
| `src/cenas/recursos.js` | 100,0% | 90,9% | 100,0% |
| `src/configuracao.js` | 100,0% | 100,0% | 100,0% |
| `src/conteudo/avatares.js` | 100,0% | 92,3% | 100,0% |
| `src/conteudo/conquistas.js` | 100,0% | 100,0% | 100,0% |
| `src/conteudo/dicasDeJogo.js` | 100,0% | 100,0% | 100,0% |
| `src/conteudo/figurasDaBiblioteca.js` | 100,0% | 100,0% | 100,0% |
| `src/conteudo/grimorio.js` | 100,0% | 100,0% | 100,0% |
| `src/conteudo/modExemplo.js` | 100,0% | 100,0% | 100,0% |
| `src/conteudo/progresso.js` | 100,0% | 94,7% | 100,0% |
| `src/conteudo/textos.js` | 100,0% | 100,0% | 100,0% |
| `src/interface/menu.js` | 100,0% | 93,6% | 100,0% |
| `src/interface/musica.js` | 98,7% | 99,0% | 100,0% |
| `src/interface/paineis.js` | 100,0% | 100,0% | 100,0% |
| `src/interface/som.js` | 100,0% | 93,5% | 100,0% |
| `src/interface/telas/ajudaDasAcoes.js` | 100,0% | 77,8% | 100,0% |
| `src/interface/telas/avatares.js` | 100,0% | 90,9% | 100,0% |
| `src/interface/telas/conquistas.js` | 100,0% | 84,6% | 100,0% |
| `src/interface/telas/grimorio.js` | 100,0% | 88,9% | 100,0% |
| `src/interface/telas/mods.js` | 98,5% | 80,0% | 100,0% |
| `src/interface/telas/online.js` | 84,3% | 65,7% | 81,8% |
| `src/interface/telas/regras.js` | 100,0% | 90,3% | 83,3% |
| `src/interface/telas/revisao.js` | 100,0% | 96,5% | 100,0% |
| `src/interface/telas/sobre.js` | 100,0% | 100,0% | 100,0% |
| `src/motor/bot.js` | 90,4% | 94,8% | 94,1% |
| `src/motor/engine.js` | 100,0% | 100,0% | 100,0% |
| `src/motor/engine/actions.js` | 100,0% | 88,7% | 100,0% |
| `src/motor/engine/core.js` | 94,6% | 89,0% | 91,2% |
| `src/motor/engine/decks.js` | 100,0% | 100,0% | 100,0% |
| `src/motor/engine/index.js` | 100,0% | 83,3% | 100,0% |
| `src/motor/engine/registry.js` | 100,0% | 73,3% | 80,0% |
| `src/motor/engine/terrains.js` | 100,0% | 100,0% | 81,8% |
| `src/motor/engine/util.js` | 100,0% | 93,1% | 78,6% |
| `src/motor/sim.js` | 49,3% | 77,8% | 40,0% |
| `src/nucleo/aleatorio.js` | 100,0% | 100,0% | 100,0% |
| `src/nucleo/baralhos.js` | 100,0% | 100,0% | 100,0% |
| `src/nucleo/cartas.js` | 100,0% | 100,0% | 100,0% |
| `src/nucleo/oponentes/comum.js` | 100,0% | 100,0% | 100,0% |
| `src/nucleo/oponentes/estrategias.js` | 100,0% | 100,0% | 100,0% |
| `src/nucleo/oponentes/index.js` | 100,0% | 92,3% | 100,0% |
| `src/nucleo/partida.js` | 99,8% | 96,3% | 97,0% |
| `src/nucleo/pontuacao.js` | 100,0% | 100,0% | 100,0% |
| `src/nucleo/rede.js` | 100,0% | 100,0% | 100,0% |
| `src/nucleo/terrenos.js` | 100,0% | 100,0% | 100,0% |
| `src/nucleo/traducao.js` | 100,0% | 85,0% | 100,0% |
| `src/nucleo/truco.js` | 100,0% | 100,0% | 100,0% |
| `src/online/configuracao.js` | 100,0% | 100,0% | 100,0% |
| `src/online/contas.js` | 90,2% | 68,8% | 50,0% |
| `src/online/firebase.js` | 48,5% | 100,0% | 10,0% |
| `src/online/sala.js` | 100,0% | 92,0% | 93,3% |
| `src/online/transportes.js` | 100,0% | 95,7% | 92,3% |
| `src/principal.js` | 100,0% | 85,7% | 100,0% |
| `src/versao.js` | 100,0% | 100,0% | 100,0% |

## Funções e métodos

Cada função ou método com nome e quantas vezes foi executado durante os testes.

### `ferramentas/documentar.js`

✅ `arquivosJs` (linha 16) — 14 execuções  
✅ `limparComentario` (linha 25) — 657 execuções  
✅ `lerModulo` (linha 37) — 88 execuções

### `ferramentas/empacotar.js`

✅ `ler` (linha 17) — 4 execuções  
✅ `trecho` (linha 38) — 4 execuções

### `ferramentas/simular.js`

✅ `media` (linha 48) — 2 execuções

### `ferramentas/versionar.js`

✅ `caminho` (linha 30) — 28 execuções  
✅ `lerArgumentos` (linha 33) — 4 execuções  
✅ `tipoDeMudanca` (linha 48) — 11 execuções  
✅ `proximaVersao` (linha 56) — 8 execuções  
✅ `gravarModuloDeVersao` (linha 64) — 3 execuções  
✅ `gravarNoReadme` (linha 75) — 3 execuções  
✅ `gravarNoHistorico` (linha 85) — 3 execuções

### `src/aplicacao.js`

✅ `normalizarOpcoes` (linha 28) — 119 execuções  
✅ `iniciar` (linha 52) — 26 execuções  
✅ `salvar` (linha 60) — 101 execuções  
✅ `salvarOpcoes` (linha 63) — 30 execuções  
✅ `alternarSom` (linha 66) — 3 execuções  
✅ `alternarMusica` (linha 76) — 4 execuções  
✅ `jogar` (linha 84) — 24 execuções  
✅ `irParaMenu` (linha 93) — 5 execuções  
✅ `modoImersivo` (linha 106) — 25 execuções  
✅ `registrarMao` (linha 123) — 16 execuções  
✅ `marcarVerbeteLido` (linha 151) — 40 execuções

### `src/arte/avatares.js`

✅ `desenharAvatar` (linha 17) — 356 execuções  
✅ `curve` (linha 31) — 2.730 execuções  
✅ `olho` (linha 168) — 112 execuções  
✅ `gato` (linha 178) — 28 execuções  
✅ `robo` (linha 194) — 28 execuções  
✅ `coruja` (linha 211) — 28 execuções  
✅ `monge` (linha 224) — 28 execuções  
✅ `nobre` (linha 241) — 28 execuções  
✅ `decifrador` (linha 257) — 28 execuções  
✅ `cosmico` (linha 271) — 28 execuções

### `src/arte/botoes.js`

✅ `desenharFaisca` (linha 10) — 85 execuções  
✅ `desenharBotao` (linha 25) — 155 execuções

### `src/arte/cartas.js`

✅ `dadosDaCarta` (linha 22) — 1.699 execuções  
✅ `simboloDeColecao` (linha 54) — 775 execuções  
✅ `ilustracaoDaCarta` (linha 63) — 659 execuções  
✅ `posicoesDosNaipes` (linha 114) — 840 execuções  
✅ `fileira` (linha 115) — 13.440 execuções  
✅ `desenharCartaCompleta` (linha 132) — 659 execuções  
✅ `desenharCartaDaMesa` (linha 203) — 1.034 execuções  
✅ `indice` (linha 265) — 2.068 execuções

### `src/arte/cartasDeTerreno.js`

✅ `desenharCartaDeTerreno` (linha 16) — 112 execuções

### `src/arte/cenarios.js`

✅ `perfilDeSerra` (linha 11) — 1.362 execuções  
✅ `sub` (linha 14) — 172.974 execuções  
✅ `montanhas` (linha 23) — 447 execuções  
✅ `estrelas` (linha 40) — 495 execuções  
✅ `constelacao` (linha 48) — 692 execuções  
✅ `vinheta` (linha 70) — 1.814 execuções  
✅ `raios` (linha 75) — 453 execuções  
✅ `cenarioDoNaipe` (linha 89) — 1.701 execuções

### `src/arte/emblemas.js`

✅ `desenharEmblema` (linha 7) — 5.151 execuções

### `src/arte/figuras.js`

✅ `coroa` (linha 18) — 284 execuções  
✅ `desenharFigura` (linha 41) — 405 execuções

### `src/arte/icones.js`

✅ `svg` (linha 8) — 1.276 execuções  
✅ `gato` (linha 12) — 87 execuções

### `src/arte/mesas.js`

✅ `desenharFeltro` (linha 12) — 52 execuções  
✅ `vinhetaDaMesa` (linha 36) — 26 execuções  
✅ `fibras` (linha 41) — 19 execuções  
✅ `mesaMontanha` (linha 51) — 6 execuções  
✅ `vitoriaRegia` (linha 97) — 910 execuções  
✅ `mesaPantano` (linha 111) — 13 execuções  
✅ `rosaDosVentos` (linha 145) — 7 execuções  
✅ `mesaOceano` (linha 161) — 7 execuções  
✅ `desenharMesa` (linha 186) — 77 execuções

### `src/arte/moldura.js`

✅ `corpoDaMoldura` (linha 10) — 1.807 execuções  
✅ `placa` (linha 41) — 2.205 execuções  
✅ `gema` (linha 55) — 2.356 execuções

### `src/arte/pincel.js`

✅ `criarTela` (linha 9) — 2.676 execuções  
✅ `caminhoArredondado` (linha 19) — 20.376 execuções  
✅ `hashDoTexto` (linha 30) — 2.505 execuções  
✅ `geradorComSemente` (linha 36) — 2.563 execuções  
✅ `degradeLinear` (linha 45) — 28.566 execuções  
✅ `degradeRadial` (linha 51) — 31.029 execuções  
✅ `escreverComQuebra` (linha 57) — 1.431 execuções  
✅ `ajustarFonte` (linha 71) — 1.684 execuções  
✅ `granulado` (linha 75) — 3.811 execuções  
✅ `escovado` (linha 83) — 1.808 execuções  
✅ `sombraSuave` (linha 92) — 11.231 execuções  
✅ `semSombra` (linha 97) — 17.717 execuções  
✅ `brilho` (linha 99) — 20.945 execuções  
✅ `comAlfa` (linha 104) — 85.097 execuções  
✅ `tonalizar` (linha 109) — 15.322 execuções

### `src/arte/retrato.js`

✅ `caminhoArredondado` (linha 6) — 4 execuções  
✅ `arcoGotico` (linha 11) — 16 execuções  
✅ `dourado` (linha 21) — 4 execuções  
✅ `desenharRetratoEmMoldura` (linha 35) — 4 execuções  
✅ `img.onload` (linha 42) — 4 execuções

### `src/arte/versos.js`

✅ `molduraDourada` (linha 14) — 125 execuções  
✅ `legenda` (linha 27) — 141 execuções  
✅ `versoClassico` (linha 34) — 105 execuções  
✅ `versoTruco` (linha 76) — 10 execuções  
✅ `versoFraternidade` (linha 121) — 7 execuções  
✅ `simboloYinYang` (linha 161) — 8 execuções  
✅ `versoYinYang` (linha 173) — 8 execuções  
✅ `bx` (linha 174) — 2.552 execuções  
✅ `versoPowerBI` (linha 207) — 19 execuções  
✅ `versoNobreza` (linha 272) — 5 execuções  
✅ `florDeLis` (linha 300) — 700 execuções  
✅ `coroa` (linha 309) — 5 execuções  
✅ `versoBackprop` (linha 324) — 5 execuções  
✅ `no` (linha 339) — 20 execuções  
✅ `seta` (linha 345) — 25 execuções  
✅ `desenharVerso` (linha 378) — 159 execuções

### `src/cenas/CenaCarregamento.js`

✅ `CenaCarregamento` (linha 23) — 25 execuções  
✅ `create` (linha 25) — 25 execuções  
✅ `gerarTexturas` (linha 38) — 25 execuções  
✅ `adicionar` (linha 39) — 425 execuções

### `src/cenas/CenaMenu.js`

✅ `CenaMenu` (linha 19) — 25 execuções  
✅ `create` (linha 21) — 29 execuções  
✅ `tocarMusicaDoMenu` (linha 36) — 29 execuções  
✅ `aoTocar` (linha 39) — 24 execuções  
✅ `espalharCartas` (linha 50) — 29 execuções  
✅ `update` (linha 61) — 1.107 execuções

### `src/cenas/mesa/CenaMesa.js`

✅ `CenaMesa` (linha 52) — 25 execuções  
✅ `create` (linha 55) — 23 execuções  
✅ `comecar` (linha 86) — 23 execuções  
✅ `update` (linha 92) — 4.427 execuções

### `src/cenas/mesa/ambiente.js`

✅ `reduzirMovimento` (linha 17) — 23 execuções  
✅ `criarAmbiente` (linha 23) — 23 execuções  
✅ `criarTexturasDoAmbiente` (linha 31) — 23 execuções  
✅ `luzDoTerreno` (linha 50) — 23 execuções  
✅ `ambienteNeutro` (linha 56) — 16 execuções  
✅ `ambienteMontanha` (linha 68) — 2 execuções  
✅ `onComplete` (linha 78) — 6 execuções  
✅ `ambientePantano` (linha 89) — 3 execuções  
✅ `ambienteOceano` (linha 110) — 2 execuções  
✅ `nuvemEmLaco` (linha 129) — 6 execuções  
✅ `desenharOndas` (linha 136) — 288 execuções  
✅ `atualizarAmbiente` (linha 152) — 4.427 execuções

### `src/cenas/mesa/cenario.js`

✅ `desenharCenarioFixo` (linha 20) — 23 execuções  
✅ `criarBotao` (linha 61) — 276 execuções  
✅ `textura` (linha 63) — 1.432 execuções  
✅ `pintar` (linha 82) — 1.156 execuções  
✅ `temDica` (linha 83) — 41 execuções  
✅ `mostrarDica` (linha 84) — 2 execuções  
✅ `botao.definirRotulo` (linha 108) — 2.832 execuções  
✅ `botao.habilitar` (linha 109) — 11.349 execuções  
✅ `criarPaineis` (linha 121) — 23 execuções  
✅ `criarTexto` (linha 130) — 738 execuções  
✅ `criarPainelEsquerdo` (linha 135) — 23 execuções  
✅ `criarPilha` (linha 143) — 46 execuções  
✅ `criarPlacar` (linha 192) — 23 execuções  
✅ `criarBlocoCompacto` (linha 237) — 12 execuções  
✅ `criarBotoesDeAcao` (linha 261) — 23 execuções  
✅ `p.truco.criarBotao.variante` (linha 265) — 3 execuções  
✅ `p.botaoAjuda.criarBotao.variante` (linha 266) — 1 execução  
❌ `explicar` (linha 268) — 0 execuções  
✅ `coluna` (linha 270) — 184 execuções  
✅ `tunagem` (linha 272) — 1 execução  
❌ `overfit` (linha 272) — 0 execuções  
❌ `earlystop` (linha 273) — 0 execuções  
❌ `stackoverflow` (linha 273) — 0 execuções  
✅ `dropout` (linha 274) — 3 execuções  
✅ `transfer` (linha 274) — 1 execução  
✅ `passar` (linha 274) — 1 execução  
❌ `limpar` (linha 274) — 0 execuções  
✅ `explicar` (linha 282) — 7 execuções  
✅ `atualizarChaves` (linha 294) — 34 execuções

### `src/cenas/mesa/desenho.js`

✅ `inspecionar` (linha 27) — 366 execuções  
✅ `mostrarDica` (linha 33) — 1.471 execuções  
✅ `redesenhar` (linha 38) — 1.261 execuções  
✅ `desenharMaos` (linha 76) — 1.261 execuções  
✅ `posicaoDaMaoDeCima` (linha 129) — 2.114 execuções  
✅ `notaDaCartaDaMao` (linha 136) — 1 execução  
✅ `atualizarPaineis` (linha 144) — 1.261 execuções  
✅ `textoComDicaDeJogo` (linha 164) — 1.347 execuções  
✅ `atualizarPilha` (linha 174) — 2.522 execuções  
✅ `atualizarBlocoDoJogador` (linha 195) — 3.353 execuções  
✅ `textoDaSituacao` (linha 232) — 3.353 execuções  
✅ `atualizarBlocoCompacto` (linha 239) — 1.625 execuções  
✅ `estaNaVez` (linha 257) — 11.147 execuções  
✅ `desenharDestaqueDaVez` (linha 262) — 4.030 execuções  
✅ `atualizarBotoes` (linha 279) — 1.261 execuções  
✅ `atualizarRegistro` (linha 295) — 1.261 execuções  
✅ `desenharCurva` (linha 304) — 1.261 execuções  
✅ `textoDaDica` (linha 332) — 1.347 execuções  
✅ `alvosDaAcao` (linha 367) — 3.159 execuções  
✅ `dropoutPossivel` (linha 376) — 789 execuções  
✅ `valorSelecionado` (linha 386) — 446 execuções  
✅ `calcularAlvos` (linha 392) — 1.261 execuções  
✅ `desenharConexoesEAlvos` (linha 427) — 4.030 execuções

### `src/cenas/mesa/dicas.js`

✅ `conceitoCurto` (linha 32) — 8 execuções  
✅ `alternarDicas` (linha 39) — 2 execuções  
✅ `acao` (linha 56) — 1 execução  
✅ `darDicaDoTurno` (linha 69) — 149 execuções  
✅ `textoDaDicaDeJogo` (linha 81) — 1.347 execuções  
✅ `mostrarDicaDoBotao` (linha 89) — 2 execuções  
✅ `esconderDicaDoBotao` (linha 99) — 22 execuções  
✅ `conteudoDaDica` (linha 105) — 6 execuções  
✅ `dicaDaRespostaAoTruco` (linha 164) — 11 execuções

### `src/cenas/mesa/efeitos.js`

✅ `corCss` (linha 25) — 157 execuções  
✅ `posicaoDoNeuronio` (linha 29) — 310 execuções  
✅ `origemDasCartas` (linha 35) — 52 execuções  
✅ `animarEventos` (linha 47) — 331 execuções  
✅ `animar_ativacao` (linha 59) — 249 execuções  
✅ `animar_tunagem` (linha 77) — 17 execuções  
✅ `animar_ataque` (linha 93) — 33 execuções  
✅ `onComplete` (linha 108) — 33 execuções  
✅ `animar_overfit` (linha 126) — 26 execuções  
✅ `animar_earlystop` (linha 127) — 5 execuções  
✅ `animar_stackoverflow` (linha 128) — 2 execuções  
✅ `animar_dropout` (linha 131) — 11 execuções  
✅ `animar_transfer` (linha 143) — 1 execução  
✅ `animar_completa` (linha 152) — 27 execuções  
✅ `animar_vento` (linha 159) — 10 execuções  
✅ `animar_powerbi` (linha 166) — 3 execuções  
✅ `animar_travada` (linha 172) — 3 execuções  
✅ `animar_passe` (linha 179) — 2 execuções  
✅ `animar_inicio` (linha 186) — 12 execuções  
✅ `onComplete` (linha 202) — 30 execuções  
✅ `verificarVanishing` (linha 209) — 331 execuções  
✅ `voarCarta` (linha 227) — 57 execuções  
✅ `onComplete` (linha 232) — 57 execuções  
✅ `explodir` (linha 237) — 124 execuções  
✅ `textoFlutuante` (linha 249) — 318 execuções  
✅ `onComplete` (linha 251) — 316 execuções  
✅ `faixa` (linha 255) — 94 execuções  
✅ `onComplete` (linha 272) — 94 execuções  
✅ `falar` (linha 281) — 54 execuções  
✅ `onComplete` (linha 296) — 53 execuções  
✅ `impactoDoTruco` (linha 303) — 16 execuções  
✅ `avisarVerbete` (linha 312) — 1.052 execuções

### `src/cenas/mesa/entrada.js`

✅ `realcarNeuronio` (linha 25) — 197 execuções  
✅ `aoPassarNoNeuronio` (linha 37) — 197 execuções  
✅ `executarAcao` (linha 73) — 1 execução  
✅ `acionarDropout` (linha 89) — 3 execuções  
✅ `explicarAcao` (linha 103) — 7 execuções  
✅ `aoClicarNoNeuronio` (linha 147) — 136 execuções  
✅ `aoClicarNaCarta` (linha 169) — 236 execuções  
✅ `cancelarSelecao` (linha 204) — 236 execuções  
✅ `alternarDropout` (linha 213) — 3 execuções  
✅ `fazerTransfer` (linha 220) — 1 execução  
✅ `passarAVez` (linha 228) — 2 execuções  
✅ `abrirRegrasDaMesa` (linha 236) — 5 execuções  
✅ `regras` (linha 249) — 1 execução  
✅ `ajuda` (linha 250) — 1 execução  
✅ `grimorio` (linha 251) — 1 execução  
✅ `dicas` (linha 252) — 2 execuções  
✅ `abrirAjudaDaMesa` (linha 262) — 2 execuções  
✅ `abrirMenuDaMesa` (linha 270) — 4 execuções  
✅ `q` (linha 279) — 12 execuções  
✅ `perguntarSeVoltaAoMenu` (linha 287) — 2 execuções  
✅ `acao` (linha 290) — 1 execução

### `src/cenas/mesa/layout.js`

✅ `blocosDoPlacar` (linha 65) — 27 execuções  
✅ `definirMesa` (linha 90) — 41 execuções  
✅ `geometria` (linha 103) — 23 execuções  
❌ `totalDeCamadasDaMesa` (linha 106) — 0 execuções  
✅ `colunaX` (linha 109) — 53.938 execuções  
✅ `linhaY` (linha 111) — 54.010 execuções  
✅ `cartaDaMesa` (linha 114) — 51.840 execuções  
✅ `ajustarCartaDaMesa` (linha 130) — 46.194 execuções  
✅ `ajustarLinha` (linha 141) — 23.272 execuções  
✅ `ajustarBloco` (linha 157) — 3.125 execuções

### `src/cenas/mesa/online.js`

✅ `prepararOnline` (linha 19) — 23 execuções  
✅ `aoReceber` (linha 27) — 57 execuções  
❌ `aoAvisar` (linha 28) — 0 execuções  
✅ `cadeiraOnline` (linha 34) — 97 execuções  
✅ `souAnfitriaoOnline` (linha 37) — 26 execuções  
✅ `chaveDaMao` (linha 40) — 100 execuções  
✅ `sementeDaMao` (linha 43) — 3 execuções  
✅ `jogadoresOnline` (linha 46) — 3 execuções  
✅ `enviarOnline` (linha 58) — 44 execuções  
✅ `esperarRede` (linha 65) — 59 execuções  
✅ `processarFilaOnline` (linha 72) — 116 execuções  
✅ `aplicarSubstituicao` (linha 93) — 2 execuções  
✅ `avancarNoInicioOnline` (linha 115) — 6 execuções  
✅ `avancarOnline` (linha 137) — 48 execuções

### `src/cenas/mesa/paineis.js`

✅ `cabecalho` (linha 12) — 3 execuções  
✅ `listaDeCartas` (linha 16) — 1 execução  
✅ `abrirPlacarPorCamada` (linha 26) — 1 execução  
✅ `abrirRegistroCompleto` (linha 52) — 1 execução  
✅ `abrirCemiterio` (linha 62) — 1 execução

### `src/cenas/mesa/resultado.js`

✅ `encerrarMao` (linha 30) — 16 execuções  
✅ `comemorar` (linha 68) — 8 execuções  
✅ `faixaDeVitoria` (linha 89) — 8 execuções  
✅ `onComplete` (linha 106) — 8 execuções  
✅ `chuvaDeConfete` (linha 111) — 8 execuções  
✅ `htmlDaRede` (linha 133) — 54 execuções  
✅ `mostrarResultado` (linha 151) — 22 execuções  
✅ `aoFechar` (linha 186) — 6 execuções

### `src/cenas/mesa/truco.js`

✅ `pedirTrucoHumano` (linha 13) — 4 execuções  
✅ `anunciarTruco` (linha 19) — 17 execuções  
✅ `pedirResposta` (linha 33) — 15 execuções  
✅ `acao` (linha 50) — 1 execução  
✅ `acao` (linha 51) — 9 execuções  
✅ `acao` (linha 53) — 1 execução  
✅ `aplicarResposta` (linha 64) — 16 execuções

### `src/cenas/mesa/turnos.js`

✅ `verso` (linha 22) — 51.257 execuções  
✅ `jogadorDeBaixo` (linha 25) — 13.290 execuções  
✅ `outrosJogadores` (linha 28) — 6.629 execuções  
✅ `ordemDoPlacar` (linha 34) — 5.346 execuções  
✅ `avatarDe` (linha 40) — 3.353 execuções  
✅ `montarJogadores` (linha 52) — 27 execuções  
✅ `ehVezDoHumano` (linha 63) — 11.467 execuções  
✅ `iniciarMao` (linha 72) — 27 execuções  
✅ `criarNeuronios` (linha 112) — 27 execuções  
✅ `executarJogada` (linha 140) — 369 execuções  
✅ `avancar` (linha 164) — 403 execuções  
✅ `anotarNaLinhaDoTempo` (linha 198) — 358 execuções  
✅ `avancarNoInicio` (linha 215) — 18 execuções  
✅ `comecar` (linha 228) — 12 execuções  
✅ `passarAparelho` (linha 235) — 39 execuções  
✅ `acao` (linha 240) — 38 execuções  
✅ `vezDoOponente` (linha 248) — 178 execuções

### `src/cenas/recursos.js`

✅ `prepararTextoNitido` (linha 20) — 25 execuções  
✅ `fabrica.text` (linha 23) — 4.459 execuções  
✅ `ajustarCamera` (linha 36) — 77 execuções  
✅ `ajustar` (linha 40) — 5.715 execuções  
✅ `cena.reajustarCamera` (linha 54) — 52 execuções  
✅ `texturaDaMesa` (linha 62) — 77 execuções  
✅ `colocarFundo` (linha 72) — 52 execuções  
✅ `texturaDoVerso` (linha 83) — 51.332 execuções  
✅ `texturaDaCartaNaMao` (linha 94) — 6.238 execuções  
✅ `texturaDaCartaMedia` (linha 101) — 30 execuções  
✅ `texturaDaCartaNaMesa` (linha 108) — 9.350 execuções  
✅ `criarTexturaDeInspecao` (linha 118) — 25 execuções  
✅ `texturaDeInspecao` (linha 127) — 278 execuções  
✅ `liberarCartasDaMao` (linha 144) — 27 execuções  
✅ `retanguloNaTela` (linha 152) — 2 execuções  
✅ `px` (linha 155) — 6 execuções  
✅ `py` (linha 156) — 6 execuções  
✅ `carregarIconesDasAcoes` (linha 164) — 23 execuções  
✅ `imagem.onload` (linha 169) — 184 execuções

### `src/conteudo/avatares.js`

✅ `avatarLiberado` (linha 25) — 1.730 execuções  
✅ `avatarDoJogador` (linha 30) — 1.686 execuções  
✅ `conquistaQueLibera` (linha 36) — 17 execuções  
✅ `avataresDaConquista` (linha 42) — 21 execuções

### `src/conteudo/conquistas.js`

✅ `meu` (linha 29) — 120 execuções  
✅ `teste` (linha 32) — 16 execuções  
✅ `teste` (linha 33) — 18 execuções  
✅ `teste` (linha 34) — 18 execuções  
✅ `teste` (linha 35) — 18 execuções  
✅ `teste` (linha 36) — 18 execuções  
✅ `teste` (linha 37) — 16 execuções  
✅ `teste` (linha 38) — 16 execuções  
✅ `teste` (linha 39) — 16 execuções  
✅ `teste` (linha 40) — 16 execuções  
✅ `teste` (linha 41) — 16 execuções  
✅ `teste` (linha 42) — 16 execuções  
✅ `teste` (linha 43) — 16 execuções  
✅ `teste` (linha 44) — 16 execuções  
✅ `teste` (linha 45) — 14 execuções  
✅ `teste` (linha 46) — 16 execuções  
✅ `teste` (linha 47) — 16 execuções  
✅ `teste` (linha 48) — 16 execuções  
✅ `teste` (linha 49) — 16 execuções  
✅ `teste` (linha 50) — 16 execuções  
✅ `teste` (linha 51) — 18 execuções  
✅ `teste` (linha 52) — 17 execuções  
✅ `teste` (linha 53) — 18 execuções  
✅ `teste` (linha 54) — 18 execuções  
✅ `teste` (linha 55) — 18 execuções  
✅ `teste` (linha 56) — 18 execuções  
✅ `teste` (linha 57) — 16 execuções  
✅ `teste` (linha 58) — 18 execuções  
✅ `teste` (linha 60) — 16 execuções  
✅ `teste` (linha 61) — 16 execuções  
✅ `teste` (linha 62) — 16 execuções  
✅ `teste` (linha 63) — 16 execuções  
✅ `teste` (linha 64) — 16 execuções  
✅ `teste` (linha 65) — 16 execuções  
✅ `teste` (linha 66) — 16 execuções  
✅ `teste` (linha 67) — 18 execuções

### `src/conteudo/dicasDeJogo.js`

✅ `contarValores` (linha 43) — 6.040 execuções  
✅ `escolherDicaDeJogo` (linha 57) — 6.040 execuções  
✅ `soma` (linha 63) — 12.080 execuções  
✅ `podeAtacar` (linha 64) — 6.041 execuções  
✅ `dica` (linha 70) — 7.280 execuções  
✅ `atacavel` (linha 71) — 6.040 execuções

### `src/conteudo/figurasDaBiblioteca.js`

✅ `svg` (linha 10) — 15 execuções  
✅ `traco` (linha 15) — 14 execuções  
✅ `eixos` (linha 20) — 3 execuções  
✅ `amostrar` (linha 27) — 7 execuções  
✅ `neuronio` (linha 34) — 6 execuções  
✅ `ativacoes` (linha 56) — 1 execução  
✅ `painel` (linha 57) — 3 execuções  
✅ `tela` (linha 58) — 183 execuções  
✅ `rede` (linha 70) — 1 execução  
✅ `ys` (linha 72) — 24 execuções  
✅ `curvas` (linha 86) — 1 execução  
✅ `tela` (linha 87) — 124 execuções  
✅ `treino` (linha 88) — 61 execuções  
✅ `validacao` (linha 89) — 63 execuções  
✅ `sobreajuste` (linha 101) — 1 execução  
✅ `tela` (linha 103) — 272 execuções  
✅ `suave` (linha 104) — 41 execuções  
✅ `decorada` (linha 106) — 221 execuções  
✅ `dropout` (linha 116) — 4 execuções  
✅ `ys` (linha 118) — 80 execuções  
✅ `vanishing` (linha 137) — 1 execução  
✅ `figuraDaBiblioteca` (linha 151) — 16 execuções

### `src/conteudo/grimorio.js`

✅ `bloco` (linha 16) — 660 execuções  
✅ `mi` (linha 17) — 3.720 execuções  
✅ `mo` (linha 18) — 3.780 execuções  
✅ `mn` (linha 19) — 750 execuções  
✅ `mt` (linha 20) — 660 execuções  
✅ `linha` (linha 21) — 2.070 execuções  
✅ `sub` (linha 22) — 570 execuções  
✅ `sup` (linha 23) — 630 execuções  
✅ `frac` (linha 24) — 450 execuções  
✅ `raiz` (linha 25) — 30 execuções  
✅ `soma` (linha 26) — 90 execuções  
✅ `prod` (linha 27) — 60 execuções  
✅ `parc` (linha 28) — 210 execuções  
✅ `par` (linha 29) — 630 execuções  
✅ `abs` (linha 30) — 60 execuções  
✅ `chapeu` (linha 31) — 30 execuções  
✅ `negrito` (linha 32) — 540 execuções  
✅ `camada` (linha 33) — 150 execuções  
✅ `mspace` (linha 143) — 330 execuções  
✅ `mover` (linha 145) — 90 execuções

### `src/conteudo/progresso.js`

✅ `progressoInicial` (linha 13) — 34 execuções  
✅ `migrarV1` (linha 22) — 2 execuções  
✅ `carregarProgresso` (linha 34) — 34 execuções  
✅ `salvarProgresso` (linha 46) — 103 execuções

### `src/conteudo/textos.js`

✅ `provocar` (linha 43) — 67 execuções

### `src/interface/menu.js`

✅ `escolhasDeHumanos` (linha 45) — 156 execuções  
✅ `mostrarMiniatura` (linha 55) — 250 execuções  
✅ `opcoesHtml` (linha 64) — 404 execuções  
✅ `htmlDoMenu` (linha 72) — 31 execuções  
✅ `abrirMenu` (linha 116) — 31 execuções  
✅ `campo` (linha 120) — 2.979 execuções  
✅ `atualizarDicas` (linha 123) — 125 execuções  
✅ `lerEscolhas` (linha 150) — 36 execuções  
✅ `mostrarAvatar` (linha 170) — 32 execuções

### `src/interface/musica.js`

✅ `hz` (linha 24) — 8.705 execuções  
✅ `sorteador` (linha 27) — 3.029 execuções  
✅ `voz` (linha 44) — 7.365 execuções  
✅ `chiado` (linha 70) — 897 execuções  
✅ `tambor` (linha 86) — 337 execuções  
✅ `sino` (linha 99) — 17 execuções  
✅ `harpa` (linha 112) — 607 execuções  
✅ `glockenspiel` (linha 118) — 424 execuções  
✅ `harmonicaDeVidro` (linha 131) — 290 execuções  
✅ `marimba` (linha 138) — 133 execuções  
✅ `pizzicato` (linha 144) — 352 execuções  
✅ `coro` (linha 149) — 95 execuções  
✅ `melodia` (linha 154) — 3.029 execuções  
✅ `tocar` (linha 177) — 287 execuções  
✅ `tocar` (linha 201) — 1.749 execuções  
✅ `tocar` (linha 227) — 203 execuções  
✅ `tocar` (linha 250) — 320 execuções  
✅ `tocar` (linha 282) — 470 execuções  
✅ `gravarTrilha` (linha 303) — 5 execuções  
✅ `agendar` (linha 325) — 3.486 execuções  
✅ `tocar` (linha 346) — 66 execuções  
✅ `parar` (linha 362) — 67 execuções  
✅ `tocando` (linha 375) — 12 execuções

### `src/interface/paineis.js`

✅ `$` (linha 9) — 392 execuções  
✅ `escaparHtml` (linha 12) — 5.200 execuções  
✅ `abrirPainel` (linha 31) — 184 execuções  
✅ `fechar` (linha 38) — 146 execuções  
✅ `fecharTodos` (linha 51) — 83 execuções  
✅ `mostrarAviso` (linha 62) — 121 execuções  
✅ `mostrarDicaDeJogo` (linha 78) — 4 execuções  
✅ `confirmar` (linha 98) — 55 execuções  
✅ `mostrarDicaFlutuante` (linha 126) — 5 execuções  
✅ `esconderDicaFlutuante` (linha 145) — 57 execuções

### `src/interface/som.js`

✅ `contextoDeAudio` (linha 11) — 80 execuções  
✅ `audio` (linha 14) — 1.691 execuções  
✅ `nota` (linha 33) — 1.133 execuções  
✅ `ruido` (linha 49) — 428 execuções  
✅ `desbloquear` (linha 65) — 50 execuções  
✅ `liberado` (linha 67) — 29 execuções  
✅ `definirMudo` (linha 68) — 32 execuções  
✅ `estaMudo` (linha 69) — 40 execuções  
✅ `virarCarta` (linha 70) — 250 execuções  
✅ `colocarCarta` (linha 71) — 15 execuções  
✅ `selecionar` (linha 72) — 240 execuções  
✅ `tunagem` (linha 73) — 18 execuções  
✅ `golpe` (linha 74) — 34 execuções  
✅ `explosao` (linha 75) — 5 execuções  
✅ `dropout` (linha 76) — 12 execuções  
✅ `truco` (linha 81) — 22 execuções  
✅ `vitoria` (linha 90) — 1 execução  
✅ `fanfarra` (linha 96) — 11 execuções  
✅ `campeao` (linha 111) — 2 execuções  
✅ `derrota` (linha 123) — 11 execuções  
✅ `medalha` (linha 124) — 40 execuções

### `src/interface/telas/ajudaDasAcoes.js`

✅ `doMotor` (linha 43) — 32 execuções  
✅ `abrirAjudaDasAcoes` (linha 52) — 4 execuções

### `src/interface/telas/avatares.js`

✅ `retratoDoAvatar` (linha 14) — 50 execuções  
✅ `abrirAvatares` (linha 24) — 2 execuções

### `src/interface/telas/conquistas.js`

✅ `medalhaHtml` (linha 17) — 127 execuções  
✅ `itemHtml` (linha 24) — 105 execuções  
✅ `abrirConquistas` (linha 34) — 3 execuções

### `src/interface/telas/grimorio.js`

✅ `abrirGrimorio` (linha 16) — 8 execuções  
✅ `desenharLista` (linha 25) — 10 execuções  
✅ `mostrar` (linha 33) — 10 execuções

### `src/interface/telas/mods.js`

✅ `abrirMods` (linha 28) — 3 execuções

### `src/interface/telas/online.js`

✅ `clienteDaAba` (linha 19) — 3 execuções  
❌ `usarConta` (linha 33) — 0 execuções  
✅ `transporte` (linha 48) — 3 execuções  
✅ `abrirOnline` (linha 57) — 3 execuções  
✅ `aoFechar` (linha 85) — 3 execuções  
✅ `$` (linha 86) — 81 execuções  
✅ `eu` (linha 88) — 3 execuções  
✅ `esperar` (linha 95) — 3 execuções  
✅ `desenhar` (linha 99) — 9 execuções  
❌ `mostrarConta` (linha 139) — 0 execuções  
✅ `tentar` (linha 144) — 9 execuções

### `src/interface/telas/regras.js`

✅ `abaDeAcoes` (linha 59) — 26 execuções  
✅ `abaDeExtensoes` (linha 68) — 26 execuções  
✅ `desenharArte` (linha 93) — 2 execuções  
✅ `abrirRegras` (linha 116) — 26 execuções  
✅ `mostrarAba` (linha 128) — 30 execuções  
❌ `marcarVerbeteLido` (linha 136) — 0 execuções

### `src/interface/telas/revisao.js`

✅ `placar` (linha 19) — 18 execuções  
✅ `tipoDoPasso` (linha 34) — 700 execuções  
✅ `variacoes` (linha 48) — 26 execuções  
✅ `momentosChave` (linha 56) — 9 execuções  
✅ `contagens` (linha 77) — 9 execuções  
✅ `graficoDaCurva` (linha 89) — 8 execuções  
✅ `x` (linha 95) — 721 execuções  
✅ `y` (linha 96) — 827 execuções  
✅ `linhaDoTempoHtml` (linha 130) — 9 execuções  
✅ `tabelaDaPartida` (linha 150) — 8 execuções  
✅ `abrirRevisao` (linha 161) — 9 execuções  
✅ `linha` (linha 165) — 26 execuções  
✅ `qtd` (linha 168) — 111 execuções

### `src/interface/telas/sobre.js`

✅ `abrirSobre` (linha 9) — 3 execuções

### `src/motor/bot.js`

✅ `botMoves` (linha 19) — 610.366 execuções  
✅ `optionalPass` (linha 20) — 14.063 execuções  
✅ `revealPick` (linha 24) — 2.436 execuções  
✅ `str` (linha 27) — 24 execuções  
✅ `val` (linha 30) — 12.396 execuções  
✅ `randomPolicy` (linha 35) — 593.782 execuções  
✅ `playout` (linha 54) — 72.990 execuções  
✅ `margin` (linha 65) — 132.814 execuções  
✅ `evaluate` (linha 71) — 62.722 execuções  
✅ `mean` (linha 73) — 125.444 execuções  
✅ `bad` (linha 75) — 172.639 execuções  
✅ `greedyMove` (linha 80) — 13.062 execuções  
✅ `monteCarloMove` (linha 106) — 3.520 execuções  
✅ `monteCarloResults` (linha 116) — 3.382 execuções  
✅ `defaultRollouts` (linha 134) — 40 execuções  
✅ `chooseMove` (linha 136) — 40.054 execuções  
❌ `describeMove` (linha 142) — 0 execuções

### `src/motor/engine/actions.js`

✅ `generate` (linha 18) — 2.146.213 execuções  
✅ `isValid` (linha 24) — 590.545 execuções  
✅ `execute` (linha 33) — 590.544 execuções  
✅ `generate` (linha 49) — 2.146.213 execuções  
✅ `isValid` (linha 58) — 38.406 execuções  
✅ `execute` (linha 64) — 38.282 execuções  
✅ `attackAction` (linha 84) — 126 execuções  
✅ `generate` (linha 87) — 6.438.639 execuções  
✅ `isValid` (linha 100) — 74.165 execuções  
✅ `execute` (linha 112) — 73.969 execuções  
✅ `statWeight` (linha 146) — 19.878 execuções  
✅ `generate` (linha 149) — 630.116 execuções  
✅ `isValid` (linha 159) — 19.880 execuções  
✅ `execute` (linha 171) — 19.878 execuções  
✅ `generate` (linha 186) — 969.451 execuções  
✅ `isValid` (linha 192) — 2.593 execuções  
✅ `execute` (linha 197) — 2.592 execuções  
✅ `generate` (linha 217) — 2.145.393 execuções  
✅ `isValid` (linha 218) — 2.363 execuções  
✅ `execute` (linha 219) — 2.356 execuções

### `src/motor/engine/core.js`

✅ `rulesOf` (linha 48) — 1.163.161 execuções  
✅ `scaleLayers` (linha 59) — 6.496 execuções  
✅ `newGame` (linha 66) — 6.319 execuções  
✅ `rng` (linha 70) — 399.997 execuções  
✅ `each` (linha 103) — 56.862 execuções  
✅ `mkNet` (linha 141) — 14.358 execuções  
✅ `startPlay` (linha 143) — 6.305 execuções  
✅ `revealMoves` (linha 157) — 3.089 execuções  
✅ `applyReveal` (linha 161) — 4.871 execuções  
✅ `deckOf` (linha 183) — 11.703.573 execuções  
✅ `terrainOf` (linha 184) — 5.230.325 execuções  
❌ `outputLayer` (linha 185) — 0 execuções  
❌ `layerName` (linha 186) — 0 execuções  
✅ `lastSlot` (linha 192) — 9.756.894 execuções  
✅ `nextLayer` (linha 198) — 4.468.018 execuções  
✅ `isHidden` (linha 199) — 7.178.837 execuções  
✅ `pileSize` (linha 200) — 6.542.577 execuções  
✅ `pileRoom` (linha 201) — 1.578.819 execuções  
✅ `handCardsByRank` (linha 202) — 6.219.987 execuções  
✅ `hiddenInPath` (linha 203) — 630.116 execuções  
✅ `attackTarget` (linha 207) — 153.158 execuções  
✅ `cardValue` (linha 216) — 10.054.499 execuções  
✅ `strengthOf` (linha 221) — 8.479 execuções  
✅ `stackValue` (linha 225) — 146.678 execuções  
✅ `peekCards` (linha 234) — 142.193 execuções  
✅ `takeCards` (linha 246) — 138.933 execuções  
✅ `pileCheck` (linha 251) — 112.571 execuções  
✅ `removeSlot` (linha 258) — 98.558 execuções  
✅ `finishNet` (linha 262) — 141.233 execuções  
✅ `discardHand` (linha 268) — 3.174 execuções  
✅ `addAchievement` (linha 271) — 18.852 execuções  
✅ `logEvent` (linha 274) — 727.621 execuções  
✅ `legalMoves` (linha 278) — 2.148.482 execuções  
✅ `canPass` (linha 298) — 2.148.350 execuções  
✅ `validate` (linha 305) — 732.823 execuções  
✅ `applyMove` (linha 321) — 732.503 execuções  
✅ `roundEnded` (linha 361) — 705.151 execuções  
❌ `nextK` (linha 371) — 0 execuções  
✅ `pickNext` (linha 380) — 705.151 execuções  
✅ `canAct` (linha 393) — 1.515.277 execuções  
✅ `checkStuck` (linha 398) — 733.926 execuções  
✅ `checkOver` (linha 409) — 727.621 execuções  
✅ `endGame` (linha 416) — 79.958 execuções  
✅ `neuronBonus` (linha 435) — 3.730.103 execuções  
✅ `score` (linha 439) — 766.296 execuções  
✅ `compareTwo` (linha 456) — 165.208 execuções  
✅ `val` (linha 463) — 66.898 execuções  
✅ `sum` (linha 468) — 7.254 execuções  
✅ `best` (linha 472) — 378 execuções  
✅ `high` (linha 475) — 160 execuções  
✅ `pos` (linha 481) — 1.148 execuções  
✅ `resolveWinner` (linha 485) — 79.958 execuções  
✅ `cloneState` (linha 497) — 93.610 execuções  
❌ `toPlain` (linha 505) — 0 execuções  
❌ `viewFor` (linha 513) — 0 execuções  
✅ `replay` (linha 527) — 1.000 execuções  
✅ `determinize` (linha 535) — 91.056 execuções

### `src/motor/engine/decks.js`

✅ `sumScore` (linha 23) — 740.977 execuções  
✅ `score` (linha 72) — 154.386 execuções  
✅ `activation` (linha 81) — 88.478 execuções  
✅ `activationName` (linha 87) — 88.478 execuções  
✅ `score` (linha 92) — 25.319 execuções  
✅ `trucoValue` (linha 124) — 236.895 execuções  
✅ `build` (linha 129) — 605 execuções  
✅ `strength` (linha 140) — 755 execuções  
✅ `score` (linha 141) — 40.624 execuções  
✅ `cardValue` (linha 148) — 154.299 execuções  
✅ `stackValue` (linha 149) — 6.659 execuções  
✅ `strength` (linha 151) — 508 execuções  
✅ `score` (linha 152) — 24.155 execuções  
✅ `sumScore.faceAsValue` (linha 152) — 24.155 execuções  
✅ `score` (linha 167) — 47.860 execuções  
✅ `build` (linha 182) — 918 execuções  
✅ `score` (linha 188) — 91.135 execuções  
✅ `score` (linha 195) — 382.817 execuções  
✅ `onAfterAction` (linha 196) — 527.209 execuções

### `src/motor/engine/index.js`

✅ `loadMod` (linha 24) — 1 execução

### `src/motor/engine/registry.js`

✅ `need` (linha 46) — 799 execuções  
✅ `registerDeck` (linha 56) — 294 execuções  
✅ `registerTerrain` (linha 61) — 169 execuções  
✅ `registerAction` (linha 66) — 336 execuções  
✅ `deck` (linha 72) — 11.709.932 execuções  
✅ `terrain` (linha 73) — 5.236.645 execuções  
✅ `action` (linha 74) — 727.668 execuções  
❌ `deckList` (linha 76) — 0 execuções  
❌ `terrainList` (linha 77) — 0 execuções  
✅ `actionList` (linha 78) — 2.491.866 execuções

### `src/motor/engine/terrains.js`

✅ `key` (linha 10) — 3.075.966 execuções  
✅ `neuronBonus` (linha 21) — 745.263 execuções  
✅ `onGameStart` (linha 30) — 941 execuções  
✅ `onRoundEnd` (linha 31) — 95.295 execuções  
✅ `neuronBonus` (linha 38) — 994.858 execuções  
❌ `status` (linha 42) — 0 execuções  
✅ `onGameStart` (linha 49) — 946 execuções  
✅ `onRoundEnd` (linha 50) — 69.439 execuções  
✅ `onCardPlayed` (linha 54) — 120.453 execuções  
✅ `neuronBonus` (linha 60) — 743.596 execuções  
❌ `status` (linha 65) — 0 execuções

### `src/motor/engine/util.js`

✅ `mulberry32` (linha 13) — 119.846 execuções  
✅ `rand` (linha 26) — 1.951.202 execuções  
✅ `shuffle` (linha 35) — 99.966 execuções  
❌ `rankLabel` (linha 43) — 0 execuções  
❌ `cardLabel` (linha 44) — 0 execuções  
✅ `isFace` (linha 45) — 8.225.489 execuções  
✅ `nominalValue` (linha 48) — 9.891.303 execuções  
✅ `cardStrength` (linha 55) — 7.216 execuções  
✅ `standardDeck` (linha 60) — 5.803 execuções  
❌ `otherPlayer` (linha 69) — 0 execuções  
✅ `playerCount` (linha 70) — 20.801.009 execuções  
✅ `nextPlayer` (linha 71) — 8.625.477 execuções  
✅ `opponents` (linha 76) — 6.725.568 execuções  
✅ `round2` (linha 82) — 1.163.220 execuções

### `src/motor/sim.js`

✅ `runGame` (linha 6) — 2.020 execuções  
❌ `emptyStats` (linha 18) — 0 execuções  
❌ `accumulate` (linha 27) — 0 execuções  
❌ `summarize` (linha 50) — 0 execuções  
✅ `choose` (linha 61) — 15 execuções

### `src/nucleo/aleatorio.js`

✅ `sortear` (linha 13) — 2.430 execuções  
✅ `sortearInteiro` (linha 25) — 2.030 execuções  
✅ `embaralhar` (linha 36) — 30 execuções  
✅ `sementeNova` (linha 45) — 26 execuções

### `src/nucleo/baralhos.js`

✅ `montarBaralho` (linha 12) — 40 execuções  
✅ `BARALHOS.<computed>.montar` (linha 61) — 40 execuções  
✅ `pontosDaCarta` (linha 69) — 5.829 execuções  
✅ `nomeDaCarta` (linha 76) — 1.950 execuções  
✅ `manilhaDaCarta` (linha 83) — 2 execuções

### `src/nucleo/cartas.js`

✅ `ehFigura` (linha 40) — 77.025 execuções  
✅ `rotuloCarta` (linha 45) — 47.305 execuções  
✅ `baralhoPadrao` (linha 50) — 8 execuções

### `src/nucleo/oponentes/comum.js`

✅ `novoGerador` (linha 10) — 47.381 execuções  
✅ `determinizar` (linha 19) — 5.014 execuções  
✅ `chanceDeVitoria` (linha 27) — 76 execuções

### `src/nucleo/oponentes/estrategias.js`

✅ `jogadaAleatoria` (linha 15) — 38.773 execuções  
✅ `jogadaGulosa` (linha 20) — 648 execuções  
✅ `jogadaMonteCarlo` (linha 30) — 47 execuções

### `src/nucleo/oponentes/index.js`

✅ `cartaDeInicio` (linha 30) — 29 execuções  
✅ `forca` (linha 38) — 44 execuções  
✅ `escolherJogada` (linha 49) — 1.190 execuções  
✅ `querTrucar` (linha 61) — 68 execuções  
✅ `responderAoTruco` (linha 74) — 20 execuções

### `src/nucleo/partida.js`

✅ `novoJogador` (linha 74) — 5.778 execuções  
✅ `todasAsCartas` (linha 84) — 2.846 execuções  
✅ `indexarCartas` (linha 96) — 2.846 execuções  
✅ `montar` (linha 118) — 10.414 execuções  
✅ `novaMao` (linha 147) — 2.852 execuções  
✅ `copiarMao` (linha 176) — 7.568 execuções  
✅ `atualizarVisao` (linha 186) — 58.103 execuções  
✅ `carta` (linha 188) — 3.071.510 execuções  
✅ `emitir` (linha 222) — 58.485 execuções  
✅ `anotar` (linha 227) — 54.785 execuções  
✅ `somas` (linha 232) — 49.204 execuções  
✅ `anotarHistorico` (linha 237) — 49.753 execuções  
❌ `totalDeCamadas` (linha 244) — 0 execuções  
✅ `fronteira` (linha 247) — 24.676 execuções  
✅ `alvosDeAtivacao` (linha 253) — 3.039 execuções  
✅ `alvosDeEmpilhamento` (linha 262) — 227 execuções  
✅ `efeitoDoEmpilhamento` (linha 277) — 5.176 execuções  
✅ `podeEmpilhar` (linha 287) — 325 execuções  
✅ `camadasDesfaziveis` (linha 297) — 795 execuções  
✅ `valorParaTransfer` (linha 304) — 6.616 execuções  
✅ `podePassar` (linha 317) — 595 execuções  
✅ `jogadasLegais` (linha 327) — 11.832 execuções  
✅ `idsNoMotor` (linha 337) — 7.260 execuções  
✅ `jogadaParaND` (linha 351) — 47.758 execuções  
✅ `jogadaParaTT` (linha 386) — 115.664 execuções  
✅ `ids` (linha 388) — 31.522 execuções  
✅ `ultimo` (linha 389) — 13.767 execuções  
✅ `anunciarInicio` (linha 416) — 239 execuções  
✅ `narrarAtivacao` (linha 425) — 40.407 execuções  
✅ `narrarEmpilhamento` (linha 437) — 5.136 execuções  
✅ `encerrar` (linha 467) — 2.698 execuções  
✅ `finalizarMao` (linha 484) — 16 execuções  
✅ `aplicarJogada` (linha 499) — 47.440 execuções  
✅ `carta` (linha 511) — 7.255 execuções

### `src/nucleo/pontuacao.js`

✅ `arredondar` (linha 41) — 20.194 execuções  
✅ `pontuarRede` (linha 49) — 20.639 execuções  
✅ `decimal` (linha 81) — 265 execuções  
✅ `pontuarForward` (linha 88) — 21 execuções  
✅ `mediaDePontos` (linha 106) — 2 execuções

### `src/nucleo/rede.js`

✅ `tamanhosDaMesa` (linha 25) — 3.025 execuções  
✅ `ehOculta` (linha 45) — 23.101 execuções  
✅ `nomeCamada` (linha 54) — 41.170 execuções

### `src/nucleo/traducao.js`

✅ `naipeParaTT` (linha 39) — 3.164 execuções  
✅ `rankDoValor` (linha 42) — 6.214 execuções  
✅ `valorDoRank` (linha 45) — 153.158 execuções  
✅ `cartaParaND` (linha 48) — 5.830 execuções  
✅ `cartaParaTT` (linha 56) — 153.158 execuções  
✅ `idDoNeuronio` (linha 62) — 899.937 execuções  
✅ `lugarDoNeuronio` (linha 65) — 40.410 execuções  
✅ `situacaoDaRede` (linha 77) — 119.129 execuções  
✅ `motivoDaVitoria` (linha 82) — 2.698 execuções

### `src/nucleo/truco.js`

✅ `novaPartida` (linha 25) — 218 execuções  
✅ `temTruco` (linha 30) — 9.286 execuções  
✅ `proximoValor` (linha 35) — 7.772 execuções  
✅ `ehMaoDeOnze` (linha 41) — 8.105 execuções  
✅ `podeTrucar` (linha 46) — 6.803 execuções  
✅ `pedirTruco` (linha 54) — 23 execuções  
✅ `responderTruco` (linha 65) — 26 execuções  
✅ `marcarTentos` (linha 83) — 22 execuções  
✅ `proximaMao` (linha 91) — 4 execuções

### `src/online/contas.js`

✅ `mesclarProgresso` (linha 22) — 2 execuções  
❌ `progressoDaConta` (linha 37) — 0 execuções

### `src/online/firebase.js`

✅ `firebaseConfigurado` (linha 16) — 6 execuções  
❌ `carregar` (linha 19) — 0 execuções  
❌ `entrarComGoogle` (linha 33) — 0 execuções  
❌ `entrarComEmail` (linha 40) — 0 execuções  
❌ `sairDaConta` (linha 48) — 0 execuções  
❌ `aoMudarConta` (linha 54) — 0 execuções  
❌ `conta` (linha 59) — 0 execuções  
❌ `carregarProgressoDaConta` (linha 62) — 0 execuções  
❌ `salvarProgressoNaConta` (linha 69) — 0 execuções  
❌ `transporteFirebase` (linha 80) — 0 execuções

### `src/online/sala.js`

✅ `codigoDeSala` (linha 26) — 4 execuções  
✅ `idDeCliente` (linha 32) — 3 execuções  
✅ `Sala` (linha 42) — 23 execuções  
✅ `on` (linha 59) — 32 execuções  
❌ `off` (linha 61) — 0 execuções  
✅ `emitir` (linha 62) — 496 execuções  
✅ `get souAnfitriao` (linha 64) — 722 execuções  
✅ `get minhaCadeira` (linha 67) — 340 execuções  
✅ `criar` (linha 75) — 11 execuções  
✅ `anunciarSala` (linha 90) — 39 execuções  
✅ `comecar` (linha 96) — 11 execuções  
✅ `ordenar` (linha 104) — 193 execuções  
✅ `entrar` (linha 114) — 12 execuções  
✅ `enviar` (linha 119) — 177 execuções  
✅ `sair` (linha 125) — 1 execução  
✅ `receber` (linha 134) — 453 execuções  
✅ `ao_ola` (linha 142) — 19 execuções  
✅ `ao_sala` (linha 156) — 31 execuções  
✅ `ao_pedido` (linha 164) — 112 execuções  
✅ `ao_acao` (linha 172) — 217 execuções  
✅ `ao_vivo` (linha 179) — 72 execuções  
✅ `ao_tchau` (linha 181) — 2 execuções  
✅ `aceitar` (linha 187) — 410 execuções  
✅ `pulsar` (linha 200) — 148 execuções  
✅ `ausente` (linha 207) — 233 execuções  
✅ `verificarAusentes` (linha 218) — 150 execuções  
✅ `substituir` (linha 237) — 9 execuções  
✅ `agora` (linha 245) — 268 execuções  
✅ `intervalo` (linha 246) — 3 execuções  
❌ `parar` (linha 247) — 0 execuções

### `src/online/transportes.js`

✅ `transporteLocal` (linha 13) — 3 execuções  
✅ `canal.onmessage` (linha 18) — 71 execuções  
✅ `enviar` (linha 20) — 194 execuções  
✅ `aoReceber` (linha 21) — 3 execuções  
❌ `fechar` (linha 22) — 0 execuções  
✅ `centralEmMemoria` (linha 31) — 8 execuções  
✅ `despachar` (linha 34) — 265 execuções  
✅ `conectar` (linha 36) — 20 execuções  
✅ `enviar` (linha 40) — 274 execuções  
✅ `aoReceber` (linha 41) — 20 execuções  
✅ `fechar` (linha 42) — 3 execuções  
✅ `entregar` (linha 46) — 67 execuções  
✅ `ordem` (linha 46) — 11 execuções

### `src/principal.js`

✅ `remedirAposMudarATela` (linha 25) — 6 execuções  
✅ `criarJogo` (linha 32) — 25 execuções  
✅ `iniciarJogo` (linha 53) — 26 execuções  
✅ `aoGirar` (linha 56) — 2 execuções
