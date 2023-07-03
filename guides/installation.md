---
icon: rocket
label: Installation
order: 100
---
# How to install skins after the new steam update

## Pre-requisites

!!! Download the [!badge target="blank" variant="info" text="latest SFP release"](https://github.com/PhantomGamers/SFP/releases)
[!badge target="blank" variant="info" text="Windows"](https://github.com/PhantomGamers/SFP/releases/latest/download/SFP_UI-win10-x64-SelfContained.zip) [!badge target="blank" variant="info" text="Linux"](https://github.com/PhantomGamers/SFP/releases/latest/download/SFP_UI-linux-x64-SelfContained.tar.gz) [!badge target="blank" variant="info" text="Mac"](https://github.com/PhantomGamers/SFP/releases/latest/download/SFP_UI-osx-x64-SelfContained.tar.gz) [!badge text="Recommended"]
!!!
!!!dark In case you want to use the Millennium patcher, download it for [!badge target="blank" variant="dark" text="Windows"](https://github.com/PhantomGamers/SFP/releases/latest/download/millennium.exe)
Note that this patcher has its own way of patching and requires you to manually add css, [!badge target="blank" variant="dark" text="read more at its source"](https://github.com/ShadowMonster99/millennium-steam-patcher/#readme)
!!!

### Installing a theme

1. Download a theme [!badge target="blank" variant="info" text="Metro"](https://download-directory.github.io/?url=https://github.com/AikoMidori/SteamSkins/tree/main/Metro/) [!badge target="blank" variant="info" text="Fluent"](https://download-directory.github.io/?url=https://github.com/AikoMidori/SteamSkins/tree/main/Fluent/) [!badge target="blank" variant="ghost" text="Source code"](https://github.com/AikoMidori/SteamSkins)
2. Extract the zip and open [!badge variant="dark" text="AikoMidori SteamSkins main"] [!badge variant="info" text="Metro"]/[!badge variant="info" text="Fluent"]
3. Copy/Cut the 2 folders [!badge variant="dark" text="Metro, Fluent"]
4. Paste your skin(s)
   - [x] Find the steam folder using SFP [!badge variant="info" text="Recommended"]
     - Open SFP, press the [!badge variant="dark" text="Open Files"] button, and then press [!badge variant="dark" text="skins"]
   - [ ] or find the steam folder manually
     - Locate wherever steam is installed yourself (default is [!badge variant="dark" text="C:\Program Files (x86)\Steam"])
     - If the [!badge variant="dark" text="skins"] folder doesn't exist
5. Open SFP and open the Settings :icon-gear: at the bottom left
6. Scroll down and at Steam Skin choose either Fluent or Metro
7. Done.

!!! If you're using Metro and want to use its JS
Move the contents of the [!badge variant="dark" text="Steam\steamui\skins\Metro\Metro-JS"] folder to the main skin folder (aka. [!badge variant="dark" text="Steam\steamui\skins\Metro"]) and overwrite existing files
!!!

## Other skins

==- Metro and Fluent by Shiina
!!!success Read the guide above for installing this.
You can see the skin [!badge target="blank" variant="dark" text="source code here"](https://github.com/AikoMidori/steam-dark-mode)
!!!
==- Metro and steam chat by RoseTheFlower
[!file Download](https://github.com/RoseTheFlower/MetroSteam/archive/refs/heads/master.zip)
!!!success Copy [!badge variant="dark" text="friends.custom.css"] to [!badge variant="dark" text="Steam\steamui"] or make a new folder with it in [!badge variant="dark" text="Steam\steamui\skins"]
!!!
!!!success Copy [!badge variant="dark" text="libraryroot.custom.css"] to [!badge variant="dark" text="Steam\steamui"] or make a new folder with it in [!badge variant="dark" text="Steam\steamui\skins"]
!!!
!!! You can see the skin [!badge target="blank" variant="dark" text="source code here"](https://github.com/RoseTheFlower/newsteamchat)
!!!
==- Space Theme by SpaceEnergy
!!!warning This skin was made to be used with Millennium BUT it can also be used with SFP, download it at the [!badge variant="dark" text="top of this page"](/guides/installation.md#pre-requisites)
To install this skin with Millennium, you can follow the [!badge target="blank" variant="info" text="guide provided by the author"](https://github.com/SpaceEnergy/SpaceTheme-Steam#installation)
!!!
!!! You can see the skin [!badge target="blank" variant="dark" text="source code here"](https://github.com/SpaceEnergy/SpaceTheme-Steam)
!!!
==-

## Addons for your already existing skins

Before continuing this, first install a regular skin like metro or fluent.\
Follow the guide above if you don't know how

==- Steam Friends Skin
!!! :gear: This skin features a [!badge target="blank" variant="info" text="site with customizability"](https://chat.lasr.skin/) [!badge target="blank" variant="ghost" text="Source code"](https://github.com/LaserFlash/steam-chat-skin/) :gear:
!!!
To install the base skin:
[!file RIGHT CLICK this and select Save Link As](https://raw.githubusercontent.com/LaserFlash/steam-chat-skin/main/friends.custom.css)
!!!success Save it as [!badge variant="dark" text="friends.custom.css"] to [!badge variant="dark" text="Steam\steamui"] or to the folder of your active skin in [!badge variant="dark" text="Steam\steamui\skins"]
!!!
==- Dark Store pages
[!file RIGHT CLICK this and select Save Link As](https://raw.githubusercontent.com/AikoMidori/steam-dark-mode/master/webkit.css)
!!!success Save it as [!badge variant="dark" text="webkit.css"] to [!badge variant="dark" text="Steam\steamui"] or to the folder of your active skin in [!badge variant="dark" text="Steam\steamui\skins"]
!!!
!!!warning This has yet to be updated for the new steam, check out the beta below, you can see the [!badge target="blank" variant="dark" text="source code here"](https://github.com/AikoMidori/steam-dark-mode)
!!!
==- Beta Dark Store pages
[!file RIGHT CLICK this and select Save Link As](https://raw.githubusercontent.com/BallOpener/steam-dark-mode/beta2/css/webkit.css)
!!!success Save it as [!badge variant="dark" text="webkit.css"] to [!badge variant="dark" text="Steam\steamui"] or to the folder of your active skin in [!badge variant="dark" text="Steam\steamui\skins"]
!!!
!!! You can see the [!badge target="blank" variant="dark" text="source code here"](https://github.com/BallOpener/steam-dark-mode/tree/beta2)
!!!
==- Better Store pages in terms of usability
[!file RIGHT CLICK this and select Save Link As](/assets/css/webkit.css)
!!!success Save it as [!badge variant="dark" text="webkit.css"] to [!badge variant="dark" text="Steam\steamui"] or to the folder of your active skin in [!badge variant="dark" text="Steam\steamui\skins"]
!!!
!!!primary You can [!badge target="blank" variant="dark" text="see customizable variables for this skin here"](/assets/css/store.css)
!!!
==- More coming soon...
There aren't any other skins I could find. If there is a skin you would like added, you can edit this page and add it yourself, or tell me to add it by [!badge target="blank" variant="info" text="creating an issue on github"](https://github.com/xamionex/steamskins/issues/new?assignees=xamionex&labels=documentation&projects=&template=change-request.md&title=)
==-

## Uninstalling

If you want to uninstall you will have to:

- Close Steam and SFP fully (from tray menu)
- Delete the [!badge variant="dark" text="%LOCALAPPDATA%\Steam\htmlcache\Cache\"] folder
- Launch steam

!!!warning If you want to permanently delete any modifications delete SFP and [!badge variant="dark" text="Steam\steamui\skins"]
!!!
!!!danger If you're still paranoid delete the whole [!badge variant="dark" text="Steam\steamui"] folder along with [!badge variant="dark" text="Steam\clientui"] and relaunch steam
!!!
