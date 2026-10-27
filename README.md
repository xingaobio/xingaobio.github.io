# Xin Gao — Personal Academic Webpage

> A static personal webpage for Xin Gao, Structural Biologist & Biophysicist.  
> Built with plain HTML + CSS (no frameworks). Hosted on GitHub Pages.

**Live site:** https://xingaobio.github.io

---

## 📁 File structure

```
xingaobio.github.io/
├── index.html       ← the whole page (text + styles, ~23 KB)
├── xingao.png       ← profile photo
├── pub1.png … pub6.png  ← publication figures (same order as the list)
└── README.md        ← this file
```

Images are separate files, so `index.html` is small enough to paste into any AI assistant in full.

---

## 🗂️ Page sections

| Section | What it contains |
|---|---|
| **Header** | Photo, name, title, keywords, short bio, Email / Google Scholar / ORCID / LinkedIn |
| **About** | Three-paragraph research profile |
| **Research Interests** | Four research themes + proteins and disease context studied |
| **Research Experience** | Research Fellow, Birmingham (2024–2026); PhD Researcher, UCL (2018–2023) |
| **Publications** | 6 peer-reviewed papers (thumbnails, own name in bold, DOI, first-author mark, "My contribution"), 1 preprint, 3 conference posters |
| **Education** | PhD (awarded 28 Nov 2023) → MSc → BSc |
| **Teaching & Mentoring** | UCL demonstrating and tutoring, widening participation, 6 supervised students |
| **Skills & Techniques** | Structural / Biophysical / Biochemistry / Computation / Research practice + memberships & activities |
| **Contact** | UCL email, Google Scholar, ORCID, LinkedIn, location |

---

## ✏️ How to edit with AI

Paste this prompt into any AI assistant along with the contents of `index.html`:

```
This is my personal academic webpage (index.html, plain HTML + CSS, hosted on GitHub Pages).
Images are separate files: xingao.png and pub1.png–pub6.png.
Every claim must match my CV evidence; do not add methods or results I have not confirmed.
Keep the existing academic style. Please help me: [describe the change]
```

Typical edits: add a publication (copy one `<li>` block in the Publications list and add a `pubN.png`), add a presentation (copy one `.entry` block), update the bio.

---

## 🖼️ How to update images

Replace the PNG file in the repo with a new one of the same name (Add file → Upload files on GitHub). For a new publication, upload `pub7.png` and point the new `<li>` at it.

---

## 🔗 Publication DOIs

| # | Paper | DOI |
|---|---|---|
| 1 | Bradford et al. 2025 — β2-Glycoprotein I | https://doi.org/10.1016/j.jtha.2025.02.015 |
| 2 | Gao et al. 2024 — Complement Factor H glycans | https://doi.org/10.1016/j.jbc.2024.107624 |
| 3 | Gao et al. 2023 — C5-Fc Nanobody *(Front Cover)* | https://doi.org/10.1016/j.jbc.2023.105337 |
| 4 | Hui & Gao et al. 2023 — CD64 Fc receptor | https://doi.org/10.1371/journal.pone.0288351 |
| 5 | Tang et al. 2023 — Humanised antibody fragment | https://doi.org/10.1038/s41598-023-42698-7 |
| 6 | Dunne & Gao et al. 2021 — Factor H dimerization | https://doi.org/10.3389/fimmu.2020.601895 |
| P1 | Gao 2026 — ChemRxiv preprint v2 (sole author) | https://doi.org/10.26434/chemrxiv.15006416/v2 |

---

## 🎨 Design system (for AI edits)

```
- Fonts: Source Serif 4 (headings + body) + Source Sans 3 (nav, labels, dates)
- Background: white #FFFFFF; text #1D2125; secondary text #4D545D
- Accent (links): navy #1F4E89; hairline rules #E3E5E8
- Style: classic single-column academic page, no cards, no animations
- Layout: max width 820px, sticky top nav, hairline section dividers
- Audience: academic researchers + industry/pharma recruiters
```

---

## 📬 Contact info in the page

| Field | Value |
|---|---|
| Email | xin.gao.15@ucl.ac.uk (shown in header + Contact) |
| Google Scholar | https://scholar.google.com/citations?user=3ESuTcsAAAAJ |
| LinkedIn | linkedin.com/in/xin-gao-uk |
| ORCID | 0000-0003-0877-0643 |
| Location | England, United Kingdom |
