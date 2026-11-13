# Customizing This Template

All visuals in this profile are **self-contained, static SVG files**—nothing pulls from third-party APIs or external stat servers, so the layout will never rate-limit or break. To personalize the template after forking, edit the text values directly inside the SVG files and update the destination links in `README.md`.

---

### 1. Whirling Galaxy Map (`galaxy.svg`)
* **Repository / Project Nodes:** Open `galaxy.svg` in any code editor (or vector tool like Figma) and search for the existing hardcoded node labels (`MorData`, `Glass&Void`, `WVFM Labs`, etc.) inside `<text>` tags. Replace them with your own repository or project names.
* **Header & Telemetry Labels:** Update the top and bottom corner HUD strings (`GALACTIC TELEMETRY`, repository count, and focus tags) in the same file.
* **Theme Palette:** Find and replace the three core hex colors across the SVG if you want a different accent scheme:
  * `#05070D` — Deep void background
  * `#334480` — Orbit rings & structural borders
  * `#8DA2FF` — Periwinkle highlights & active nodes

---

### 2. Audio / Focus Console (`cognitive-yield.svg`)
* **Track & Artist Info:** Open `cognitive-yield.svg` in a text editor and replace the track title (`Cognitive Yield`), subtitle (`Deep Focus · Flow State`), and artist name (`Morgan Engle`) inside their `<text>` elements.
* **Click-Through Link:** Update the wrapping `<a href="...">` URL around `cognitive-yield.svg` in `README.md` to point to your own Spotify playlist, YouTube mix, or portfolio link.

---

### 3. Wave Banners & Social Pill Dock (`assets/`)
* **Hero & Footer Waves:** Open the wave SVGs in `assets/` to edit the header title, subtitle text, or `#05070D` / `#334480` / `#8DA2FF` gradient stops.
* **Pill Dock Buttons:** Each pill button in `assets/` is a standalone SVG. Edit the `<text>` label inside any pill SVG to rename a button, and update its corresponding `<a href="...">` destination link inside `README.md`.

---

### 4. Final `README.md` Link Check
* Replace all `morgan-mordata` profile and repository URLs in `README.md` with your own GitHub username.
* Keep the local `./galaxy.svg`, `./cognitive-yield.svg`, and `./assets/...` relative paths intact so every visual loads directly from your repository.
