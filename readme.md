# William Tom Jacob — Portfolio Website

A single-page portfolio site for **William Tom Jacob**, AI Engineer specializing in RAG systems, LLM fine-tuning, and model deployment. Built with plain HTML and CSS — no frameworks, no build step.

## 🌐 Live Preview

Open `index.html` in any browser, or host the folder on any static site provider (GitHub Pages, Netlify, Vercel, etc.).

## 📁 Project Structure

```
.
├── index.html      # Page markup and content
├── style.css       # All styling (colors, layout, animations, responsive rules)
└── images/
    └── profile.jpeg  # Avatar shown in the nav bar
```

## ✨ Sections

| Section        | Description                                                                              |
| -------------- | ---------------------------------------------------------------------------------------- |
| Hero           | Name, role tags, short intro, and quick-action buttons                                   |
| Stats          | Years of experience, CGPA, LLM APIs integrated, projects shipped                         |
| About          | Background summary and core strengths                                                    |
| Skills         | Tech stack grouped by category (languages, GenAI/LLM, ML/DL, data, backend, data stores) |
| Projects       | Featured and side projects with stack tags and repo links                                |
| Experience     | Work history with role, org, dates, and highlights                                       |
| Certifications | Professional certificates                                                                |
| Education      | Degrees, institutions, and CGPA                                                          |
| Contact        | Email, LinkedIn, GitHub, and location/phone                                              |

## 🎨 Customization

All design tokens live at the top of `style.css` under `:root`:

```css
:root {
  --bg: #0b1220; /* page background */
  --bg-raised: #101a2e; /* raised panels (e.g. nav bar) */
  --bg-card: #16213a; /* card surfaces */
  --fg: #eaf0fb; /* primary text */
  --fg-dim: #9aaac7; /* secondary/dimmed text */
  --magenta: #3b82f6; /* primary accent color */
  --gold: #7dd3fc; /* secondary accent color */
  --rule: rgba(234, 240, 251, 0.1); /* borders/dividers */
  --max: 1040px; /* max content width */
}
```

Change these variables to re-theme the entire site without touching the rest of the CSS.

Fonts used (loaded via Google Fonts in `index.html`):

- **Fraunces** — headings
- **Inter** — body text
- **Space Mono** — labels, tags, and monospace accents

## 📱 Responsive Design

The layout adapts at the following breakpoints:

- `760px` — stacks the About grid and Projects grid into a single column, hides nav links
- `680px` — stats and certifications grids switch to 2 columns
- `600px` — experience items stack vertically

## ♿ Accessibility

- Respects `prefers-reduced-motion` to disable animations for users who prefer it
- Visible focus outlines on interactive elements (`:focus-visible`)
- Semantic HTML structure (`nav`, `header`, `section`, `footer`)

## 🛠️ Tech Used

- HTML5
- CSS3 (custom properties, Grid, Flexbox, keyframe animations)
- Google Fonts

## 📬 Contact

- **Email:** williamtom45@gmail.com
- **LinkedIn:** [linkedin.com/in/william-tom-jacob](https://linkedin.com/in/william-tom-jacob)
- **GitHub:** [github.com/williamtom3010](https://github.com/williamtom3010)
- **Location:** Trivandrum, Kerala, India

---

© 2026 William Tom Jacob
