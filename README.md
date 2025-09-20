# 🎨 Pixel Poet — Python × Art

**Pixel Poet** is an experimental, interactive web app that blends **creative writing, data visualization, and generative art**.  
Type in a single word (a *seed*) and choose a vibe. Behind the scenes, **Python (running in the browser via Pyodide)** generates:

1. A **micro-poem** inspired by your word and vibe.  
2. A **palette** of colors seeded from your input.  
3. A **visual canvas** rendered in one of four art modes:
   - 🌸 **Bloom** — soft rings and blooms (feelings & cycles)  
   - 🪐 **Orbit** — circles with satellites (goals & milestones)  
   - 🌊 **Wave** — sine bands and dots (rhythms & flow)  
   - ⚡ **Branch** — branching paths and sparks (shocks & growth)  

The result is a unique mix of text + art that gives symbolic meaning to the seed word you typed.

---

## ✨ Features
- **Python-powered logic**: Poems, palettes, and mode selection are all written in Python.  
- **Generative art modes**: Each seed word can trigger a completely different canvas style.  
- **Countdown guidance**: A 3-2-1 overlay explains the process (“Choosing mode… Writing poem… Painting…”).  
- **Downloadable art**: Save your generated canvas as a PNG.  
- **Shareable links**: Copy a link with your seed + vibe pre-loaded.  
- **Responsive UI**: Built with TailwindCSS and styled as a clean, modern web app.  

---

## 🛠️ Tech Stack
- **Python (Pyodide)** → Core logic for poems, palettes, insights, and geometry.  
- **JavaScript** → Event handling, canvas rendering, and UI binding.  
- **HTML + TailwindCSS** → Responsive UI and styling.  
- **Canvas API** → Draws generative art in real time.  

---

## 🚀 How It Works
1. Enter a word (e.g. `love`, `storm`, `hustle`).  
2. Pick a vibe (`dreamy`, `bold`, `serene`, etc.).  
3. Click **Generate ✨**.  
4. Watch the **countdown** as Python:
   - Seeds a palette of colors.  
   - Writes a micro-poem.  
   - Selects a visual mode.  
   - Sends geometry data to JavaScript.  
5. The canvas is painted, and you can read the poem + symbolic explanation. 
