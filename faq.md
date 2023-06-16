---
icon: question
label: FAQ
order: -100
---
# Frequently Asked Questions

## Is this free to use?

Yes, this wiki, and it's contents are open-source and free to use, most of the tools used in this wiki are linked aswell.

## How do I install custom skins?

Considering recent changes done to steam, skins aren't that hard to install, Please see our [Getting Started](/guides/installation.md) guide for more information.

## Are there any customizations available?

With steam now not using vgui (their proprietary user interface) you can fully customize any part of the steam app, overlay, big picture and even the deck ui!

To get started with this visit [this guide](/guides/customization.md)

## Something isn't working right

+++ Steam is launching but skin isnt loading or is broken

Clearing cache may solve this:

- [!badge variant="dark" text="1st method"]: Close steam and delete everything in [!badge variant="dark" text="%localappdata%\Steam\htmlcache\Cache\"]
- [!badge variant="dark" text="2nd method"]: Open steam, at the top left click Steam (or the steam icon) > Settings > Downloads > Press Clear Downloads Cache Button
- The above actions can solve the following problems:
  - the webpages look broken or are displaying broken content
  - the skins related to library, friends panel, chat don't work
+++ Steam isn't launching at all

!!!danger
Back up your skins from [!badge variant="danger" text="Steam/steamui/skins"] before doing this step
!!!

1. Close steam (either with task manager or right click, wait and then exit steam on the prompt)
2. Go to the steam folder and delete [!badge variant="dark" text="Steam/steamui"] and [!badge variant="dark" text="Steam/clientui"]
+++

## How do I uninstall?

[!badge target="blank" variant="info" text="Look at this guide"](/guides/installation.md#uninstalling)

## How do I start steam with parameters?

There is multiple ways to do this

+++ SFP Way (best)

1. In SFP naviget to the :icon-gear: at the bottom left of the window
2. Scroll down to Steam launch args
3. Add whatever parameter you want
    - Example: -cef-enable-debugging -dev

+++ Shortcut way (2nd best)

1. Right click the steam shortcut wherever you have it and add a parameter at the end of the path
![Steam properties menu](assets/images/steam_properties.png)

+++ Registry startup way
Note that this method is unreliable and risky if you don't know what you're doing

1. Open [!badge variant="dark" text="Regedit"] / [!badge variant="dark" text="Registry Editor"]
2. Navigate to [!badge variant="dark" text="HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\Run"]
3. Edit the [!badge variant="dark" text="Steam"] key (dword)
4. Add a parameter same as in the picture above
+++
