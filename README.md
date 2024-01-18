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
