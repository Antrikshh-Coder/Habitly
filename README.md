# 🌱 Habitly – Layout & Habit Cards

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

1. **Custom Vector SVG Logo**:
   - Modern sprout growth mark inside a rounded teal gradient container.
   - Accompanying bold brand title: `Habitly.` with a signature teal terminal period.
2. **Browser SVG Favicon**:
   - Embedded SVG favicon for a polished browser tab appearance.
3. **Productivity Vector Illustration**:
   - Clean, lightweight SVG dashboard graphic integrated into the Welcome card showing habit progression and streak celebration.
4. **User Profile Avatar**:
   - Styled SVG vector avatar with user initials `AM`.
5. **Habit Cards (5 Required Daily Habits)**:
   - 💧 **Drink 2L Water** (Health | Streak: 7 days)
   - 📚 **Read 20 Pages** (Learning | Streak: 12 days)
   - 🏃 **Morning Exercise** (Fitness | Streak: 5 days)
   - 🧘 **Meditation** (Wellness | Streak: 9 days)
   - 💻 **Learn Coding** (Productivity | Streak: 15 days)

---

## 📋 CodGen Week 1 Checklist & Requirements

| Requirement | Specification in Brief | Implementation Details |
| :--- | :--- | :--- |
| **Header** | The Habitly name, logo/emoji, and plain-text date | Features custom SVG logo, `Habitly.` name, subtitle, plain-text date (`Tuesday, 17 November 2026`), and user avatar (`AM`). |
| **Summary Row** | 3 stat cards with hard-coded values | `Done today 3/5` (circular ring), `Best streak 12 days` (fire badge), and `This week 78%` (progress bar). |
| **Habit Cards** | At least 5 cards in a grid with emoji, name, streak, and visible 'Complete' button | 5 daily habits with emojis, titles, teal-highlighted streaks, and visible Complete buttons. |
| **Card Design Guide** | `White + soft shadow + 12px radius` | Habit and stat cards strictly use `border-radius: 12px`, pure `#FFFFFF` background, and soft dual shadows. |
| **Official Colors** | Navy (`#0B1F3A`), Teal (`#14B8A6`), Background (`#F8FAFC`) | All colors configured in `:root`. Teal is used for buttons, accents, and streak highlights as instructed. |
| **Spacing** | Multiples of `8px` | Strict 8px scale: `8px`, `16px`, `24px`, `32px`, `40px`, `48px`. |
| **Typography** | Inter from Google Fonts | Loaded Inter with system font fallback in `font-family`. |
| **Grid Recommendation** | `repeat(auto-fit, minmax(240px, 1fr))` | Applied CSS Grid `repeat(auto-fit, minmax(260px, 1fr))` with 16px gaps for an adaptive multi-column layout. |
| **Responsive** | Must look good at 360px, 768px, and 1280px | 1-column on phone (360px), multi-column on tablet (768px) and laptop/desktop (1280px). Zero horizontal scroll. |
| **Hover States** | Buttons and cards | Smooth elevation transitions on cards, teal hover and lift on buttons. |
| **Footer** | `'Built with the CodGen Frontend Internship \| codgen.in'` | Verbatim match with styled link to `codgen.in`. |

---

## 📁 Project Structure

```text
Habitly/
│
├── index.html        # Semantic HTML5 markup with SVG logo, illustration, and components
├── style.css         # Pure CSS3 stylesheet using CSS variables, Grid, and Flexbox
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

## 🌐 GitHub Pages Deployment Instructions

1. Push your changes:
   ```bash
   git add index.html style.css README.md
   git commit -m "feat: complete CodGen Week 1 Habitly layout with SVG branding"
   git push -u origin main
   ```
2. On GitHub, navigate to **Settings > Pages**.
3. Under **Build and deployment**, select **Deploy from a branch**, set branch to **`main`** and folder to **`/(root)`**.
4. Click **Save**. Your site will be live at `https://antrikshh-coder.github.io/Habitly/`.

---

## 👨‍💻 Author

**Antriksh Manwadkar**  
*CodGen Frontend Development Internship – Week 1*  
Built with the CodGen Frontend Internship | [codgen.in](https://codgen.in)
