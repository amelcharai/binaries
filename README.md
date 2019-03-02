# binaries
Create binaries from web pages by using [Nativefier](../jiahaog/nativefier)


## RMC
- Linux

```sh
nativefier --platform linux --arch armv7l --name "RMC" https://rmc.bfmtv.com/mediaplayer/live-audio/
```

## TSO
- Windows

```sh
nativefier --name “TSO” --platform windows --flash-path "C:\WINDOWS\system32\Macromed\Flash\pepflashplayer64_32_0_0_142.dll" "https://www.thesettlersonline.fr/fr/jouer"
```

- OSX

```sh
nativefier --name "TSO" --flash-path "/Users/${username}/Library/Application Support/Google/Chrome/PepperFlash/32.0.0.142/PepperFlashPlayer.plugin" "https://www.thesettlersonline.fr/fr/jouer"
```

Get Flash path by opening Chrome and typing

```
chrome://flash
```
