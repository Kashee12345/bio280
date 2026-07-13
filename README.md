# The Interactive Body — BIO 280 (Joyce University)

A free, animated, interactive pathophysiology study resource. **86 hands-on lessons**
covering the entire BIO 280 semester (Weeks 1–14), across 16 body-system sections.
Every lesson is a single self-contained HTML file — no installs, no accounts, works on
any phone, tablet, or projector.

A study resource for **Joyce University** BIO 280 students, by **Dr. Akash Garg**.
*(An independent supplement — not an official Joyce University publication.)*

---

## The site (4 pages + 86 lessons)

This is a small multi-page website. The four top-level pages share a navigation bar:

| Page | File | What it is |
|------|------|------------|
| **Home** | `index.html` | Landing page — welcome, highlights, and the two ways in |
| **Lessons** | `lessons.html` | The full library: all 86 lessons grouped by body system |
| **By Week** | `weeks.html` | The same lessons mapped to BIO 280 Weeks 1–14 |
| **About** | `about.html` | What it is, how to use it, and the disclaimer |

`index.html` is the front door — start there. Every other file is one of the 86
interactive lessons, all sitting in this same folder so the links resolve.

The 16 lesson sections: Fluids & Electrolytes · Acid-Base & ABGs · Pathogens &
Immunity · Cells, Cancer & Inflammation · Sepsis, Pain & Neuro · Mental Health &
Brain · MSK, Skin & Burns · Genetics · Endocrine · Blood · Heart & Vessels · Kidneys
& Urinary · Lungs · Gut · Liver, Bile & Pancreas · Reproductive Systems.

Highlights include two interactive **calculators** — the **ABG Interpreter** and the
**Punnett Square Calculator** — plus draggable sliders (intracranial pressure,
electrolytes, CKD), audio (Lung Sounds), and a 3D coronary-artery voyage.

---

## View it locally

Just **double-click `index.html`** — it opens in any browser. Click through Home →
Lessons / By Week, tap any lesson, and use the browser's Back button to return.

---

## Publish it free (GitHub Pages)

1. Create a new repository on GitHub (e.g. `bio280`).
2. Upload **every file in this folder** — keep them together; the lessons must sit next
   to `index.html`.
3. In the repo: **Settings → Pages → Source → `main` branch / root → Save**.
4. In about a minute your site is live at
   `https://YOUR-USERNAME.github.io/bio280/`.

Share the link with students — the Home page loads first.

---

## Notes

- Everything is self-contained and works offline **except** two internet-based pieces:
  Google Fonts (used site-wide for styling) and the **CoronaryQuest3D** lesson, which
  streams the Three.js 3D library from a CDN. Both just look their best when online.
- No tracking, no ads, no sign-up. 100% free to use and share.
