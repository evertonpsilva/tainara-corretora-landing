# Tainara Gomes — Landing Page

Site estático de página única para a corretora de imóveis Tainara Gomes
(Fortaleza/CE). HTML + CSS puro, sem build — publica direto no GitHub Pages.

## Como editar

- **Textos**: abra `index.html`, todo o conteúdo visível está lá (seções
  `#sobre`, `#servicos`, `#imoveis`, `#clientes`, `#contato`).
- **Imóveis em destaque**: cada `<article class="card listing">` é um
  anúncio. Os dois primeiros ("Paço das Águas" e "Casas em Horizonte") vieram
  de posts reais do Instagram dela — confirme se ainda estão disponíveis antes
  de divulgar, ou troque pelos anúncios ativos (título, localização, preço e
  link do botão).
- **Sonhos realizados** (`#clientes`): carrossel de fotos de clientes que
  já receberam as chaves (`assets/cliente-1.jpg` a `cliente-3.jpg`). Para
  adicionar mais, copie um `<figure class="carousel-slide">` dentro de
  `.carousel-track` e inclua a foto em `assets/`. Não há depoimento em texto
  atribuído a cliente nenhum — só a legenda genérica da foto; se for
  adicionar uma citação real, peça autorização do cliente antes.
- **Foto de perfil**: `assets/foto-tainara.jpg`, usada tanto no hero principal
  (`.hero-portrait`) quanto no selo rotacionado (`.hero-badge`, texto "Consulta
  grátis"). Para trocar, substitua o arquivo (mantenha o mesmo nome) e ajuste
  `object-position` em `styles.css` se o enquadramento do rosto mudar.
- **CRECI**: `29377`, conforme informado. Se o registro dela usar um formato
  diferente (ex.: com dígito verificador), atualize em `index.html` (aparece
  no rodapé e perto do botão de WhatsApp).
- **Cores**: variáveis no topo de `styles.css` (`:root`), incluindo o
  gradiente do hero (`--color-accent-start`/`--color-accent-end`).
- **Fonte de título**: Fraunces (Google Fonts), carregada no `<head>` do
  `index.html`; aplicada a `h1`/`h2` via `--font-display` em `styles.css`.

## Rodar localmente

Abra `index.html` direto no navegador, ou:

```bash
python3 -m http.server 8000
```

## Publicação

O site é publicado via GitHub Pages a partir da branch `main`, raiz do
repositório.
