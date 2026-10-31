# Projekt Stockdale

Společnost pro zvládání dnešní doby. Otevřené místo, kde lidé zkoumají dopady AI na společnost a společně hledají doporučení pro jednotlivce, firmy a správu věcí veřejných.

Web je jeden statický soubor `index.html`. Po pushi do `main` ho nasadí workflow v `.github/workflows/static.yml` na GitHub Pages.

## Jazyky

Česky: `index.html`, anglicky: `en/index.html`. Obě stránky se odkazují přes přepínač vpravo nahoře.

## Lokálně

Otevři `index.html` v prohlížeči (dvojklik). Stránka je samostatný soubor, logo a fotka jsou vložené přímo v něm. Originály (`logo-cs.png`, `logo-en.png`, fotka) jsou ve složce `assets/`.

## Nasazení

1. Vytvoř prázdné repo (např. `projekt-stockdale`) na GitHubu.
2. V této složce: `git init -b main && git add -A && git commit -m "První verze" && git remote add origin <URL repa> && git push -u origin main`
3. V repu: Settings → Pages → Source: GitHub Actions.
