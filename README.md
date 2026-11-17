# CuboMente

Jogo de quebra-cabeça visuoespacial em página única (HTML, CSS e JS puros, sem dependências de build). Olhe o padrão-modelo e reproduza-o nos cubos interativos antes que o tempo acabe.

## Como jogar

- Clique (ou use Tab e Enter/Espaço) em um cubo para alternar entre os 6 estados: branco, diagonais, azul.
- São 8 níveis de dificuldade crescente (grids 2×2 e 3×3), com tempo limite por nível.
- Você tem 3 vidas: errar ou estourar o tempo custa uma vida.
- Acertos valem 100 pontos mais um bônus de até 50 pela rapidez.
- O melhor placar fica salvo no navegador (`localStorage`).

## Executar

Abra `index.html` no navegador. O projeto também é publicado via GitHub Pages.

## Estrutura

- `index.html`: versão clássica 2D (estilos, marcação e lógica).
- `3d.html`: versão 3D com three.js (carregado via CDN, versão 0.160.0).
- `CHANGELOG.md`: histórico de versões.

## Versionamento

SemVer (`major.minor.fix`) com tags git `vX.Y.Z`; commits seguem Conventional Commits.
