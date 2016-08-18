---
title:  "macOS translucent Dockicons"
date:   2016-08-18
---
![Dock with transparent hidden Appicons](assets/blgimg/2016-08-18-dock.png)

A lot of people asked me, how managed to make the icons of hidden (*CMD + H*) apps on my Dock translucent.

All you need is your Macs Terminal and the following line:   

`defaults write com.apple.Dock showhidden -bool YES && killall Dock`
