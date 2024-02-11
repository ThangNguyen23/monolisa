# MonoLisa - ДiSC-8 crack

`Version: 2.017+, 10.02.24 Prerelease`

This is a **FULL 1:1** crack of the crazy expensive MonoLisa font, and what is there to say? We are publishing this so just anyone can use it, feel free add it to any project you want

If you see a new version was posted to their site, **open an issue**. We're gonna try to keep this as up do date as can be

# Examples
## JavaScript 
![image](https://github.com/d8-bbc11/monolisa/assets/159638529/fd00411e-46c7-4bf9-9c9a-7bad109cb623)

<sup>Color scheme: [Tokyo Night](https://marketplace.visualstudio.com/items?itemName=enkia.tokyo-night)</sup>

# Installation
Download both `.ttf` files, then on
- Windows:
  - Install the regular version **first**, then the italic one.
  - If italic version appears instead of the regular one, just install regular again.
- Mac:
  - Install like a regular font, if there's any issues **REPORT THEM**
- Linux:
  - Paste the files into your `~/.local/share/fonts` folder
  - Run `fc-cache -f -v` in the terminal
## Webfont
  - Download both `.woff2` files to your site's folder, and add this to your stylesheet
  ```css
  @font-face {
   font-family: MonoLisa;
   src: url("MonoLisa-regular.woff2");
   font-weight: 100 900;
   font-style: normal;
   font-display: block;
  }
  @font-face {
   font-family: MonoLisa;
   src: url("MonoLisa-italic.woff2");
   font-weight: 100 900;
   font-style: italic;
   font-display: block;
  }
  ```
  Then you can add `font-family:'MonoLisa';` to eg. `<pre>`
## Visual Studio Code setup
To edit the font's features, add a line to your settings.json
* Windows: `%APPDATA%\Code\User\settings.json`
```json
"editor.fontLigatures": "'feat','ures'"
```
## Feature List
### Best to have
* `ss02` - Italic Script Version
* `ss11` - Centered hexadecimal x ***0xF***
* `liga` - Coding ligatures
***
### Other
* `frac` - Fractions, turns 1/2 into ½
* `onum` - Old style numbers
* `calt` - Whitespace ligatures
* `zero` - Slashed zero
* `ss01` - Normal asterisk
* `ss03` - Alternative ***g***
* `ss04` - Other alternative ***g***
* `ss05` - Alternative ***ß***
* `ss06` - Alternative ***@***
* `ss07` - Alternative curly brackets ***{}***
* `ss08` - Alternative parenthesis ***()***
* `ss09` - Alternative ***>=*** ligature
* `ss10` - Other alternative ***>=*** ligature
* `ss12` - Thin backslash
* `ss13` - Alternative ***$***
* `ss14` - Alternative ***&***
* `ss15` - ***i*** without serif
* `ss16` - ***r*** without serif
* `ss17` - Alternative ***.=*** and ***..=*** ligature
* `ss18` - Alternative ***@***
# What works?
* ***LITERALLY EVERYTHING***, including:
  * Full character set
  * Coding ligatures
  * Symbols & Powerline
  * Slashed 0
  * Script variant and other OpenType™ features
  * Variable font
  * Variable Webfont
  * Access to prerelease
  * Commercial use (theoretically)
  * Users / Domains: ∞ unlimited
  * Page views: ∞ unlimited
  * Print / Apps: ∞ unlimited
  
## ...and this turns out to be the...

![image](https://github.com/d8-bbc11/monolisa/assets/159638529/da0e0ee9-63a0-4444-8a77-7baefbaa4c41)

LOL
