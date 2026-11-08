PHYSIOBLOG — PACCHETTO STATICO PER CLOUDFLARE PAGES

CONTENUTO
- Sito statico HTML/CSS, senza CMS e senza abbonamenti applicativi.
- Home, archivio Articoli, 10 pagine articolo, Video, Profilo, Contatti, Privacy.
- 12 video YouTube con caricamento su clic.
- Logo e asset grafici in /assets.
- Sitemap.xml e robots.txt.

PUBBLICAZIONE SU GITHUB + CLOUDFLARE PAGES
1. Estrai lo ZIP.
2. Carica TUTTI i file e le cartelle contenuti nella cartella del pacchetto nella root del repository GitHub `Physioblog/physioblog` (non caricare la cartella contenitore come sottocartella).
3. Esegui il commit sul branch `main`.
4. Cloudflare Pages dovrebbe avviare automaticamente il deploy collegato al repository.
5. Controlla il sito su https://www.physioblog.it/ e verifica anche le pagine interne.

CONFIGURAZIONE BUILD CLOUDFLARE PAGES
- Framework preset: None
- Build command: lasciare vuoto
- Build output directory: /
- Root directory: /
Nessun comando di build è necessario.

NOTA PRIVACY
La pagina Privacy è una bozza informativa prudenziale basata sui servizi previsti (hosting Cloudflare, contatti e video YouTube attivati dall'utente). Non è una certificazione legale. Prima della messa online verifica i fornitori effettivamente attivi, i log e le impostazioni YouTube/Cloudflare; aggiorna l'informativa se aggiungi analytics, newsletter, moduli, cookie o altri servizi.

IMPORTANTE
Il pacchetto non modifica direttamente GitHub, DNS o Cloudflare: il caricamento e il commit restano a carico del proprietario del repository.
