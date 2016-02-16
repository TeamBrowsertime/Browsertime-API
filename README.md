# Browsertime-API

## How to add movies
**Only movies are supported now.**  
Just use the following format to add a movie.  

If you want to add movies, just do a PR to moviedb.md with the following information.
```
    torrentlink: magnet:?xt=urn:btih:28C5E48CAFE6CA1FA511D6B30D042F0ED688405A
    moviename: the_lobster.tt3464902.2015.720p.mp4
    webhash: 6f903a813189357585123d2afd169b3be5eecc50
```
**torrentlink**: is the magnet link of the downloaded movie.
**moviename**: <a href="#naming-conventions">Read this</a>.
**webhash**: <a href="#seeding">Read this</a>.


#### Naming conventions
```
moviename.imdbid.year.quality.mp4
```
**moviename:** is alway without capitals and spaces are dashes.  
**imdb ID:** must be a 9 char string that links to the movie on imdb.  
**year:** The release year of the movie.  
**quality:** 480p/720p/1080p (prefered 720p or 1080p).  
**extension:** must be mp4. 

An example of this format:
```
steve_jobs.tt2080374.2015.720p.mp4
```
  
  
#### Seeding
Just go to http://instant.io/ and drag and drop or select the file with the naming convention. Eventually you'll see a hash. That's the **webhash** you need to add.  

**Remember:** keep the tab with instant.io or browsertime running the movie as long open as possible, when you close it the movie will stop being seeded and this project won't last for long.

## FAQ
Why do we need naming conventions?  
*When the name and the video file stays the same the torrent hash will also stay the same. Even when the movie is totally unseeded. This way we can simply hardcode all the hashes because it will stay the same.*
