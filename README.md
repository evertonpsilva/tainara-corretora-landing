# Tainara Gomes — Landing Page

Site estático de página única para a corretora de imóveis Tainara Gomes
(Fortaleza/CE). HTML + CSS puro, sem build — publica direto no GitHub Pages.

## Como editar

- **Textos**: abra `index.html`, todo o conteúdo visível está lá (seções
  `#sobre`, `#servicos`, `#imoveis`, `#contato`).
- **Imóveis em destaque**: cada `<article class="card listing">` é um
  anúncio. Troque título, bairro, preço e o link do botão.
- **Foto de perfil**: o círculo com "TG" em `.hero-photo` é um placeholder.
  Para usar uma foto real, adicione o arquivo em `assets/` e troque o `<div
  class="avatar-circle">` por `<img src="assets/foto-tainara.jpg" alt="Tainara Gomes">`.
- **CRECI**: o número no site está parcial (`29377...`) — confirme o número
  completo e atualize em `index.html` (aparece no rodapé e perto do botão de
  WhatsApp).
- **Cores**: variáveis no topo de `styles.css` (`:root`).

## Rodar localmente

Abra `index.html` direto no navegador, ou:

```bash
python3 -m http.server 8000
```

## Publicação

O site é publicado via GitHub Pages a partir da branch `main`, raiz do
repositório.
