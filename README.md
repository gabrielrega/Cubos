# CuboMente

Jogo de quebra-cabeça visuoespacial em página única (HTML, CSS e JS puros, sem dependências de build). Olhe o padrão-modelo e reproduza-o nos cubos interativos antes que o tempo acabe.

## Como jogar

- Clique (ou use Tab e Enter/Espaço) em um cubo para alternar entre os 6 estados: branco, diagonais, azul.
- São 8 níveis de dificuldade crescente (grids 2×2 e 3×3), com tempo limite por nível.
- Você tem 3 vidas: errar ou estourar o tempo custa uma vida.
- Acertos valem 100 pontos mais um bônus de até 50 pela rapidez.
- O melhor placar fica salvo no navegador (`localStorage`).

### Versão 3D (`3d.html`)

- Os cubos têm 6 faces: 2 brancas, 2 azuis e 2 diagonais. Todos são iguais; o que importa é a face e a rotação que ficam para cima.
- **Arraste** um cubo da bandeja até uma casa do tabuleiro (soltar num cubo já colocado troca os dois).
- **Arraste sobre um cubo colocado** para virá-lo: horizontal gira, vertical tomba. Ele sempre assenta em múltiplos de 90°. Um toque rápido dá um quarto de volta.
- **Segure** um cubo colocado (ou use Shift/botão direito) para pegá-lo e movê-lo.
- Teclado: setas escolhem a casa, Espaço coloca o próximo cubo, Q/E giram, W/S tombam, Backspace devolve e C confirma.

## Executar

Abra `index.html` no navegador. O projeto também é publicado via GitHub Pages.

## Estrutura

- `index.html`: versão clássica 2D (estilos, marcação e lógica).
- `3d.html`: versão 3D com three.js (carregado via CDN, versão 0.160.0).
- `CHANGELOG.md`: histórico de versões.

## Versionamento

SemVer (`major.minor.fix`) com tags git `vX.Y.Z`; commits seguem Conventional Commits.
