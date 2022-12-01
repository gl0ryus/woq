# World of Quinoa 
**_A world of warcraft inspired theme_**

![p][p]

# Features
- ![#8f8f8f](https://placehold.co/15x15/8f8f8f/8f8f8f.png) `< 1`
- ![#ffffff](https://placehold.co/15x15/ffffff/ffffff.png) `< 2`
- ![#1eff00](https://placehold.co/15x15/1eff00/1eff00.png) `< 10`
- ![#0070dd](https://placehold.co/15x15/0070dd/0070dd.png) `< 20`
- ![#a335ee](https://placehold.co/15x15/a335ee/a335ee.png) `< 60`
- ![#ff8000](https://placehold.co/15x15/ff8000/ff8000.png) `< 90`
- ![#e6cc80](https://placehold.co/15x15/e6cc80/e6cc80.png) `< 100`
- ![#00ccff](https://placehold.co/15x15/00ccff/00ccff.png) `> 100`



# Installation

### Clone this repo (Windows)
1. Clone or download this repo as a .ZIP
2. Move it somewhere where qBittorrent can find it.
3. Ensure you use a trailing slash.

### Clone this repo (Linux)
1. `sudo git clone https://github.com/gl0ryus/woq.git /opt/woq && sudo chown -R nobody:nogroup /opt/woq/`


### Activate Alterative WebUI in qBittorrent
1. Under `Tools->Preferences->WebUI` enable `Use alternative WebUI`.
2. Choose a location that points to the `woq` folder, i.e. `/opt/woq/`
3. Restart qBittorrent or refresh your browser for changes to take effect.

You can also change these settings via the config file. The relevant entries are:

- `WebUI\AlternativeUIEnabled=true`
- `WebUI\RootFolder=/opt/woq/`

### Update theme (Linux)
1. `cd /opt/woq`
2. `sudo git pull`

### Tested
Tested in 4.3.9

# Credits
- bp
- imabee
- qbittorrent

[p]: p.png
