Simulador de orçamento de drywall, sanca de gesso, cantoneiras e boiserie para o apartamento tipo do Flores de Bragança (MRV).

- Site estático: um único `index.html`. Sem banco de dados; o rascunho fica salvo no navegador do cliente.
- O pedido fecha pelo WhatsApp.

## Onde editar

No topo do `<script>` em `index.html`:

- `WHATSAPP` e `FONE_VISIVEL`: número que recebe os pedidos.
- `MEDIDAS`: quanto cada serviço ocupa (rebaixo do forro, sanca, painel, parede).
- `MAO_DE_OBRA`: preço da mão de obra por unidade (`preco`) e a referência de mercado (`media`).
- `ITENS`: materiais da Leroy Merlin, com `preco`, `real` (preço lido no site ou estimado), `url` e `afiliado` (cole aqui o seu link de afiliado).

## Publicar na Vercel

Conecte este repositório ao projeto `horvatti-drywall` na Vercel (Settings → Git). Framework: "Other", sem comando de build. Cada push na branch `main` publica de novo.

Site no ar: https://horvatti-drywall.vercel.app
