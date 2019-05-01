# Firefox UI customization

Changing Firefox interface with userChrome.css and userContent.css.	

## Features

- centered address in urlbar
- floating centered findbar on the top of the page
- subtle tab separators
- tab close button visible only on hover
- unnecessary buttons removed
- context menus cleaned up
- dark thin scrollbars
- dark JS alerts/prompts
- dark viewsource and error pages
- bookmarks bar on newtab page on hover
- background image on newtab page
- floating navbar in fullscreen mode
- compact addons overflow menu
- 

Some colors might be hardcoded to match the theme I use ([ArcDark](https://addons.mozilla.org/en-US/firefox/addon/arc-dark-theme-we/)).

## Installation

1. Open your profile from `about:support > Profile Folder`.
2. Inside create a folder named `chrome`.
3. Copy contents of this repository into this `chrome` folder.

Comment out `@import` lines in `userChrome.css` and `userContent.css` to disable certain tweaks. Such as 

`/*@import url('userContent/about_newtab.css');*/`

## Examples

![NewTab screenshot](https://i.imgur.com/8FuAGz3.png)
*Photo by Osman Rana on Unsplash*

![Webpage screenshot](https://i.imgur.com/5SQTHnF.png)

Min/max/close buttons stand out because on my Windows 8.1 they are controlled by OS and cannot be changed by Firefox.

## Other great custom Firefox UI projects

- [Firefox csshacks](https://github.com/MrOtherGuy/firefox-csshacks)
- [UserChrome Tweaks](https://github.com/Timvde/UserChrome-Tweaks)
- [Quantum Nox](https://github.com/Izheil/Quantum-Nox-Firefox-Dark-Full-Theme)
- [CustomCSSforFx](https://github.com/Aris-t2/CustomCSSforFx)
