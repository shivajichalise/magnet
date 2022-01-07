# magnet

a simple bash script which fetches selected torrent's magnet link and downloads using qbittorrent.

> check Bugswriter's [notflix](https://github.com/Bugswriter/notflix) if you want to stream directly rather than downloading. (I copied half of the code from notflix :P)

> NOTE: it requires qbittorrent & dialog to run and uses GNU Core Utilities commands `grep`, `awk`, `sed`, `paste` etc.

```
pacman -S dialog qbittorrent
apt install dialog qbittorrent
```

## Installing

For the current user:

```
curl https://raw.githubusercontent.com/shivajichalise/magnet/main/magnet > ~/usr/local/bin/magnet && chmod +755 ~/usr/local/bin/magnet
```

Or simply copy the `magnet` file to a location in your `$PATH` and make it executable.

## Usage

- run `magnet <search-query>` or just `magnet`
- if asked for input give appropriate input
- choose from given options
- torrent client will open; select required files and hit start

## How it works

this script scrapes [1337x.to](https://1337x.to) and gets the magnet link after opens qbittorrent to download

## Self-Promotion

Star the repository on [Github](https://github.com/shivajichalise/magnet)
Follow [shivajichalise](http://shivajichalise.com.np) on [Github](https://github.com/shivajichalise)
