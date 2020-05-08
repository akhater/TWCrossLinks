# TWCrossLinks
TWCrossLinks is the core plugin of [Drift](https://akhater.github.io/drift) that I have repacked as a separate plugin since I realize that not a lot would prefer to add a plugin to their existing installation instead of install the whole package.

# Features:
* Adds a footer in the bottom of every Tiddler showing the keywords of that tiddler (if present)
* Adds a footer in the bottom of every Tiddler showing all different types of inbound links to that tiddler (if present)
_Backlinks_ | _Tags_ | _Keywords_ | _Freelinks_
* Footer won't show unless existing
* _Backlinks_ & _Freelinks_ can be directly transcluded on hover 

# Change log
***2020-05-08***: v0.1.3

* Added counter showing the number of inbound links
* Fixed bug in Freelinks
* Saved some screen real-estate in the footer
* Added the possibility to remove the toggle and show the tabs by default saving even more screen estate 
 
***2020-05-05***: v0.1.1
* Inbound links for "Backlinks" and "Freelinks" can now be transcluded in a pop-up, try it by enabling this feature from the TWCrosslinks config panel
* Bug fixes

***2020-05-03***: v0.0.7
* Added configuration panel, can be found at $:/ak/plugins/TWCrossLinks
    * You can now set the Default state of the "inbound links" {Shown / Hidden}
    * You can now set the Default "inbound links" tab

***2020-05-02***: v0.0.3
* Initial Release

# Installation
Download the [JSON file](https://github.com/akhater/TWCrossLinks/blob/master/%24__ak_plugins_TWCrossLinks.json) and drag/drop it in your TiddlyWiki
 
 # Usage & Demo site
 * Check [Drift](https://akhater.github.io/drift)
 
 # Credits 
 * Danielo515 for his code  of [Context Plugin](http://contextplugin.tiddlyspot.com/)
 
 
 # Discussion 
https://groups.google.com/forum/#!topic/tiddlywiki/9ra0s9AEKl4
 
