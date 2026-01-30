# 🚀 AI: Alla Är Välkomna

En interaktiv presentation om hur AI demokratiserar tech-världen och gör IT tillgängligt för alla – oavsett ålder eller bakgrund.

**Presentatör:** Said Borna | DevOps-student, Chas Academy 2026

---

## 📖 Om Presentationen

Från "Hello World" till live-projekt på bara 5 månader. En personlig resa som visar hur AI förändrar spelreglerna för alla som vill lära sig teknik vid 41 års ålder.

### 🎯 Huvudbudskap

- **IT är för alla** – ålder och bakgrund spelar ingen roll längre
- **AI som verktyg** – game changer
- **Prompt Engineering** – hemligheten bakom framgång
- **Förändring är oundviklig** – häng med eller häng efter

---

## 🛠️ Teknik Stack

- **Reveal.js 5.1.0** – Slideshows med animationer
- **HTML/CSS/JavaScript** – Pure vanilla
- **GitHub Pages** – Hosting via GitHub Actions
- **Transformers-intro** – Med tech/AI-logos och ljud

---

## 📂 Projektstruktur

```
gymnasie-presentation/
├── index.html              # Landningssida med QR-kod
├── slides.html             # Huvudpresentationen (8 slides)
├── assets/
│   ├── audio/
│   │   └── Transformers-roboticsound.wav  # Intro-ljud
│   └── image/
│       └── ChasAcademy-logga.png          # Lokal logotyp
├── .github/
│   └── workflows/
│       └── deploy.yml      # Auto-deploy till GitHub Pages
└── README.md
```

---

## 🚀 GitHub Pages Deployment

### ✅ Setup (En Gång)

För att få din `.github.io`-adress:

1. **Gå till repo Settings → Pages**
2. Under **Build and deployment**:
   - **Source**: Välj `GitHub Actions` ✅
   - *(INTE "Deploy from a branch")*
3. **Repot måste vara public** (eller GitHub Pro/Team)

### 🔄 Automatisk Deploy

Workflow i `.github/workflows/deploy.yml` deplojar automatiskt vid:

- Push till `main`-branch
- Manuell trigger via Actions-fliken

**URL blir:** `https://s-borna.github.io/gymnasie-presentation/`

### 💻 Lokal Utveckling

```bash
# Öppna direkt (ingen build behövs)
open index.html
open slides.html

# Eller starta lokal server
python3 -m http.server 8000
# Besök: http://localhost:8000
```

---

## 📱 Funktioner

### 🏠 Landningssida (index.html)

- Personlig intro med gradient-effekter
- QR-kod för mobil-åtkomst
- Direktlänk till slides
- Sociala länkar: Portfolio, GitHub, LinkedIn

### 🎬 Presentationen (slides.html)

**8 slides med auto-animationer:**

1. **Titel** – AI: Alla är välkomna 🫶🏼
2. **Hook** – 41 år, Hello World för 5 månader sedan
3. **IT för alla** – Myter vs verklighet
4. **Vad AI gör** – Medicin, forskning, vardagen
5. **Utvecklingen** – Häng med eller häng efter
6. **Är AI riskfritt?** – Nej, men förändring är oundviklig
7. **Hemligheten** – Prompt Engineering 🎯
8. **Avslut** – Kontaktlänkar + frågor

**Special Features:**

- Transformers-intro med 20 flyande tech/AI-logos
- Real audio från Transformers (sekunder 5-17)
- Progressive reveal med Reveal.js fragments
- Responsive design för alla skärmar

---

## 🎨 Design

**Färgpalett:**

- Cyan: `#00f0ff` (Primary)
- Pink: `#ff006e` (Secondary)
- Dark: `#0a0a0f` (Bakgrund)

**Typsnitt:**

- Outfit (headings)
- Space Mono (code/tech)
**Typsnitt:**
- Outfit (headings)
- Space Mono (code/tech)

---

## 👨‍💻 Kontakt

**Said Borna**
DevOps-student | Chas Academy 2026

- 🌐 Portfolio: [saidborna.com](https://saidborna.com)
- 💻 GitHub: [@S-Borna](https://github.com/S-Borna)
- 💼 LinkedIn: [Said Borna](https://www.linkedin.com/in/saidborna)

---

## 📋 Checklista för GitHub Pages

- [ ] Repository är **public**
- [ ] `.github/workflows/deploy.yml` finns på plats
- [ ] Settings → Pages → Source: **"GitHub Actions"**
- [ ] Push till `main` → Kolla **Actions-fliken** för status
- [ ] Besök: `https://s-borna.github.io/gymnasie-presentation/`

---

*Built with ☕ and AI*
