# Web — Ivana Soukupová, virtuální asistentka

Statická one-page prezentace inspirovaná strukturou asistentkamb.cz (žádné převzaté texty ani grafika — struktura + vlastní copy podle profesního profilu z PDF).

## Soubory
- `index.html` — celá stránka
- `style.css` — styly (bez frameworku, jen Google Fonts: Fraunces + Inter)
- `img/ivana.jpg` — portrét

## Struktura sekcí
1. Hero — „Více prostoru pro růst. Méně operativy na vašem stole."
2. Pás kompetencí (ticker)
3. Co pro vás dělám — 3 karty
4. Budu váš parťák — foto + 3 principy
5. Obsah, který pracuje za vás — výčet výstupů
6. Tři možnosti spolupráce — jednorázově / pravidelně / dlouhodobě (ceny = placeholder)
7. Mapa spolupráce — 6 služeb v rozklikávacím accordionu (obsah z PDF)
8. Jak začneme — 3 kroky
9. O mně
10. Reference — placeholdery (doplnit reálné!)
11. FAQ — 6 dotazů
12. Kontakt + patička

## Co doplnit před spuštěním
- **Ceny** v sekci Spolupráce (`[doplnit] Kč`)
- **Reálné reference** v sekci Reference (teď jsou tam hranaté závorky)
- Vlastní doménu, favicon, OG obrázek, cookie/GDPR text, IČO do patičky

## Lokální náhled
```
cd projects/ivana-asistentka && python3 -m http.server 8931
```
Otevřít http://localhost:8931

## Nasazení
Stačí nahrát složku kamkoli na statický hosting (Netlify, Vercel, Cloudflare Pages, FTP).
