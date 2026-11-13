# Caixas responsivas

Página feita só com HTML e CSS. As caixas ficam **lado a lado** em telas largas e passam a ficar **uma embaixo da outra** quando a tela fica estreita.

## Arquivos

- `index.html`: estrutura da página.
- `style.css`: estilos e responsividade.

## Como abrir

Dê dois cliques no `index.html` para abrir no navegador. Depois redimensione a janela (ou gire o celular) para ver as caixas mudarem de horizontal para vertical.

## Como funciona

1. `.caixas` usa `display: flex` com `flex-direction: row`, então as caixas ficam em linha.
2. Cada `.caixa` tem `flex: 1 1 0`, o que divide a largura igualmente entre elas.
3. A media query `@media (max-width: 768px)` troca para `flex-direction: column`, e as caixas empilham.
