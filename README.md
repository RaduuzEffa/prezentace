# 🃏 WOW Deck Studio — 3D Interaktivní Prezentace (Styl 5:55 & 7:00)

Interaktivní prezentační aplikace a editor ve stylu **3D karet na dřevěném stole se scrollytellingem, neonovými propojovacími linkami a 3D rozborem s klikacími piny** (inspirováno videem *Higgsfield + Claude Fable 5.2* od času `5:55` a `7:00`).

---

## ✨ Hlavní funkce

1. **Autentická 3D karetní animace (styl 5:55)**
   - **Balíček karet na stole**: Nahoře na stole leží balíček karet s pulzující neonovou diodou, dole na stole jsou vějířovitě rozložené všechny karty prezentace (`01` až `07`+).
   - **3D Vzlet a otočení o 180° (Card Flip)**: Při přechodu na kartu se karta zvedne ze stolu do 3D prostoru, ukáže svou přední černo-zlatou stranu (s fotkou/ikonou/videem) a plynule se otočí o 180° na čistou bílou kartu se shrnutím.
   - **Animovaná neonová vodící linka (SVG Leader Line)**: Z hrany karty vyjede svítící neonová linka přímo k detailnímu panelu vpravo.
   - **Složení karet zpět do balíčku (Finále 6:40)**: Stiskem klávesy `G` (nebo kliknutím na balíček nahoře / posunem za poslední kartu) se všechny karty efektně sbalí zpět do balíčku uprostřed stolu.

2. **Interaktivní 3D/Schéma s číselnými piny (styl 7:00 Starship)**
   - Každý slide může kromě klasického textu, obrázku nebo videa obsahovat **Interaktivní schéma s klikacími piny (`1`, `2`, `3`, `4`...)** nebo **Grid klíčových KPI metrik**.
   - V editoru stačí **kliknout přímo do náhledu obrázku** a pin se automaticky umístí na přesné souřadnice `X% / Y%`.

3. **Vestavěný Studio Editor (`Klávesa E`)**
   - **Správa karet**: Přidávání, duplikování, změna pořadí a mazání karet.
   - **Plná kontrola nad obsahem**: Vkládání vlastních obrázků (z disku i URL), videí (MP4/WebM soubory i YouTube odkazy), odrážek, tlačítek a cenových/metrických štítků.
   - **6 efektů animace nadpisu**: *3D Rozpad znaků (Char Stagger)*, *Zaostření z mlhy (Blur Reveal)*, *Kybernetický Glitch*, *Psací stroj (Typewriter)*, *Dynamický výjezd (Slide Up)* a *Filmové rozestoupení (Cinematic)*.
   - **Přizpůsobení vzhledu**: Změna prostředí (*Dřevěný stůl 5:55*, *Tmavý vesmír 7:00*, *Černý karbon*, *Obsidiánová mřížka*, *Vlastní fotka pozadí*), barvy akcentů, barev karet, fontů, velikosti písma, vlastního loga v hlavičce a **okna řečníka vpravo dole** (skryto / vizitka s fotkou / **živá webkamera přímo z prohlížeče**!).

4. **Šablony, JSON Zálohy, Samostatný HTML & PDF Export**
   - **3 připravené šablony na 1 klik**: *Styl Videa 5:55 + 7:00*, *Čistá šablona (Clean Starter)* pro rychlou tvorbu nové prezentace na libovolné téma, a *Firemní Pitch před kolegy*.
   - **JSON Export & Import**: Kompletní záloha prezentace do souboru `.json` a okamžité načtení.
   - **Stažení hotového `index.html`**: Vygeneruje samostatný `index.html` s tvou aktuální prezentací napevno uloženou uvnitř — stačí ho poslat kolegům nebo nahrát na GitHub.
   - **PDF Export (`16:9`)**: Naformátuje všechny karty a panely do širokoúhlých stránek `16:9` pro tisk nebo uložení jako PDF.

5. **100% Offline & PWA (Progressive Web App)**
   - Funguje okamžitě po dvojkliku na [index.html](file:///Users/rp/.gemini/antigravity/scratch/wow-deck-studio/index.html) i bez internetu (veškeré textury dřeva, 3D efekty, částice i zvuky karet jsou generovány procedurálně přímo v prohlížeči).
   - Při nahrání na **GitHub Pages** (nebo spuštění přes lokální server) nabízí plnou instalaci jako **PWA aplikace** do PC/Macu či tabletu díky [manifest.json](file:///Users/rp/.gemini/antigravity/scratch/wow-deck-studio/manifest.json) a [sw.js](file:///Users/rp/.gemini/antigravity/scratch/wow-deck-studio/sw.js).

---

## ⌨️ Klávesové zkratky při prezentaci

| Klávesa / Akce | Funkce |
| :--- | :--- |
| `Kolečko myši` / `→` / `Mezerník` | Další karta (Scrollytelling) |
| `←` | Předchozí karta |
| `R` nebo **Klik na 3D kartu** | Otočit kartu o 180° (Přední černo-zlatá ↔ Zadní bílá strana) |
| `G` nebo **Klik na balíček nahoře** | Sbalit všechny karty do balíčku / Rozdat karty na stůl |
| `E` | Otevřít / Zavřít **Studio Editor** |
| `F` | Celá obrazovka (Čistý prezentační režim) |
| `L` | Zapnout / Vypnout červené **laserové ukazovátko** |
| `1` – `9` | Přepnout aktivní bod u schématu s interaktivními piny |

---

## 🌐 Jak nahrát na GitHub Pages (jako plnou instalovatelnou PWA)

1. Vytvoř nový repozitář na GitHubu a nahraj do něj soubory ze složky:
   - `index.html`
   - `manifest.json`
   - `sw.js`
   - `icon-192.svg` a `icon-512.svg`
2. V nastavení repozitáře (**Settings → Pages**) vyber větev `main` a ulož.
3. Po otevření GitHub Pages adresy v Chrome / Edge / Safari klikni v adresním řádku na ikonu **Nainstalovat aplikaci (PWA)** — prezentace pak poběží jako samostatná desktopová aplikace i zcela offline.
