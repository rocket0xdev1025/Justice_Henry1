# Justice for Henry Nowak — $HENRY Website

A powerful, modern single-page website built with Tailwind CSS (CDN) + vanilla JavaScript.

## Features
- Striking hero with real portrait and powerful case imagery
- Full narrative of the tragedy + visual timeline
- 4 official embedded X/Twitter posts (Ben Habib, Visegrad24, Vox Populi, Keir Starmer)
- Clear **4-step "Buy $HENRY using ETH"** guide (MetaMask + Uniswap on Ethereum)
- Prominent contract address (one-click copy everywhere)
- Interactive "I Stand With Henry" pledge + confetti animation
- Fully responsive + mobile menu
- Keyboard shortcut: press **C** to copy the CA
- Live-ish price ticker + smooth interactions
- Direct links to Uniswap + DexScreener

## Token
- **Ticker**: $HENRY
- **Chain**: Ethereum
- **Contract**: `0x652b1284d689f7e7b77128f08f5fb90fe893ae1b` (demo address — replace with real $HENRY ETH contract if different)

## How to view / run locally
Simply open `index.html` in any modern browser.

For best experience (Twitter embeds + images):
```powershell
# Optional — serve locally
npx serve . -p 5173
# or
python -m http.server 5173
```

Then visit http://localhost:5173

**Note**: Twitter embeds require an internet connection.

## Assets
All images are stored in `/assets/images/`:
- `henry_avatar.jpg` — clean portrait (used in nav/logo)
- `henry_photo.jpg` — powerful split image (Henry vs killer)
- `father_statement.png` — Henry with his mother
- `contrast_bored.png` — killer at sentencing

## Customize
- Update the contract address in one place (search for the 0x address)
- Swap images easily in `/assets/images`
- Change colors via the `.justice-red` / tailwind classes
- Typography: Anton (display) for bold justice headlines, Playfair Display serif for the story narrative

## Deploy
Drop the folder on Netlify, Vercel, GitHub Pages, or Cloudflare Pages. Zero build step needed.

Built to honor Henry Nowak and keep the demand for bodycam footage and police accountability alive.

#JusticeForHenryNowak
