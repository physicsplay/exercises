# exercises
Games based on specific exercises in Physics

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

