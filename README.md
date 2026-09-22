# 0xR0H4N — Portfolio Website

A cyberpunk-themed, single-page portfolio site for **Rohan S.**, a cybersecurity researcher and CTF player. Built as a self-contained HTML/CSS/JS page with a terminal/hacker aesthetic — scanlines, glitch effects, animated particles, and reveal-on-scroll sections.

🔗 **Live site:** [0xr0h4n.netlify.app](https://0xr0h4n.netlify.app)

---

## 👤 About

3rd-year Computer Science (Cybersecurity) student at **Jerusalem College of Engineering, Chennai**, focused on offensive security and vulnerability research.

- 🛡️ **President of CyberNexus** — college cybersecurity club
- 🚩 **Jr. Lead at Flaggers United** — a growing CTF community
- 🎯 RE/PWN player — reverse engineering & binary exploitation
- 🏆 Responsibly disclosed vulnerabilities to **NASA, Ferrari, WHO, UNICEF, UNESCO, Zoho, LG**, and more

## ✨ Features

- Fully responsive single-page layout (desktop → mobile)
- Animated hero section with glitch text, floating particles, and a rotating gradient photo frame
- Graceful image fallbacks — hero photo and CTF snapshots show styled placeholders if the image file isn't found
- Terminal-style "About" panel with a typewriter status line
- Skills grid, awards grid, and a Bug Bounty Hall of Fame section with verified disclosure badges
- Scroll-triggered reveal animations via `IntersectionObserver`
- Social links: GitHub, LinkedIn, X/Twitter, YouTube, Medium, HackerOne, Bugcrowd

## 🗂️ Sections

| Section | Description |
|---|---|
| **Hero** | Name, tagline, stats (CTF wins, Hall of Fames, best rank) |
| **About** | Bio, roles, terminal-style profile card |
| **Skills** | Web app security, pentesting, OSINT, reverse engineering, etc. |
| **Awards** | CTF competition placements (1st/2nd) across colleges & communities |
| **Hall of Fame** | Verified bug bounty recognitions from major organizations |
| **CTF Moments** | Photo grid of CTF wins (with placeholders until images are added) |
| **Contact** | Social links + terminal-style "connect" panel |

## 🛠️ Tech Stack

- **HTML5 / CSS3** — no frameworks, single self-contained file
- **Vanilla JavaScript** — particles, image fallback logic, scroll reveal, typewriter effect
- **Google Fonts** — Russo One, Share Tech Mono, Rajdhani
- Hosted on **Netlify**

## 🚀 Running Locally

No build step required — it's a static file.

```bash
git clone https://github.com/0xr0hrncr7/<repo-name>.git
cd <repo-name>
```

Then just open `index.html` in your browser, or serve it locally:

```bash
python3 -m http.server 8000
```

## 🖼️ Adding Photos

Drop these files into the project root:

- `photo.jpeg` — hero profile photo
- `1.jpeg` through `8.jpeg` — CTF moment photos

If a file is missing, the page automatically falls back to a styled placeholder — no code changes needed.

## 📬 Connect

- GitHub: [@0xr0hrncr7](https://github.com/0xr0hrncr7)
- LinkedIn: [in/0xr0h4n](https://in.linkedin.com/in/0xr0h4n)
- X/Twitter: [@Rohan8889965802](https://x.com/Rohan8889965802)
- HackerOne: [0xr0h4ncr7](https://hackerone.com/0xr0h4ncr7)
- Bugcrowd: [0xr0h4n](https://bugcrowd.com/0xr0h4n)
- Medium: [@0xr0h4n](https://0xr0h4n.medium.com/)

---

<p align="center">Crafted with ♥ by ROHAN S. · 0xr0h4n · © 2026</p>
