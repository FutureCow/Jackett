# Jackett

[![GitHub issues](https://img.shields.io/github/issues/Jackett/Jackett.svg?maxAge=60&style=flat-square)](https://github.com/Jackett/Jackett/issues)
[![GitHub pull requests](https://img.shields.io/github/issues-pr/Jackett/Jackett.svg?maxAge=60&style=flat-square)](https://github.com/Jackett/Jackett/pulls)
[![Build status](https://ci.appveyor.com/api/projects/status/gaybh5mvyx418nsp/branch/master?svg=true)](https://ci.appveyor.com/project/Jackett/jackett)
[![Github Releases](https://img.shields.io/github/downloads/Jackett/Jackett/total.svg?maxAge=60&style=flat-square)](https://github.com/Jackett/Jackett/releases/latest)
[![Docker Pulls](https://img.shields.io/docker/pulls/linuxserver/jackett.svg?maxAge=60&style=flat-square)](https://hub.docker.com/r/linuxserver/jackett/)
[![Discord](https://img.shields.io/badge/discord-chat-7289DA.svg?maxAge=60&style=flat-square)](https://discord.gg/J865QuA)

This project is a new fork and is recruiting development help.  If you are able to help out please contact us.

Jackett works as a proxy server: it translates queries from apps ([Sonarr](https://github.com/Sonarr/Sonarr), [Radarr](https://github.com/Radarr/Radarr), [SickRage](https://sickrage.github.io/), [CouchPotato](https://couchpota.to/), [Mylar](https://github.com/evilhero/mylar), [DuckieTV](https://github.com/SchizoDuckie/DuckieTV), [qBittorrent](https://www.qbittorrent.org/), etc) into tracker-site-specific http queries, parses the html response, then sends results back to the requesting software. This allows for getting recent uploads (like RSS) and performing searches. Jackett is a single repository of maintained indexer scraping & translation logic - removing the burden from other apps.

Developer note: The software implements the [Torznab](https://github.com/Sonarr/Sonarr/wiki/Implementing-a-Torznab-indexer) (with [nZEDb](https://github.com/nZEDb/nZEDb/blob/dev/docs/newznab_api_specification.txt) category numbering) and [TorrentPotato](https://github.com/RuudBurger/CouchPotatoServer/wiki/Couchpotato-torrent-provider) APIs.



#### Supported Systems
* Windows using .NET 4.6.1 or above [Download here](https://www.microsoft.com/net/framework/versions/net461).
* Linux and macOS using Mono 5.8 or above. [Download here](http://www.mono-project.com/download/).

### Supported Public Trackers
 * 1337x
 * Anidex
 * Anime Tosho
 * AniRena
 * AudioBookBay
 * BTstor.net
 * btbit
 * BTKitty
 * cpasbien
 * cpasbienClone
 * DIGBT
 * ETTV
 * EliteTorrent.biz
 * ExtraTorrent.ag
 * EZTV
 * Frozen Layer
 * GkTorrent
 * Horrible Subs
 * IdopeClone
 * Il Corsaro Nero <!-- maintained by bonny1992 -->
 * Il Corsaro Blu
 * Isohunt2
 * KATcrs
 * KickAssTorrent
 * KickAssTorrent (thekat.se clone)
 * LimeTorrents
 * MagnetDL
 * MejorTorrent <!-- maintained by ivandelabeldad -->
 * Monova
 * Newpct (aka: tvsinpagar, descargas2020, torrentlocura, torrentrapid, tumejortorrent, pctnew, etc)
 * Nyaa.si
 * Nyaa-Pantsu
 * Nyoo
 * ProStyleX
 * RARBG
 * RuTor
 * shokweb
 * ShowRSS
 * SkyTorrentsClone
 * sukebei.Nyaa.si
 * sukebei-Pantsu
 * The Pirate Bay
 * TNTVillage <!-- maintained by bonny1992 -->
 * Tokyo Toshokan
 * Torlock
 * TorrentCouch
 * Torrent Downloads
 * TorrentFunk
 * TorrentGalaxy.org
 * TorrentKitty
 * Torrent9
 * Torernt9 clone (torrents9.ch)
 * Torrentz2
 * Torrof
 * World Wide Torrents
 * YTS.ag
 * Zooqle

### Supported Semi-Private Trackers
 * 7tor
 * Alein
 * ArenaBG
 * CzTorrent
 * Deildu
 * Film-Paleis
 * Gay-Torrents.net
 * Gay-Torrents.org
 * GDF76
 * Kinozal
 * LostFilm.tv
 * Mega-Bliz
 * Metal Tracker
 * MVGroup Forum
 * MVGroup Main
 * Newstudio
 * NetHD
 * NoName Club
 * RockBox
 * RuTracker
 * SkTorrent
 * Union Fansub
 * Vanila
 * Xtreme Zone
 * YggTorrent
 * Ztracker

### Supported Private Trackers
 * 2 Fast 4 You
 * 3D Torrents
 * 3evils
 * 420files
 * 720pier
 * Abnormal
 * Acid-Lounge
 * AlphaRatio (AR)
 * AnimeBytes
 * AnimeTorrents (AnT)
 * Anthelion
 * AOX
 * ArabaFenice
 * Arche Torrent
 * AsianCinema
 * AsianDVDClub
 * AST4u
 * Audiobook Torrents
 * Awesome-HD (AHD)
 * Avistaz (AsiaTorrents)
 * B2S-Share
 * Back-ups
 * BakaBT
 * bB
 * BeyondHD (BHD)
 * BIGTorrent
 * BigTower
 * Bit-City Reloaded
 * BIT-HDTV
 * Bithorlo
 * BitHUmen
 * BitMe
 * BitMeTV
 * BitSoup  [![(invite needed)][inviteneeded]](#)
 * BitsPiracy
 * Bitspyder
 * BitTorrentFiles  [![(invite needed)][inviteneeded]](#)
 * BJ-Share
 * BlueBird
 * Blutopia (BLU)
 * Brasil Tracker
 * BroadcastTheNet (BTN)
 * BrokenStones
 * BTGigs
 * BTNext (BTNT)
 * BTXpress (BTX)
 * Carpathians
 * CasStudioTV
 * CCFBits
 * CGPeers
 * CHDBits
 * Cinematik
 * Cinemageddon
 * CinemaZ (EuTorrents)
 * Classix
 * DanishBits
 * DataScene
 * DesiTorrents
 * Diablo Torrent
 * DigitalHive
 * Downloadville
 * Dragonworld Reloaded
 * Dream Team
 * DXDHD
 * EliteHD  [![(invite needed)][inviteneeded]](#)
 * Elit Tracker
 * Elite-Tracker
 * Empornium (EMP)
 * eStone
 * Ethor.net (Thor's Land)
 * FANO.IN
 * FileList (FL)
 * Femdomcult
 * Freedom-HD
 * FullMixMusic
 * FunFile
 * FunkyTorrents (FT)
 * Fuzer
 * GAYtorrent.ru
 * GazelleGames (GGn)
 * Gfxnews
 * GFXPeers
 * GigaTorrents
 * GimmePeers <!-- maintained by jamesb2147 -->
 * Girotottent
 * GODS
 * Greek Team
 * HacheDe
 * Hardbay
 * HD4Free (HD4)
 * HD-Forever (HDF)
 * HD-Only (HDO)
 * HD-Space (HDS)
 * HD-Spain
 * HD-Torrents (HDT)
 * HD-Bits.com
 * HDBits
 * HDChina (HDWing)
 * HDCity
 * HDHome (HDBigger)
 * HDME
 * HDSky
 * HDTorrents.it
 * Hebits
 * Hon3y HD
 * HQSource
 * HuSh 
 * Hyperay
 * ICE Torrent
 * I Love Classics
 * Immortalseed
 * inPeril
 * Insane Tracker
 * IPTorrents (IPT)
 * JPopsuki
 * Kapaki
 * Karagarga
 * LinkoManija
 * LosslessClub
 * M-Team (TP)
 * Magico (Trellas)
 * Majomparádé
 * Manicomio Share
 * Mononoké-BT
 * MoreThanTV (MTV)
 * MyAnonamouse
 * myAmity
 * MySpleen
 * NCore
 * Nebulance (NBL)
 * New Real World
 * NordicBits (NB)
 * Norbits
 * notwhat.cd
 * Orpheus
 * Ourbits
 * Passione Torrent <!-- maintained by bonny1992 -->
 * PassThePopcorn (PTP)
 * PirateTheNet
 * PiXELHD
 * PolishSource
 * PolishTracker
 * Pretome
 * PrivateHD (PHD)
 * Psytorrents
 * PT99
 * PTFiles
 * PuntoTorrent
 * PWTorrents (PWT)
 * Racing4Everyone (R4E)
 * Redacted (PassTheHeadphones)
 * Red Star Torrent
 * Redtopia (RED)
 * RetroFlix
 * RevolutionTT
 * RGU
 * RoDVD
 * Romanian Metal Torrent
 * SceneFZ
 * SceneHD
 * SceneReactor
 * SceneRush
 * SceneTime
 * SDBits
 * Secret Cinema
 * Shareisland
 * ShareSpaceDB
 * Shazbat
 * Shellife
 * Speed-Share
 * SpeedCD
 * SpeedTorrent Reloaded
 * SportsCult
 * SportHD
 * Superbits
 * TakeaByte
 * Tasmanit
 * TBPlus
 * TenYardTracker
 * The Empire
 * The Geeks
 * The Horror Charnel (THC)
 * The Occult
 * The New Retro
 * The Place
 * The Shinning (TsH)
 * The Show
 * The Vault
 * The-Torrents
 * Torrent Network
 * Torrent Sector Crew
 * Torrent.LT
 * TorrentBD
 * TorrentBytes
 * TorrentCCF  [![(invite needed)][inviteneeded]](#)
 * TorrentDay
 * Torrentech
 * TorrentHeaven
 * TorrentHR
 * Torrenting
 * Torrentland
 * TorrentLeech (TL)
 * TorrentSeeds (TS)
 * Torrent-Syndikat
 * TOrrent-tuRK (TORK)
 * TorViet
 * ToTheGlory
 * TranceTraffic
 * Trezzor
 * TurkTorrent (TT)
 * TV Chaos UK
 * TV-Vault
 * u-torrents (SceneFZ)
 * UHDBits
 * Ultimate Gamer Club
 * Waffles
 * World-In-HD
 * WorldOfP2P (WOP)
 * x-ite.me (XM)
 * xBytesV2
 * XSpeeds
 * XWTorrents (XWT)
 * Xthor
 * ExoticaZ (Your Exotic Torrents)
 * Zamunda.net
 * Zelka.org

Trackers marked with  [![(invite needed)][inviteneeded]](#) have no active maintainer and are missing features or are broken. If you have an invite for them please send it to kaso1717 -at- gmail.com to get them fixed/improved.

### Aggregate indexers

A special "all" indexer is available at `/api/v2.0/indexers/all/results/torznab/api`.
It will query all configured indexers and return the combined results.

If your client supports multiple feeds it's recommended to add each indexer directly instead of using the all indexer.
Using the all indexer has no advantages (besides reduced management overhead), only disadvantages:
* you loose control over indexer specific settings (categories, search modes, etc.)
* mixing search modes (IMDB, query, etc.) might cause low quality results
* indexer specific categories (>= 100000) can't be used.
* slow indexers will slow down the overall result
* total results are limited to 1000

To get all Jackett indexers including their capabilities you can use `t=indexers` on the all indexer. To get only configured/unconfigured indexers you can also add `configured=true/false` as query parameter.

## Installation on Windows

We recommend you install Jackett as a Windows service using the supplied installer. You may also download the zipped version if you would like to configure everything manually.

To get started with using the installer for Jackett, follow the steps below:

1. Download the latest version of the Windows installer, "Jackett.Installer.Windows.exe" from the [releases](https://github.com/Jackett/Jackett/releases/latest) page.
2. When prompted if you would like this app to make changes to your computer, select "yes".
3. If you would like to install Jackett as a Windows Service, make sure the "Install as Windows Service" checkbox is filled.
4. Once the installation has finished, check the "Launch Jackett" box to get started.
5. Navigate your web browser to: http://127.0.0.1:9117
6. You're now ready to begin adding your trackers and using Jackett.

When installed as a service the tray icon acts as a way to open/start/stop Jackett. If you opted to not install it as a service then Jackett will run its web server from the tray tool.

Jackett can also be run from the command line if you would like to see log messages (Ensure the server isn't already running from the tray/service). This can be done by using "JackettConsole.exe" (for Command Prompt), found in the Jackett data folder: "%ProgramData%\Jackett".

## Installation on Linux
 1. Install [Mono 5.8](http://www.mono-project.com/download/#download-lin) or better (using the latest stable release is recommended)
       * Follow the instructions on the mono website and install the `mono-devel` and the `ca-certificates-mono` packages.
       * On Red Hat/CentOS/openSUSE/Fedora the `mono-locale-extras` package is also required.
 2. Install  libcurl:
       * Debian/Ubunutu: `apt-get install libcurl4-openssl-dev`
       * Redhat/Fedora: `yum install libcurl-devel`
       * For other distros see the  [Curl docs](http://curl.haxx.se/dlwiz/?type=devel).
 3. Download and extract the latest `Jackett.Binaries.Mono.tar.gz` release from the [releases page](https://github.com/Jackett/Jackett/releases) and run Jackett using mono with the command `mono --debug JackettConsole.exe`.

Detailed instructions for [Ubuntu 14.x](http://www.htpcguides.com/install-jackett-on-ubuntu-14-x-for-custom-torrents-in-sonarr/) and [Ubuntu 15.x](http://www.htpcguides.com/install-jackett-ubuntu-15-x-for-custom-torrents-in-sonarr/)

If you want to run it with a user without a /home directory you need to add `Environment=XDG_CONFIG_HOME=/path/to/folder` to your systemd file, this folder will be used to store your config files.  

Mono must be compiled with the Roslyn compiler (default), using MCS will cause "An error has occurred." errors (See https://github.com/Jackett/Jackett/issues/2704).

### Install as service
1. Install Jackett with the steps from above.
2. Open the Terminal and run `sudo ./install_service_systemd.sh` You need root permissions to install the service.
2. If the installation was a success, you can close the Terminal window.

The service will start on each logon. You can always stop it by running `systemctl stop jackett.service` from Terminal. You can start it again it using `systemctl start jackett.service`.
Logs are stored as usual under `~/.config/Jackett/log.txt` and also in `journalctl -u jackett.service`.

### Installation on Linux via Ansible

On a RHEL/Centos 7 system: [linuxhq.jackett](https://galaxy.ansible.com/linuxhq/jackett)

On an Ubuntu 16 system: [chrisjohnson00.jackett](https://galaxy.ansible.com/chrisjohnson00/jackett)

## Installation on macOS

### Prerequisites
Install [Mono 5.8](http://www.mono-project.com/download/#download-mac) or better (using the latest pkg installer is recommended).
 * Setup ssl support by running `curl -sS https://curl.haxx.se/ca/cacert.pem | cert-sync --user /dev/stdin`

### Install as service
1. Download and extract the latest `Jackett.Binaries.Mono.tar.gz` release from the [releases page](https://github.com/Jackett/Jackett/releases).
2. Open the extracted folder and double-click on `install_service_macos`.
3. If the installation was a success, you can close the Terminal window.

The service will start on each logon. You can always stop it by running `launchctl unload ~/Library/LaunchAgents/org.user.Jackett.plist` from Terminal. You can start it again it using `launchctl load ~/Library/LaunchAgents/org.user.Jackett.plist`.
Logs are stored as usual under `~/.config/Jackett/log.txt`.

### Run without installing as a service
Download and extract the latest `Jackett.Binaries.Mono.tar.gz` release from the [releases page](https://github.com/Jackett/Jackett/releases) and run Jackett using mono with the command `mono --debug JackettConsole.exe`.

## Installation using Docker
Detailed instructions are available at [LinuxServer.io Jackett Docker](https://hub.docker.com/r/linuxserver/jackett/). The Jackett Docker is highly recommended, especially if you are having Mono stability issues or having issues running Mono on your system eg. QNAP, Synology. Thanks to [LinuxServer.io](https://linuxserver.io)

## Installation on Synology
Jackett is available as beta package from [SynoCommunity](https://synocommunity.com/)

## Running Jackett behind a reverse proxy
When running jackett behind a reverse proxy make sure that the original hostname of the request is passed to Jackett. If HTTPS is used also set the X-Forwarded-Proto header to "https". Don't forget to adjust the "Base Path Override" Jackett option accordingly.

Example config for apache:
```
<Location /jackett>
    ProxyPreserveHost On
    RequestHeader set X-Forwarded-Proto expr=%{REQUEST_SCHEME}
    ProxyPass http://127.0.0.1:9117
    ProxyPassReverse http://127.0.0.1:9117
</Location>
```

Example config for nginx:
```
location /jackett {
	proxy_pass http://127.0.0.1:9117;
	proxy_set_header X-Real-IP $remote_addr;
	proxy_set_header X-Forwarded-For $proxy_add_x_forwarded_for;
	proxy_set_header X-Forwarded-Proto $scheme;
	proxy_set_header X-Forwarded-Host $http_host;
	proxy_redirect off;
}
```

## Troubleshooting

* __Command line switches__

  You can pass various options when running via the command line, see --help for details.

* __Error "An error occurred while sending the request: Error: TrustFailure (A call to SSPI failed, see inner exception.)"__

  This is often caused by missing CA certificates.
  Try reimporting the certificates in this case:
   - On Linux (as user root): `wget -O - https://curl.haxx.se/ca/cacert.pem | cert-sync /dev/stdin`
   - On macOS: `curl -sS https://curl.haxx.se/ca/cacert.pem | cert-sync --user /dev/stdin`

*  __Enable enhanced logging__

  You can get *enhanced* logging with the command line switches `-t -l` or by enabling `Enhanced logging` via the web interface (followed by clicking on the `Apply Server Settings` button).
  Please post logs if you are unable to resolve your issue with these switches ensuring to remove your username/password/cookies.
  The logfiles (log.txt/updater.txt) are stored in `%ProgramData%\Jackett` on Windows and `~/.config/Jackett/` on Linux/macOS.

## Configuring OMDb
This feature is used as a fallback to get the movie/series title if only the IMDB ID is provided in the request.
To use it, please just request a free API key on [OMDb](http://www.omdbapi.com/apikey.aspx) (1,000 daily requests limit) and paste the key in Jackett

## Creating an issue
Please supply as much information about the problem you are experiencing as possible. Your issue has a much greater chance of being resolved if logs are supplied so that we can see what is going on. Creating an issue with '### isn't working' doesn't help anyone to fix the problem.

## Contributing

Jackett's framework typically allows our team and volunteering developers to implement new trackers in a couple of hours

Depending on logic complexity, there are two common ways new trackers are implemented:

1. simple [definitions](http://github.com/Jackett/Jackett/tree/master/src/Jackett.Common/Definitions) (.yml / YAML), and;
2. advanced (native) [indexers](http://github.com/Jackett/Jackett/tree/master/src/Jackett.Common/Indexers) (.cs / C#)

Read more about the [simple definition format](https://github.com/Jackett/Jackett/wiki/Definition-format).

If you are a developer then it's recommended to download the free community version of [Visual Studio](http://visualstudio.com)

If you are not a developer and would like a (new) tracker supported then feel free to leave an [issue](https://github.com/Jackett/Jackett/issues) request.

All contributions are welcome just send a pull request.

## Building from source

### Windows
* Install the .NET Core [SDK](https://www.microsoft.com/net/download/windows)
* Open the Jackett solution in Visual Studio 2017 (version 15.9 or above)
* Right click on the Jackett solution and click 'Rebuild Solution' to restore nuget packages
* Select Jackett.Server as startup project
* In the drop down menu of the run button select "Jackett.Server" instead of "IIS Express"
* Build/Start the project

### OSX


```bash
# manually install osx dotnet via: 
https://dotnet.microsoft.com/download?initial-os=macos
# then: 
git clone https://github.com/Jackett/Jackett.git
cd Jackett/src

# dotnet core version
dotnet publish Jackett.Server -f netcoreapp2.2 --self-contained -r osx-x64 -c Debug # takes care of everything
./Jackett.Server/bin/Debug/netcoreapp2.2/osx-x64/JackettConsole # run jackett
```

### Linux


```bash
sudo apt install mono-complete nuget msbuild dotnet-sdk-2.2 # install build tools (debian/ubuntu)
git clone https://github.com/Jackett/Jackett.git
cd Jackett/src

# dotnet core version
dotnet publish Jackett.Server -f netcoreapp2.2 --self-contained -r linux-x64 -c Debug # takes care of everything
./Jackett.Server/bin/Debug/netcoreapp2.2/linux-x64/JackettConsole # run jackett
```
<!--
# mono version (currently broken)
nuget restore Jackett.sln # prepare dependencies
msbuild Jackett.Server/Jackett.Server.csproj /t:Build /p:Configuration=Debug # compile
mono Jackett.Server/bin/Debug/JackettServer.exe # run jackett
-->

## Screenshots

![screenshot](https://i.imgur.com/0d1nl7g.png "screenshot")

[inviteneeded]: https://raw.githubusercontent.com/Jackett/Jackett/master/.github/label-inviteneeded.png
