# exercises
Games based on specific exercises in Physics

# 🎮 Physics Games — based on specific High School exercises  
# 🎮 Παιχνίδια Φυσικής — βασισμένα σε συγκεκριμένες ασκήσεις Λυκείου

> **EN:** A collection of small, playable physics games. Each game is tied to a *specific exercise* (or exercise type) from high school Physics, so students practice the exact concepts they need — through gameplay.  
> **EL:** Μια συλλογή από μικρά, παικτικά παιχνίδια Φυσικής. Κάθε παιχνίδι αντιστοιχεί σε *συγκεκριμένη άσκηση* (ή τύπο άσκησης) Φυσικής Λυκείου, ώστε οι μαθητές να εξασκούνται στα σωστά ζητούμενα — μέσα από gameplay.

---

## 📌 Table of Contents / Περιεχόμενα
- [EN — Overview](#en--overview)
- [EN — Repository structure](#en--repository-structure)
- [EN — Play online (GitHub Pages)](#en--play-online-github-pages)
- [EN — Run locally](#en--run-locally)
- [EN — Add a new game](#en--add-a-new-game)
- [EN — Design principles](#en--design-principles)
- [EL — Περιγραφή](#el--περιγραφή)
- [EL — Δομή αποθετηρίου](#el--δομή-αποθετηρίου)
- [EL — Παίξε online (GitHub Pages)](#el--παίξε-online-github-pages)
- [EL — Εκτέλεση τοπικά](#el--εκτέλεση-τοπικά)
- [EL — Πρόσθεσε νέο παιχνίδι](#el--πρόσθεσε-νέο-παιχνίδι)
- [EL — Αρχές σχεδίασης](#el--αρχές-σχεδίασης)
- [License](#license)
- [Credits](#credits)

---

# EN — Overview

This repository hosts **online physics games** (pure HTML/CSS/JS) designed for **high school (Lyceum)**.  
Each game maps to a **specific exercise**: you get the same givens, the same target quantity, and the same physics laws — but in an interactive, score-based mission.

✅ Goals:
- Make students *calculate*, not guess  
- Visualize the physics (motion, energy, forces, circuits, etc.)  
- Provide feedback: theory vs experiment, error %, attempts, hints

---

## EN — Repository structure

Suggested structure (feel free to adapt):


---

## EN — Play online (GitHub Pages)

You can publish the games with **GitHub Pages**.

**Option A (simple):**  
- Put each game in `/docs/<game-name>/index.html`
- Enable GitHub Pages to serve from the `docs/` folder

**Option B (root / custom landing page):**  
- Create a main `index.html` that links to games
- Place games under `/games/...` and link to them

---

## EN — Run locally

Because these are static HTML games, you can run them by simply opening `index.html` in a browser.

For best results (and to avoid browser restrictions), run a tiny local server:

- VS Code → “Live Server” extension, or  
- Any simple local server you prefer

---

## EN — Add a new game

1. Create a new folder under the correct topic:
   - `games/<topic>/<exercise-slug>/index.html`

2. Add inside the game:
   - **Intro screen** (scenario, difficulty, language)
   - **Game screen** (canvas + controls + formulas always visible)
   - **End screen** (medal, stats, error analysis)

3. In the root `README.md` (this file), add the game to the list of games.

Recommended naming:
- `projectile-horizontal-launch`
- `pendulum-energy-losses`
- `ohms-law-circuit-01`

---

## EN — Design principles

Most games in this repo aim to follow these principles:

- **Scientific accuracy (SI units)**
- **Visible formulas in the UI**
- **Pause mode** for calculations
- **Hints** (with score penalty)
- **End analysis:** theoretical vs measured value + error %
- **Gamification:**
  - Score emphasizes reasoning (not trial-and-error)
  - Medals by error threshold (e.g., 🥇 < 5%, 🥈 < 10%, 🥉 < 20%)

---

# EL — Περιγραφή

Αυτό το αποθετήριο φιλοξενεί **online παιχνίδια Φυσικής** (καθαρό HTML/CSS/JS) για **Λύκειο**.  
Κάθε παιχνίδι είναι “ντυμένη” εκδοχή μιας **συγκεκριμένης άσκησης**: ίδια δεδομένα, ίδιο ζητούμενο, ίδιοι νόμοι — αλλά με διαδραστικό τρόπο και βαθμολογία.

✅ Στόχοι:
- Να βοηθά τους μαθητές να *υπολογίζουν* (όχι να μαντεύουν)  
- Να οπτικοποιεί τη Φυσική (κίνηση, ενέργεια, δυνάμεις, κυκλώματα κ.ά.)  
- Να δίνει ανατροφοδότηση: θεωρία vs πείραμα, σφάλμα %, προσπάθειες, υποδείξεις

---

## EL — Δομή αποθετηρίου

Προτεινόμενη δομή (μπορείς να την προσαρμόσεις):

