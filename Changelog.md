**Changes to the OSMC Classic-Like skin**

---

**_v0.0.2_**

_Restore_
- Restored view to episodes left to watch
- Restore OSMC Blue as default Color/Theme
- Restore MyOSMC to Mainmenu

**Changes to the OSMC skin**

---

**_v19.0.0_**

_New_
- add new v19 features (music library, movie sets, PVR additions and chapter/EDL markers in video OSD)
- add channel sort by and sort order toggles to PVR guide side menu
- add artist, album and radio now/next/RDS information to fullscreen music/radio playback window
- add new info button to video and music OSD
- add trackt.tv ratings information to video info dialog
- add first WebLate translations
- new skin design

_Improved_
- rework look of default fullscreen music playback screen to match general skin look
- refine video fullscreen OSD and info dialog behaviour
- improve behaviour of weather widget when no weather information is available
- improve widget headings and general secondary label information
- improve localize consistency
- add missing custom colour settings
- improve skin setting select process for settings with a lot of options to choose from
- use translatable labels for skin setting options
- improve media flags positioning and edge case handling
- move My OSMC link from home menu to settings window

_Fixed_
- add missing "play recorded programme" button to PVR info dialog
- fix cut-off text of plot/description text boxes

---

**_v18.5.0 - November 2020_**

_Improved_
- add videos and music root directory to home menu entry and submenu customization dialog
- add picture and addon browser directory to home menu entry and submenu customization dialog

---

**_v18.4.0 - October 2020_**

_New_
- add channel group switching buttons to OSD PVR channels list
- add Library Node Editor support
- new square versions of existing views for video addons and music
- add automatic masking for scope skin version
- add second dialog page to music, PVR and addon info dialog
- add setting to force a specific view for video addons
- add missing PVR seek slider

_Improved_
- improve wording in skin settings
- improve watched/listened to indicator for all views/widgets
- adjust media window view positioning and size
- adjust wall and wide view for music
- improve spacing of wall low view
- improve PVR descriptions
- rework now playing information and fullscreen music playback information
- add missing detail labels to PVR and music info dialogs
- show TV show episode thumb in video info dialog
- use the more extended list view for more content types (addons, games, files and pictures)
- improve second label of more extended list view
- add wide view support to games and programs
- harmonize non-focus animations
- improve scrollbar size relative to their controls
- add favourites to home menu entry/submenu and widget customization dialog

_Fixed_
- fix default view music and video navigation
- fix PVR channels window heading label
- fix widget icon fallback
- fix PVR OSD dialogs

---

**_v18.3.0 - May 2020_**

_New_
- add standard Kodi 'Menu' key functionality to access side menu in all windows
- add new Wide low info view
- add support for Up Next addon
- add playlist button to video OSD
- add 3D depth information to GUI elements
- add new widget layouts (square and square small)
- add new 2.33:1 scope masking option

_Improved_
- make Wide low view accessible for music views
- make disabled text colour more readable
- improve widget details and window headings
- improve debug overlay
- improve overall handling of music videos
- improve playlist window
- add missing scrollbars
- rework most dialogs for consistency
- improve widget positioning and widget icon size
- improve skinshortcuts management dialog
- improve video info dialog button behaviour
- remove unnecessary song and picture list view

_Fixed_
- fix settings button labels for 21:9 and 4:3 modes
- fix music playlist editor window
- fix side menu return button behaviour
- fix edge alignment of dialogs and windows
- fix watched/listened to status for a play count higher than 1

---

**_v18.2.0 - March 2020_**

_New_
- add new pre-defined widgets
- add setting to change whether video info dialog shows details or plot first
- add setting to set a solid colour instead of background images
- add audio and subtitle language information to media flags
- add setting to toggle media flags information shown (first)
- add new seek indicator to audio and video player
- add new scope version
- add new scrolling label
- add new never hide music information during playback setting
- add skin settings explanations
- add setting to hide item count

