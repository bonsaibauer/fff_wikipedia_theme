# FFForeground Theme für wiki.fridaysforfuture.de

Das Redesign von wiki.fridaysforfuture.de, basiert auf Foreground https://github.com/wikimedia/mediawiki-skins-Foreground und wurde nach den Corporate Identity Farben erstellt.

## Download

First, copy the Foreground source files in Medaiwki Path /skins, you can use git to clone the repository, which makes it very easy to update the code, using:

    git clone https://github.com/bonsaibauer/ffforeground-theme.git Foreground

After that, you can issue `git pull` to update the code at anytime.

## Setup

Once the skin is in place add one the following lines to your "LocalSettings.php" file.

### Update these settings:

$wgSitename = "FFF Infopoint";
$wgMetaNamespace = "Fridays for Future Wiki";
$wgLogo = $wgScriptPath . '/skins/Foreground/logo/fff_earth_120px.png';
$wgDefaultSkin="Foreground";

### Add these settings:

$wfLoadSkin( 'Foreground' );
$wgSkipSkins = array( 'addyourskinshere eg. vector', 'vector2', '...' );

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

## Wiki-Settings

### We need to update Mediawiki:Sidebar for the best experience on your wiki:

* navigation
** mainpage|mainpage-description
** recentchanges-url|recentchanges
** randompage-url|randompage
** helppage|help
* SEARCH
* TOOLBOX

*Über uns
** Forderungen|Forderungen
** Nationale Forderungen | Unsere Forderungen
** Kampagnenübersicht|Kampagnenübersicht
** FFF Glossar | FFF Glossar

*Demo
** FFF-Tools|FFF-Tools
** Streikzahlen eintragen|Streikzahlen eintragen
** Generatoren|Generatoren
** Pressearbeit für OGs|Pressearbeit für OGs
** Corporate-Identity | Corporate Identity

*Organe
** Ortsgruppen| Ortsgruppen
** Bundesebene | Bundesebene 
** Arbeitsgruppen| Arbeitsgruppen
** Projektgruppen | Projektgruppen
** Wissensgruppen | Wissensgruppen
** Plena, Safespaces & Foren | Plena, Safespaces & Foren
** FFF Call | FFF Call
** Gremien & gewählte Teams | Gremien
** Communication Task Force | CTF
** PlenAG-Vernetzung | PlenAG-Vernetzung
** For Future Bewegungen | For Future Bündnis

*Service
** Übersicht|Übersicht
** Formulare|Formulare
** Infogruppen|Infogruppen
** Finanzbericht|Finanzbericht

*Konzepte
** FINTA-Strukturen|FINTA-Strukturen
** Strukturpapier|Strukturpapier
** Finanzkonzept|Finanzkonzept
** Rechtshilfe Finanzkonzept|Rechtshilfe Finanzkonzept
** Pressekonzept|Pressekonzept
** Chatkonzpet|Chatkonzept
** Öffentlichkeitsarbeit bzgl. SboGs|Öffentlichkeitsarbeit bzgl. SboGs

*Wiki - Mitarbeit
** Special:AllPages|Alle Seiten
** Spezial:Kategorien|Alle Kategorien
** Wiki-Checklist|Wiki - Checkliste
** Wiki-Kodex|Wiki - CoC
** Wiki-Aufbau|Wiki - Aufbau


-------------------------------------------
# Example

![Bild 18 01 24 um 20 18](https://github.com/bonsaibauer/fff-foreground-theme/assets/129884416/1e46ab0d-3d6e-4cb5-b855-2923e4a699c0)
![Bild 18 01 24 um 20 21](https://github.com/bonsaibauer/fff-foreground-theme/assets/129884416/479610e5-bc84-4dc1-adf5-27621b4435de)
![Bild 18 01 24 um 20 19](https://github.com/bonsaibauer/fff-foreground-theme/assets/129884416/6f774f17-1f2c-432c-a0b8-14e1bd174be4)
![Bild 18 01 24 um 20 19 (1)](https://github.com/bonsaibauer/fff-foreground-theme/assets/129884416/9e49dac0-1dd3-4550-a1c7-cf80262072db)




