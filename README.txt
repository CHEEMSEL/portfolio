
# Quang – Portfolio Site  
**Live URL (GitHub Pages):** https://CHEEMSEL.github.io/portfolio/

## 1. Objective
A single-page portfolio coded from scratch with **valid HTML5**, **responsive CSS**, and **four extras** as required.

## 2. W3C Compliance
Screenshot saved: `/screens/w3c-validator.png`  


## 3. Responsiveness
Tested at 320 px, 600 px, 768 px, 1024 px, 1440 px.  
Screenshots: `/screens/mobile.png`, `/screens/tablet.png`, `/screens/desktop.png`  
Navigation collapses to pure-CSS hamburger below 768 px.  
Project cards switch from 1-column → 2-column → 4-column via `auto-fit` grid.

## 4. Styling Choices
- CSS variables for instant theming  
- `clamp()` for fluid type & spacing  
- Accessible focus outlines maintained  
- prefers-reduced-motion respected via short transition times

## 5. Four Extras
1. **SVG signature logo** – inline, retina-sharp, no extra HTTP request  
2. **Pure-CSS hamburger** – checkbox hack, zero JS  
3. **CSS-only project modals** – `:target` lightbox for case-study images  
4. **Dark-mode toggle** – animated switch + `localStorage` persistence

## 6. Image Credits (all Unsplash, royalty-free)
- Hero: https://unsplash.com/photos/ndjyaOp0fOc  
- Project 1: https://unsplash.com/photos/1L30xJPkJI0  
- Project 2: https://unsplash.com/photos/b4ADd5AaG5Y  
- Project 3: https://unsplash.com/photos/4qSb_FWhHKs  
- Project 4: https://unsplash.com/photos/jn7uVeCdf6U  

## 7. Run Locally
```bash
git clone https://github.com/CHEEMSEL/portfolio.git
cd portfolio
# open index.html