_Improved_
- rework home menu customization dialogs
- improve sort by and sort order toggles
- improve video info dialog (animations and buttons)
- improve alignment and positioning of item count and media flags
- show view toggle only when more than one view is available
- improve info dialogs (more information/layout with video and addon info dialogs)
- update Artist Slideshow integration (v3 update)
- improve OSD animations
- show item count with empty containers
- improve music player during radio playback
- improve visible window elements when busy dialog is active
- let live TV and radio OSD listen to Kodi OSD settings

_Fixed_
- move hide scrollbars setting to skin settings window
- hide MyOSMC home menu entry and widget on non-OSMC systems
- fix overlapping in views with big horizontal titles
- add scrollbar to music album info dialog (if details list is too long)
- fix now playing dialog for radio and live TV playback
- fix kiosk mode behaviour

---

**_v18.1.0 - November 2019_**

_New_
- add 21:9 and 4:3 modes
- add option to show lock icon for encrypted PVR channels (show encrypted channel icons by default)

_Improved_
- use OSMC busy spinner for widget loading
- add Disabled option to Adjust OSD on-time during video pause button
- rework skin structure for Transifex localization
- improve widget icon animations
- rework dialog animations to prevent bright transition

_Fixed_
- don't show parts of weather widget during widget loading
- localize all labels

---

**_v18.0.1 - October 2019_**

_New_
- add new video player OSD settings (show OSD after beginning of playback and before end of playback)
- add new second video info dialog screen (with extended rating, audio and subtitle information and bigger plot text box)
- add new wall info view (based on wall view)
- add new adjust representation of video duration setting
- add new multi-image (folder) background option
- add new individual background option for home menu entries
- add new options for music OSD to automatically show
- add user rating to music and video library
- add new side-menu player controls
- add new options to hide watched indicator in video library and listened to indicator in music library

_Improved_
- add audio information to video info dialog
- use font type for bold, light and italic instead of label formatting (where possible)
- prevent stacking of window/dialog text during background video playback
- show special watched indicator icons for videos watched more than once
- add listened to indicator for music

_Fixed_
- only offer rip CD feature when an audio CD is present

---

**_v18.0.0 - May 2019_**

_New_
- add new subtitle selection to match v18 requirements
- add new games section to match v18 requirements
- add new resolution select button/dialog in video player
- add player icon to now playing dialog
- add new dependency button in addon info dialog to match v18 requirements
- new colour options (colour sets, background gradients, adjustable opacity)
- add PVR channel number input dialog
- add PVR timeshift status dialog
- add welcome dialog on non-OSMC devices
- add director button to video info dialog
- add new views (wide low, wall small, wall low, wall info, list info)
- add new sub-menu indicator icon
- add "Random TV shows" widget as new standard for TV shows home menu entry
- add new dialog navigation indicators
- add ratings toggle for IMDb, Metacritic, Rotten Tomatoes and TVDb
- add new video player OSD settings (show OSD after beginning of playback and before end of playback)

_Improved_
- adjust syntax, values, labels and infobools to match v18 requirements
- adjust PVR section to match v18 requirements
- highlighting colour now adjusts according to text color
- streamline OSD animations
- add missing adjustable plot fonts
- let favourites dialog behave like a normal window
- add file path and name to refresh button in video info dialog
- add song/album year to music player
- add wide list as music view
- add music OSD album art size switch
- adjust widget headings to always show and adjust animations to match widget animations
- add option to change widget labels

_Fixed_
- show proper game widget title when not using skinshortcuts script
- highlighting is now more consistent
- fix current position/time remaining and current time/end time for PVR playback
- hide deprecated previous/next channel buttons in PVR playback OSD
- fix background of subtitle settings window
- fix layout of PVR playback dialogs
- fix dialog list navigation
- change font size of media tags to prevent overlap with titles/details
- only offer rip CD feature when an audio CD is present

---

**_v17.0.5 - June 2018_**

_New_
- add option to adjust dim factor of unfocused art 
- add option for additional text highlight
- add channel icon to PVR info dialog
- add new widget options (through skin.helper.widgets script)
- add AURO media flags (based on file naming)
- add new cover art highlighting (size change depending on focused state)
- add new movie collection indicator

