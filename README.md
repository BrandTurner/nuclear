# ![nuclear](https://raw.githubusercontent.com/nukeop/nuclear/master/resources/media/nuclear/logo_small.png) 

[![twitter](https://raw.githubusercontent.com/nukeop/nuclear/master/resources/media/nuclear/github/twitter.png)](https://twitter.com/nuclear_player) [![mobile](https://raw.githubusercontent.com/nukeop/nuclear/master/resources/media/nuclear/github/mobile.png)](https://github.com/nukeop/nuclear-mobile) [![website](https://raw.githubusercontent.com/nukeop/nuclear/master/resources/media/nuclear/github/website.png)](http://nuclear.gumblert.tech/) 

An Electron-based, multiplatform music player app that streams from multiple sources

#### Support on Beerpay

[![Beerpay](https://beerpay.io/nukeop/nuclear/badge.svg?style=beer-square)](https://beerpay.io/nukeop/nuclear)  [![Beerpay](https://beerpay.io/nukeop/nuclear/make-wish.svg?style=flat-square)](https://beerpay.io/nukeop/nuclear?focus=wish)

## What is this?
nuclear is a free music streaming program that pulls content from free sources all over the internet.

If you know [mps-youtube](https://github.com/mps-youtube/mps-youtube), this is a similar music player but with a GUI.
It's also focusing more on audio. Imagine Spotify which you don't have to pay for and with a bigger library.

***IMPORTANT***: This is a pre-alpha project. Things _are_ broken, and will remain broken for at least some time, until I implement the core features and have more time for bug fixing. You can use the existing releases at the risk of being disappointed, or clone the repo and run the dev version (just clone the repo, then run `npm install` and `npm run dev` in the directory you cloned it to). If you want to be notified when I release a not-so-broken version, check the official website and sign up to the mailing list (it will only ever be used to notify about major releases).

## Features

- Searching for and playing music from youtube (including integration with playlists), bandcamp (including albums), and soundcloud
- Searching for related songs in youtube
- Downloading from youtube
- Searching for albums (powered by last.fm and musicbrainz), album view, automatic song lookup based on artist and track name (in progress, can be dodgy sometimes)
- Song queue, which can be exported as a playlist
- Loading saved playlists (stored in json files)
- Scrobbling to last.fm (along with updating the 'now playing' status)

## Planned features

- Searching for artists, albums, and individual track without the hassle of choosing the source manually (like spotify or deezer)
- Support for local files
- Better playlists
- Better last.fm integration
- Browsing by genre
- Browsing by popularity
- Country-specific top lists
- Newest releases
- Listening suggestions (similar artists, albums, tracks)
- Download regardless of the source
- Info boxes for artists, albums, and tracks
- Realtime lyrics
- Some sort of locally stored library/favourites (no need to store this on anyone's servers like big players do)


## Screenshots
This will be updated as the program evolves.

![album search](http://i.imgur.com/HtaLDSa.jpg)

![album display](http://i.imgur.com/t5V0kXG.jpg)

![dashboard](http://i.imgur.com/rVBAGLG.png)

![artist view](http://i.imgur.com/EOd1auB.png)

![playlist view](http://i.imgur.com/KYFwu7P.jpg)

![legacy search](http://i.imgur.com/WKBVq1u.jpg)

![coverflow](http://i.imgur.com/eAPTDSc.gif)
