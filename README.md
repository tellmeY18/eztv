<h1 align="center">just working Fork of notflix</h1>

<h1 align="center">EZTV</h1>
<p align="center">f@#k netflix use EZTV a tool which search magnet links and stream it with Webtorrent</p>

##
<p align="center">
<img src="./animated.gif" alt="Video Preview" width="500px">
</p>

##

> Watch this video to understand - [bugswriter's notflix](https://youtu.be/FbE19_omaWY)

### How does this work?

This is a shell script. It scape eztv.re and get the magnet link.
After this it use [Webtorrent] to stream the video from magnet link.
For scraping script use simple gnu utils like sed, awk, paste, cut.

## Requirements

* [Webtorrent](https://github.com/webtorrent/webtorrent) - A tool to stream torrent. `sudo npm install webtorrent -g`
## Installation

### cURL
cURL **EZTV** to your **$PATH** and give execute permissions.

```sh
$ sudo curl -sL "https://github.com/tellmeY18/eztv.git" -o /usr/bin/
$ sudo chmod +x /usr/bin/eztv
```
- To update, just do `curl` again, no need to `chmod` anymore.
- To uninstall, simply remove `EZTV` from your **$PATH**, for example `sudo rm -f /usr/bin/eztv.

## License
This project is licensed under [GPL-3.0](https://raw.githubusercontent.com/Illumina/licenses/master/gpl-3.0.txt).

