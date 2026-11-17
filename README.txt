Blackwell Dictionary - files
  public/index.html           the website
  worker.js + wrangler.jsonc  Cloudflare (Workers) - serves the site and the chat at /api/chat
  api/chat.js                 chat server if you ever use Vercel
  netlify/ + netlify.toml     chat server if you ever use Netlify

Set these variables on your host, then redeploy:
  GEMINI_API_KEY   (secret)  your key from aistudio.google.com/apikey
  AI_MODEL                   e.g. gemini-3.5-flash-lite
  AI_THINKING                optional, e.g. low
