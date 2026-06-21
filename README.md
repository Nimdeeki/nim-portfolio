# Nim Deeki Sherpa — Personal Portfolio Website

A responsive personal portfolio website built using HTML and CSS, showcasing my background, technical skills, and contact information. This project was built as part of Week 1 (HTML) and Week 2 (CSS) of my web development internship at Developers Arena.

---

##  Project Overview

This portfolio website is a single-page site that introduces me, lists my technical skills, and provides a way for visitors to contact me. The goals of this project were to:

- Practice semantic HTML structure (header, nav, main, section, footer)
- Apply CSS styling concepts — selectors, the box model, positioning, Flexbox, and responsive design
- Build a clean, professional, mobile-friendly layout from scratch
- Get hands-on experience with the full HTML → CSS workflow used in real web projects

---

## Setup Instructions

To run this project locally you can do this:

1. download this repository
   ```
   git clone https://github.com/nimdeeki/portfolio.git
   ```
2. Open the project folder in VS Code (or any code editor)
3. Make sure the following files are in the same folder:
   - `index.html`
   - `style.css`
   - `images/` folder (containing `nim.jpeg`)
4. Open `index.html` using the **Live Server** extension in VS Code
   (Right-click `index.html` → "Open with Live Server")
5. The site will open in your browser at `http://127.0.0.1:5500` (or similar)



##  Code Structure

```
portfolio/
│
├── index.html          # Main HTML file — page structure and content
├── style.css            # External stylesheet — all styling and layout
├── README.md             # Project documentation (this file)
│
├── images/
│   └── nim.jpeg          # Profile picture used in the About section
│
└── screenshots/
    ├── desktop-view.png  # Full page screenshot — desktop
    
```

### File responsibilities

| File | Purpose |
|---|---|
| `index.html` | Contains the page structure: header/nav, About section, Skills section, Contact form, and Footer |
| `style.css` | Contains all visual styling — colors, typography, layout, hover effects, and responsive media queries |

---

## CSS Concepts Used

| Concept | Where it's used |
|---|---|
| **External CSS** | Single `style.css` file linked via `<link>` in the HTML `<head>` |
| **Element selector** | `body`, `nav a`, `hr` |
| **ID selector** | `#about`, `#skills`, `#contact` — targeting each unique page section |
| **Pseudo-class selector** | `:hover` on nav links, buttons, skill tags; `:focus` on form inputs |
| **CSS Box Model** | `padding`, `margin`, and `border-box` sizing used throughout for consistent spacing |
| **Flexbox** | Used for the header/nav bar, skills tag list, contact form, and footer layout |
| **CSS Variables (`:root`)** | Centralized color scheme (`--primary`, `--accent`, `--dark`, etc.) for easy theme changes |
| **Transitions** | Smooth hover animations on buttons, links, and skill tags (`transition: all 0.3s ease`) |
| **Media Queries** | Two breakpoints (`768px` and `480px`) to adapt layout for tablets and mobile phones |
| **Google Fonts** | Poppins font imported and applied site-wide for consistent, modern typography |

---

## Responsiveness Approach

The site is built mobile-first in mindset, using **Flexbox** for all layout sections so elements naturally adapt to different screen widths. Two media query breakpoints handle the bigger structural changes:

- **`@media (max-width: 768px)`** — Tablets and large phones: the header stacks vertically instead of side-by-side, and the contact form expands to full width
- **`@media (max-width: 480px)`** — Small phones: font sizes are reduced and navigation spacing is tightened so text doesn't feel cramped

This was tested by resizing the browser window in Chrome DevTools (toggle device toolbar) to simulate different screen sizes.

---

## Testing Evidence

The site was tested for:

- **Cross-browser consistency** — checked in Google Chrome and Microsoft Edge
- **Responsive behavior** — verified using Chrome DevTools device toolbar at common breakpoints (375px mobile, 768px tablet, 1440px desktop)
- **Functional checks**:
  - All navigation links scroll to the correct section
  - Hover effects trigger correctly on nav links, skill tags, and buttons
  - Contact form fields show focus state when clicked
  - Required fields (`name`, `email`) cannot be submitted empty
  - External links (GitHub, LinkedIn) open in a new tab

---



## Connect

- **GitHub:** [github.com/nimdeeki](https://github.com/nimdeeki)
- **LinkedIn:** [Nim Deeki Sherpa](https://www.linkedin.com/in/nim-deeki-sherpa-b226b9329)

---

© 2026 Nim Deeki Sherpa
