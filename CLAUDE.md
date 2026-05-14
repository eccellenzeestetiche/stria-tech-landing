# Regole operative Claude Code

Quando l’utente chiede una modifica, devi sempre:

1. Modificare davvero i file necessari della landing:
   - index.html
   - style.css
   - assets/

2. Non limitarti a spiegare. Devi applicare la modifica nei file.

3. Dopo ogni modifica devi eseguire automaticamente:

```bash
git status
git add .
git commit -m "update landing"
git pull --rebase origin main
git push
