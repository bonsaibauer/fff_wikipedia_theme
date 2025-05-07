[![Repository](https://img.shields.io/badge/Repository-fff__wikipedia__theme-blue?style=flat&logo=github)](https://github.com/bonsaibauer/fff_wikipedia_theme)
![License](https://img.shields.io/badge/License-BSD%202--Clause-blue)
[![Report Problem](https://img.shields.io/badge/Report-new_Problem_or_Issue-critical?style=flat&logo=github)](https://github.com/bonsaibauer/fff_wikipedia_theme/issues/new)


# 🌍 FFF Wikipedia Theme

Ein an die **Corporate Identity** von Fridays for Future angepasstes MediaWiki-Skin, basierend auf dem beliebten [Foreground-Skin](https://github.com/wikimedia/mediawiki-skins-Foreground).

> 🌱 Optimiert für [wiki.fridaysforfuture.de](https://wiki.fridaysforfuture.de)

---

## 📥 Installation

### 1. Skin herunterladen

Kopiere die Theme-Dateien in das `/skins`-Verzeichnis deiner MediaWiki-Installation:

```bash
cd /var/www/html/skins
git clone https://github.com/bonsaibauer/fff_wikipedia_theme.git Foreground
```

Zum Aktualisieren des Themes:

```bash
cd /var/www/html/skins/Foreground
git pull https://github.com/bonsaibauer/fff_wikipedia_theme.git
```

---

## ⚙️ Konfiguration

### 1. In `LocalSettings.php` einfügen

#### Bestehende Einstellungen anpassen:

```php
$wgSitename = 'FFF Infopoint';
$wgMetaNamespace = 'Fridays for Future Wiki';
$wgDefaultSkin = 'Foreground';
```

#### Neue Einstellungen hinzufügen:

```php
wfLoadSkin( 'Foreground' );
$wgSkipSkins = [ 'vector', 'vector2' ];

$wgForegroundFeatures = [
  'showActionsForAnon' => true,
  'NavWrapperType' => 'divonly',
  'showHelpUnderTools' => true,
  'showRecentChangesUnderTools' => true,
  'enableTabs' => false,
  'wikiName' => $wgSitename,
  'navbarIcon' => true,
  'IeEdgeCode' => 1,
  'showFooterIcons' => false,
  'addThisPUBID' => '',
  'useAddThisShare' => '',
  'useAddThisFollow' => ''
];

$wgLogo = $wgScriptPath . '/skins/Foreground/logo/fff_earth_120px.png';
```

---

## 🧭 Wiki-Navigation anpassen

Bearbeite `MediaWiki:Sidebar`, um die neue Navigation zu übernehmen:

```wiki
* Mitmachen
** Wiki - Einführung|Wie schreibe ich einen Artikel?
** recentchanges-url|recentchanges
** Special:AllPages|Alle Seiten
** Spezial:Kategorien|Alle Kategorien
** randompage-url|randompage
** helppage|help
* SEARCH
* TOOLBOX

* Über uns
** Forderungen|Unsere Forderungen
** Kampagnenübersicht|Unsere Kampagnen
** FFF Glossar|FFF Glossar

* Demo
** FFF-Tools|FFF-Tools
** Streikzahlen eintragen|Streikzahlen eintragen
** Generatoren|Generatoren
** Pressearbeit für OGs|Pressearbeit für OGs
** Corporate-Identity|Corporate Identity

* Gruppen
** Ortsgruppen|Ortsgruppen
** Bundesebene|Bundesebene 
** Arbeitsgruppen|Arbeitsgruppen
** Projektgruppen|Projektgruppen
** Wissensgruppen|Wissensgruppen

* Vernetzung
** FFF Call|FFF Call
** Plena, Safespaces & Foren|Plena, Safespaces & Foren
** Gremien & gewählte Teams|Gremien
** Communication Task Force|CTF
** PlenAG-Vernetzung|PlenAG-Vernetzung
** For Future Bewegungen|For Future Bündnis

* Service
** Übersicht|Übersicht
** Formulare|Formulare
** Infogruppen|Infogruppen
** Finanzbericht|Finanzbericht

* Konzepte
** FINTA-Strukturen|FINTA-Strukturen
** Strukturpapier|Strukturpapier
** Finanzkonzept|Finanzkonzept
** Rechtshilfe Finanzkonzept|Rechtshilfe Finanzkonzept
** Pressekonzept|Pressekonzept
** Chatkonzpet|Chatkonzept
** Öffentlichkeitsarbeit bzgl. SboGs|Öffentlichkeitsarbeit bzgl. SboGs
```

---

## 🎨 Design-Vorschau
| Screenshot | Vorschau |
|------------|----------|
| **Bild 1** | ![Bild 1](https://github.com/bonsaibauer/fff-foreground-theme/assets/129884416/1e46ab0d-3d6e-4cb5-b855-2923e4a699c0) |
| **Bild 2** | ![Bild 2](https://github.com/bonsaibauer/fff-foreground-theme/assets/129884416/479610e5-bc84-4dc1-adf5-27621b4435de) |
| **Bild 3** | <img src="https://github.com/bonsaibauer/fff-foreground-theme/assets/129884416/6f774f17-1f2c-432c-a0b8-14e1bd174be4" width="280"> |
| **Bild 4** | <img src="https://github.com/bonsaibauer/fff-foreground-theme/assets/129884416/9e49dac0-1dd3-4550-a1c7-cf80262072db" width="280"> |

---

## 🤝 Mitwirken

Pull Requests, Bug-Reports oder Feature-Vorschläge sind jederzeit willkommen!

---

## 📎 Download

🔽 [fff_wikipedia_theme.zip](https://github.com/bonsaibauer/fff_wikipedia_theme/archive/refs/heads/main.zip)
