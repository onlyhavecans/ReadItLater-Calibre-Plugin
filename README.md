#Read It Later V3 recipe for Calibre
I added a bunch of functionality to the baked in Read It Later plugin for Calibre.
It's currently called "Version Three" since it seems I'm the third person to work on it.

# Changes from official
* Displays articles from oldest to newest
* Uses max_articles_per_feed to determine how many articles to download per eBook (Default 50)
* Has a minimum_articles setting at the top. Plugin fails to run if you don't have enough articles (Default 10, set to 0 to disable)
* Marks downloaded articles read

If anyone can think of other cool features I will consider them.
(I was considering redoing the way it formats the book but wanted to release as is for now.)

# Notes
## Installation
This should work with all recent version of Calibre.
* Under the "Fetch News" dropdown select "Add a Custom Source"
* Click "Load Recipe From File" and choose the ReadItLater_v3.recipe file
* Edit max_articles_per_feed & minimum_articles to set your max and minimum articles downloaded per eBook
* Save and Close
* Under "Schedual News Download" Select the new Read It Later v3 and fill out your credentials

## Misc
The original version has been modified and reposted under the GPLv3 Licence.
I have posted the Official/Original code here for reference only, I make no claims on having contrtibuted to anything but Version Three