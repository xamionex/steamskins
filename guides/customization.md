---
icon: gear
label: Customization
order: 50
---
# How to customize any skin that you install

!!!
Most skins *should* have an import for config.css from the relative folder, that being said you should always check if it really has it. For example [!badge target="blank" variant="dark" text="Fluent"](https://github.com/AikoMidori/SteamSkins/) and [!badge target="blank" variant="dark" text="Metro"](https://github.com/AikoMidori/SteamSkins/) both have them.
!!!
To check if your skin has it or doesn't check if it has this inside the [!badge target="blank" variant="dark" text="library.custom.css"] file:

```css
@import url('config.css');
```

==- It does
After confirming this, you can customize the skin, to create this file and customize your skin read the below guide
==- It doesn't
Add it after all the skins' own @imports\
Example:

```css
/* comments or whatever blahblahblahblahblahblahblahblahblah */
/* made somewhere in idkwhere by this person in the year of today */
@import url(http://stars.chromeexperiments.com/)
@import url(https://sandspiel.club/)
@import url(https://thecodetherapy.com/)
@import url('config.css'); <-------- YOU WILL ADD IT HERE, AFTER ALL THE OTHER @imports
```

==-

## Customizing

+++ Customization using config with skin

!!! Customization when you have a steam skin selected with SFP
!!!

1. In [!badge variant="dark" text="Steam/steamui/\<YOUR SKIN\>"] create a [!badge variant="dark" text="config.css"] file
   - If you don't know how right click an empty space, under `New` select `Text document`, then rename it to `config.css`
2. Open the `config.css` file with a text or code editor
   - If you don't have anything open it with Notepad, it's preinstalled on windows
3. Add any code customization you want

+++ Customization without using config with skin

!!! Customization when you have a steam skin selected with SFP but dont want to make a config.css file
!!!

1. In [!badge variant="dark" text="Steam/steamui/\<YOUR SKIN\>"] open the [!badge variant="dark" text="libraryroot.custom.css"] file with a text or code editor
   - If you don't have anything open it with Notepad, it's preinstalled on windows
2. Add any code customization you want

+++ Customization without skin

!!! Customization without a skin activated
!!!

1. In [!badge variant="dark" text="Steam/steamui/"] create a [!badge variant="dark" text="libraryroot.custom.css"] file
   - If you don't know how right click an empty space, under `New` select `Text document`, then rename it to `libraryroot.custom.css`
2. Open the `libraryroot.custom.css` file with a text or code editor
   - If you don't have anything open it with Notepad, it's preinstalled on windows
3. Add any code customization you want

+++

### Customization examples

==- Fluent/Metro Customization Example

#### Changing the variables in this example changes the accent color of the skin

```css
:root {
    --custompurple: purple;
    --customtransp: purple;

    --libraryhome: var(--custompurple); /* Highlight library color */
    --libraryhometransp: var(--customtranspurple); /* Highlight library color with opacity */
    --scrollbar: var(--custompurple); /* Scrollbar color */
    --progressbar: var(--custompurple); /* Progressbar color */
    --gamelist: var(--custompurple); /* Game list selected color */
    --titlenamehover: var(--custompurple); /* Game list title hover name color */
    --textcolor: var(--custompurple); /* Text color */
}
```

or with [!badge target="blank" variant="dark" text="hex colors (click here)"](https://www.google.com/search?q=color+picker):

```css
:root {
    --custompurple: #6624e2;
    --customtransp: #6624e2b3;

    --libraryhome: var(--custompurple); /* Highlight library color */
    --libraryhometransp: var(--customtranspurple); /* Highlight library color with opacity */
    --scrollbar: var(--custompurple); /* Scrollbar color */
    --progressbar: var(--custompurple); /* Progressbar color */
    --gamelist: var(--custompurple); /* Game list selected color */
    --titlenamehover: var(--custompurple); /* Game list title hover name color */
    --textcolor: var(--custompurple); /* Text color */
}
```

**Changing `--YourLibraryName` changes the name of home button**

```css
:root {
    --YourLibraryName: "YOUR LIBRARY" !important;
}
```

!!!success If you want to edit anything else using the pre-existing config [!badge target="blank" variant="dark" text="look at this file"](https://shiinaskins.com/steam-library/remote!url=master&config.css)
If you want to change a variable from there, add it inside `:root` in config.css like in the example above.
!!!
==- ADVANCED: No skin specific customization
**This step requires you to atleast know what CSS is and how to "code" in it.**

1. Open SFP and enter the :icon-gear: menu
2. In `Steam launch args` add the following `-dev`
   - This will make it so whenever you edit the config.css it *should* reload the page
     - In case it doesn't you'll have to edit directly on steam using `CTRL+SHIFT+I` or `F12` aka the devtools
3. As any kid did with their low budget laptop on a random school site to seem like they're hacking you can go ham with css here and change whatever you want, just remember the classes you want to change and make sure you save them in `config.css`
!!!dark
ProTip: open the source codes of skins in this guide and learn from their css
!!!
==-
