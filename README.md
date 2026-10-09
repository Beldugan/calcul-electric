# Calculul sistemelor de propulsie electrice

Aplicația îndrumarului „Proiectarea sistemelor de propulsie electrice ale autovehiculelor” (C. Tudor, A.-M. Beldugan, Universitatea „Ovidius” din Constanța, 2026).
Rulează integral în browser, fără server și fără instalare.

- **Cerințe (cap. 2):** ciclul WLTC clasa 3b (cu viteză limitată când v_max < 131 km/h), energia la roată, puterile cerute.
- **Dimensionare (cap. 3):** motor (putere de vârf și continuă, cuplu, turație), raportul reductorului, invertorul, bateria (celule în serie și paralel, tensiune, curent relativ, masă), performanțe.
- **Simulare WLTC (cap. 5):** bilanțul energetic, consumul pe faze, punctele de funcționare ale motorului.
- **Autonomie (§5.4):** WLTC la 23 °C, 35 °C cu climatizare, −7 °C cu încălzire, viteză constantă, plus un scenariu propriu.
- **Încărcare și termic (cap. 6–7):** DC CC–CV, AC, temperatura bateriei, încărcarea la rece.
- **Variante (cap. 8):** reductor cu două trepte, două motoare.
- **Cost și CO₂ (cap. 9)** și **Verificări (§12.2)**.

Exemplele 1 (autoturism mic, după Dacia Spring) și 2 (SUV, după Renault Scenic E-Tech) dau exact valorile din îndrumar.

## Publicare pe GitHub Pages

1. Creați depozitul public `calcul-electric` în contul `beldugan` și încărcați în rădăcina lui fișierele `index.html`, `style.css`, `app.js`, `ev.js`, `presets.js`, `ciclu.js` (și, opțional, acest README).
2. Settings → Pages → Source: *Deploy from a branch*, ramura `main`, dosarul `/ (root)`.
3. Aplicația devine disponibilă la `https://beldugan.github.io/calcul-electric/` (adresa din codul QR al îndrumarului).
