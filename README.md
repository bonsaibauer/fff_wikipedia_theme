# FFF-Foreground Skin für Mediawiki's

[MediaWiki](https://www.mediawiki.org) skin that focuses on putting your content in the *foreground*. It supports
responsive layouts and has classes predefined for [Semantic MediaWiki](https://www.semantic-mediawiki.org/).
Built on the [Zurb Foundation](http://foundation.zurb.com) CSS framework.

## Download

First, copy the Foreground source files, you can use git to clone the repository, which makes it very easy to update the code, using:

    git clone https://github.com/bonsaibauer/fff-foreground-theme.git Foreground

After that, you can issue `git pull` to update the code at anytime.

## Setup

Once the skin is in place add one the following lines to your "LocalSettings.php" file.

	wfLoadSkin( 'Foreground' );
	$wgDefaultSkin = 'foreground';
# Foreground is specific, so lets disable other skins
    	$wgSkipSkins = array( 'cologneblue', 'modern', 'monobook', 'vector' );

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


And Replace: 

	$wgSitename = "FFF Infopoint";
	$wgMetaNamespace = "FFF Infopoint";
	$wgLogo = $wgScriptPath . '/skins/Foreground/logo/fff_earth_120px.png';

-------------------------------------------

![Bild 18 01 24 um 20 18](https://github.com/bonsaibauer/fff-foreground-theme/assets/129884416/1e46ab0d-3d6e-4cb5-b855-2923e4a699c0)
![Bild 18 01 24 um 20 21](https://github.com/bonsaibauer/fff-foreground-theme/assets/129884416/479610e5-bc84-4dc1-adf5-27621b4435de)
![Bild 18 01 24 um 20 19](https://github.com/bonsaibauer/fff-foreground-theme/assets/129884416/6f774f17-1f2c-432c-a0b8-14e1bd174be4)
![Bild 18 01 24 um 20 19 (1)](https://github.com/bonsaibauer/fff-foreground-theme/assets/129884416/9e49dac0-1dd3-4550-a1c7-cf80262072db)




