# Browsertime-API

## How to add movies
**Only movies are supported now.**  
Just use the following format to add a movie.  

### Naming conventions
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




When willing to seed a movie just do a PR to the moviedb.md
#### Movie Format
    Torrent Link: https://kat.cr/the-lobster-2015-720p-brrip-x264-aac-etrg-t12053399.html
    Movie Name: the_lobster.tt3464902.2015.720p.mp4
    Webtorrent Hash: 6f903a813189357585123d2afd169b3be5eecc50
    
    Torrent Link: https://kat.cr/steve-jobs-2015-720p-brrip-x264-aac-etrg-t12014709.html
    Movie Name: steve_jobs.tt2080374.2015.720p.mp4
    Webtorrent Hash: 6f903a813189357585250d2afd169b3be5eecc50 


## FAQ
Why do we need naming conventions? 
*When the name and the video file stays the same the torrent hash will also stay the same. Even when the movie is totally unseeded. This way we can simply hardcode all the hashes because it will stay the same.*
