# Setup

## Nightbot

```
!addcom !vibe $(eval a=$(urlfetch json https://raw.githubusercontent.com/<ghuser>/<ghrepo>/main/vibes.json); a[Math.floor(Math.random()*a.length)] )
```

Note: Replace `<ghuser>` and `<ghrepo>` with the values of this repo.

# TODO 
* Add error handling 
