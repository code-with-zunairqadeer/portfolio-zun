# Portfolio Website 🌐

My personal portfolio site — the public face of my GitHub. Built with plain
HTML, CSS, and JavaScript: no frameworks, no build step, deploys anywhere.

**Live:** https://stately-pie-3411a1.netlify.app

## What's on it

- **Hero** — who I am and where I'm headed (AI/ML & AI agents)
- **About** — background, focus areas, approach
- **Projects** — featured repos with links (grows as I ship)
- **Stack** — languages, tools, and focus areas
- **Contact** — LinkedIn and GitHub links

## Run locally

Just open `index.html` in a browser — or serve it properly:

```bash
# Python
python -m http.server 8000

# Node
npx serve .
```

Then visit http://localhost:8000.

## Project structure

```
portfolio-zun/
├── index.html   # all content & structure
├── styles.css   # dark theme, responsive layout
├── script.js    # mobile nav + scroll reveal
└── README.md
```

## Deployment

Static site — deployed on **Netlify** with continuous deployment from `main`.
Every push here rebuilds the live site automatically.

---

*Part of my long-term portfolio: [github.com/code-with-zunairqadeer](https://github.com/code-with-zunairqadeer)*