_Improved_
- add more weather information to weather window
- refine music icons
- remove watched status for music items (in views and widgets)
- adjust representation of object based audio codec tags
- refine positioning and scaling of media tag icons
- adjust viewtype 55 for music and add-ons to match viewtype 53 for movies and TV shows
- improve highlight colour of selected text
- change appearance of all progress icons to round shape
- add no dimming of cover art
- dim watched and collection indicator depending on cover dimming setting
- update watched overlay icon to match appearance of new movie collection indicator
- add current control ID to debug overlay
- change overlay colour setting to match appearance of background colour setting

_Fixed_
- fix scrollbar in music navigation
- fix item widths in various windows
- fix weather window
- fix focused items in addon list view (e.g. YouTube)
- fix PVR views to add scrolling and adapt season/episode representation
- fix widget details label for PVR items (when using skinshortcuts script)
- fix scrollbar in file browser

---

**_v17.0.4 - March 2018_**

_New_
- music track duration added to music info dialog
- 3D label shown under media flags now (after first playback and/or if named according to Kodi wiki)
- Atmos/DTS:X label shown under media flags now (if named according to Kodi wiki)
- show codec information in music “now playing” window
- show current audio/subtitle stream in info dialog during full screen video playback
- add file size label next to duration label in file view
- add adjustable font sizes/styles to plot/description texts (addon info, music info, full screen info, PVR info and video info dialog) – font sizes 27 (S), 30 (M), 33 (L) and 36 (XL) available in normal and light
- add option to show date above system time
- add option to adjust OSD on-time during video pause
- add option to hide thumbnail art of unwatched TV show episodes

_Improved_
- show resolution with “p”-suffix (global)
- show 4K resolution as 2160p (global)
- adjust playback time and finish time in “now playing” dialog to match representation in full screen video playback window
- show media flags in a two-line textbox
- translate video/audio codecs in media flags to more understandable labels
- add scrolling of long titles in “now playing” window for music
- add scrolling of long album titles/artist tags in music list view
- show more specific channel layout information (2.0, 5.1, 7.1, etc.)
- replace “Aired on” in details of TV show episodes (in list view) by translatable “First air date”
- adjust representation of season/episode titles to one syntax everywhere: S01E01
- replace "Loading…" upon widget loading at startup of mediacenter by translatable "Please wait…"
- add cycling of controls highlight in context menu

_Fixed_
- window heading and system clock moved slightly down and reduced width of “now playing” dialog to avoid overlaps
- adjust height of plot textbox in list view to avoid overlap with new media flag representation
- use titles when available instead of item labels
- recognize TV show specials and show them correctly (no season, just episode S1)
- adjust width of scrolling titles in wall view and wide list view to avoid overlap with new media flags
- “now playing” dialog now shows album/artist tags correctly even when one of them or both are not present in the currently playing music file
- fix custom background colour option
- bring back current playlist button in music OSD functionality

---

**_v17.0.3 - July 2017_**

---

**_v17.0.2 - March 2017_**

---

**_v17.0.1 - March 2017_**

---

**_v16.9.3 - January 2017_**

---

**_v16.9.3 - January 2017_**

---

**_v16.9.2 - November 2016_**

Fix crash in PVR guide window; Font updates

---

**_v16.9.1 - November 2016_**

Library image fixes and now playing information

---

**_v16.9.0 - September 2016_**

Release

---

**Changelog v19.0.0**

_accommodate  for changes of the v19 skin engine_
_add  localize files for WebLate translations_
_replace old TextColor1, TextColor2 by new TextColorFO, TextColorNF variables in all files_
_replace masking includes conditions by new expressions_
_add new seperate includes coordinates files_
_adjust coordinates for new skin design_
_remove deprecated 31091-1.DATA.xml file for default My OSMC home menu entry_

defaults.xml:
- remove deprecated colours

