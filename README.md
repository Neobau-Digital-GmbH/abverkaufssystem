# Abverkaufssystem 2026
### Das operative Vertriebshandbuch für Bauträger-Teams

Entwickelt von **neubau.marketing** — Unternehmensberatung für Neubauvermarktung im DACH-Raum.

**Live:** https://neobau-digital-gmbh.github.io/abverkaufssystem/

---

## Was ist das?

Ein browserbasiertes Vertriebs-Schulungsdeck für Bauträger-Vertriebsteams. Kein Login, keine App, keine Installation — direkt im Browser nutzbar. Jede Slide ist sofort anwendbar, ohne Vertriebsvorkenntnisse.

Inhaltlich fundiert auf MIT-Studien zur Lead-Response-Zeit, Cialdini-Prinzipien und validierten Vertriebsmethoden, adaptiert für den deutschen Neubaumarkt 2026.

---

## Navigation

| Aktion | Steuerung |
|---|---|
| Nächste Slide | `→` / `↓` / `Leertaste` / Pfeil rechts |
| Vorherige Slide | `←` / `↑` / Pfeil links |
| Direkt zu Slide | Dots am unteren Rand |
| Erste Slide | `Pos1` |
| Letzte Slide | `Ende` |

---

## Slides

| Datei | Inhalt |
|---|---|
| `slide_00.html` | Das System — Pipeline-Übersicht & Commitment |
| `slide_00a.html` | Warum jetzt — Marktveränderung & Expertenstatus |
| `slide_01.html` | Reaktionszeit — Die ersten 5 Minuten |
| `slide_02.html` | Vorqualifikation — 5 Fragen, 5 Minuten |
| `slide_02a.html` | Vorqualifikation Hands-on — Opening Script & Tools |
| `slide_03.html` | Käufertypen — Der Macher, Enthusiast, Bedächtige, Analytiker |
| `slide_04.html` | Eigennutzer vs. Kapitalanleger — Zwei verschiedene Gespräche |
| `slide_05.html` | Das Online-Meeting — 7 Phasen, 45 Minuten |
| `slide_05a.html` | Online-Meeting Hands-on — Vorbereitung & Pitch-Deck |
| `slide_06.html` | Nachfassen — 2-Phasen-Modell, mind. 5 Versuche |
| `slide_07.html` | Einwände — 5 häufigste + Spezialfall |
| `slide_08.html` | Marktargumente 2026 — 4 belegbare Zahlen |
| `slide_09.html` | KPIs & Reporting — Was tracken, was die Zahlen bedeuten |

---

## Slides bearbeiten

Jede Slide ist eine eigenständige HTML-Datei. Inhalte sind direkt im HTML editierbar.

**Neue Slide hinzufügen:**
1. Neue Datei `slide_XX.html` anlegen (bestehende Slide als Vorlage)
2. In `index.html` unter `const SLIDES = [...]` an der richtigen Position eintragen
3. Pushen → automatisches Deployment via GitHub Pages

**Reihenfolge ändern:**
Nur in `index.html` die SLIDES-Array-Reihenfolge anpassen — Dateinamen bleiben unverändert.

---

## Deployment

Gehostet via **GitHub Pages** auf dem `main`-Branch.  
Jeder Push auf `main` → automatisches Deployment, live in ~1 Minute.

---

## Vertraulichkeit

Dieses Deck enthält proprietäre Vertriebsmethoden und interne Benchmarks von neubau.marketing.  
**Nicht öffentlich teilen.** Nur für onboarded Kundenprojekte bestimmt.

---

*neubau.marketing — Neobau Digital GmbH*
