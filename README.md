# Clinical & Medical Statistics — A Reference Booklet

**Author:** Jayant Rane  
**Affiliation:** Clinical Academic Consultant in Clinical Oncology, UCLH / University College London  
**Year:** 2025

A concise, applied reference booklet for clinicians and clinical researchers. Covers study design, clinical trial methodology, bias, complex and adaptive trial designs, survival analysis, regression, diagnostic accuracy, meta-analysis, translational statistics, and practical software commands for R, Stata, and SPSS.

## Live site

**[View the booklet online →](https://YOUR-USERNAME.github.io/YOUR-REPO-NAME/)**

*(Replace the URL above with your actual GitHub Pages URL after deployment.)*

## Contents

| Section | Topic |
|---------|-------|
| 01 | Study Design & Evidence Hierarchy |
| 01a | Randomised Trials |
| 01b | Observational Studies |
| 01c | Bias in Clinical Trials |
| 01e | Complex Trials with Translational Research |
| 01f | Confounders in Trial Design |
| 01g | Oncology Trial Atlas |
| 01h | Surgical Lessons from Oncology Trials |
| 01i | Trial Phases |
| **01k** | **Sample Size & Power Calculation** *(new)* |
| 01j | Small Sample Strategies |
| 02 | Types of Variables |
| 02b | Visualising Clinical Data |
| **04b** | **Statistical Test Decision Flowchart** *(new)* |
| 03 | Probability |
| 04 | Hypothesis Testing & p-values |
| 05 | Multiple Hypothesis Testing |
| 06 | Diagnostic Tests |
| 07 | Survival Analysis |
| **07** | **Kaplan-Meier Curves — Annotated** *(new)* |
| 08 | Regression Analysis |
| 08b | Confounding, Adjustment & Interaction |
| 08c | Reporting Templates & Common Mistakes |
| 09 | Meta-analysis |
| **09a** | **Forest Plot — Annotated** *(new)* |
| 09b | Translational Statistics |
| 10 | R, Stata & SPSS |

## Features

- 100 pages including 4 new visual pages and 16 pages with fill panels
- Interactive table of contents with section navigation
- Full-text search across all section titles
- Click any page to fullscreen
- Keyboard navigation (← → arrow keys, `T` for contents, `/` for search)
- Swipe navigation on mobile
- 97+ active external reference links per section
- Works offline once loaded (images are local files)
- Shareable URLs: every page has a unique hash (e.g. `#survival`, `#p71`)

## How to deploy on GitHub Pages

1. **Fork or create** a new repository on GitHub  
2. **Upload all files** — keep the folder structure:
   ```
   index.html
   pages/
     p001.jpg
     p002.jpg
     ... (100 files)
   README.md
   ```
3. Go to **Settings → Pages**  
4. Under **Source**, select `main` branch, root folder `/`  
5. Click **Save** — your site will be live at `https://YOUR-USERNAME.github.io/YOUR-REPO-NAME/`

### Using Git (recommended)

```bash
git clone https://github.com/YOUR-USERNAME/YOUR-REPO-NAME.git
cd YOUR-REPO-NAME
# Copy index.html, pages/ folder, README.md into this directory
git add .
git commit -m "Initial booklet upload"
git push origin main
```

## File structure

```
index.html          Main HTML file (122 KB — lightweight, no embedded images)
pages/              Folder of 100 page images (11 MB total, ~110 KB each)
  p001.jpg          Title page
  p002.jpg          Index
  p003.jpg          Study Design & Evidence Hierarchy
  ...
  p100.jpg          SPSS Workflow
README.md           This file
```

## Keyboard shortcuts

| Key | Action |
|-----|--------|
| `→` / `↓` / `Space` | Next page |
| `←` / `↑` | Previous page |
| `Home` | First page |
| `End` | Last page |
| `T` | Toggle table of contents |
| `/` or `S` | Focus search |
| `Esc` | Close search / fullscreen / sidebar |

## License

© 2025 Jayant Rane. All rights reserved.  
For educational and non-commercial clinical research use.