strings.po:
- update PVR fullscreen playback localize (31171)
- rework localize for new trackt.tv ratings information (31115)
- rework localizes for consistency (31136, 31182, 31193, 31201, 31315, 31331, 31357)
- rework localizes for new skin colour settings (31023, 31024, 31025, 31026, 31037, 31050, 31060, 31150)
- rework localizes for new skin settings secondary labels (31061, 31070, 31152, 31153, 31154, 31168, 31235, 31319)
- add new localizes for new skin settings secondary labels (31413, 31414, 31415, 31416, 31417, 31418, 31419, 31420, 31421, 31422, 31423, 31424, 31425, 31426, 31427, 31428, 31429, 31430, 31431, 31432)
- rework localizes for new skin design (31235, 31290)
- rework deprecated background gradient localize for new content types (31293)
- remove deprecated background gradient localizes (31111, 31262, 31263, 31264, 31265, 31266)
- update localize for streamlined plot/description font size setting (31326)
- add new localizes for new content types (31433, 31434)

Textures.xbt:
- update textures file with new OSD ranges and new PVR reminder icon
- update textures file with new music OSD info button file and reworked music OSD repeat button file
- update textures file with new background overlay image files for new skin design

mainmenu.DATA.xml:
- remove My OSMC from default skinshortcuts home menu layout

template.xml:
- hide weather widget when no weather information is available
- improve widget heading details

AddonBrowser.xml:
- replace WindowBackgroundImage include with new WindowBackgroundImageVertical include
- remove texturesliderbar from scrollbar

Coordinates_DialogVideoInfo.xml:
- add new sets information
- rework coordinates for improved ratings and audio/subtitle streams information

Coordinates_DialogPVRInfo.xml:
- add new reminder icon

Coordinates_MusicOSD.xml:
- adjust width and position of right OSD buttons

Coordinates_MusicVisualisation.xml:
- adjust coordinates for reworked fullscreen music playback window

Coordinates_Settings.xml:
- adjust coordinates of settings entry list to fit new My OSMC entry

Coordinates_VideoFullScreen.xml:
- add new coordinates for chapter and EDL markers

Coordinates_VideoOSD.xml:
- update right options width for new info button

Coordinates_Viewtype52.xml:
- add conditional visibility of view icons for movie sets

Coordinates_Viewtype521.xml:
- add conditional visibility of view icons for movie sets

Coordinates_Viewtype522.xml:
- add conditional visibility of view icons for movie sets

Coordinates_Viewtype53.xml:
- add conditional visibility of view icons for movie sets

Coordinates_Viewtype531.xml:
- add conditional visibility of view icons for movie sets

Coordinates_Viewtype532.xml:
- add conditional visibility of view icons for movie sets

Coordinates_Viewtype533.xml:
- add conditional visibility of view icons for movie sets

Coordinates_Viewtype534.xml:
- add conditional visibility of view icons for movie sets

Custom_Confirm_Reset_Skin_Settings.xml:
- replace DialogFanart include with new DialogBackgroundImage include
- remove deprecated dialogButtonBackground include

Custom_Confirm_Reset_Skin_Settings.xml:
- add new adjustable explanation text boxes

Custom_Welcome.xml:
- replace DialogFanart include with new DialogBackgroundImage include
- remove deprecated dialogButtonBackground include

DialogAddonInfo.xml:
- add new versions and update buttons
- replace DialogFanart include with new DialogBackgroundImage include
- add new secondary parameter to time include
- remove deprecated dialogButtonBackground include

DialogAddonSettings.xml:
- replace DialogFanart include with new DialogBackgroundImage include
- add new secondary parameter to time include
- remove deprecated dialogButtonBackground include

DialogConfirm.xml:
- replace DialogFanart include with new DialogBackgroundImage include
- add new secondary parameter to time include
- remove deprecated dialogButtonBackground include

DialogFavourites.xml:
- replace WindowBackgroundImage include with new WindowBackgroundImageVertical include
- move time include to not be affected by WindowFadeAnimation
- remove texturesliderbar from scrollbar

