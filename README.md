# Pocket recipe for Calibre
This is a fork of the original 2011 Calibre ReadItLater plugin.

I am currently working on rebranding it to [Pocket](http://getpocket.com/) and moving it to their new webpage/interface. Please bear with me as changes they have made to their backend may affect the current functionality of the plugin.

If you have suggestions of feature suggestions I will consider them. Please submit them as issues.

# Installation
* Under the "Fetch News" drop down select "Add a Custom Source"
* Click "Load Recipe From File" and choose the ReadItLater_v3.recipe file
* Edit max_articles_per_feed & minimum_articles to set your max and minimum articles downloaded per eBook
* Save and Close
* Under "Schedule News Download" Select the new Read It Later v3 custom recipie and fill out your credentials

# Changelog
## Changes from ReadItLater v3 to Pocket v1.0
* Name change

## Changes from 2011 version to ReadItLater v3
* Displays articles from oldest to newest
* Uses max_articles_per_feed to determine how many articles to download per eBook (Default 50)
* Has a minimum_articles setting at the top. Plugin fails to run if you don't have enough articles (Default 10, set to 0 to disable)
* Marks downloaded articles read with option at the top to disable
* Shows timestamp on the cover under the date

# Notes
I have removed the Official/Original code I was posting here, since this fork has been merged into the official codebase, please reference the [official code repository](http://bazaar.launchpad.net/~kovid/calibre/trunk/files/head:/recipes/) for the source.