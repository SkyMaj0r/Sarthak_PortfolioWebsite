# Sarthak Suwan — Portfolio

> नित्यं जाग्रतः भव — *Always be vigilant.*

Personal portfolio of **Sarthak Suwan** (`SkyMaj0r`) — Computer Science student at SRM IST Chennai, working at the intersection of cybersecurity and software engineering.

A single, dependency-free `index.html`. No build step, no framework, no tracking.

## Highlights

- **Reconnaissance** — a live, client-side demonstration of what any website can passively read from a visitor (device, browser, GPU, network, session signals, WebRTC local-IP exposure). Runs entirely in the browser; nothing is logged, stored, or transmitted.
- **Featured project** — *MSME Shield*, a CERT-In-aligned cyber risk quantification platform.
- Custom cursor, cursor-reactive background orbs, scroll-reveal, and a typewriter hero hint — built with restraint in a Dieter Rams–inspired minimalist system.
- Fully responsive, dark theme, accessible markup.

## Stack

Vanilla HTML, CSS, and JavaScript. Type: Cormorant Garamond + DM Sans (Google Fonts). No external JS dependencies.

## Structure

```
.
├── index.html      # entire site — markup, styles, and scripts
└── README.md
```

## Run locally

Open `index.html` in a browser, or serve it:

```bash
python3 -m http.server 8000
# visit http://localhost:8000
```

> Note: the Reconnaissance network lookup (public IP / ISP / location) only resolves over HTTPS on the deployed site. Opening via `file://` or plain `localhost` will show those fields as *blocked / offline* — everything else still runs.

## Deploy

Static — host anywhere. Currently deployed on **Netlify**:

1. Push this repo to GitHub.
2. Netlify → *Import an existing project* → select the repo.
3. Leave build command and publish directory empty. Deploy.

Every push to `main` redeploys automatically. Works equally well on GitHub Pages or Cloudflare Pages.

## Privacy

The Reconnaissance section is a transparency demonstration, not a tracker. All collection happens in the visitor's browser and is discarded. There is no analytics, no backend, and no persistence anywhere in this project.

## Contact

- Email — sarthaksuwan30@gmail.com
- GitHub — [github.com/SkyMaj0r](https://github.com/SkyMaj0r)
- LinkedIn — [Sarthak Suwan](https://linkedin.com/in/sarthak-suwan-670a33224)

---

© 2026 Sarthak Suwan.
