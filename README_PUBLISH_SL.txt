FLOATCLIP — JAVNA STRAN PRIVACY + SUPPORT (GITHUB PAGES)
Datum: 2026-11-08

VSEBINA:
- index.html     predstavitvena stran (EN + SL)
- privacy.html   pravilnik zasebnosti (EN + SL)
- support.html   podpora (EN + SL)
- styles.css     lokalni izgled brez zunanjih odvisnosti
- .nojekyll      statično objavljanje brez Jekyll procesiranja

KAJ JE PREVERJENO:
- vse povezave med stranmi so relativne (delujejo tudi v podmapi na GitHub Pages)
- ni JavaScript, omrežnih pisav, analitike, oglasov ali piškotkov, ki bi jih nastavila naša stran
- zadeva je ločena od FloatClip C++ source in izdajnih paketov
- javni naslov podpore: floatclip.support@proton.me

KAKO OBJAVITI (ROČNO, BREZ CODEXA):
1. Na https://github.com se prijavi v račun, ki naj bo lastnik strani.
2. Ustvari nov PUBLIC repozitorij, npr. floatclip-site; ne uporabi zasebnega izvornega repozitorija aplikacije.
3. V koren repozitorija naloži pet datotek iz tega ZIP-a: index.html, privacy.html, support.html, styles.css in .nojekyll. Naloži samo datoteke spletne strani. README_PUBLISH_SL.txt ni treba naložiti.
4. V Settings > Pages > Build and deployment > Source izberi 'Deploy from a branch'; branch 'main' in folder '/(root)'; klikni Save.
5. V nastavitvah Pages poišči dejanski objavljeni URL. Ne ugibaj URL-ja; odvisen je od GitHub uporabniškega imena in imena repozitorija.
6. Odpri javno stran, privacy.html in support.html; preveri navigacijo, videz na telefonu in delovanje e-poštne povezave.
7. Nato v Partner Center uporabi dejanski Privacy policy URL in Support URL (ali support e-poštni naslov).

POMEMBNO:
- GitHub Free Pages za javne repozitorije je na voljo brezplačno.
- GitHub Pages spletna mesta so JAVNA. Ne dodajaj source kode, privatnih ključev, podpisnih certifikatov, nastavitvenih datotek, dokaznih ZIP-ov ali osebnih podatkov.
- GitHub Pages pri obiskih lahko hrani IP-naslove za varnost; to je razloženo na privacy.html.
- Pravilnik je projektni osnutek glede na pregled v27; pred objavo preveri navedbe proti končni stabilni izdaji.
- V nobenem polju ni dodano osebno ime avtorja; javna blagovna znamka je machinefhead.
- Spletne strani še niso objavljene. Microsoft Store izdelek ostaja In draft.

Uradni viri:
https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site
https://learn.microsoft.com/en-us/windows/apps/publish/publish-your-app/msix/support-info
