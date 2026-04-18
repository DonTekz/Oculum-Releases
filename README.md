# 🔮 **OCULUM - RPG TOOLSET**

> **Status:** 🟠 **BETA - Intensive Entwicklung aktiv**  
> **Version:** 1.1.4 | **Created by:** DonTekz | **Last Updated:** 2026-04-18

---

## 📑 **Inhaltsverzeichnis**

| 🇩🇪 Deutsch | 🇬🇧 English |
|:-----:|:-----:|
| [Überblick](#-überblick) | [Overview](#-overview) |
| [Features](#-main-features) | [Features](#-main-features-1) |
| [Module & Creators](#-module--creators) | [Modules & Creators](#-modules--creators-1) |
| [Sprachzusammensetzung](#-technical-stack) | [Tech Stack](#-technical-stack-1) |
| [Bekannte Probleme](#-known-issues) | [Known Issues](#-known-issues-1) |
| [Roadmap](#-roadmap) | [Roadmap](#-roadmap-1) |

---

## 🇩🇪 **DEUTSCH VERSION**

---

### 🔮 **Überblick**

```
┏━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━┓
┃   ⚔️ OCULUM RPG TOOLSET ⚔️         ┃
┃                                    ┃
┃   "Schmiede dein Schicksal"        ┃
┃                                    ┃
┃   🎲 RPG Helper     ┃
┃   🤖 KI-Assistent integriert       ┃
┃   👥 Multiplayer-fähig             ┃
┃   🎨 Fantasy-Design inkl.          ┃
┗━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━┛
```

**Oculum** ist ein umfassendes **RPG-Management-Tool** Tabletop-Rollenspiele. Mit diesem Beta-Toolset kannst du:

- 🐉 **Kreaturen erstellen** (Monster, NPCs, Bosse)
- ⚔️ **Gegenstände & Items** designen
- 🧙 **Zauber & Spells** inventarisieren
- 👤 **Charaktere & NPCs** verwalten
- 📖 **Geschichten & Kampagnen** schreiben
- 🎲 **Würfler & Token-Generator** nutzen
- 🤖 **KI-Dungeon-Master** für Inspiration
- 📡 **Multiplayer-Lobby** für Spieler-Sessions
- 🎨 **4 visuelle Themes** zum Wechseln

---

### ✨ **Main Features**

#### 🐉 **1. Creature Creator - Kreaturen erstellen**

```
┌─────────────────────────────────────┐
│ KREATUR EDITOR                      │
├─────────────────────────────────────┤
│                                     │
│ 📋 BASIS-TAB (👹)                  │
│   • Name & Bild des Monsters        │
│   • Herausforderungsgrad (CR)       ���
│   • Größe & Kreaturentyp            │
│   • Gesinnung & Sprachen            │
│   • XP-Berechnung automatisch       │
│                                     │
│ ⚔️ WERTE-TAB (⚔️)                  │
│   • 6 Attribute (STR, DEX, CON...)  │
│   • Armor Class (AC)                │
│   • Trefferpunkte (HP)              │
│   • Geschwindigkeit                 │
│   • Sinne (Darkvision, etc.)        │
│                                     │
│ ✨ FÄHIGKEITEN-TAB (✨)            │
│   • Rettungswürfe                   │
│   • Fertigkeiten                    │
│   • Schwachstellen & Resistenzen    │
│   • Immunitäten                     │
│   • Besondere Fähigkeiten (Traits)  │
│                                     │
│ 🔥 AKTIONEN-TAB (🔥)              │
│   • Normale Aktionen                │
│   • Reaktionen                      │
│   • Legendäre Aktionen              │
│   • Hortaktionen (Lair Actions)     │
│   • Damage-Berechnung               │
│                                     │
│ 📜 LORE-TAB (📜)                   │
│   • Beschreibung (intern)           │
│   • Begegnungstext (zum Vorlesen)   │
│   • Loot & Drops                    │
│   • Münzen/Währung                  │
│   • 🤖 AI-generierter Loot/Lore    │
│                                     │
│ 🎯 ZUSÄTZE:                        │
│   • KI: Monster (Stats & Lore)      │
│   • Preview anzeigen                │
│   • Clear/Leeren Button             │
│   • Speichern                       │
└─────────────────────────────────────┘
```

#### 🗡️ **2. Item Creator - Gegenstände designen**

- 🎁 Waffen & Rüstungen
- 💎 Magische Items
- 🧪 Tränke & Komponenten
- 📦 Ausrüstung & Werkzeuge
- ⭐ Seltenheitsstufen

#### 🧙 **3. Character Creator - Charaktere verwalten**

- 👤 Spieler-Charaktere erstellen
- 📊 Leveling & Experience
- 💪 Fähigkeiten & Fertigkeiten
- 📜 Character Sheet Viewer
- *(In Arbeit - WIP)*

#### 🎭 **4. NPC Creator - NPCs generieren**

- 🎭 Nicht-spielbare Charaktere
- 📍 Settlements & Orte
- 💬 Dialog-Trees
- 🎬 Persönlichkeiten
- *(In Arbeit - WIP)*

#### 🔮 **5. Spell Creator - Zauber-Bibliothek**

- 📖 Zauber-Details
- ✨ Effekt-Beschreibungen
- 📊 Damage & Duration
- 🎯 Spell Levels (Cantrip bis 9)
- 🔍 Quickview & Hover-Info

#### 📖 **6. Story Creator - Kampagnen schreiben**

- 📝 Story/Szenen-Editor
- 🎨 Zen-Modus (ablenkungsfrei)
- 🏗️ Plot-Strukturen
- 🔗 Verknüpfungen
- 📱 Export als PDF/JSON

#### 📝 **7. Campaign Log - Session-Logs**

- 📓 Sessionprotokolle
- ⏰ Timeline der Ereignisse
- 💭 Notizen & Gedanken
- 📊 Statistiken

---

### 🤖 **KI-Integration (Groq API - 100% kostenlos)**

```
┌─────────────────────────────────────┐
│ 🤖 AI-DUNGEON-MASTER-ASSISTENT     │
│                                     │
│ Schnell-Buttons:                    │
│ 💡 Plot-Twist                       │
│ 🎭 NPC-Idee                        │
│ ⚔️ Encounter Generator              │
│ 🧩 Rätsel & Puzzle                  │
│ 💰 Loot-Generierung                 │
│ 🗣️ Dialog-Ideen                     │
│                                     │
│ + Freie Prompts möglich!            │
│                                     │
│ Features:                           │
│ • Contextual AI (bezieht Kontext)   │
│ • Offline-Modelle optional          │
│ • Mistral AI für lokale Nutzung     │
│ • Real-time Streaming Responses     │
└─────────────────────────────────────┘
```

---

### 🎨 **Visual Design System (4 Themes)**

```
┌──────────────────────────────────────┐
│  THEME SELECTION                     │
├──────────────────────────────────────┤
│                                      │
│ 📚 Magier-Bibliothek (Mage Library) │
│    → Blaue Töne, magisch            │
│    → Bücherregale & Arkane Symbole  │
│                                      │
│ ⚒️  Zwergen-Schmiede (Dwarf Forge)  │
│    → Rote & Orange Töne             │
│    → Metall & Feuer-Effekte         │
│                                      │
│ 🌿 Elfen-Laube (Elf Grove)          │
│    → Grüne & Gold Töne              │
│    → Natur & Waldthema              │
│                                      │
│ 📜 Pergament (Parchment)            │
│    → Klassisches Beige/Braun        │
│    → Altpapier-Look                 │
│                                      │
└──────────────────────────────────────┘
```

---

### 🎲 **Tools & Utilities**

| 🛠️ Tool | 📝 Beschreibung | 🔧 Funktion |
|:---:|---|---|
| 🎲 **Würfel-Gott** | Dice Roller | d4, d6, d8, d10, d12, d20 + custom |
| 🪙 **Token-Schmied** | Token Generator | Runde Tokens mit Rahmen-Styles |
| 📡 **Live Übertragung** | DM Broadcast | Zeige Bilder & NPCs für Spieler |
| 👥 **Player Lobby** | Multiplayer | Spieler-Sessions in Echtzeit |
| 💾 **Archiv** | Backup/Export | JSON Export & Import |
| 🌍 **Sprach-System** | Localization | Deutsch & English |

---

### ⚙️ **Technical Stack**

```
┌────────────────────────────────────┐
│ SPRACHZUSAMMENSETZUNG              │
├────────────────────────────────────┤
│                                    │
│ JavaScript   ████████░░  64.8%    │
│ CSS          ██████░░░░  20.2%    │
│ HTML         ███░░░░░░░  10.5%    │
│ Python       ██░░░░░░░░   4.3%    │
│ Inno Setup   ░░░░░░░░░░   0.2%    │
│                                    │
└────────────────────────────────────┘
```

**Technologien:**
- 🌐 **Frontend:** HTML5, CSS3, JavaScript (Vanilla)
- 🔗 **Multiplayer:** Socket.IO für Real-Time Communication
- 🤖 **AI:** Groq API (kostenlosen LLM-Service)
- 🎨 **UI Libraries:** Marked.js (Markdown), Tone.js (Audio)
- 📱 **Responsive:** Mobile-optimiert
- 🎙️ **Audio:** Sound Effects & Ambience Sounds
- 💾 **Storage:** LocalStorage + JSON Export

---

### ⚠️ **Known Issues / Bekannte Probleme**

```
╔════════════════════════════════════╗
║ 🔴 KRITISCHE PROBLEME              ║
╚════════════════════════════════════╝

• KI-API-Timeouts bei großen Requests
  → Status: In Bearbeitung
  → Lösung: Timeout-Handling (Q2 2026)

╔════════════════════════════════════╗
║ 🟠 WICHTIGE PROBLEME               ║
╚════════════════════════════════════╝

• Lobby-Instabilität bei vielen Spielern
  → Status: In Bearbeitung
  → Lösung: Connection-Refactor (Q3 2026)

• Token-Generator zeigt Rendering-Fehler
  → Status: Identifiziert
  → Lösung: Canvas-Optimierung geplant

• Deutsche Übersetzungen teilweise unvollständig
  → Status: Community-Feedback erwünscht
  → Lösung: Laufende Ergänzung

╔════════════════════════════════════╗
║ 🟡 MINOR-PROBLEME                  ║
╚════════════════════════════════════╝

• Einige UI-Elemente bei niedriger Auflösung
• Audio-Sync bei schnellen Klicks
```

---

### 🛤️ **Roadmap - Fahrplan**

```
Q2 2026  ████████░░  40% AKTIV
├─ ✅ KI-Integration stabilisieren
├─ ✅ Fehler-Handling verbessern
├─ ⏳ Neue Creator-Module hinzufügen
├─ ⏳ Lobby-Optimierungen
└─ ⏳ API-Caching implementieren

Q3 2026  ████░░░░░░  20% GEPLANT
├─ ⏳ Multiplayer-Lobby überarbeiten
├─ ⏳ Performance-Tests durchführen
├─ ⏳ Community-Feedback integrieren
├─ ⏳ Mobile-App-Vorbereitung
└─ ⏳ Kampagnen-Import/Export

Q4 2026  ██░░░░░░░░  10% GEPLANT
├─ ⏳ Beta → Release übergang
├─ ⏳ Dokumentation finalisieren
├─ ⏳ Größere Beta-Nutzergruppe
├─ ⏳ Marketing & Outreach
└─ ⏳ Version 1.0.0 Release

2027 🌟  ░░░░░░░░░░   0% TRÄUME
├─ 💭 Native Mobile Apps (iOS/Android)
├─ 💭 Cloud-Speicher Integration
├─ 💭 Community Marketplace
├─ 💭 Advanced Analytics Dashboard
└─ 💭 API für 3rd-Party Integration
```

**Legend:** ✅ Abgeschlossen | ⏳ Geplant | 🔄 In Bearbeitung | 💭 Zukünftig

---

## 🇬🇧 **ENGLISH VERSION**

---

### 🔮 **Overview**

```
┏━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━┓
┃   ⚔️ OCULUM RPG TOOLSET ⚔️         ┃
┃                                    ┃
┃   "Forge Your Destiny"             ┃
┃                                    ┃
┃   🎲 RPG Helper     ┃
┃   🤖 AI-Assistant Integrated       ┃
┃   👥 Multiplayer-Ready             ┃
┃   🎨 Fantasy Design Included       ┃
┗━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━┛
```

**Oculum** is a comprehensive **RPG Management Tool** designed tabletop role-playing games. With this Beta toolset, you can:

- 🐉 **Create Creatures** (Monsters, NPCs, Bosses)
- ⚔️ **Design Items & Loot**
- 🧙 **Manage Spells & Cantrips**
- 👤 **Create & Manage Characters**
- 📖 **Write Stories & Campaigns**
- 🎲 **Use Dice Roller & Token Generator**
- 🤖 **Get AI-DM Inspiration**
- 📡 **Run Multiplayer Sessions**
- 🎨 **Switch Between 4 Visual Themes**

---

### ✨ **Main Features**

#### 🐉 **1. Creature Creator - Design Monsters**

```
┌─────────────────────────────────────┐
│ CREATURE EDITOR                     ���
├─────────────────────────────────────┤
│                                     │
│ 📋 BASIS TAB (👹)                  │
│   • Monster name & image            │
│   • Challenge rating (CR)           │
│   • Size & creature type            │
│   • Alignment & languages           │
│   • XP calculation (automatic)      │
│                                     │
│ ⚔️ STATS TAB (⚔️)                  │
│   • 6 Attributes (STR, DEX, CON)   │
│   • Armor Class (AC)                │
│   • Hit Points (HP)                 │
│   • Movement Speed                  │
│   • Senses (Darkvision, etc.)       │
│                                     │
│ ✨ SKILLS TAB (✨)                 │
│   • Saving throws                   │
│   • Skills                          │
│   • Vulnerabilities & resistances   │
│   • Immunities                      │
│   • Special traits & abilities      │
│                                     │
│ 🔥 ACTIONS TAB (🔥)               │
│   • Regular actions                 │
│   • Reactions                       │
│   • Legendary actions               │
│   • Lair actions                    │
│   • Damage calculation              │
│                                     │
│ 📜 LORE TAB (📜)                   │
│   • Internal description            │
│   • Encounter text (to read aloud)  │
│   • Loot & drops                    │
│   • Coins/currency                  │
│   • 🤖 AI-generated loot/lore      │
│                                     │
│ 🎯 EXTRAS:                          │
│   • AI: Monster (Stats & Lore)      │
│   • Show preview                    │
│   • Clear button                    │
│   • Save                            │
└─────────────────────────────────────┘
```

#### 🗡️ **2. Item Creator - Design Equipment**

- 🎁 Weapons & Armor
- 💎 Magical Items
- 🧪 Potions & Components
- 📦 Gear & Tools
- ⭐ Rarity Levels

#### 🧙 **3. Character Creator - Manage Characters**

- 👤 Player character creation
- 📊 Leveling & XP tracking
- 💪 Skills & proficiencies
- 📜 Character sheet viewer
- *(Work In Progress - WIP)*

#### 🎭 **4. NPC Creator - Generate NPCs**

- 🎭 Non-player characters
- 📍 Settlements & locations
- 💬 Dialog trees
- 🎬 Personalities
- *(Work In Progress - WIP)*

#### 🔮 **5. Spell Creator - Spell Library**

- 📖 Spell details & descriptions
- ✨ Effect descriptions
- 📊 Damage & duration
- 🎯 Spell levels (Cantrip to 9)
- 🔍 Quickview & hover info

#### 📖 **6. Story Creator - Write Campaigns**

- 📝 Story/scene editor
- 🎨 Zen mode (distraction-free)
- 🏗️ Plot structures
- 🔗 Cross-references
- 📱 Export as PDF/JSON

#### 📝 **7. Campaign Log - Session Notes**

- 📓 Session protocols
- ⏰ Timeline of events
- 💭 Notes & thoughts
- 📊 Statistics

---

### 🤖 **AI Integration (Groq API - 100% Free)**

```
┌─────────────────────────────────────┐
│ 🤖 AI-DUNGEON-MASTER-ASSISTANT     │
│                                     │
│ Quick Buttons:                      │
│ 💡 Plot Twist                       │
│ 🎭 NPC Idea                        │
│ ⚔️ Encounter Generator              │
│ 🧩 Puzzles & Riddles                │
│ 💰 Loot Generation                  │
│ 🗣️ Dialog Ideas                     │
│                                     │
│ + Custom prompts possible!          │
│                                     │
│ Features:                           │
│ • Contextual AI (pulls context)     │
│ • Optional offline models           │
│ • Mistral AI for local use          │
│ • Real-time streaming responses     │
└─────────────────────────────────────┘
```

---

### 🎨 **Visual Design System (4 Themes)**

```
┌──────────────────────────────────────┐
│  THEME SELECTION                     │
├──────────────────────────────────────┤
│                                      │
│ 📚 Mage Library                      │
│    → Blue tones, magical             │
│    → Bookshelves & arcane symbols    │
│                                      │
│ ⚒️  Dwarf Forge                      │
│    → Red & orange tones              │
│    → Metal & fire effects            │
│                                      │
│ 🌿 Elf Grove                         │
│    → Green & gold tones              │
│    → Nature & woodland theme         │
│                                      │
│ 📜 Parchment                         │
│    → Classic beige/brown             │
│    → Old paper look                  │
│                                      │
└──────────────────────────────────────┘
```

---

### 🎲 **Tools & Utilities**

| 🛠️ Tool | 📝 Description | 🔧 Function |
|:---:|---|---|
| 🎲 **Dice Roller** | Dice God | d4, d6, d8, d10, d12, d20 + custom |
| 🪙 **Token Smith** | Token Generator | Round tokens with border styles |
| 📡 **Live Broadcast** | DM Stream | Show images & NPCs to players |
| 👥 **Player Lobby** | Multiplayer | Real-time player sessions |
| 💾 **Archive** | Backup/Export | JSON export & import |
| 🌍 **Language System** | Localization | German & English |

---

### ⚙️ **Technical Stack**

```
┌────────────────────────────────────┐
│ LANGUAGE COMPOSITION               │
├────────────────────────────────────┤
│                                    │
│ JavaScript   ████████░░  64.8%    │
│ CSS          ██████░░░░  20.2%    │
│ HTML         ███░░░░░░░  10.5%    │
│ Python       ██░░░░░░░░   4.3%    │
│ Inno Setup   ░░░░░░░░░░   0.2%    │
│                                    │
└────────────────────────────────────┘
```

**Technologies:**
- 🌐 **Frontend:** HTML5, CSS3, Vanilla JavaScript
- 🔗 **Multiplayer:** Socket.IO for real-time communication
- 🤖 **AI:** Groq API (free LLM service)
- 🎨 **UI Libraries:** Marked.js (Markdown), Tone.js (Audio)
- 📱 **Responsive:** Mobile-optimized
- 🎙️ **Audio:** Sound effects & ambience
- 💾 **Storage:** LocalStorage + JSON export

---

### ⚠️ **Known Issues**

```
╔════════════════════════════════════╗
║ 🔴 CRITICAL ISSUES                 ║
╚════════════════════════════════════╝

• AI API timeouts on large requests
  → Status: In progress
  → Solution: Timeout handling (Q2 2026)

╔════════════════════════════════════╗
║ 🟠 IMPORTANT ISSUES                ║
╚════════════════════════════════════╝

• Lobby instability with many players
  → Status: In progress
  → Solution: Connection refactor (Q3 2026)

• Token generator rendering errors
  → Status: Identified
  → Solution: Canvas optimization planned

• Some translations incomplete
  → Status: Community feedback wanted
  → Solution: Ongoing improvements

╔════════════════════════════════════╗
║ 🟡 MINOR ISSUES                    ║
╚════════════════════════════════════╝

• UI elements at low resolutions
• Audio sync on rapid clicks
```

---

### 🛤️ **Roadmap**

```
Q2 2026  ████████░░  40% ACTIVE
├─ ✅ Stabilize AI integration
├─ ✅ Improve error handling
├─ ⏳ Add new creator modules
├─ ⏳ Lobby optimizations
└─ ⏳ Implement API caching

Q3 2026  ████░░░░░░  20% PLANNED
├─ ⏳ Refactor multiplayer lobby
├─ ⏳ Conduct performance tests
├─ ⏳ Integrate community feedback
├─ ⏳ Mobile app preparation
└─ ⏳ Campaign import/export

Q4 2026  ██░░░░░░░░  10% PLANNED
├─ ⏳ Beta → Release transition
├─ ⏳ Finalize documentation
├─ ⏳ Expand beta user group
├─ ⏳ Marketing & outreach
└─ ⏳ Version 1.0.0 release

2027 🌟  ░░░░░░░░░░   0% DREAMS
├─ 💭 Native mobile apps (iOS/Android)
├─ 💭 Cloud storage integration
├─ 💭 Community marketplace
├─ 💭 Advanced analytics dashboard
└─ 💭 API for 3rd-party integration
```

**Legend:** ✅ Completed | ⏳ Planned | 🔄 In Progress | 💭 Future

---

## 🤝 **Support & Community**

```
╔════════════════════════════════════╗
║          📞 CONTACT US             ║
╠════════════════════════════════════╣
║                                    ║
║ 📧 Email:                          ║
║    support@oculum-test.com         ║
║                                    ║
║ 💬 Discord:                        ║
║    discord.gg/oculum              ║
║                                    ║
║ 🐛 Issues:                         ║
║    GitHub Issues Tracker           ║
║                                    ║
║ 📖 Docs:                           ║
║    wiki/documentation              ║
║                                    ║
╚════════════════════════════════════╝
```

---

## 📜 **License & Credits**

```
Created with ❤️ by DonTekz

Version: 1.1.0 (Offline AI Update)
Last Updated: 2026-04-18
Status: 🟠 BETA - Active Development

Powered by:
• Groq API (AI)
• Socket.IO (Multiplayer)
• Marked.js (Markdown)
• Tone.js (Audio)

Join us on GitHub: https://github.com/DonTekz/Oculum-Test
```

<div align="center">

---

### ✨ **Thank You for Joining the Adventure!** ✨

**"May Your Rolls be High and Your Stories Legendary!"**

🎲 Oculum RPG Toolset 🎲

</div>
