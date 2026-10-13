# Info-Real – site legal pentru Meta (GitHub Pages)

Acest pachet conține un microsite public static pentru setările Meta for Developers:

- `privacy.html` → Privacy Policy URL
- `data-deletion.html` → Data Deletion Instructions URL
- `terms.html` → Terms of Service URL
- `index.html` → pagina principală
- `style.css` → design responsiv Info-Real

## FOARTE IMPORTANT, ÎNAINTE DE PUBLICARE

Înainte de publicarea site-ului și folosirea URL-urilor în Meta, completează:

- `{{OPERATOR_NAME}}` → numele operatorului legal (PF sau firmă, după decizia proprietarului).
- Adresa de contact este configurată: `t2k.skyline.group@gmail.com` (indicată explicit de titular).

Acest draft este construit pe comportamentul surselor Android verificate la 13 octombrie 2026. Revizuiește afirmațiile înainte de publicare dacă schimbi funcțiile aplicației. Nu reprezintă aviz juridic.

## Publicare gratuită pe GitHub Pages

1. Creează un repository GitHub NOU și PUBLIC `Info-real-legal` sub contul care administrează proiectul. Păstrează repository-ul Android `Info-real` privat.
2. Încarcă cele 5 fișiere HTML/CSS în rădăcina repository-ului public (nu `build_legal.py`, nu README cu date sensibile).
3. `Settings → Pages → Build and deployment → Deploy from a branch → main → / (root) → Save`.
4. GitHub publică în mod obișnuit la adresa `https://<GitHub-username>.github.io/Info-real-legal/`. IMPORTANT: acesta este doar formatul, verifică URL-ul exact afișat în Settings → Pages înainte să-l folosești în Meta.
5. Deschide toate cele trei pagini într-o fereastră incognito, fără login GitHub.
6. Inserează în Meta App Settings → Basic URL-urile HTTPS confirmate, fiecare în câmpul corespunzător.

## Securitate

Nu pune App Secret, Access Token, Page Token, chei Android, date personale sau rapoarte private în repository-ul public.

Actualizat: 13.10.2026

## STADIU 13 octombrie 2026

Adresa de contact este completată. Identitatea legală a operatorului (`{{OPERATOR_NAME}}`) trebuie confirmată înainte de activarea GitHub Pages; HTML-urile sunt deocamdată marcate `noindex,nofollow`. Pentru publicare elimină marcajul de draft după completarea operatorului și verificarea afirmațiilor.