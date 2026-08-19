# My HBCU Collective — Immersive 3D World Website

**Live repo:** https://github.com/omarshands-rva/my-hbcu-collective

An immersive, continuous 3D universe you navigate by scrolling. Built with Three.js.

## Concept

Centered on the HBCU Collective vision:

- HBCU by Association (Network · Radio · Podcast · Business Directory)
- On The Yard (news & culture)
- Directory by Audience (Universities · Organizations · Alumni Associations)
- Venture Lab
- Coin/Token economy layer
- Social + Email
- “Free Google of the HBCU Space”

## Experience

Scroll drives a cinematic camera path through 7 distinct 3D zones with interactive hover objects, section navigation dots, search, and glass UI panels.

## Run locally

```bash
git clone https://github.com/omarshands-rva/my-hbcu-collective.git
cd my-hbcu-collective
python3 -m http.server 8080
# then open http://localhost:8080
```

Or deploy the folder to Vercel / Netlify / GitHub Pages.

## Files

- `index.html` — Structure + storyboard panels
- `styles.css` — Cinematic dark UI (gold / emerald)
- `main.js` — Three.js world + scroll engine + interactions

---

Built as a high-fidelity 3D world-scroll prototype for the HBCU Collective.
