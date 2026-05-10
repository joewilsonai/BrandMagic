# BrandMagic

**Turn your boring content into branded assets.**

A lightweight AI app that takes raw content — a blog post, a screenshot, a quote, a clip — and rewraps it in your brand: fonts, colors, layout, voice. Ready to share in seconds.

## What it does

- **Drop in raw content** — text, image, or URL
- **Pick a brand kit** — color palette, font pairing, tone of voice
- **Get back a branded asset** — social card, blog header, quote graphic, or share image

## Stack

- **React** + **TypeScript** + **Vite**
- **Google Gemini** for content + brand transformation
- Single-page app, no backend

## Run locally

```bash
git clone https://github.com/joewilsonai/BrandMagic
cd BrandMagic
npm install
# Add your Gemini API key to .env.local:
#   GEMINI_API_KEY=your_key_here
npm run dev
```

## License

MIT
