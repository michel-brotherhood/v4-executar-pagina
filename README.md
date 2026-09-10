# V4 Executar — Landing Page

Landing page estática recriada a partir da referência visual da V4 Company.

## Cloudflare Pages / Workers Static Assets

Configuração recomendada ao conectar este repositório:

- **Framework preset:** None
- **Build command:** deixe vazio, ou use `npx wrangler deploy` se o projeto estiver usando o fluxo Workers Static Assets
- **Build output directory:** `public`
- **Root directory:** `/`
- **Production branch:** `main`

O conteúdo público está em `public/`, com `public/index.html` na raiz do diretório de saída. O `wrangler.jsonc` aponta explicitamente para essa pasta para evitar o upload de `.git` ou arquivos de configuração como assets do site.