DialogFullScreenInfo.xml:
- add new onleft and onright controls to switch between PVR now and next information
- change onclick to close info dialog

DialogGameControllers.xml:
- replace DialogFanart include with new DialogBackgroundImage include
- add new secondary parameter to time include
- remove deprecated dialogButtonBackground include

DialogKeyboard.xml:
- replace DialogFanart include with new DialogBackgroundImage include
- add new secondary parameter to time include
- remove deprecated dialogButtonBackground include

DialogMediaSource.xml:
- replace DialogFanart include with new DialogBackgroundImage include
- add new secondary parameter to time include
- remove deprecated dialogButtonBackground include

DialogMusicInfo.xml:
- add new release date, original date, BPM and file information detail labels
- replace DialogFanart include with new DialogBackgroundImage include
- add new secondary parameter to time include
- remove deprecated dialogButtonBackground include

DialogNumeric.xml:
- replace DialogFanart include with new DialogBackgroundImage include
- add new secondary parameter to time include
- remove deprecated dialogButtonBackground include

DialogPictureInfo.xml:
- replace DialogFanart include with new DialogBackgroundImage include
- add new secondary parameter to time include
- remove deprecated dialogButtonBackground include

DialogPVRChannelGuide.xml:
- rework adjustable plot text boxes

DialogPVRChannelManager.xml:
- replace DialogFanart include with new DialogBackgroundImage include
- add new secondary parameter to time include
- remove deprecated dialogButtonBackground include

DialogPVRChannelOSD.xml:
- rework adjustable plot text boxes

DialogPVRGroupManager.xml:
- replace DialogFanart include with new DialogBackgroundImage include
- add new secondary parameter to time include
- swap channels and grouped channels list positions
- remove deprecated dialogButtonBackground include

DialogPVRGuideSearch.xml:
- replace DialogFanart include with new DialogBackgroundImage include
- add new secondary parameter to time include
- remove deprecated dialogButtonBackground include

DialogPVRInfo.xml:
- add new first aired detail labels
- add new 'Add reminder' button
- add missing "play recorded programme" button
- replace DialogFanart include with new DialogBackgroundImage include
- add new secondary parameter to time include
- remove deprecated dialogButtonBackground include

DialogSelect.xml:
- replace DialogFanart include with new DialogBackgroundImage include
- add new secondary parameter to time include
- remove deprecated dialogButtonBackground include

DialogSubtitles.xml:
- rework background overlay
- remove deprecated dialogButtonBackground include

DialogTextViewer.xml:
- replace DialogFanart include with new DialogBackgroundImage include
- add new secondary parameter to time include

DialogVideoInfo.xml:
- add new movie set poster image
- rework visibility conditions for new movie set information
- improved ratings and audio/subtitle streams information (add tracks.tv)
- replace DialogFanart include with new DialogBackgroundImage include
- add new secondary parameter to time include
- remove deprecated dialogButtonBackground include

EventLog.xml:
- replace WindowBackgroundImage include with new WindowBackgroundImageVertical include
- remove texturesliderbar from scrollbar

FileBrowser.xml:
- replace DialogFanart include with new DialogBackgroundImage include
- add new secondary parameter to time include
- remove deprecated dialogButtonBackground include

FileManager.xml:
- replace WindowBackgroundImage include with new WindowBackgroundImageHorizontalLow2 include

Home.xml:
- replace WindowBackgroundImage include with new WindowBackgroundImageVerticalHome include
- remove deprecated isHomeWindow paramter from time include
- add new narrow and wide parameters to time include

Includes.xml:
- rework DefaultView include for reworked video addons forced view skin setting
- add new coordinates includes for seperate Includes files
- rework onloads for reworked description/plot font size setting as well as for new skin design

Includes_Home.xml:
- restructure main list control and add missing viewtype label

Includes_MediaFlags.xml:
- rework MediaFlags include for new skin design (only one single position and improved conditional visibility)

Includes_Time_NowPlaying.xml:
- rework Time include for reworked window heading (two lines) as now playing controls (adapting to new width available with new skin design)

