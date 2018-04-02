# Flexget config for Sonarr

## Series
From Trakt list to Sonarr, if the series has completed watched status, only future episode tracking. 
If any unseen episodes, Sonarr will search for any missing episodes on disk.

## Anime
From Trakt series list, checking language/genres/type, if the series has completed watched status, only future episode tracking.
If any unseen episodes, Sonarr will search for any missing episodes on disk.
Tag with anime and set series anime type when added

## Movies
Check new releases list, if rating and vote requirements are met, add to watchlist

### Changelog

* Removed archive list, only series and movies now

* Delay on archive and cleanup tasks
* No seperate anime list, all in one list
* Anime added with filter by language/type and genre
* No specific delete list, list compare instead, if not in series list, remove from Sonarr

* Seen shows only get added if they have not ended and all episodes have not been seen
* If show has ended and all episodes seen, it is removed from Sonarr


