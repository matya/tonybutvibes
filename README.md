# About

This is the repo containing the `vibes.json`, used as the source file for a randomly picked positive message for nightbot to send to a twitch channel, based on a schedule.

See more details: https://docs.nightbot.tv/control-panel/timers

# Setup

## Nightbot

```
!addcom !vibe $(eval a=$(urlfetch json https://raw.githubusercontent.com/<ghuser>/<ghrepo>/main/vibes.json); a[Math.floor(Math.random()*a.length)] )
```

Note: Replace `<ghuser>` and `<ghrepo>` with the values of this repo.

# TODO 
* Add error handling 
