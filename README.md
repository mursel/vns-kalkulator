# VNS Kalkulator PWA

Ovo je PWA verzija aplikacije.

Bitno:
- PWA se ne može normalno instalirati direktno iz `file://` fajla.
- Mora biti otvorena preko `https://` linka ili preko lokalnog servera.

Najlakše:
1. Uploaduj cijeli folder na GitHub Pages, Netlify, Vercel ili bilo koji HTTPS hosting.
2. Otvori link u Chrome na Androidu.
3. Chrome menu ⋮ → Install app / App installieren / Zum Startbildschirm hinzufügen.

Za lokalni test na računaru:
```bash
cd vns_pwa_app
python3 -m http.server 8000
```
Onda otvori:
http://localhost:8000
