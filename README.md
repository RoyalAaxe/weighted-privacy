# weighted-privacy

Publieke privacy policy voor de Weighted-app, gehost via GitHub Pages.

**Live URL (na deploy):** https://royalaaxe.github.io/weighted-privacy/
Deze URL staat al hardcoded in de app (`src/constants/legal.ts` → `PRIVACY_URL`) en in de
App Store-listing (Support URL).

## Eenmalig deployen

1. Maak op GitHub een **public** repo met exact deze naam: `weighted-privacy`
   (account `RoyalAaxe` → anders klopt de URL niet).
2. Push de inhoud van deze map (`index.html` + `README.md`) naar `main`.
   ```bash
   cd weighted-privacy
   git init && git add . && git commit -m "Privacy policy"
   git branch -M main
   git remote add origin https://github.com/RoyalAaxe/weighted-privacy.git
   git push -u origin main
   ```
3. GitHub → repo → **Settings → Pages** → Source: `Deploy from a branch`,
   Branch: `main` / `/ (root)` → Save.
4. Wacht ~1 min, open https://royalaaxe.github.io/weighted-privacy/ → moet de policy tonen.

## Bijwerken
Pas `index.html` aan, update de datum, commit + push. Pages publiceert automatisch.
De bron-tekst staat ook in `Weighted/PRIVACY.md` (houd ze gelijk).
