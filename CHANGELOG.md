# Changelog

Todas as mudanças notáveis deste projeto são documentadas aqui.
Formato baseado em [Keep a Changelog](https://keepachangelog.com/pt-BR/1.1.0/);
versionamento conforme [SemVer](https://semver.org/lang/pt-BR/).

## [Não lançado]
### Adicionado
- Cubos jogáveis acessíveis por teclado (Tab, Enter e Espaço), com foco visível e `aria-label` descrevendo o estado.

### Corrigido
- Revisão das tentativas usava o tamanho de grid errado após erros, pois o histórico tem uma entrada por tentativa e não por nível.

## [0.1.0] - 2026-03-30
### Adicionado
- Jogo CuboMente: 8 níveis gerados proceduralmente, timer, 3 vidas e pontuação com bônus de tempo.
- Seis estados de cubo (branco, azul e quatro diagonais).
- Estilos de padrão: intruso, listras, xadrez, borda, simétrico, cruz e X.
- Tela final com revisão das tentativas.

### Corrigido
- Timer com erro de ponto flutuante, tempo no timeout e renderização de diagonais nos mini-cubos.
