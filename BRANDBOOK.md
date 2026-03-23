# Tower Ventures — Brand & UI Design System

## 1. Markenidentität

**Claim:** Intelligente Technologie für ein besseres Morgen
**Tonalität:** Klar, sachlich, kompetent — mit Tiefgang statt Buzzwords.
Deutsch als Hauptsprache. Duzen in Lernkontexten (Agentix), Siezen auf der Hauptseite.

**Logo:** `public/logo.png` — wird auf dunklem und hellem Hintergrund eingesetzt.
Mindestgröße: 32×32px. Freiraum: mindestens halbe Logo-Breite auf jeder Seite.

---

## 2. Farbsystem

### Primärfarben (Akzente)

| Rolle | Light Mode | Dark Mode | Verwendung |
|---|---|---|---|
| Accent Blue | `#1a6dca` | `#3b8ef0` | Primärer Akzent, Links, CTAs |
| Accent Purple | `#8b2fc9` | `#a855f7` | Sekundärer Akzent, Gradient-Partner |

**Gradient:** `linear-gradient(135deg, accent-blue, accent-purple)` — für Buttons, Textakzente, Bordüren.

### Hintergrund & Oberflächen

| Rolle | Light Mode | Dark Mode | Verwendung |
|---|---|---|---|
| Background | `#f8f9fc` | `#06080f` | Seiten-Hintergrund |
| Surface | `#ffffff` | `#0c1021` | Karten, Panels, Sidebar |
| Surface Elevated | `#f0f2f8` | `#131830` | Hover-States, aktive Elemente |
| Surface Inset | `#ebeef5` | `#0a0e1a` | Eingabefelder, eingelassene Bereiche |

### Text

| Rolle | Light Mode | Dark Mode | Verwendung |
|---|---|---|---|
| Foreground | `#0f1729` | `#e8ecf4` | Überschriften, primärer Text |
| Secondary | `#374160` | `#b0bcd5` | Fließtext, Beschreibungen |
| Muted | `#6b7a99` | `#7b8ab0` | Labels, Hilfstexte, Timestamps |
| Disabled | `#a0aac0` | `#3e4a6a` | Deaktivierte Elemente |
| On Accent | `#ffffff` | `#ffffff` | Text auf Accent-Buttons |

### Borders

| Rolle | Light Mode | Dark Mode | Verwendung |
|---|---|---|---|
| Border | `#dfe3ee` | `#1e2642` | Standard-Rahmen |
| Border Subtle | `#ebeef5` | `#151c35` | Trennlinien, leichte Abgrenzung |
| Border Active | `#1a6dca` | `#3b8ef0` | Fokussierte/aktive Elemente |

### Semantische Farben

| Rolle | Light Mode | Dark Mode | Verwendung |
|---|---|---|---|
| Success | `#16a34a` | `#22c55e` | Erfolg, abgeschlossen, aktiv |
| Warning | `#d97706` | `#f59e0b` | Warnungen, gesperrt |
| Error | `#dc2626` | `#ef4444` | Fehler, verboten |
| Info | `#1a6dca` | `#3b8ef0` | Hinweise (= Accent Blue) |

### Agentix Wochen-Akzente

Für die 4 Lernwochen werden abgeleitete Farben aus dem Brand-Spektrum verwendet:

| Woche | Farbe | Dark Mode | Bedeutung |
|---|---|---|---|
| Woche 1 | `#1a6dca` | `#3b8ef0` | Orientierung (= Accent Blue) |
| Woche 2 | `#8b2fc9` | `#a855f7` | Steuern/Einschätzen (= Accent Purple) |
| Woche 3 | `#c05621` | `#f07a3b` | Sicherheit (Warm, warnend) |
| Woche 4 | `#0f8a6b` | `#34d399` | Bauen/Gestalten (Grün, Wachstum) |

---

## 3. Typografie

### Font-Stack

| Verwendung | Font | Fallback |
|---|---|---|
| UI / Fließtext | Geist Sans | `system-ui, sans-serif` |
| Code / Mono | Geist Mono | `ui-monospace, monospace` |

Keine weiteren Fonts. Keine Serif-Fonts.

### Größen & Gewichte

