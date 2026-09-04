# PureGPT
Secure Cloudflare Worker project.

## Important
The API key is NOT included in these files.

After deployment, add a Cloudflare secret named:
OPENAI_API_KEY

Do not put the API key in index.html or script.js.

Files:
- src/worker.js: secure server-side API proxy
- public/index.html
- public/style.css
- public/script.js
- wrangler.jsonc
- package.json
