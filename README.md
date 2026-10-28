# 🏎️ Formula 1 Grand Prix Portfolio

A high-octane developer portfolio themed around **Formula 1 Grand Prix**, built **exclusively using HTML5 and CSS3** (zero JavaScript required).

Featuring liveries from **Scuderia Ferrari**, **Mercedes-AMG Petronas**, **Red Bull Racing**, and **McLaren**, complete with authentic race telemetry graphics, timing tower leaderboards, pit wall scorecards, and F1 driver broadcast profiles.

---

## 🏁 Key Features & F1 Mechanics

### 1. 🛞 Pirelli P-Zero Rolling Wheel Navbar
- On page load, a custom-rendered **Pirelli P-Zero soft compound tyre** (complete with yellow sidewall typography, OZ Racing magnesium alloy spokes, and a Ferrari-red central locking nut) rolls in across the viewport (`transform: rotate(-720deg) translateX(0)`).
- As the tyre rolls across, the **navigation HUD unrolls and unfurls** directly behind its path using CSS `@keyframes navUnfurl` with a dynamic `clip-path` expansion.
- Hovering over the wheel triggers a burnout wheelspin with smoke effects.

### 2. 🔴 5 Red Lights Sequence & Driver Grid Profile (Hero)
- **FIA Start Lights Gantry**: 5 red starting lights illuminate sequentially (`🔴 🔴 🔴 🔴 🔴`), hold, and extinguish: *"Lights out and away we go!"*
- **Official F1 TV Broadcast Lower-Third Profile**:
  - Driver Number `#01` with carbon fiber texture.
  - Driver Helmet with tricolor visor and aerodynamic livery.
  - Pole Position status.
  - **Location**: Based in **Pune / Delhi, India** (the twin high-speed circuits of India's tech ecosystem).
  - Role: **Full-Stack Engineer & Aspiring Entrepreneur**.
  - Live biometrics and telemetry HUD (0-100 km/h deploy times, 8th Gear MERN/PERN, 15,000 RPM VCS/DSA, 99.98% podium reliability).
  - SVG Interactive Circuit Map with moving DRS blip.

### 3. ⏱️ F1 Live Timing Tower (Skills Leaderboard & Overtakes)
- Styled precisely like the **Official Formula 1 Live Timing Tower**:
  - **P1 // MERN Stack** (Scuderia Ferrari) – *Executes DRS overtake on the straight into P1!*
  - **P2 // PERN Stack** (Mercedes-AMG Petronas) – *Hunting fastest sector times!*
  - **P3 // DSA & Algorithms** (Red Bull Racing) – *Mastery of time/space complexity O(1).*
  - **P4 // VCS & DevOps** (McLaren Papaya) – *Trunk branching and Git CI/CD pit stops.*
  - **P5 // System Design & AWS** (Aston Martin) – *High-throughput cloud chassis.*
  - **OUT // Slow Monoliths & Memory Leaks** – *Overtaken & retired (Engine blown 💥).*
- Animated overtakes with position swaps, DRS active pulses, purple sector glows (`🟣`), and live interval gaps.

### 4. 📊 F1 Constructor Pitwall Scorecards (Projects)
- Projects display as high-performance **pitwall telemetry monitors and constructor scorecards** that slide in from alternate left and right sides:
  - **ApexTrade**: Ultra-Low Latency Order Engine (PERN Stack) — Ferrari Rosso Corsa.
  - **PetronasSync**: Real-Time Collaboration & VCS Engine (MERN Stack) — Mercedes Petronas Teal.
  - **AeroSort**: Visual Algorithmic Grid & DSA Telemetry — Red Bull Racing Matte Navy.
  - **PapayaCloud**: Microservices Dispatcher & API Paddock — McLaren Papaya Orange.
- Scorecards include pitstop response times (0.08s), downforce graphs, constructor championship points (`+25 PTS`), and cockpit links.

### 5. 🧑‍🚀 Driver Dossier & Entrepreneurial Drive (About Me)
- High-tech bento grid detailing engineering philosophy: *"Aerodynamic Code with Zero Drag & Ruthless Velocity."*
- Entrepreneurial mission: Bridging the gap between robust software engineering and scalable commercial startup ventures.
- Biometrics & track record of deployments, hackathons, and founder initiatives.

### 6. 🏆 Grand Prix Seasons (Experience)
- Career timeline modeled after F1 championship stints:
  - **Season 2024-2026 // Soft Compound (🔴 S)**: Lead Full-Stack Engineer & Product Builder (Pune & Delhi).
  - **Season 2023-2024 // Medium Compound (🟡 M)**: Full-Stack Developer & Systems Contender.
  - **Season 2022-2023 // Hard Compound (⚪ H)**: Algorithmic Systems & Junior Software Driver.

### 7. 📻 Pit-to-Car Radio & Email Search Dispatch Bar (Contact)
- Styled like an F1 pitwall radio console on frequency `450.250 MHz`.
- Interactive search dispatch bar with query input and *"TRANSMIT EMAIL"* action (`mailto:`).
- Paddock coordinates: **Pune / Delhi, India**.

---

## 🛠️ Tech Stack

- **HTML5**: Semantic tags, accessible landmarks, custom inline SVGs for F1 cars, circuits, and telemetry dials.
- **CSS3**: Custom properties, CSS Grid, Flexbox, `@keyframes` animations, `clip-path`, SVG filters, backdrop filters, and responsive media queries.
- **No external JavaScript libraries required**.

---

## 🚀 How to Run Locally

You can open the portfolio in any modern browser:

### Option 1: Direct File Open
Double-click `index.html` or open it with your browser:
```bash
open index.html
```

### Option 2: Local HTTP Server (Python)
```bash
python3 -m http.server 8000
```
Then visit `http://localhost:8000` in your browser.

