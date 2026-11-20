# 🚀 Habitly – Layout & Habit Cards

> **CodGen Frontend Development Internship | Habitly**  
> **Week 1 Task Brief: Build the Habitly Layout**  
> Built by **Antriksh Manwadkar**

---

## 📌 Project Overview

**Habitly** is a clean, modern, and responsive static habit-tracking dashboard built strictly according to the **CodGen Week 1 Task Brief: Layout & Habit Cards**. It allows users to visually inspect their daily habits, track active streaks, and observe progress statistics in a well-crafted SaaS interface.

- **Technologies**: Pure HTML5 & CSS3 (Zero JavaScript)
- **Live Demo (GitHub Pages)**: [https://antrikshh-coder.github.io/Habitly/](https://antrikshh-coder.github.io/Habitly/)
- **GitHub Repository**: [https://github.com/Antrikshh-Coder/Habitly](https://github.com/Antrikshh-Coder/Habitly)

---

## 🎨 Visual Assets & Design Details

1. **Official Brand Logo**:
   - High-resolution Habitly calendar with active checkmark logo (`logo.jpg`).
   - Accompanying bold brand title: `Habitly.` with a signature teal terminal period.
2. **Browser Tab Favicon**:
   - Linked to `logo.jpg` for a polished browser tab appearance.
3. **Daily Habits Tracked**:
   - 💧 **Drink 2L Water** (Category: Health | Streak: 7 days)
   - 📚 **Read 20 Pages** (Category: Learning | Streak: 12 days)
   - 🏃 **Morning Exercise** (Category: Fitness | Streak: 5 days)
   - 🧘 **Meditation** (Category: Wellness | Streak: 9 days)
   - 💻 **Learn Coding** (Category: Productivity | Streak: 15 days)

---

## 📋 CodGen Week 1 Checklist & Requirements

| Requirement | Specification in Brief | Implementation Details |
| :--- | :--- | :--- |
| **Header** | The Habitly name, logo/emoji, and plain-text date | Features official `logo.jpg`, `Habitly.` name, tagline, and plain-text date (`Friday, 20 November 2026`). |
| **Summary Row** | 3 stat cards with hard-coded values | `Done today 3/5` (circular ring), `Best streak 12 days` (fire badge), and `This week 78%` (progress bar). |
| **Habit Cards** | At least 5 cards in a grid with emoji, name, streak, and visible 'Complete' button | 5 daily habits forming a responsive grid with pastel emoji containers, category badges, teal-highlighted streaks, and visible Complete buttons. |
| **Card Design Guide** | `White + soft shadow + 12px radius` | Habit and stat cards strictly use `border-radius: 12px`, pure `#FFFFFF` background, and soft dual shadows. |
| **Official Colors** | Navy (`#0B1F3A`), Teal (`#14B8A6`), Background (`#F8FAFC`) | All colors configured in `:root`. Teal is used for buttons, accents, and streak highlights as instructed. |
| **Spacing** | Multiples of `8px` | Strict 8px scale: `8px`, `16px`, `24px`, `32px`, `40px`. |
| **Typography** | Inter from Google Fonts | Loaded Inter with system font fallback in `font-family`. |
| **Grid Recommendation** | `repeat(auto-fit, minmax(240px, 1fr))` | Applied responsive grid with `repeat(auto-fit, minmax(260px, 1fr))` and 20px gaps. |
| **Responsive** | Must look good at 360px, 768px, and 1280px | 1-column on phone (360px), 2-column on tablet (768px), and multi-column on laptop/desktop (1280px). Zero horizontal scroll. |
| **Hover States** | Buttons and cards | Smooth elevation transitions on cards, teal hover and lift on buttons. |
| **Footer** | `'Built with the CodGen Frontend Internship \| codgen.in'` | Verbatim match with styled link to `codgen.in`. |

---

## 📁 Project Structure

```text
Habitly/
│
├── index.html        # Semantic HTML5 markup with brand logo, cards, and footer
├── style.css         # Pure CSS3 stylesheet using CSS variables, Grid, and Flexbox
├── logo.jpg          # Official Habitly brand logo
├── .nojekyll         # GitHub Pages static deploy marker
└── README.md         # Project documentation and submission details
```

---

## 🚀 How to Run Locally

```bash
# Option 1: Direct open in default browser
open index.html

# Option 2: Lightweight local HTTP server
python3 -m http.server 8000
```
Then visit `http://localhost:8000`.

---

## 🌐 Submission Links

When submitting via your CodGen submission form, provide these two links:

1. **GitHub Repository Link**:
   `https://github.com/Antrikshh-Coder/Habitly`
2. **Live GitHub Pages Link**:
   `https://antrikshh-coder.github.io/Habitly/`

*(Make sure to verify the live link in an incognito window before submitting, as instructed in the brief!)*

---

## 👨‍💻 Author

**Antriksh Manwadkar**  
*CodGen Frontend Development Internship – Week 1*  
Built with the CodGen Frontend Internship | [codgen.in](https://codgen.in)
