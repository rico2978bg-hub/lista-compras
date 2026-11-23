# Lista de compras

A lista de compras da família, feita em um único arquivo HTML: HTML, CSS e JavaScript puros, sem servidor e sem nenhuma API paga.

- Adiciona itens sem repetir. A comparação ignora maiúsculas/minúsculas e espaços extras.
- Marca itens como comprados (ficam riscados) e remove itens com o ×.
- Guarda um histórico de quantas vezes cada item foi comprado. Desmarcar um item desfaz a contagem.
- Sugere até 8 dos itens mais comprados que não estão na lista. Um clique adiciona o item de volta.
- Monta um cardápio simples com os itens da lista e mostra o que falta para cada prato.

## Como usar

Abra o `index.html` no navegador, ou use o link do GitHub Pages do repositório.

Os dados ficam no `localStorage` do navegador, nas chaves `compras_lista` e `compras_historico`. Cada navegador e cada endereço guardam sua própria lista.
