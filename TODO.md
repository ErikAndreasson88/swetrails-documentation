# General
* Recheck licens for text
* OSM licens, all trails?
* System to follow "right to erasure" (Deletion of any information that can be used to identify a person [Data may be saved for legal reasons]) [MANUALY DONE CURRENTLY]
* Uploads of images ip users? (CC0 default?, COMMUNITY UNLICENSED?)

# Frontend

## High
* Menus not behaving when in mobile view, (multiple menus visible)
* ON upload image with cords to newPoiPage where no cords are set. The auto set position is not working inthis scenario.
* In route edit mode, no tool should be preselected.
* Orientation on currently uploading images in image rotatater thing.

## Backlog
* New POI - Culture
* Change default contrast color route sections?
* WYSIWYG handle pasted text!
* Markdown + wysiwyg editor support grid
* Markdown issue on inherited depth (If it is gonna be supported)
* Upload private gpx tracks (only visible for the user)
* Upload private images(licens and still public but unbound)
* Filter to allow show every POI on close view (Default)
* fix route bounds weast/east/... so that it can include over the world border of 180
* Documentation on what section number is in editLinePage

# Combined
* Fileuploader naming can fail if provided filename is not equal to provided file. (Dump filename from form content)
* Page lock (Lock pages from change (Privalage management?)

# Backend

## High
* Send email when new images has been added for verification

## Backlog
* Privalage management on url_id


## Springboot - Web crawler / repeat batch work every x hour/day/month
* [24Hour]	verify that routes/pois has text for all available url languages (delete url language if not is the case when age>24H)
* [7Day]	Clear all files that has no links
* [7Day]	verify all links in database. Even in markdown
* [1Month]	(Auto generation checker needs to be built) check page for changes EX: DANO https://dalslandnordmarken.se/sv/lagerplatser/
