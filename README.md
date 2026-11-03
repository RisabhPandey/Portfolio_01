# Risabh Pandey — AI / Machine Learning Portfolio

Modern, dark-themed portfolio website for **Risabh Pandey**, an AI / Machine Learning Engineer specializing in Generative AI, multi-agent systems, RAG pipelines, and production ML applications.

**Live:** [https://risabh-pandey-01.netlify.app/](https://risabh-pandey-01.netlify.app/)

---

## Features

- Clean dark theme with indigo accent
- Fully responsive (mobile-first)
- Typing animation in hero
- Project filtering (All / Multi-Agent / RAG / Deep Learning / LLM Apps)
- Smooth scroll & subtle scroll-reveal animations
- Contact form powered by EmailJS
- Fast, plain HTML + CSS + JS (no framework)

---

## Tech Stack

- HTML5
- CSS3 (custom properties, grid, flexbox)
- Vanilla JavaScript
- EmailJS (contact form)
- Font Awesome 6
- Google Fonts (Inter + JetBrains Mono)

---

## Project Structure

```
Portfolio_01/
├── index.html              # Main page
├── styles.css              # All styles
├── script.js               # Interactions
├── README.md
├── portfolio.png           # Favicon
├── risabh_main_.jpeg       # Profile photo
├── Risabh_Pandey_CV.html   # Resume (downloadable)
└── (optional assets)
```

---

## Sections

1. **Hero** — Name, rotating title, short value prop, CTAs, social links
2. **About** — Photo, professional summary, education, contact details, resume download
3. **Skills** — Grouped: Programming, ML & NLP, Data Analytics, Backend & Deploy, Web
4. **Projects** — 6 real projects with live demos + GitHub links and tech tags
5. **Contact** — Info + EmailJS form

---

## Featured Projects

| Project | Stack | Live |
|---------|-------|------|
| ResearchMind | LangChain, Mistral, FastAPI | [Demo](https://researchmind-multi-agent-ai.onrender.com/) |
| RAG-PDF-Reader | LangChain, ChromaDB, Streamlit | [Demo](https://rag-pdf-reader-01-22.streamlit.app/) |
| Research Paper Classification | GCN, ONNX, FastAPI | [Demo](https://research-paper-classification-xtec.onrender.com/) |
| MNIST Digit Recognizer | TensorFlow CNN, FastAPI | GitHub only |
| Movie Information Extractor | LangChain, Pydantic, Streamlit | [Demo](https://movie-information-extractor-01-22.streamlit.app) |
| AI Video Assistant with RAG | Whisper, ChromaDB | GitHub only |

---

## Local Development

1. Clone the repo:
   ```bash
   git clone https://github.com/RisabhPandey/Portfolio_01.git
   cd Portfolio_01
   ```
2. Open `index.html` in a browser, or use a local server:
   ```bash
   npx serve .
   # or
   python -m http.server 8000
   ```

---

## Deployment (Netlify)

1. Push changes to the `main` branch of this repository.
2. Netlify will auto-deploy if the site is already connected.
3. Or drag-and-drop the folder into [Netlify Drop](https://app.netlify.com/drop).

---

## Replacing Images

| File | Purpose | Notes |
|------|---------|-------|
| `risabh_main_.jpeg` | Profile photo (About section) | Prefer square/portrait, face centered. ~400–600 px. |
| `portfolio.png` | Favicon | 32×32 or 64×64 PNG works well. |

If the profile image is missing, the page falls back to the GitHub avatar.

**Recommended:** Keep the same filenames so no HTML changes are needed. Just overwrite the files.

---

## Resume / CV

The “Download Resume” buttons currently point to `Risabh_Pandey_CV.html`.

To use a proper PDF:

1. Export your resume as `Risabh_Pandey_CV.pdf`.
2. Place it in the root of the repo.
3. Update the two links in `index.html` from:
   ```html
   href="Risabh_Pandey_CV.html" ... download
   ```
   to:
   ```html
   href="Risabh_Pandey_CV.pdf" download="Risabh_Pandey_CV.pdf"
   ```

---

## Contact Form

Uses the existing EmailJS configuration already present in the original site:

- Public key: `wP0j4X8W_J4sYYCDi`
- Service: `service_fnlm2cm`
- Template: `template_xsda5j9`

If you change EmailJS accounts, update the init call in `index.html` and the `emailjs.send(...)` arguments in `script.js`.

---

## Social Links

- **GitHub:** [github.com/RisabhPandey](https://github.com/RisabhPandey)
- **LinkedIn:** [linkedin.com/in/risabhpandey94](https://www.linkedin.com/in/risabhpandey94)
- **Email:** rishabhpandey8176@gmail.com
- **Phone:** +91 9452617299

---

## License

MIT — feel free to use this structure for your own portfolio.
