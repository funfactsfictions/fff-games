# FFF Games – webes prototípusok

- `index.html` – **Real or Fiction?** (Fun Fact's Fictions arculat) → `https://<felhasználónév>.github.io/<repo>/`
- `forever-facts/index.html` – **Forever Facts Daily** (tavernás változat) → `https://<felhasználónév>.github.io/<repo>/forever-facts/`

## Feltöltés GitHub Pages-re (kb. 5 perc)

1. GitHubon: **New repository** → név pl. `fff-games` → **Public** → Create.
2. **Add file → Upload files** → húzd be az `index.html`-t és a `forever-facts` mappát → **Commit changes**.
3. **Settings → Pages** → Source: *Deploy from a branch* → Branch: `main`, mappa: `/ (root)` → **Save**.
4. 1–2 perc múlva él: `https://<felhasználónév>.github.io/fff-games/`

## Látogatásmérés (GoatCounter, ingyenes, nem kell hozzá cookie-banner)

1. Regisztrálj: https://www.goatcounter.com/signup – válassz egy kódot, pl. `fffgames`.
2. Mindkét `index.html`-ben keresd meg ezt a sort, és írd be a kódodat:
   `const GOATCOUNTER_CODE="";` → `const GOATCOUNTER_CODE="fffgames";`
3. Töltsd fel újra a két fájlt.

A GoatCounter-felületen ezt fogod látni:
- oldalmegnyitások
- `rof-from-instagram`, `rof-from-youtube`, `rof-from-facebook`, `rof-from-tiktok` – honnan jöttek
- `rof-daily-start`, `rof-finish-3of5` … – hányan kezdték el és fejezték be, milyen eredménnyel
- `rof-share` – hányan osztották meg
(Forever Facts változatnál ugyanez `ffd-` előtaggal.)

## Linkek a reelekhez

- Instagram: `https://<felhasználónév>.github.io/fff-games/#from-ig`
- Facebook: `…/#from-fb` · YouTube: `…/#from-yt` · TikTok: `…/#from-tt`

A Megosztás gomb a GitHubon automatikusan az oldal saját címére mutat.