| Stufe | Größe | Gewicht | Line-Height | Verwendung |
|---|---|---|---|---|
| Display | `3rem–4.5rem` | 800 (extrabold) | 1.1 | Hero-Headline Landing Page |
| H1 | `1.875rem` (30px) | 700 (bold) | 1.2 | Seitenüberschriften |
| H2 | `1.25rem` (20px) | 600 (semibold) | 1.3 | Sektionsüberschriften |
| H3 | `1rem` (16px) | 600 | 1.4 | Kartenüberschriften |
| Body | `0.875rem` (14px) | 400 | 1.6 | Fließtext, Beschreibungen |
| Small | `0.75rem` (12px) | 400 | 1.5 | Labels, Hilfstext |
| Tiny | `0.6875rem` (11px) | 500 | 1.4 | Badges, Tags, Timestamps |
| Micro | `0.625rem` (10px) | 500 | 1.3 | Uppercase-Labels, Fortschritt |

### Uppercase-Labels

Für Sektions-Kennzeichnungen: `font-size: 10px`, `letter-spacing: 2–3px`, `text-transform: uppercase`, Farbe: `muted`.

---

## 4. Spacing & Layout

### Spacing-Skala (rem)

```
4px   = 0.25rem   (xs)
8px   = 0.5rem    (sm)
12px  = 0.75rem   (md)
16px  = 1rem      (base)
24px  = 1.5rem    (lg)
32px  = 2rem      (xl)
48px  = 3rem      (2xl)
64px  = 4rem      (3xl)
```

### Container

- Max-Width: `72rem` (1152px) — Hauptinhalt
- Padding horizontal: `1.5rem` (mobile), `2rem` (desktop)
- Max-Width für Textblöcke: `40rem` (640px)

### Sidebar (Agentix)

- Breite: `220px` fest
- Background: Surface
- Border-Right: Border Subtle

### Header/Navbar

- Höhe: `52–56px`
- Background: Surface
- Border-Bottom: Border Subtle
- **Links:** Logo + Brand
- **Mitte:** Tab-Navigation (Lernpfad | Sandbox | Assets)
- **Rechts:** Theme-Toggle (Light/Dark) + Sidebar-Toggle + User-Menu

### Header-Toggles (analog VS Code)

| Toggle | Icon | Funktion |
|---|---|---|
| Theme | `<Sun />` / `<Moon />` | Light ↔ Dark Mode wechseln |
| Sidebar | `<PanelLeft />` | Sidebar ein-/ausblenden |
| User | `<User />` oder Avatar-Initialen | Dropdown: Email, Logout |

---

## 5. Komponenten

### Buttons

**Primary (CTA):**
```
Background: gradient(135deg, accent-blue, accent-purple)
Text: white, 14px, semibold
Padding: 12px 28px
Border-Radius: 9999px (pill)
Shadow: accent-blue/20 0 4px 14px
Hover: brightness +10%, shadow vergrößern
```

**Secondary:**
```
Background: surface
Border: 1px gradient-border (blau→lila)
Text: foreground, 14px, medium
Padding: 8px 20px
Border-Radius: 9999px
Hover: surface-elevated
```

**Ghost:**
```
Background: transparent
Border: 1px solid border
Text: muted, 13px
Padding: 6px 14px
Border-Radius: 6px
Hover: surface, text → foreground
```

**Small Action:**
```
Background: accent-blue/10
Border: 1px solid accent-blue/25
Text: accent-blue, 11px
Padding: 4px 10px
Border-Radius: 4px
```

### Karten

```
Background: surface
Border: 1px solid border
Border-Radius: 8px
Padding: 16px
Hover: border → border-active (transition 0.2s)
```

### Eingabefelder

```
Background: surface-inset
Border: 1px solid border
Border-Radius: 6px
Padding: 8px 12px
Font: 13px, secondary color
Focus: border → accent-blue, box-shadow: 0 0 0 2px accent-blue/15
```

### Badges / Tags

```
Background: [farbe]/10
Text: [farbe], 11px, medium
Padding: 2px 8px
Border-Radius: 4px
```

### Progress Bar

```
Track: border (Höhe: 3px, border-radius: 2px)
Fill: accent-blue (oder Wochen-Farbe)
Transition: width 0.5s ease
```

### Checkboxen (Agentix Sessions)

```
Größe: 18×18px
Border: 1.5px solid border
Border-Radius: 4px
Checked: background → wochen-farbe, border → wochen-farbe, icon: ✓ weiß
```

### Modal

```
Overlay: #000000 / 70% opacity
Container: surface, border: border, border-radius: 8px
Max-Width: 640px
Max-Height: 85vh
Header: border-bottom, padding 16px 20px
Body: padding 20px, overflow-y auto
Footer: border-top, padding 12px 20px
```