Includes_Widgets.xml:
- add widget heading animations to hide and show weather widget heading depending on availability of weather information

Includes_Windows_Dialogs.xml:
- rework WindowBackgroundImage and DialogBackgroundImage includes for new skin design
- remove deprecated dialogButtonBackground include

LoginScreen.xml:
- replace WindowBackgroundImage include with new WindowBackgroundImageVertical include

MusicOSD.xml:
- add new info button

MusicVisualisation.xml:
- rework look of default fullscreen music playback window to match general skin look
- rework fullscreen music playback to show additional album, artist and radio now/next/RDS information
- replace WindowBackgroundImage include with new WindowBackgroundImagePlain include

MyGames.xml:
- replace WindowBackgroundImage include with new WindowBackgroundImageMultiView include
- remove texturesliderbar from scrollbars

MyMusicNav.xml:
- replace WindowBackgroundImage include with new WindowBackgroundImageMultiView include
- remove texturesliderbar from scrollbars

MyMusicPlaylistEditor.xml:
- replace WindowBackgroundImage include with new WindowBackgroundImageHorizontalLow2 include
- adjust font size of details labels

MyPics.xml:
- replace WindowBackgroundImage include with new WindowBackgroundImageMultiView include
- remove texturesliderbar from scrollbar

MyPlaylist.xml:
- replace WindowBackgroundImage include with new WindowBackgroundImageVertical include
- remove texturesliderbar from scrollbar

MyPrograms.xml:
- replace WindowBackgroundImage include with new WindowBackgroundImageMultiView include
- remove texturesliderbar from scrollbars

MyPVRChannels.xml:
- replace WindowBackgroundImage include with new WindowBackgroundImageVertical include
- rework adjustable plot text boxes
- remove texturesliderbar from scrollbar
- adjust channel count font size

MyPVRGuide.xml:
- add channel sort by and sort order toggles (ID 3 and 4) to PVR guide side menu
- replace WindowBackgroundImage include with new WindowBackgroundImageHorizontalEPG include
- rework adjustable plot text boxes
- add missing channel count

MyVideoNav.xml:
- add hidden list for movie sets information
- replace WindowBackgroundImage include with new WindowBackgroundImageMultiView include
- remove texturesliderbar from scrollbars

MyWeather.xml:
- replace WindowBackgroundImage include with new WindowBackgroundImageHorizontalWeather include

script-skin_helper_service-ColorPicker.xml:
- replace DialogFanart include with new DialogBackgroundImage include
- add new secondary parameter to time include
- remove deprecated dialogButtonBackground include

script-skinshortcuts.xml:
- rework background overlay
- add new secondary parameter to time include
- add adjustable explanation text box
- remove deprecated button grouplist background

script-skinshortcuts-static.xml:
- hide weather widget when no weather information is available
- improve widget heading details
- remove My OSMC entry from default home menu layout
- adjust home menu entry numbering

Settings.xml:
- replace WindowBackgroundImage include with new WindowBackgroundImageVerticalHome include
- add new narrow and wide parameters to time include
- add new My OSMC settings entry

SettingsCategory.xml:
- replace WindowBackgroundImage include with new WindowBackgroundImageVerticalHome include
- add new narrow and wide parameters to time include
- add adjustable explanation text box
- rework settings level button
- add new My OSMC entry to settings navigation side menu

SettingsProfile.xml:
- replace WindowBackgroundImage include with new WindowBackgroundImageVerticalHome include
- add new narrow and wide parameters to time include
- add missing scrollbar
- add new My OSMC entry to settings navigation side menu

SettingsScreenCalibration.xml:
- replace WindowBackgroundImage include with new WindowBackgroundImagePlain include
- add missing time include

SettingsProfile.xml:
- replace WindowBackgroundImage include with new WindowBackgroundImageVerticalHome include
- add new narrow and wide parameters to time include
- add new My OSMC entry to settings navigation side menu

