# RetroTxt

Turn many pieces of ANSI text art and ASCII/NFO plain text into HTML5 **text** using RetroTxt. The browser agnostic WebExtension that takes retro text files and stylises them into a more pleasing, useful format to view and copy in a web browser.

Available for installation from both the [Chrome store](https://chrome.google.com/webstore/detail/retrotxt/gkjkgilckngllkopkogcaiojfajanahn) and [Mozilla Add-ons](https://addons.mozilla.org/en-US/firefox/addon/retrotxt/).

- View ANSI, ASCII, NFO, Shift JIS, PCBoard, Wildcat text art as HTML
- RGB 16.7 million, xterm 256 and IBM VGA 16 colour support
- Swappable ANSI palettes, xterm, VGA, CGA, monochrome and switchable iCE Colors
- Swappable ASCII & NFO colour themes, DOS, Windows, Amiga, C-64, Apple II, Atari ST
- SAUCE metadata parsing
- Multiple text encodings support including CP437, ISO-8959-1, Windows-1252, Shift JIS
- Text rendering toggles, smeared, shadow and normal
- Multiple IBM PC font support such as VGA, PS/2, EGA, CGA, MDA plus variants and more
- Various Amiga fonts plus Mona, Commodore PETSCII, Atari ATASCII, Atari ST and Apple II

Limitations
- A lot of [Bulletin Board System](https://spectrum.ieee.org/tech-history/cyberspace/social-medias-dialup-ancestor-the-bulletin-board-system) era ANSI art that relied on the 80x25 terminal with cursor positioning to create visual text motion and animations do not convert to HTML

![RetroTxt showcase](/docs/assets/zii-rtxt-ad.png)

## Documentation

### [Read](https://github.com/bengarrett/RetroTxt/blob/master/docs/index.md)

## Install

### [Chrome](https://chrome.google.com/webstore/detail/retrotxt/gkjkgilckngllkopkogcaiojfajanahn) · [Firefox](https://addons.mozilla.org/en-US/firefox/addon/retrotxt/)

#### [Or use the source code](https://github.com/bengarrett/RetroTxt/blob/master/docs/source_code.md)

### Requirements

**Chrome 55** or **Firefox 55** or newer browsers.

## Run RetroTxt

After install you can run RetroTxt on any text or ANSI art file viewed in the browser by clicking the toolbar button.

Selected toolbar button

![RetroTxt toolbar button in Chrome](/docs/assets/retrotxt_toolbar_button_chrome.png)

You can test the RetroTxt install by clicking on one of the 10 Sample artworks found on the `welcome.html` tab that launches after installation.

![RetroTxt samples](/docs/assets/rtxt-samples.png)

Elsewhere there are thousands of text files hosted at [textfiles.com](https://textfiles.com/directory.html) or [Project Gutenberg's](https://www.gutenberg.org/catalog/) _plain text_ books. Or download one of the amazing text art packs created by [Blocktronics](http://blocktronics.org/artpacks/) or found at [textmod.es](https://pc.textmod.es/) and use the `file:///` protocol to browse and view the text art files saved onto your hard drive.

### Permissions

Chrome requires **Allow access to file URLs** selected if you wish to use RetroTxt with text files stored on your local computer.

## License

### GNU LESSER GENERAL PUBLIC LICENSE

#### An important note about the license

While RetroTxt uses a [GNU Lesser General Public License v3.0](https://choosealicense.com/licenses/lgpl-3.0/), the included fonts **are not**. You should read each font license that is in the `fonts/` subdirectory before redistribution, as some of the added collections do not permit the sale or modification of their fonts and packages.

## Credits

RetroTxt by [Ben Garrett](https://bens.zone/) on [Twitter @bens_zone](https://twitter.com/bens_zone) and [GitHub](https://github.com/bengarrett/)

RetroTxt ANSI logo Zeus II [Twitter @Zeus_II](https://twitter.com/Zeus_II)

- PC fonts [_The Ultimate Oldschool PC Font Pack_](https://int10h.org/oldschool-pc-fonts/) by Viler
- Commodore Amiga fonts [_Multi Platform Fonts In Amiga Aspect v1.0_](https://www.trueschool.se/) by TrueSchool Ascii
- Apple II font [_Print Char 21_](http://www.kreativekorp.com/software/fonts/apple2.shtml) by Kreative Korp
- Atari ATASCI font [_Atari Classic TrueType Fonts_](http://members.bitstream.net/marksim/atarimac/fonts.html) by Mark L. Simonson
- Atari ST font [_8x16 system font_](https://www.dafont.com/atari-st-8x16-system-font.font) by divVerent
- Commodore 64 font [_C64 Pro Mono TrueType v1.2_](http://style64.org/c64-truetype) from Style

Options icons by [Google Material Design](https://material.google.com/)

Tippy tooltips by [atomiks](https://github.com/atomiks/tippyjs/)