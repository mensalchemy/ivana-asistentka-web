# Web — Ivana Soukupová, virtuální asistentka

Statická one-page prezentace. **Veškerý obsah pochází výhradně z profesního profilu (PDF).**
Z webu asistentkamb.cz byla převzata pouze obecná struktura stránky (pořadí sekcí), žádné texty ani formulace.

## Soubory
- `index.html` — celá stránka
- `style.css` — styly (bez frameworku, Google Fonts: Fraunces + Inter)
- `img/ivana.jpg` — portrét
- `img/logo.svg` — logo (značka + favicon)
- `robots.txt` — zákaz indexace

## Struktura sekcí (vše z PDF)
1. Hero — „Více prostoru pro růst. Méně operativy na vašem stole." + Co vám to přinese
2. Pás: Převzít • Komunikovat • Dotáhnout
3. Proč právě se mnou — Tři pilíře + pracovní standard
4. Můj přístup — „Delegování má práci odebrat." + Princip spolupráce (4 kroky)
5. Mapa spolupráce — 6 oblastí v accordionu (Proč delegovat / Co převezmu / Co se změní / Výsledek)
6. Tři možnosti spolupráce — jednorázově 400 Kč/hod, pravidelně od 5 000 Kč/měsíc, dlouhodobě individuálně
7. Kde přináším největší hodnotu — Jak začneme (3 kroky)
8. O mně
9. Reference — **FIKTIVNÍ ukázkové texty, nutno nahradit reálnými**
10. FAQ (odpovědi vychází z PDF)
11. Kontakt — hlavní tlačítko rovnou vytáčí telefon (`tel:`)
12. Patička

## Noindex
`<meta name="robots" content="noindex, nofollow, ...">` + `robots.txt`.
Na GitHub Pages v podsložce funguje reálně jen meta tag; robots.txt začne platit po přesunu na vlastní doménu.

## Co doplnit před ostrým spuštěním
- **Reálné reference** místo ukázkových (sekce `#reference`, označená komentářem v HTML)
- Doména, OG obrázek, cookie/GDPR text, IČO do patičky

## Lokální náhled
```
cd projects/ivana-asistentka && python3 -m http.server 8931
```

## Nasazení
Public repo `mensalchemy/ivana-asistentka-web` → GitHub Pages.
Aktualizace = `git push` do `main`, web se přegeneruje do ~1 minuty.