SkinSettings.xml:
- remove deprecated bigger music OSD album art setting
- add new custom focus control colour, custom non-focus control colour, custom OSD cache bar colour and custom masking colour settings
- change label2 of settings with multiple options to use variables
- let default colour set and default video addon view open a select dialog
- adjust automatically showing music OSD setting to match general skin setting formatting
- replace WindowBackgroundImage include with new WindowBackgroundImageVerticalHome include
- add new narrow and wide parameters to time include
- update Default color sets setting for new skin design
- remove deprecated Background color gradient setting
- add adjustable explanation text box

SmartPlaylistEditor.xml:
- replace DialogFanart include with new DialogBackgroundImage include
- add new secondary parameter to time include
- remove deprecated dialogButtonBackground include

SmartPlaylistRule.xml:
- replace DialogFanart include with new DialogBackgroundImage include
- add new secondary parameter to time include
- remove deprecated dialogButtonBackground include

Variables.xml:
- adjust MusicNextPlaying variables to avoid showing wrong information while shuffle is enabled during playback
- add new MusicNextPlayingLabel variables for reworked fullscreen music playback window
- rework label2 variable for new movie sets information and improved TV show details
- add new masking condition expressions
- move OSMCBackgroundOverlayName variable to skin settings variable file
- add new settingsbuttonunfocusdim variable for button hightlight dimming in settings window
- remove deprecated HeadingLabel variable
- add new HeadingLabelSecondary variable for reworked window heading (two lines)
- add new channel, timers and TV/radio search content types
- add new MediaFlagsDuration variable

Variables_Colours.xml:
- adjust colour variables to use new colour settings needed for skin setting select dialog feature
- use new colour setting label variables for colour name variables

Variables_SkinSettings.xml:
- remove SkinSettingsExplanation variable value of deprecated bigger music OSD album art setting
- change skin setting explanation variable localize formatting
- add new MaskingBars, DefaultColorSet, DefaultBackgroundOpacity, DefaultOverlayOpacity, OSMCBackgroundOverlay, HideOSD, PlotFont, infodialogfirstpage, videodurationformat, mediaflags and DefaultVideosView variables for reworked skin setting label2
- replace Dark green colour set by new Dark blue colour set
- adjust default opacity of background and overlay colours
- adjust overlay colours to match background colours

Variables_SkinSettings.xml:
- rework SkinSettingsExplanation variable after removing deprecated skin setting
- rework DefaultColorSet variable after adding replacing Dark green colour set by new Dark blue colour set

VideoFullScreen.xml:
- add new chapter and EDL markers
- rework adjustable plot text boxes

VideoOSD.xml:
- adjust controls onleft for new info button
- add onback to controls grouplists to close fullscreen info dialog when closing the video OSD
- add new info button to right controls

Viewtype511.xml:
- add conditional visibility of view icons for movie sets
- rework adjustable plot text boxes

Viewtype52.xml:
- add conditional visibility of view icons for movie sets

Viewtype521.xml:
- add conditional visibility of view icons for movie sets

Viewtype522.xml:
- add conditional visibility of view icons for movie sets
- rework adjustable plot text boxes

Viewtype525.xml:
- rework adjustable plot text boxes

Viewtype53.xml:
- add conditional visibility of view icons for movie sets
- adjust title font size for new skin design

Viewtype531.xml:
- add conditional visibility of view icons for movie sets
- rework adjustable plot text boxes

Viewtype532.xml:
- add conditional visibility of view icons for movie sets
- adjust title font size for new skin design

Viewtype533.xml:
- add conditional visibility of view icons for movie sets
- rework adjustable plot text boxes

Viewtype534.xml:
- add conditional visibility of view icons for movie sets
- adjust title font size for new skin design

Viewtype535.xml:
- adjust title font size for new skin design

Viewtype536.xml:
- rework adjustable plot text boxes

Viewtype537.xml:
- adjust title font size for new skin design

Viewtype538.xml:
- rework adjustable plot text boxes

Viewtype539.xml:
- adjust title font size for new skin design

addon.xml:
- bump version to 19.0.0
