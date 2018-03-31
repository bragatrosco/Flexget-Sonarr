# Flexget config for Sonarr

## Series
From Trakt list to Sonarr, if the series has completed watched status, only future episode tracking. 
If any unseen episodes, Sonarr will search for any missing episodes on disk.

## Anime
From Trakt anime list to Sonarr, if the series has completed watched status, only future episode tracking.
If any unseen episodes, Sonarr will search for any missing episodes on disk.
Tag with anime and set series anime type when added

## Movies
Check new releases list, if rating and vote requirements are met, add to watchlist

### Changelog

* Seen shows only get added if they have not ended and all episodes have not been seen
* If show has ended and all episodes seen, it is removed from Sonarr
```
Allows re-downloading seen shows now. Just mark episodes as unseen on Trakt and it will be re-added to Sonarr and downloaded
```


