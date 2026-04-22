# Xin Gao — Personal Academic Webpage

> A static personal webpage for Xin Gao, Structural Biologist & Biophysicist.  
> Built with plain HTML + CSS (no frameworks). Hosted on GitHub Pages.

**Live site:** https://xingaobio.github.io

---

## 📁 File structure

```
xingaobio.github.io/
├── index.html       ← entire webpage (all images embedded inside)
└── README.md        ← this file
```

> All photos are embedded directly inside `index.html` as base64 data — so you only ever need to manage one file.

---

## 🗂️ Page sections

| Section | What it contains |
|---|---|
| **Hero** | Name, title, photo, bio, links to email / LinkedIn / ORCID |
| **About** | Profile summary, key stats (years, publications, students) |
| **Research Interests** | 3 cards + target proteins + computational tools |
| **Publications** | 6 papers with images, year badges, DOI links |
| **Education** | PhD → MSc → BSc timeline |
| **Skills** | Biophysical / Structural / Biochemistry / Leadership chips |
| **Conferences** | 3 presentations |
| **Contact** | Email, LinkedIn, ORCID, location |

---

## ✏️ How to edit with AI

Paste this prompt into any AI assistant (Claude, ChatGPT, etc.) along with the contents of `index.html`:

---

### 🤖 Prompt template

```
I have a personal academic webpage for Xin Gao, a structural biologist.
The entire site is in a single index.html file (images are base64-embedded inside it).

Here is the current index.html:
[paste file contents here]

Please help me: [describe what you want to change]

Examples of things I might ask:
- "Update my bio in the About section to say..."
- "Add a new publication: title, authors, journal, year, DOI"
- "Change the accent colour from teal to deep blue"
- "Add a new conference presentation"
- "Replace the hero subtitle with..."
- "Add a new skills category called 'Languages' with Python, R, MATLAB"
```

---

## 🖼️ How to update images

Because images are embedded in the HTML, to update a photo:

1. Open `index.html` in a text editor or on GitHub (pencil icon ✏️)
2. Search for the image you want to replace (Ctrl+F):
   - Profile photo: search for `alt="Xin Gao"`
   - Publication images: search for `alt="Publication 1 image"` through `alt="Publication 6 image"`
3. Replace the entire `src="data:image/png;base64,..."` value with a new base64 string

**Or — ask an AI:**
> "Please replace the profile photo in my index.html with this new image"  
> *(attach both the HTML file and the new image)*

---

## 🔗 Publication DOIs

| # | Paper | DOI |
|---|---|---|
| 1 | Bradford et al. 2025 — β2-Glycoprotein I | https://doi.org/10.1016/j.jtha.2025.03.006 |
| 2 | Gao et al. 2024 — Complement Factor H glycans | https://doi.org/10.1016/j.jbc.2024.107624 |
| 3 | Gao et al. 2023 — C5-Fc Nanobody *(Front Cover)* | https://doi.org/10.1016/j.jbc.2023.105337 |
| 4 | Hui & Gao et al. 2023 — CD64 Fc receptor | https://doi.org/10.1371/journal.pone.0288351 |
| 5 | Tang et al. 2023 — Humanised antibody fragment | https://doi.org/10.1038/s41598-023-42504-4 |
| 6 | Dunne & Gao et al. 2021 — Factor H dimerization | https://doi.org/10.3389/fimmu.2020.601895 |

---

## 🎨 Design system (for AI edits)

If asking an AI to redesign or restyle, share this context:

```
Design system:
- Fonts: Lora (headings, serif) + DM Sans (body, sans-serif)
- Background: warm ivory #FAF8F4
- Accent colour: teal oklch(50% 0.13 182)
- Secondary accent: amber oklch(62% 0.13 55)
- Text: dark brown #2A2118
- Style: warm, approachable, academic
- Layout: single scrolling page with sticky nav
- Audience: academic researchers + industry/pharma recruiters
```

---

## 📬 Contact info in the page

| Field | Value |
|---|---|
| Email | xingaouk@gmail.com |
| LinkedIn | linkedin.com/in/xin-gao-uk |
| ORCID | 0000-0003-0877-0643 |
| Location | England, United Kingdom |
