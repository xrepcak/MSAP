**Nebula Core** je interaktívny webový audio vizualizér postavený na knižnici **Three.js**. Projekt transformuje zvukové vlny na dynamické pohyby častíc v 3D priestore, pričom ponúka pokročilé funkcie pre analýzu hudby v reálnom čase, vrátane detekcie úderov (BPM) a spracovania basov.

## 🚀 Hlavné funkcie

- **3D Časticový systém:** Vizualizácia tvorená 15 000 časticami s plynulými animáciami a aditívnym blendingom.
- **Tri vizualizačné módy:**
    - **Amplitúda (Spektrum):** Reaguje na intenzitu zvuku naprieč frekvenčným spektrom.
    - **BPM (Beat Detection):** Využíva algoritmus *Bass Flux* na detekciu úderov a dynamickú zmenu farieb.
    - **Čas (Chroma Shift):** Plynulý farebný cyklus, ktorého rýchlosť je ovplyvnená energiou skladby.
- **Audio Engine:**
    - Podpora pre **Drag & Drop** nahrávanie súborov priamo do prehliadača.
    - Možnosť meniť rýchlosť prehrávania (**Pitch**) v reálnom čase bez straty synchronizácie.
    - Presný Seek-bar s výpočtom zostávajúceho času a automatickým zastavením po skončení skladby.
- **Stabilizované UI:** Obsahuje dynamický marquee systém pre dlhé názvy skladieb a responzívny sklenený (glassmorphism) ovládací panel.

## 🛠 Technológie

- **Web Audio API:** Na analýzu frekvencií a správu zvukových uzlov (Gain, Analyser, Source).
- **Three.js (WebGL):** Na vykresľovanie 3D grafiky a GPU akcelerované animácie častíc.
- **HTML5 / CSS3:** Moderný styling a spracovanie súborov.

## 📥 Inštalácia a spustenie

Projekt nevyžaduje žiadnu zložitú inštaláciu ani serverový backend.

1. Naklonujte repozitár:
   ```bash
   git clone [https://github.com/vas-profil/nebula-core.git](https://github.com/vas-profil/nebula-core.git)