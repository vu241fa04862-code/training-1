# ⚡ PulseFit // Pro Athletic & Biometrics Bento Grid

A modern, responsive Bento Grid dashboard interface engineered using **pure HTML5 and Vanilla CSS (CSS Grid & Flexbox)** with **zero JavaScript or external frameworks**.

Designed with a brand-new, unique theme: **Next-Gen Pro Athletic Performance & Biometric Intelligence OS**, meticulously adhering to the reference bento grid proportions, cell spans, and responsive stacking flow.

---

## 📸 Layout Highlights

### 🖥️ Desktop Layout (4 Columns × 3 Rows CSS Grid)
The desktop layout utilizes named `grid-template-areas` with precise cell spanning:
- **Card 1 (Routine Generator):** Column 1, Row 1 (Warm Cream accent)
- **Card 2 (Hero Bio-AI):** Columns 2 & 3, Row 1 (Electric Violet, 2-column span)
- **Card 3 (Circadian Peak Window):** Column 4, Rows 1 & 2 (Soft Lilac, 2-row span)
- **Card 4 (AI Athletic Coach):** Column 1, Rows 2 & 3 (Warm Amber, 2-row span)
- **Card 5 (Wearable Sync):** Column 2, Row 2 (Clean White, multi-device badges)
- **Card 6 (Consistency & Streak):** Column 3, Row 2 (Vibrant Amber, calendar widget)
- **Card 7 (CNS Recovery Stat):** Column 2, Row 3 (Clean White, display stat + avatars)
- **Card 8 (Progressive Overload):** Columns 3 & 4, Row 3 (Electric Violet, 2-column span)

### 📱 Mobile Layout (Single Column Stack)
Stack order strictly mirrors the mobile reference flow:
1. **Hero Card** — *Crush Your PRs 10x Faster with Bio-AI*
2. **Wearable Sync** — *Sync multiple wearables and biometric rings*
3. **Streak & Consistency** — *Maintain a consistent training schedule*
4. **Optimal Timing Window** — *Circadian bar chart & peak anabolic zone*
5. **Progressive Overload** — *Training volume velocity & PR stats*
6. **Recovery Rate Metric** — *>84% faster CNS recovery with coach avatars*
7. **Routine Generator** — *Create custom training splits quicker*
8. **AI Coach Chat** — *Interactive chat bubbles & prompt bar*

---

## 🎨 Design System & Aesthetic Tokens

- **Signature Palette:**
  - Electric Violet: `hsl(256, 75%, 58%)` & `hsl(256, 80%, 48%)`
  - Energetic Amber: `hsl(41, 100%, 64%)` & `hsl(38, 92%, 50%)`
  - Warm Sand / Cream: `hsl(36, 68%, 94%)`
  - Soft Lavender: `hsl(254, 88%, 91%)`
  - Clean Surface White: `#ffffff`
  - Background Neutral: `#f6f5f4`
- **Typography:**
  - **Plus Jakarta Sans** (Google Fonts) with geometric weights (500, 600, 700, 800) and optical kerning (`letter-spacing: -0.04em`).
- **Micro-Interactions & Pure CSS Effects:**
  - Subtle 3D lift (`transform: translateY(-4px)`) and diffused dual shadows on card hover.
  - Live pulse animation on the biometric status indicator and peak zone badge.
  - Interactive hover state on device badges, avatars, and action buttons.
  - High-performance vector SVGs embedded directly for instantaneous rendering.

---

## 🚀 Features

- [x] **Zero Dependencies:** Pure HTML5 and Vanilla CSS3.
- [x] **100% Responsive:** Desktop (4-col), Tablet (2-col), and Mobile (1-col) layouts.
- [x] **Semantic HTML:** Proper heading hierarchy (`h1`, `h2`), `main`, `section`, `article`, `header`, and `footer`.
- [x] **Accessible:** ARIA labels, high-contrast readable color pairings, and scalable typography using `clamp()`.
- [x] **SEO Optimized:** Complete meta descriptions, open-graph readiness, and proper document structure.

---

## 💻 How to Run Locally

1. Clone or download this repository:
   ```bash
   git clone https://github.com/<your-username>/pulsefit-bento-grid.git
   cd pulsefit-bento-grid
   ```
2. Open `index.html` in any modern web browser:
   - Double click `index.html`, or
   - Use VS Code Live Server, or
   - Run a simple local HTTP server:
     ```bash
     python -m http.server 3000
     # Or using npx
     npx serve .
     ```
3. Open `http://localhost:3000` in your browser.

---

## 📄 License
MIT License © 2026 PulseFit Labs.
