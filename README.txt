Blackwell Dictionary - files
  index.html                  the website
  netlify/functions/chat.js   chat server for Netlify (+ netlify.toml)
  functions/api/chat.js       chat server for Cloudflare Pages
  api/chat.js                 chat server for Vercel

Set these environment variables on whichever host you use, then redeploy:
  GEMINI_API_KEY   your key from aistudio.google.com/apikey
  AI_MODEL         e.g. gemini-3.5-flash-lite
  AI_THINKING      optional, e.g. low
