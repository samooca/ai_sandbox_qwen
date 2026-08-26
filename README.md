```markdown
# 🎬 15 Product Shot Angles for Ad Film — Interactive Study Platform

An educational, mobile-first Web App / PWA designed as a high-fidelity visual study guide and interactive reference tool for commercial directors, 3D visualizers, art directors, and D2C filmmakers.

---

## 📌 Overview

This project transforms the source guide **"15 Product Shot Angles For Ad Film"** into an interactive digital learning hub. It breaks down essential cinematic shot angles, lighting recipes, platform-specific use cases, and visual psychology to bridge the gap between static product showcase and emotionally compelling brand storytelling.

---

## ✨ Key Features

* **Interactive Study Tooltips & Modals:** Fast tap/hover micro-summaries for camera terminology, lighting techniques, and cinematic jargon.
* **Smart Cross-Linking:** Dynamic semantic connections between related angles (e.g., *Macro Detail* ↔ *Abstract Texture*, *Low-Angle Hero* ↔ *Ground-Up*).
* **Lighting & Setup Cheat Sheets:** Recommended lighting setups (raking light, hard 45° key, softbox symmetry, rim backlighting) for every individual angle.
* **Mobile-First & Fluid Layout:** Spacious touch targets, wide margins, and generous negative space tailored for relaxed on-the-go reading.
* **PWA & Offline Ready:** Configured with a lightweight service worker and web manifest for instant offline reference on mobile devices.
* **Semantic & Accessible:** Structured with HTML5 landmarks, WCAG 2.1 AA compliance, and Schema.org (`TechArticle` / `LearningResource`) metadata.

---

## 📐 The 15 Angles Cataloged

| # | Shot Angle | Primary Emotional / Strategic Function | Recommended Lighting |
|---|---|---|---|
| **01** | **Low-Angle Hero** | Authority, grandeur, premium brand stature | Hard 45° key + soft fill |
| **02** | **Eye-Level Straight-On** | Honesty, transparency, zero-flattery trust | Soft, even bilateral diffusion |
| **03** | **Three-Quarter (45° Turn)** | 3D depth, tactile volume, natural perspective | Directional key with soft falloff |
| **04** | **Flat Lay (Top-Down)** | Lifestyle curation, aesthetic context, density | Diffused angled overhead |
| **05** | **Macro Detail** | Quality proof, material integrity, craftsmanship | Shallow raking/grazing light |
| **06** | **Floating Product** | Pure focus, surrealism, high-tech/luxury vibe | Multi-directional isolated fill |
| **07** | **In-Use Contextual** | Conversion trigger, relatability, human touch | Natural ambient / situational light |
| **08** | **Close-Up Pour / Reveal** | Sensory stimulation, appetite/desire appeal | Rim / backlighting for translucency |
| **09** | **Dutch Angle (Tilted)** | Tension, dynamism, youth-culture scroll-stopper | Clean directional key |
| **10** | **Top-Front Hybrid** | Balance of surface clarity and frontal geometry | Overhead 25° forward angle |
| **11** | **Ground-Up Shot** | Monumental scale, architectural impact | Overhead rim + backlit separation |
| **12** | **Symmetrical Front** | Rigor, precision, high-end luxury minimalism | Identical bilateral softboxes |
| **13** | **Over-the-Shoulder** | Immersive lifestyle immersion, narrative framing | Organic, scene-matched natural light |
| **14** | **Before-and-After** | Transformation proof, utility demonstration | Matched exposure & framing |
| **15** | **Abstract Texture** | Conceptual depth, raw ingredient close-up | Extreme low-angle raking light |

---

## 📁 Repository Structure

```text
ai_sandbox_qwen/
└── content/
    ├── 15 Product Shot Angles For Ad Film.pdf   # Source document & curriculum
    ├── 15-Product-Shot-Angles-For-Ad-Film.png   # Visual infographic & asset
    ├── index.html                               # Main interactive PWA / Web App
    └── README.md                                # Documentation & study guide

```

---

## 🚀 Getting Started

### Local Development

1. **Clone the repository:**
```bash
git clone [https://github.com/samooca/ai_sandbox_qwen.git](https://github.com/samooca/ai_sandbox_qwen.git)
cd ai_sandbox_qwen/content

```


2. **Serve the project:**
You can use any static local server:
```bash
# Using Python 3
python3 -m http.server 8080

# Or using Node (npx)
npx serve .

```


3. **Open in browser:**
Navigate to `http://localhost:8080` or open `index.html` directly.

---

## 🛠️ Tech Stack & Standards

* **Structure:** Semantic HTML5 (`<main>`, `<article>`, `<section>`, `<nav>`)
* **Styling:** Modern utility-first styling (Tailwind CSS or modern CSS custom properties)
* **Interactivity:** Vanilla Modern JavaScript (ES Modules, Popover API / Dialogs)
* **Metadata:** OpenGraph, Twitter Cards, JSON-LD Structured Data
* **Offline Support:** Manifest JSON + Service Worker Cache

---

## 📄 License & Attribution

Educational content structured for ad film production workflows and visual reference.

```

```
