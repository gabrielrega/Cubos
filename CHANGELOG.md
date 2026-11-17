# Changelog

Todas as mudanças notáveis deste projeto são documentadas aqui.
Formato baseado em [Keep a Changelog](https://keepachangelog.com/pt-BR/1.1.0/);
versionamento conforme [SemVer](https://semver.org/lang/pt-BR/).

## [Não lançado]

## [0.3.0] - 2026-11-17
### Adicionado
- Versão 3D (`3d.html`) com three.js e cubos físicos de 6 faces (2 brancas, 2 azuis, 2 diagonais): pegue os cubos na bandeja, arraste até o tabuleiro e vire-os até a face certa. Tabuleiros com sombras, câmera com paralaxe, confete ao acertar e tremor ao errar. Mantém as regras, o recorde e o controle por teclado.

## [0.2.0] - 2026-11-17
### Adicionado
- Recorde de pontuação salvo no navegador (`localStorage`), exibido nas telas inicial e final.
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
