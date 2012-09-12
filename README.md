CouchPotato Server (sphere's german fork)
=====

CouchPotato (CP) is an automatic NZB and torrent downloader. You can keep a "movies I want"-list and it will search for NZBs/torrents of these movies every X hours.
Once a movie is found, it will send it to SABnzbd or download the torrent to a specified directory.

This is a fork of [CouchPotato Server](https://github.com/RuudBurger/CouchPotatoServer) for german users.

Current changes:
* Default settings: Don't ignore "german", require one of "dl, german, deutsch, ger", ignore any of "english, englisch"
* Use German metadata from tmbd
* Lookup in "Foreign Movies" category for all kinds of releases (dvdr, cam, ts, dvdrip, tc, r5, scr, 720p, 10p, bd50) on newznab provider
* Use this repository for automatic git based updates
* Don't score down releases with "german"-word
* Removed score boost for release-groups which are famous for english releases (TODO: german release groups)
* also increase release-score if movie year and release year differ just one year

[Original Readme](https://github.com/RuudBurger/CouchPotatoServer/blob/master/README.md)

- sphere
