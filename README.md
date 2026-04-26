# Fur-Reel News

The official site for **Fur-Reel News** — a comedy news show concept anchored by Dan Retriever (golden retriever, lead anchor) and Allison Catpur (white Persian, co-anchor / culture & contempt). Format: SNL Weekend Update, but every anchor has fur and zero patience.

Currently in production. Video segments will be generated with Kling AI 3.0 once the first batch of stories is locked.

## What's here

A single-page static site presenting the show concept:

- Live news ticker with rotating fake headlines
- Hero shot of the anchors at the desk
- Bio cards for Dan and Allison
- "Story Lineup" portfolio of pilot stories
- Behind-the-set photo gallery
- Weekly programming plan
- Newsletter signup ("The Bark & Mew")

## Stack

Plain HTML, CSS, and a tiny bit of vanilla JS. No build step. No dependencies. Fonts loaded from Google Fonts (Bebas Neue, Fraunces, DM Sans, JetBrains Mono).

## Local dev

From inside this folder:

```bash
python3 -m http.server 8000
```

Open <http://localhost:8000>.

## Deploy

The site is fully static — drop it on any host. Easiest path is GitHub Pages (see below), but Netlify, Vercel, Cloudflare Pages, or S3 all work with zero config.

## Structure

```
fur-reel-news/
├── index.html          # the whole site
├── images/             # AI-generated stills of the anchors and set
└── README.md
```

## Roadmap

- [ ] Add real video segments once Kling AI clips are produced
- [ ] Wire newsletter signup to a real provider (Buttondown / Beehiiv / ConvertKit)
- [ ] Episode permalinks once content exists
- [ ] About page with show pitch deck

## Credits

- Concept &amp; production: Greg
- Anchors: Dan Retriever, Allison Catpur
- Set photography: AI-generated, custom for the show
- Web design: built with Claude
