# Personal Portfolio Project Guidelines

## Project Overview
This project is a personal portfolio website designed to showcase skills, experience, and projects. The design goal is to achieve a **minimalist, modern, and professional** look, inspired by the "Personal Portfolio Hero Section" reference design.

## Technology Stack
- **Core:** HTML5, CSS3 (Vanilla), Vanilla JavaScript.
- **Icons:** Font Awesome.
- **Typography:** Google Fonts (Poppins, Inter, Caveat).
- **No Heavy Frameworks:** The current structure relies on pure HTML/CSS for maximum performance and simplicity, unless scaling requires a framework like Vite/React later.

## Design System & Aesthetics
### 1. Principles
- **Minimalism:** Embrace whitespace. Do not clutter the UI with unnecessary elements.
- **Modernity:** Use soft shadows, rounded corners, clean typography, and subtle micro-animations (e.g., hover effects on buttons and social icons).
- **Professionalism:** Maintain high contrast for readability, logical visual hierarchy, and an organized layout.

### 2. Color Palette (Reference)
- **Background:** Warm off-white/cream (`#FDFBF6`) to make the site feel approachable but clean.
- **Primary Text:** Dark Charcoal/Black (`#1A1A1A`) for strong readability.
- **Accent Color:** Mustard Yellow/Orange (`#EBB02D` / `#F2994A`) used for highlights, icons, and CTA elements.
- **Secondary Accent:** Teal (`#2D6A6A`) for subtle complementary details.
- **Surface:** White (`#FFFFFF`) for cards and elevated elements.

### 3. Typography
- **Headings (H1-H6):** `Poppins` (Weights: 500, 600, 700, 800) - for a bold, geometric, modern feel.
- **Body Text:** `Inter` (Weights: 400, 500) - highly readable for paragraphs and UI elements.
- **Stylistic Accents:** `Caveat` (Weight: 700) - for cursive, creative flair (e.g., "Creative" tag).

### 4. Layout & UI Elements
- **Containers:** Max-width constrained (e.g., 1400px) and centered.
- **Cards:** White background, subtle drop shadow (`box-shadow: 0 10px 30px rgba(0,0,0,0.05)`), rounded corners (`border-radius: 20px`).
- **Images:** Soft, organic shapes or large circular crops for hero portraits.

## Coding Standards

### HTML
- Use semantic HTML tags (`<header>`, `<nav>`, `<main>`, `<section>`, `<footer>`, `<article>`).
- Maintain a clean and logical document outline.
- All interactive elements must have accessible names and focus states.

### CSS
- Use CSS Variables (`:root`) for colors, fonts, and spacing to ensure consistency.
- Avoid inline styles.
- Organize CSS logically: Variables -> Resets -> Typography -> Components -> Layout -> Media Queries.
- Use Flexbox and CSS Grid for layouts.
- **Responsiveness:** Ensure a mobile-first or highly adaptable responsive design. Use media queries for standard breakpoints (e.g., 1200px, 992px, 768px, 480px).

### JavaScript (When applicable)
- Keep it modular and well-commented.
- Use ES6+ syntax (`const`, `let`, arrow functions, template literals).
- Add JS only for functional enhancements (e.g., smooth scrolling, form validation, dynamic filtering of projects) to keep the site lightweight.

## AI Assistant Instructions
When assisting with this project, the AI should:
1. Always adhere to the defined color palette and typography.
2. Prioritize clean, modern UI solutions that don't overcomplicate the codebase.
3. Suggest CSS animations or transitions only if they add a "premium" feel without degrading performance.
4. Update this `CLAUDE.md` file if the tech stack or design system evolves.
