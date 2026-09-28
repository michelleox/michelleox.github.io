# Clara Michelle, tema Jekyll próprio

Tema reconstruído para GitHub Pages sem `remote_theme`, sem tema pai e sem plugins obrigatórios.

## Estrutura

- `_layouts/`: estruturas de home, post e página.
- `_includes/`: header, newsletter, footer, lista de posts e navegação.
- `_posts/`: publicações Markdown.
- `assets/css/style.css`: todo o visual do tema.
- `assets/img/banner-460x60.jpg`: banner da home.
- `arquivos.html`: arquivo automático por ano.
- `tags.html`: índice automático de tags.
- `paginacao.html`: segunda página sem plugin, exibindo posts após o limite definido em `posts_per_page`.

## Configuração rápida

Edite `_config.yml` para alterar domínio, descrição, GitHub, banner e endpoint da newsletter.

Para ativar o clique do banner, preencha `banner_url`.
Para conectar a newsletter, troque `newsletter_action` pelo endpoint do serviço usado.


## Descoberta, redes sociais e agentes de IA

O template inclui Open Graph, Twitter Cards, canonical, JSON-LD, sitemap.xml, feed.xml, robots.txt e llms.txt.
O `robots.txt` permite rastreamento público, incluindo OAI-SearchBot, GPTBot, ChatGPT-User, Google-Extended, ClaudeBot, PerplexityBot e Applebot. A regra `User-agent: *` também permite crawlers compatíveis que não estejam listados nominalmente.

`llms.txt` é incluído como convenção experimental de descoberta por agentes e não deve ser tratado como padrão oficial universal.
