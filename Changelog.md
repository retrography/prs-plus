### 2.0.18 ###
  * ALL: Added scaling option to Standby Image
  * x50: Updated translations

### 2.0.17 release candidate 3 (2011.12.12) ###
  * x50: Fixed [Issue #244](https://code.google.com/p/prs-plus/issues/detail?id=#244) "books deleted using PC do not dissapear if scanning is "disabled (load cache)""
  * ALL: Fixed missing translation
  * 600: Fixed [Issue #237](https://code.google.com/p/prs-plus/issues/detail?id=#237) Menu Customization is buggy
  * ALL: Fixed [Issue #234](https://code.google.com/p/prs-plus/issues/detail?id=#234) "Mah Jong reports "no more moves" when moves are still available"


### 2.0.16 release candidate 2 (2011.11.26) ###
  * ALL: Minor translation fixes (RUS, TUR)
  * ALL: StandbyImage: Fix for scaling bug in Sony code
  * 300/505/600: Added $a0 (no wrap space) to fonts (to be added to x50 in 2.1.x)

### 2.0.15 release candidate (2011.11.21) ###
  * ALL: Fixed #171 "The "Copy to IM..." menu items are not present in Card via Mount, if card scanning is not disabled"
  * ALL: Fixed bug that prevented SD/MS card scan mode from being changed on the fly
  * ALL: Fixed #214 MSG\_COPYING\_BOOK not translated
  * ALL: EPUB Css styles are now sorted
  * ALL: Fixes #215 fb2epub converter doesn't work with cards with disabled scanning
  * 350/650: Improved Dutch translation (drMerry)
  * 350/650: Fixed "Continue searching from the begining doesn't work" (Sony bug)
  * 350/650: Added 1-Column Split (quisvir)
  * x50: "Cycle booklist" action now also cycles through collections (quisvir)
  * x50: Added option to treat periodicals as books (quisvir)
  * x50: Fixed #211  that caused SD/MS card scan options to be ignored on the first boot
  * 600/x50: Added Page Turn by Single Tap (quisvir)
  * 600/x50: Close reading popup menu (dict etc) and cancel selection by tapping page (quisvir)
  * 600/x50: Fixed #207 Collection sorting broken for Cyrillic
  * 600: Fixed #197 "SD/MS card via mount" doesn't handle non-latin characters
  * 600: Added keyCodes and Hold keyCodes to key bindings
  * 600: Fonts updated to the latest version
  * 600: Added Turkish translation
  * 600: Changed "holding option button" default action to do "go to parent view"
  * 600: Shifted games to the bottom of "More" list

### 2.0.14 beta (2011.09.22) ###
  * x50: Fixed #128 books/collections sorting
  * x50: Fixed "Coming back to Home from an other menu takes long"
  * 300/500: Fixed CoverPage as StandbyImage, fixed problem with next page after sleepmode
  * ALL: BrowseFolder patched with Shura1oplots FileSize in Comment & added FileType
  * ALL: Fixed russian localisation of "No Book, 1 Book, x Books"

### 2.0.13 beta (2011.09.14) ###
  * 505: Fixed #126 "images/audio lists are empty"
  * 505: Fixed #139 "Menu customizer values are not translated"
  * 505: Fixed #150 "Some options in the setup menu are not translated" needs reflash! not working with beta-pack on SD-Card
  * 505: Added #39 "Hold joypad arrows events"
  * x50: Fixed #120 "No keyboard in SP-EN dictionary"
  * x50: Enabled "half-page-mask" in landscape mode (like PRS-505), added option to set PDF-border-color to white
  * x50: Added option to preset custom Contrast and Brightness values (quisvir)
  * x50: Added option to toggle NEW-flag manually, hide standard collections and show reading-progress in home menu and thumbnail views (quisvir)
  * x50: Added Home Menu Booklist customization (quisvir)
  * 600/x50: Games moved into Games node
  * 600/x50: Added various Touch-Screen related options (disable dictionary and page-turn-gestures)
  * 600/x50: Enabled panning while ZoomLocked (quisvir)
  * ALL: Fonts: Added Korean alphabet (3131-314E unicode range), updated Czech d t l L letters, added up/down arrows
  * ALL: Added #70 "Make node containers accessible via menu customizer"
  * ALL: Added #24 "Displaying first page of the book on standby"
  * ALL: Screenshot: captured image is now  visible to the user, not only to the system :)
  * ALL: BrowseFolders:  added optional ".." item (by Shura1oplot)
  * ALL: Action are now grouped and have icons (by Shura1oplot)
  * ALL: New icons for utils and games (by surquizu, Shura1oplot, ?)
  * ALL: Updated existing games (Chess now comes with puzzles)
  * ALL: Added MineSweeper (by Mark Nord), Draughts, XO-Cubed and Solitaire (by Ben Chenoweth)
  * ALL: Added Calendar app (by Ben Chenoweth)
  * All: Added various "Standby" options (display book cover, last screen) (by Mark Nord)

### 2.0.12 beta (2011.05.26) ###
  * 505: Fixed German translation
  * ALL: Fixed Courier font name
  * ALL: ~~Sudoku can be exited by pressing home button~~ (not in 950, maybe other models)
  * 350/650: Fixed custom CSS path

### 2.0.11 beta ###
  * 300: Fixed broken XML in Spanish translation
  * 300: Added Ukrainian localization by Bookoman
  * 300/505: Fixed "actions do not work"
  * 300/505: Added French localization by sengian (installer)
  * 300/505: Fixed bug related to "Skip book menu" option
  * 505: Restored localizations
  * 505: Restored 1.1.3 menu layout with "Multimedia"
  * 600: Added Portuguese localization by OTNeto
  * 600: Added Czech localization by milanv
  * 600/x50: Fixed keyboard: "aaaa" is shown instead of ascented (popup) letters
  * 600/x50: TextScale addon was included
  * x50: Reduced statusbar index / clock font size, moved "playing" indicator to the left
  * x50: Fixed "Periodicals"
  * x50: Fixed sorting in "books" for non latin alphabets
  * 950: Added GMT+10 timezone
  * ALL: Screenshot: captured image is now immediatelly visible to the system
  * ALL: Folders: Added option to disable scanning without loading cache (as it was in 1.1.3)
  * ALL: Folders: Added "via mount" card access (uses Linux "mount" command instead of mtools like buggy utility)
  * ALL: Added "LRF Text Scale" addon that allows to customize zoom levels

### 2.0.10 alpha ###
  * x50: Fixed doRotate action
  * x50: Fixed #68 x50: Deleting books opened via Book History is bugged
  * x50: Fixed #66 x50: Collection editing broken, if collection node is not in the 4th slot
  * x50: Periodicals node no longer "unmovable", replaced with "Browse Folders" by default
  * x50: Added Belorussian / Ukranian chars (as popups) to keyboard
  * x50: Added rotate by 0 / 90 / 180 / 270 / clock wise / counter clock wize actions
  * 600: Added rotate by 90 action
  * 600: Added Belorussian / Ukranian chars (as popups) to keyboard
  * 600: Added #47&48 Spanish (by ?) & Catalan (by Alex Castrillo) localizations
  * 300/505: Added Dictionary (by Clemenseken, lysak, m-land, Mark Nord)
  * 300: Added #57 Spanish localization (by Carlos)
  * 300: Fixed #63 author/title sort in 2.0.5alpha not working (patch by vento...@airpost.net)
  * ALL: Added
    * Calculator by Mark Nord
    * Chess by Ben Chenoweth / Stefano Gioffre
    * Five in a Row by Ben Chenoweth
    * Five Balls by Clemenseken
    * Free Cell by Ben Chenoweth
    * Mahjong by Clemenseken
    * Sudoku by Obelix
  * ALL: Integrated fb2toepub converter (by Alexey Bobkov)
  * ALL: Added sample folders.cfg / EPUB css file that references LRF fonts
  * 300/505: PRPInstaller folder is deleted automatically after reboot (no need to reboot multiple times to delete it)
  * 350/650/950: Created "all in one" installer (Windows only)

### 2.0.9 alpha (bugfixes/enhancements for x50) ###
  * x50: Fixed "Holding option /zoom buttons should call "Go Back in Menus" and "Search" respectively"
  * 350/650: Fixed "Text Memo open => press root => reboot"
  * x50: Fixed ""more" node doesn't have parent if not visible"
  * ALL: Fixed "BrowseFolders view not refreshing on settings change, if there is a book open via BrowseFolders"
  * x50: "Fixed Page index in book is not updated when book is opened"
  * ALL: Implemented "goto TOC, doOption, doSearch, doRotate, doMenu, doSize, doRoot actions"
  * x50: Implemented "Russian phonetic keyboard (original keyboard xml by boroda)"
  * x50: Implemented "Latin-English and Latin-Georgian scrollbars"

### 2.0.8 alpha (ported to 650/350) ###
  * ALL: Added Core.config.userCSSFile support (instead of hardcoded style.css)
  * 650/350: Ported to 650 (tested) and 350 (should work :))

### 2.0.7 alpha ###
  * Implemented #? possibility to download files using web browser
  * ALL: Implemented # sort by filename, showing filename as comment

### 2.0.6 alpha (ported to 950) ###
  * ALL: "Fixed #34  MenuCustomizer should put unassigned nodes into default one"
  * ALL: Implemented #55 "'Jump to Folders' action"
  * ALL: Fixed #64 "Wrong german translation file"
  * 300: Fixed "next/prev" page actions consuming "goto page" key events
  * 600,x50: Added "books" scrollbar customization feature

### 2.0.5 alpha ###
  * 600: BrowseFolders will apear in "more", if not shown on the main page.
  * 300: Fixed sort by title (Russian locale)

### 2.0.4 alpha ###
  * ALL: Updated "about prs+"
  * ALL: Added Russian translation fixes by happyhgy
  * ALL: implemented #16 "88.1% (add decimal) in statusbar"
  * ALL: Fixed #36 (wrong Courier font name)
  * ALL: Fixed #17 "clock is not updated when going from standby"

  * 600: Temporary fix for #42
  * 600: Added Georgian keyboard (ergonomic)
  * 600: Fixed #28 "Stand-by image should be independent of screen orientation" (added landscape subfolder support, as there is no way to rotate the image"
  * 600: Fixed #41 "PRS+ Firmware version number missing on About page"
  * 600: Fixed #14 " by author/title sorting doesn't work for non latin chars"
  * 600: Implemented #26 Chinese localization
  * 600: Implemented #29 Italian localizaiton
  * 600: Fixed #23 (Calc not working)
  * 600: Added Georgian translation (by rawerfas)
  * 600: Implemented: #31 "Use Volume buttons to move through history"
  * 600: Fixed #37 "prsp.sh in IM is not called"

  * 300: Fixed DicitonaryCL
  * 300: Fixed #14 " **by author/title sorting doesn't work for non latin chars"
  * 300: Added Georgian translation (by rawerfas)
  * 300: Fixed #13 "back/fordward history actions do not work"
  * 300: Implemented #20 "bind default "hold numeric button" actions"
  * 300: First digit is ignored, if it is zero, when opening "goto" dialog
  * 300: Fixed "next/prev" page actions consuming "goto page" key events**


### 2.0.3 preview ###
  * 600: added standby "wallpaper" feature (randomly showing /database/system/PRSPlus/wallpaper on standby)
  * 600: added option to open books directly from MS/SD card, with disabled scanning

### 2.0.2 preview ###
  * 300: Added "hold" events (researched by Mark Nord, implemented by kravitz)
  * 300: Fixed BH bug (list of books wasn't correctly updated)
  * 300: #Added libfskload

### 2.0.1 preview ###
  * 300: Added Italian localization
  * 300: Improved installer to support common 18060 firmware

### 2.0.0 preview ###
  * Big part of PRS+ code rewritten from scratch to simplify porting to new devices
  * Current version only supports 300

### 1.1.3 ###
  * Minor bugfixes (not worth updating from 1.1.2rc unless you delete books from collections all day long).
### 1.1.2 release candidate ###
  * Bugfixes
### 1.1.1 beta ###
  * Added Simplified Chinese translation by thawk
  * Amended most translations.
  * Changed BookHistory to immediately open books instead of showing book menu. Renamed corresponding action from ContinueReading to BookHistory (<font color='red'>as a result, old key binding to ContinueReading won't work until reassigned</font>)
  * Fixed all known bugs (Dictionary path, EPUB zoom, PageIndex's ppm/time left)

### 1.1.0 beta ###
  * Localization
    * Catalan by surquizu
    * Czech by Hobogen
    * Deutsch by Duglum & klawong & Mark Nord
    * English
    * French by Duglum & VICTORSJG
    * бѓҐбѓђбѓ бѓ—бѓЈбѓљбѓ by kartu
    * Р СѓСЃСЃРєРёР№ by SLL
    * Spanish by VICTORSJG & surquizu
  * page per minute / remaining time settings for PageIndex
  * dictionary by Clemenseken & Lisac (to use it, put your dictionary files int /database/system/PRSPlus/dictionary. Dictionary files MUST have "dic" extension)
  * Book History by kravitz
  * option to set default zoom size, limit available zoom steps by kravitz
  * Main menu customization by kravitz
  * Introduced "safe mode", if reader is connected to USB during startup, PRS+ does not load.
  * PRS+ settings moved to /opt0, PRS+ addons and core are now built into firmware

### 1.0.2 ###
#### Script ####
  * Added EpubUserStyle addon that allows to switch between files with .css extension located in /database/system/PRSPlus/epub folder
  * Added TextEncoding addon, that allows to switch between Latin1 / win1521 encodings in text/rtf files.
  * Added mount/umount feature to BrowseFolders (experimental). SD cards with folder structure of any complexity should now be accessible. Mounting and unmounting takes roughtly half a second.
  * Removed obsolete prsp.sh samples
#### Firmware ####
  * Support for switching between win1251/Latin1 txt/rtf file encodings
  * Removed prsp.sh call from SD card, added . call to /database/system/PRSPlus/prsp.sh (located in Internal Memory)
  * Added porkupan's (aka boroda) "is usb connected"check, if reader is connected via USB during startup, neither prsp.sh is called, nor LD\_PRELOAD is set.

### 1.0.1 ###
#### Script ####
  * Added chinese and Russian shell script samples
  * Added VICTORSJG's "menu index"
  * Fixed missing string problem for next/previous song actions.
  * Fixed NaN problem in epubs page index
#### Firmware ####
  * Fixed call to prps.sh

### 1.0.0 ###
#### Script ####
  * Added settings to disable usage of "titleSorter" field. (useful in case someone has half-balked LRFs)
  * Added thawk's titleSorter support (titleSorter is an invisible field in LRF files that is used for sorting)
  * Added next/previous song actions by KrzyInuYasha
  * Added PRS+ version info to ABOUT
  * Fixed problem with screenshot confirmation message (it wasn't disappearing in some cases)
  * Fixed problem with "doCenter" like keys, caused by multiple keys being bound to a single function.
  * Fixed epub page number bug

#### Firmware ####
  * Added win1251 to UTF-8 (cyrillic only) so file) (for "export LD\_PRELOAD=/opt/sony/ebook/application/Latin1toUTF8.so" hack)
  * Added call to /Data/database/system/PRSPlus/prsp.sh file to startup shell script.
  * Added igorsk's libfskLoad.so to /opt/sony/ebook/application folder, with corresponding prspVm.xml file (used by dictionary and similiar apps)

### 1.0.0 RC2 ###
#### Script ####
  * Fixed problem with "doCenter" like keys, caused by multiple keys being bound to a single function.
  * Fixed problem with screenshot confirmation message (it wasn't disappearing in case image was saved to internal memory)