### Chat-Bubbles (Sandbox)

```
User:     background: accent-blue/12, border: accent-blue/25
Assistant: background: surface, border: border
Font: 13px, line-height: 1.7
Max-Width: 78%
Border-Radius: 8px
Padding: 10px 14px
```

---

## 6. Animationen & Transitions

### Standard-Transition
```
transition: all 0.2s ease
```

### Fade-Up (Seitenelemente)
```
@keyframes fade-up {
  0% { opacity: 0; transform: translateY(28px); }
  100% { opacity: 1; transform: translateY(0); }
}
Timing: 0.8s cubic-bezier(0.16, 1, 0.3, 1)
Staggering: +0.1s pro Element
```

### Pulse (Ladeindikator)
```
@keyframes pulse {
  0%, 100% { opacity: 0.3; }
  50% { opacity: 1; }
}
3 Dots, je 6×6px, accent-blue, Versatz 0.2s
```

### Hover
- Karten: Border-Farbe wechselt (0.2s)
- Buttons: brightness/shadow-Änderung (0.3s)
- Links: color-Änderung (0.15s)

---

## 7. Dark/Light Mode

- **Systemeinstellung:** `prefers-color-scheme` als Default
- Alle Farben über CSS Custom Properties in `:root`
- Agentix übernimmt das gleiche System — kein hartkodierter Dark Mode
- Komponenten nutzen nur Variablen, nie direkte Hex-Werte

---

## 8. Icons

- **Lucide React** — einzige Icon-Library, tree-shakeable
- Keine Emojis, keine Unicode-Symbole im UI
- Größen: `size-4` (16px) für Inline, `size-5` (20px) für Navigation, `size-6` (24px) für Feature-Icons
- Farbe über Tailwind: `text-primary`, `text-muted-foreground`, etc.

### Icon-Mapping (Session-Typen)

| Typ | Icon | Lucide Komponente |
|---|---|---|
| Tool | Schraubenschlüssel | `<Wrench />` |
| Reflexion | Kreis mit Punkt | `<CircleDot />` |
| Sandbox | Hexagon | `<Hexagon />` |
| Übung | Stift | `<PenTool />` |
| Demo | Play | `<Play />` |
| Asset | Download | `<Download />` |

### Icon-Mapping (Navigation)

| Element | Lucide Komponente |
|---|---|
| Lernpfad | `<BookOpen />` |
| Sandbox | `<Terminal />` |
| Assets | `<FileText />` |
| Einstellungen | `<Settings />` |
| Logout | `<LogOut />` |
| Fortschritt | `<CheckCircle />` |
| Gesperrt | `<Lock />` |
| Pfeil rechts | `<ChevronRight />` |
| Schließen | `<X />` |
| Kopieren | `<Copy />` |

---

## 9. Responsive Breakpoints

| Name | Breite | Verhalten |
|---|---|---|
| Mobile | < 640px | Single Column, Sidebar collapsed |
| Tablet | 640–1024px | Sidebar optional, angepasste Grids |
| Desktop | > 1024px | Volle Sidebar, Multi-Column Grids |

### Navigation Pattern

**Desktop (> 768px):**
- Sidebar links: Phasen-Navigation (220px, fest)
- Hauptnavigation im Header (Lernpfad | Sandbox | Assets)

**Mobile (< 768px):**
- Sidebar entfällt
- Bottom Bar für Hauptnavigation (Lernpfad | Sandbox | Assets)
- Phasen-Auswahl als Dropdown oder horizontaler Swipe oben

---

## 10. Do's und Don'ts

### Do
- CSS Custom Properties für alle Farben
- Tailwind-Klassen bevorzugen, inline styles vermeiden
- Gradient sparsam einsetzen — nur für CTAs und Akzente
- Ausreichend Kontrast (WCAG AA mindestens)
- Konsistente Spacing-Skala verwenden

### Don't
- Keine zusätzlichen Fonts einbinden
- Keine CSS-Frameworks neben Tailwind
- Keine festen Hex-Werte in Komponenten — immer Variablen
- Kein reines Schwarz (#000) oder reines Weiß (#fff) als Hintergrund
- Keine Schatten auf Dark Mode (außer auf Accent-Buttons)
- Keine Animationen > 1s Dauer für UI-Interaktionen
