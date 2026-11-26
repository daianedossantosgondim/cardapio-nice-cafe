# Cardápio NICE CAFÉ

Cardápio digital do delivery do NICE CAFÉ. Página estática (HTML, CSS e JavaScript puros), publicada na Vercel.

## Como editar

Tudo fica em `index.html`, no bloco `<script>`:

- `LOJA`: número do WhatsApp, dias e horário do delivery.
- `CARDAPIO`: categorias e pratos. Para pôr preço, troque `preco: null` por um número, por exemplo `preco: 29.90`.
- Fotos ficam na raiz (`prato-*.jpg`). Para trocar uma foto, substitua o arquivo com o mesmo nome.

Cada alteração enviada para a branch `main` pode ser publicada de novo na Vercel.
