PDA kontrola balení - PWA verze

Obsah složky:
- index.html - aplikace
- manifest.webmanifest - nastavení instalace do mobilu
- service-worker.js - nutné pro PWA/offline cache
- icons/ - ikony aplikace

Důležité:
Kamera v mobilním prohlížeči funguje pouze přes HTTPS nebo localhost.
Proto aplikaci nahrajte na HTTPS hosting, například GitHub Pages, Netlify, Vercel nebo vlastní webhosting s HTTPS.

Rychlé nasazení přes GitHub Pages:
1. Vytvořte nový GitHub repository.
2. Nahrajte všechny soubory z této složky do kořene repository.
3. V GitHubu otevřete Settings -> Pages.
4. Source nastavte na Deploy from a branch, branch main, folder /root.
5. Počkejte na zveřejnění a otevřete v mobilu HTTPS adresu.
6. V Chrome na Androidu zvolte menu tři tečky -> Přidat na plochu / Instalovat aplikaci.

Poznámka:
Aplikace zatím používá knihovny XLSX a html5-qrcode z CDN, takže pro první načtení musí být zařízení online.
