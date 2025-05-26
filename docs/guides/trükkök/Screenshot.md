---
title: Screenshot setup 
sidebar_position: 11
---

### Screenshot shortcut

én mindig képernyő részletet akarok kivágni `Shift+Cmd+4` ennek hatására feljön egy célkereszt és így lehet részeket kivágni gyorsan.   
Ha kijelölés közben nyomva tartod a Control-t akkor egyből clipboard-ra kerül a kép

(Lehet teljes screent \+ teljes ablakot \+ by default tud screen recording videót is ez `Shift+Cmd+5` itt külön be lehet állítani h microfon vegyen hangot v sem)   
Bővebben: [https://support.apple.com/en-us/102646](https://support.apple.com/en-us/102646)  
Terminálon be lehet állítani, hogy hova mentse a Screenshotokat, nekem a Desktopon van egy Screenshots mappa és ebbe kerül minden, nem a Desktopra szemetelek, szóval **létre kell hozni a foldert** ahova menteni akarod, majd **Terminal**ban:   
``` console
defaults write com.apple.screencapture location /Users/tothi/Desktop/Screenshots  
killall SystemUIServer
```
