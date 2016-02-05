# Pocket+ recipe for Calibre
This is a fork of the original 2011 Calibre ReadItLater plugin. I modified the the plugin to get (1) The latest (more or less as the original version of the plugin) (2) and your content organized by tags! 

Now, you get **The latest** and **the content organized by your tags**:

![fig2](doc/02.jpg)

![fig1](doc/03.jpg)

.. before:

![fig1](doc/01.jpg)

At the moment you have to define your own tags in the code (variable `self.tags`). It should be changed at some point.

# Installation

* Under the "Fetch News" drop down select "Add a Custom Source"
* Click "Load Recipe From File" and choose the Pocket.recipe file
* Edit max_articles_per_feed & minimum_articles to set your max and minimum articles downloaded per eBook
* Save and Close
* Under "Schedule News Download" Select the new Pocket recipe under custom and fill out your credentials

# Changelog
## Pocket v1.4.1
* Modified version of the plugin to get (1) The latest (more or less as the original version of the plugin) (2) and your content organized by tags! 
## Pocket v1.4
* The first photo in an article is now included with the article

## Pocket v1.3.1 (The 'I rushed 1.3 because of api changes' bugfix release)
* Default mark as read again
* fix mark as read errors
* fix tag filtering
* Added h1 titles to articles

## Pocket v1.3
* Updated to the new v3 of the API
* Switched off the old, now broken, text view
* Added ability to switch between _oldest to newest_ & _newest to oldest_
* Added ability to filter by tag (only one because of the API)
* Automatically filters out saved items in the queue that do not have articles (pictures and videos)
* Big thanks to Mila Frerichs for the help with the new text view!

## Pocket v1.2
* Added new feature to fail with a warning instead of an error when not enough articles are found
    * This feature is not yet in 0.8.51 so you will still get the conversion error

## Pocket v1.1
* Check for article pages that are empty or malformed. Fixes issue #3 (Exception when there is no article)

## Changes from ReadItLater v3 to Pocket v1.0
* Name change
* Pointed to new domain (http://getpocket.com/)
* Still uses old RIL interface to pull content

## Changes from 2011 version to ReadItLater v3
* Displays articles from oldest to newest
* Uses max_articles_per_feed to determine how many articles to download per eBook (Default 50)
* Has a minimum_articles setting at the top. Plugin fails to run if you don't have enough articles (Default 10, set to 0 to disable)
* Marks downloaded articles read with option at the top to disable
* Shows timestamp on the cover under the date

# Notes
I have removed the Official/Original code I was posting here, since this fork has been merged into the official codebase, please reference the [official code repository](http://bazaar.launchpad.net/~kovid/calibre/trunk/files/head:/recipes/) for the source.
