# Changelog
## 1.13.4 (64780) - 17/05/2023
* Improved management of triggers when the keyboard appears
* The backup files now include the name of the application
* Various bug fixes and improvements

## 1.13.3 (65752) - 15/05/2023
* New option:**Keep accessibility running** tries to restore the accessibility service if it is killed by the system (see **Required permission**)
* Better support for rooted devices
* Various bug fixes and improvements

## 1.13.2 (65300) - 03/05/2023
* Various bug fixes and improvements

## <a href="https://github.com/toneiv/UbikiTouch/milestone/47">1.13.1</a> (65200) - 27/04/2023
* Improved on-screen keyboard management<br>
* Improved screen rotation management<br>
* Improved display of available widgets<br>
* Various bug fixes and improvements<br>

## 1.13.0 (64770) - 17/04/2023
* New interface for adding and editing custom actions
* It is now possible to record custom actions of type "curve"
* Custom actions can now be represented by a cursor during their execution: this can be deactivated globally in **Custom action** / **Advanced settings** or individually for each action
* Support for the potential conflict with the tracker when a drag action is executed with Auto Cursor
* Redesign of animations
* New Action: **Turn off screen**
* Fixed bugs in the "Show left/right cursor" widget
* Fixed bugs in the "Temporarily disable triggers" actions
* Support for themed icons on Android 13

## <a href="https://github.com/toneiv/UbikiTouch/milestone/46">1.12.13</a> (62322) - 06/12/2022
* New Action: **Adjust Volume (System, Media, Notification, Ringtone or Alarm) with slider** (see **Media actions**)
* New Action: **Adjust Brightness with slider** (see **Actions**)
* Ability to set the thickness of a trigger to a minimum value of 5px
* Ability to set the amplitude of bottom menu for curve or wave to a maximum value of 25% of the length of the screen
* Improved management of trigger rotation
* Various bug fixes and improvements

## 1.12.12 (61354) - 14/09/2022
* Various bug fixes and improvements

## <a href="https://github.com/toneiv/UbikiTouch/milestone/45">1.12.11</a> (61332) - 12/09/2022
* Improvement of the paste function
* Clarification in the presentation of custom actions
* New Actions: **Temporarily disable triggers for 5, 10 or 30s**

## 1.12.10 (61278) - 01/07/2022
* Fix bugs with keyboard behavior

## 1.12.9 (61120) - 11/07/2022
* Vibration strength can now be adjusted up to 500ms
* Various bug fixes and improvements

## 1.12.8 (61103) - 06/07/2022
* Various bug fixes and improvements

## <a href="https://github.com/toneiv/UbikiTouch/milestone/44">1.12.7</a> (61012) - 27/06/2022
* New Action: **Toggle Flashlight** (Android Marshmallow and up)
* New Action: **Scroll backward** and **Scroll forward** : can be used for example to scroll through a web page
* Ability to set the shape of the trigger (rectangle, rectangle with round corners, line) (see **Trigger look**)
* Ability to set the strength and colour of the halo for the sub-menu and the selected menu (see **Pie/Curve/Wave menu** / **Menu appearance**)
* Ability to set the strength and colour of the halo for different state of the tracker (see **Auto Cursor** / **Color**)
* Ability to use an intent to activate/deactivate the trigger of your choice (see **https://ubikitouch.toneiv.eu/faq** / **Intent/Tasker**)
* Ability to export and import a zip containing preferences and actions (see **Misc** / **Backup & restore**)

## 1.12.6 (60524) - 30/05/2022
* Various bug fixes and improvements

## 1.12.5 (60513) - 25/05/2022
* Various bug fixes and improvements

## 1.12.4 (60408) - 16/05/2022
* AutoCursor animations improvement
* Removal of separate services for the menu and custom actions
* Memory footprint and performance improvements
* Fixed: minor bug when recording custom actions

## 1.12.3 (60371) - 11/05/2022
* AutoCursor animations improvement
* Removal of separate services for the menu and custom actions
* Memory footprint and performance improvements

## 1.12.2 (59611) - 27/04/2022
* Performance improvements

## 1.12.1 (59540) - 25/04/2022
* Various bug fixes and improvements

## <a href="https://github.com/toneiv/UbikiTouch/milestone/43">1.12.0</a> (59528) - 08/04/2022
* New: auto click with pointer on first release after swipe (see **Auto Cursor** / **Behaviour** / **Auto click**)
* New: auto click with pointer after each move (see **Auto Cursor** / **Behaviour** / **Auto click**)
* New: possibility to adjust color of the tracker when auto click is on (See **Auto Cursor** / **Colors** / **Tracker auto-click color and transparency**)
* New: menu available on the tracker with following actions : copy text, toggle auto-click, close (See **Auto Cursor** / **Behaviour** / **Action on long click**, **Action on double click**, **Action when clicking outside while pressing the tracker**)
* New: **Copy text** action available through the tracker menu
* New: improved performance of the recent applications menu
* New: improved memory footprint of the application
* Fixed: bad behaviour of the Toggle Auto-rotate action
* Various bug fixes and improvements

## 1.11.5 (58472) - 10/03/2022
* Fixed: improved compatibility with native Android navigation gestures
* Various bug fixes and improvements

## 1.11.4 (58410) - 27/02/2022
* Fixed: while using the cursor, on some devices, a significant delay could be observed when clicking on the tracker
* Various bug fixes and improvements

## 1.11.3 (58368) - 31/01/2022
* Fixed: a shift when manipulating the cursor could appear on some devices

## 1.11.2 (58329) - 15/01/2022
* Fixed : ability to define launcher in blacklist list
* Fixed : UbikiTouch now works on more system screens
* New: Ability to specify the location of the cursor on the screen when using the "Show left/right cursor" shortcut (see https://ubikitouch.toneiv.eu/faq.html#intent02)

## <a href="https://github.com/toneiv/UbikiTouch/milestone/42">1.11.1</a> (58245) - 16/12/2021
* New: **Recent applications menu** position : the position of the menu on the screen is now configurable (see **Recent Apps** / **Size and appearance**)
* New: Action/application/shortcut selection screens are now filterable
* Various bug fixes and improvements<br>

## <a href="https://github.com/toneiv/UbikiTouch/milestone/41">1.11.0</a> (58092) - 08/12/2021
* New: **Recent applications action** available: including the ability to set sound and vibration on click and long click, the ability to set a blacklist (application not to be displayed in the recent menu) as well as the ability to customise columns, rows and icon size
* New: vibration and sound can be set for trigger (see **Misc** / **Trigger sound and vibration**)
* New: vibration and sound can be set for menu (see **Misc** / **Menu sound and vibration**)
* New: vibration and sound can be set for cursor (see **Auto Cursor** / **Cursor sound and vibration**)

## 1.10.10 (56994) - 25/11/2021
* New: **Previous App** action can now be used instead of **Previous App Native** action
* New: Added information to fix the bug affecting the tab group view in **Google Chrome**: this is an option available in **Chrome** when an application uses the accessibility service (see in **Google Chrome** **Settings** / **Accessibility** / Uncheck **Simplified view for open tabs**)
* New: **Round corner on trigger** option : it is now possible to enable or disable this option. Disabling this option may address possible transparency issues on some devices. (see **Trigger** / **Trigger look**

## 1.10.9 (56217) - 16/10/2021
* Update **Google Play Billing Library** to 4.0.0

## <a href="https://github.com/toneiv/UbikiTouch/milestone/40">1.10.8</a> (56007) - 11/10/2021
* Update **Target API level 30 (Android 11)**
* New: possibility to fix delay for the **Previous App Native** action (see **Choose Action** / **Actions** / **Previous App Native** then long click)
* New: **Fixed: top of the screen** option for **Vertical reference point** (see **Auto Cursor** / **Behaviour**)
* New: Option to temporarily turn off gestures when keyboard is showing (see **Misc** / **Keyboard Behaviour**)
* New: Option to show the nav bar when keyboard is showing (see **Misc** / **Keyboard Behaviour**)
* Fixed: backup and restore does not work for the fourth gesture set in the pro version

## <a href="https://github.com/toneiv/UbikiTouch/milestone/39">1.10.7 (55740)</a> - 01/07/2021
* New: possibility to reduce the long click delay of the cursor to 250 ms

## 1.10.6 (55722) - 29/04/2021
* Fixed: bug affecting icon color and transparency

## 1.10.5 (55689) - 28/04/2021
* Fixed: random crash when accessing custom actions screen
* Fixed: compatibility issue with backup and restore on Android 11
* Various bug fixes and improvements

## 1.10.4 (55608) - 22/03/2021
* New: possibility to add a feedback message to a custom text action (see Custom Action  / Action / Edit)
* Various bug fixes and improvements

## 1.10.3 (54429) - 11/03/2021
* Improved "click & drag" functionality of the cursor
* Various bug fixes and improvements

## <a href="https://github.com/toneiv/UbikiTouch/milestone/38">1.10.2 (54246)</a> - 10/03/2021
* New: possibility to customize angle for each menu item (see Trigger / Menu actions)
* New: possibility to add a glowing halo effect on menu and/or tracker
* Improvement in movement detection on triggers
* Fixed: paste function should now work on Samsung Android 11
* Various bug fixes and improvements

## <a href="https://github.com/toneiv/UbikiTouch/milestone/37">1.10.1 (51102)</a> - 17/02/2021
* New: possibility to add several independent triggers
* New: possibility to assign click and/or long click action on triggers
* New: new cursor menu available
* New: simplified interface for positioning triggers
* New: possibility to choose delay for long click activation on the cursor
* New: Hungarian translation thanks to István Kriskó
* Memory footprint improvements
* Performance improvements
* Various bug fixes and improvements
* Improvement in click, long click and drag detection with cursor
* Fixed: missing translations available again

## <a href="https://github.com/toneiv/UbikiTouch/milestone/36">1.9.5 (45288)</a> - 08/01/2021
* New:  possibility to choose action on cursor long click (none, long click, click, remove cursor)
* New:  possibility to choose action on cursor long click and drag (none, drag)
* New:  possibility to choose color for the cursor
* New : accessibility service for custom actions is no longer started automatically
* Various bug fixes and improvements

## <a href="https://github.com/toneiv/UbikiTouch/milestone/35">1.9.4 (44946)</a> - 02/01/2021
* New : sound feedback can be added for click and/or long click on the menus (see Misc settings)
* New : triggers can be set to remain in portrait mode position (see Misc settings)
* New : triggers can be set to appear only in portrait or lanscape mode (see Misc settings)
* Improvement in custom actions recording process
* Improvement of pie ui fluidity
* Various bug fixes and improvements

## 1.9.3 (40302) - 09/12/2020
* New: cursor can be set to have no delay and thus remain on the screen until it is manually removed
* New: experimental semi-automatic method for granting \"Write Secure Settings\" permission via ADB using the WebADB API. See https://ubikitouch.toneiv.eu/adb in your browser.
* Improvement of the explanation tutorial to activate ADB

## 1.9.2 (39621) - 05/12/2020
* Fixed: crash in tuto screen for 4.4. android version

## 1.9.1 (39603) - 04/12/2020
* Various bug fixes and improvements

## 1.9.0 (39432) - 02/12/2020
* Fixed: UbikiTouch menu is available again in settings screen in Android 10
* Overall efficiency and fluidity improvement
* Various bug fixes and improvements

## 1.8.1 (36480) - 20/11/2020
* Fixed : bug in the record process of swipe<br>
* Various bug fixes and improvements

## 1.8.0 (36108) - 19/11/2020
* New: option to remove the cursor by flinging it on any side of the screen (see Cursor options)
* New: navigation drawer
* Enhancement of interface lisibility
* Various bug fixes and improvements

## 1.7.16 (34101) - 10/11/2020
* New: option to choose animation on tracker click
* Fixed: screenshots taken with the application could sometimes include the UbikiTouch menu
* Various bug fixes and improvements

## 1.7.15 (33873) - 05/11/2020
* New: improvement in custom actions management screen
* Various bug fixes and improvements

## 1.7.14 (33312) - 27/10/2020
* New: option to add a delay before executing a custom action (see Custom Action / Edit / Waiting time before executing action)
* New: option to hide "UbikiTouch is displaying over other apps" persistent notification (see Misc settings)
* Fixed: compatibility with latest Google Review API
* Fixed: error with classic and modern cursor icon in Android 4.4
* Various bug fixes and improvements

## 1.7.13 (32496) - 07/10/2020
* Various bug fixes and improvements

## 1.7.12 (32493) - 30/09/2020
* New: improvement in compatibility with Android 11
* Various bug fixes and improvements

## 1.7.11 (31830) - 02/09/2020
* Fixed: increased blacklist compatibility (especially with games)

## 1.7.10 (31476) - 01/09/2020
* New: interface enhancements
* Various bug fixes and improvements

## 1.7.9 (31086) - 28/08/2020
* Fixed: unexpected crash in tutorial screens for Android 4.4

## 1.7.8 (30789) - 26/08/2020
* Fixed: on some devices, the purchase service for the Pro version was not working properly

## 1.7.7 (30501) - 24/08/2020
* Various bug fixes and improvements

## 1.7.6 (30468) - 09/08/2020
* Various bug fixes and improvements

## 1.7.5 (30402) - 08/08/2020
* New: improvement in compatibility with future Android 11
* Various bug fixes and improvements

## 1.7.4 (30210) - 06/08/2020
* New: option to choose size of the cursor
* New: option to choose shape of the cursor
* New: option to choose animation on cursor click
* New: live update of cursor and tracker when editing options
* Various bug fixes and improvements

## 1.7.3 (29292) - 28/07/2020
* New: ability to remove 250ms delay on click for the cursor (when No Action on Double click is selected)
* Various bug fixes and improvements

## 1.7.2 (29148) - 27/07/2020
* Various bug fixes and improvements

## 1.7.1 (29121) - 23/07/2020
* Fixed: curve menu did not disappear completely at rest

## 1.7.0 (29061) - 21/07/2020
* Enhancement of menus fluidity and response time
* New:  ability to specify curve shape: follow the touch or static (see Wave/Curve settings / Animation)
* Various bug fixes and improvements

## <a href="https://github.com/toneiv/UbikiTouch/milestone/33?closed=1"> 1.6.0 (26244)</a> - 06/07/2020
* New:  ability to duplicate settings from one side to another (see Trigger / Template)
* New : ability to define action on double click on the tracker
* New : ability to define action on click outside the tracker
* New : ability to define action when clicking outside while pressing the tracker
* New : ability to define a vertical dynamic reference point for the tracker (see Cursor / Vartical reference point)
* Fixed: the cursor launched with shortcuts did not always reach the side
* Fixed: the cursor launched with shortcuts wasn\'t set properly on landcape mode

## 1.5.3 (25377) - 01/07/2020
* New:  min delay for disapperance of cursor set to 200ms
* New: 2 shortcuts, show cursor left and show cursor right

## <a href="https://github.com/toneiv/UbikiTouch/milestone/32?closed=1"> 1.5.2 (24852)</a> - 29/06/2020
* New:  possibility to choose the style for the tracker countdown
* New:  ability to precisely position the triggers as a percentage of the screen
* New:  live update of the trigger when changing its settings
* Fixed: enhanced precision when dragging the cursor
* Fixed: prevents accidental clicks when dragging the cursor
* Fixed: menu was not displayed correctly on Android 8.0

## 1.5.1 (24204) - 25/06/2020
* Fixed: the cursor did not display correctly in landscape mode

## <a href="https://github.com/toneiv/UbikiTouch/milestone/31?closed=1"> 1.5.0 (24183)</a> - 23/06/2020
* New: possibility to choose the sensitivity to cursor movement
* New: possibility to display the menu even if only one submenu is defined
* New: UbikiTouch is available when Quick Settings is displayed
* Overall efficiency and fluidity improvement

## 1.4.11 (23316) - 18/06/2020
* New: improved cursor drag functionality: ability to perform complex move
* New: animation when performing drag or move
* Fixed: cursor will not interact with triggers or tracker while moving
* Fixed: cursor stopped working unexpectedly with some devices
* Various bug fixes and improvements

## 1.4.10 (22617) - 14/06/2020
* Fixed: small bug with cursor trail

## 1.4.9 (22575) - 14/06/2020
* New: improve cursor trail fluidity
* New: add cursor trail effect
* New: cursor now available for Android Versions lower than Nougat (24)
* Fixed: less intrusive popup warning for Huawei devicess

## 1.4.8 (20943) - 08/06/2020
* New: cursor compatibility mode to improve its operation with some versions of Android
* Fixed: the tracker was not correctly drawn when changing dimensions

## 1.4.7 (20412) - 02/06/2020
* New: cursor is now available in free version with limited features
* Fixed: add Google Pay exception

## <a href="https://github.com/toneiv/UbikiTouch/milestone/30?closed=1">1.4.6 (19740)</a> - 26/05/2020
* New: 3s countdown in the tracker before disappearance
* New: trail effect on cursor
* New: option to disable trail effect on cursor
* New: option to show icon in the menu to access keyboard options when keyboard shows up
* New: tips and news to showcase features of the app
* Fixed: remote cursor set as default action was not working
* Fixed: improved management of long press in cursor

## 1.4.5 (17298) - 09/05/2020
* New: improved management of accessibility permissions activation
* Fixed: edge transparency on Android 5.0
* Various bug fixes and improvements

## 1.4.4 (16797) - 27/04/2020
* New: improved movement of the remote cursor to reach the sides more easily
* New: ability to make long clicks with remote cursor
* New: ability to make drag with remote cursor
* New: ability to cancel long click or drag by clicking with another finger outside of the tracker for remote cursor
* New: ability to close remote cursor by double clicking tracker
* New: ability to choose color for click and long click for remote cursor
* New: round corner for triggers
* New: improved management of icons color and transparency in menus
* Fixed: rare crash while creating db

## 1.4.2 (16543) - 22/04/2020
* Fixed: second action swipe and hold was not working correctly

## <a href="https://github.com/toneiv/UbikiTouch/milestone/29?closed=1"> 1.4.1 (16525)</a> - 21/04/2020
* New: adjustable cursor size
* New: visualization of triggers while modifying their appearance
* New: option to immediately trigger the second action when the waiting time is reached
* New: improved Italian translation thanks to Andrea Bruzzesi &lt;andrea.bruzzesi@gmail.com&gt;
* Fixed: bug with remote cursor & auto-trigger
* Fixed: bug with pie ui and cursor behaviour

## 1.4.0 (16407) - 15/04/2020
* New: action "Remote cursor"
* Fixed: bug in tutorial

## 1.3.6 (15993) - 04/04/2020
* Various bug fixes and improvements

## <a href="https://github.com/toneiv/UbikiTouch/milestone/28?closed=1"> 1.3.5 (15945)</a> - 30/03/2020
* Fixed: under certain conditions, the Pie menu was not correctly released after use
* Various bug fixes and improvements

## <a href="https://github.com/toneiv/UbikiTouch/milestone/27?closed=1"> 1.3.4 (15842)</a> - 24/03/2020
* New: online FAQ available in Help Screen
* Various bug fixes and improvements

## <a href="https://github.com/toneiv/UbikiTouch/milestone/26?closed=1"> 1.3.3 (15121)</a> - 21/03/2020
* Fixed: launch action based on distance functionality was broken for some configurations
* Fixed: improved ui to enable/disable some permissions
* Fixed: improved ui when using slider
* Fixed: UbikiTouch now work in Android Setting
* Fixed: media actions for Generic Music Player fixed, they work now for all players
* Fixed: inconsistency in min value for drag tension in animation settings

## <a href="https://github.com/toneiv/UbikiTouch/milestone/25?closed=1"> 1.3.1 (15121)</a> - 12/02/2020
* Fixed: incorrectly displayed message "this feature is not supported" for some actions
* Fixed: app unexpectedly getting killed in the background with some Samsung devices
* Fixed: stronger tile management
* New: 4 actions instead of 3 configurable in menus

## <a href="https://github.com/toneiv/UbikiTouch/milestone/24?closed=1"> 1.3.0 (15062)</a> - 04/02/2020
* Fixed: with some devices, the application did not start at boot time even though it was configured for
* Fixed: with some devices, the service was unexpectedly killed when leaving the application
* Fixed: under certain conditions, the application hid the navigation bar when the device woke up while the current application was blacklisted
* Fixed: broken shortcuts icons
* Fixed: actions type (up, down, left, right, click...) wasn\'t properly ordered in treeview display
* Fixed: stronger tile management
* Fixed: stronger custom actions list management in settings
* New: 2 shortcuts, start and stop UbikiTouch
* New: Root implementation for managing permissions
* Various bug fixes and improvements

## <a href="https://github.com/toneiv/UbikiTouch/milestone/23?closed=1"> 1.2.6 (14704)</a> - 08/01/2020
* Fixed: fixed an error preventing to export the bin file of the actions
* Fixed: the triggers were sometimes inaccessible in immersive mode with the hidden navbar, now all triggers are available when using applications such as YouTube, Netflix, …
* Fixed: under rare conditions, the navigation bar could be erroneously hidden when the screen is switched on
* Fixed: under rare conditions, the menu icons were not correctly removed when the screen was rotated
* Fixed: pulse animations on the settings screen will disappear after a few days
* Various bug fixes and improvements

## 1.2.5 (13961) - 12/12/2019
* Fixed: rare crash on tuto screens
* Fixed: on some smartphone models the application would not restart after a reboot
* Various bug fixes and improvements

## 1.2.4 (13941) - 04/12/2019
* New: restore option in blacklisted app management
* New: Persian/Farsi translation thanks to Amin Shabanpour
* Fixed: rare exception while switching foreground app

## 1.2.3 (13781) - 06/11/2019
* Fixed: crash when opening settings for bottom curve size
* New: improvement in blacklisted app management

## 1.2.2 (13723) - 01/11/2019
* Fixed: Auto-triggering left and right wasn\'t properly disabled

## 1.2.1 (13720) - 31/10/2019
* Fixed: crash during fresh installation

## <a href="https://github.com/toneiv/UbikiTouch/milestone/22?closed=1"> 1.2.0 (13667)</a> - 31/10/2019
* New: detection of clicks on the trigger zone and propagation to the elements below
* New: option to block physical buttons
* New: configurable distance for the visibility of the secondary action
* New: configurable waiting time for the visibility of the secondary action
* New: add search in preferences
* New: ui redesign
* Updated ui with latest Material specification
* Fixed: lowered auto-trigger threshold

## <a href="https://github.com/toneiv/UbikiTouch/milestone/21?closed=1"> 1.0.0 (12541)</a> - 08/10/2019
* Improved stability and performances
* New: option to vibrate on short press
* New: option to show unselected waves in Wave Ui
* New: option to choose type of action : click, long click, swipe top, swipe bottom, swipe left, swipe right
* New: option to record a swipe
* New: option to edit actions to change type (click, long click, swipe), duration or coordinates
* New: option to copy action as child or sibling

## <a href="https://github.com/toneiv/UbikiTouch/milestone/20?closed=1"> 0.9.18 (12179)</a> - 05/09/2019
* New: wildcards can be used in actions to identify resources (edit icon on text action)
* New: shortcuts to show/hide Navigation Bar
* New: option to show navbar when current app is in blacklist
* Fixed: rare exception while updating menu view
* Fixed: UbikiTouch enables itself while switching rotation
* Various bug fixes and improvements

## <a href="https://github.com/toneiv/UbikiTouch/milestone/19?closed=1"> 0.9.17 (12037)</a> - 03/08/2019
* Fixed: height of bottom menu was not correctly calculated after toggling navbar

## <a href="https://github.com/toneiv/UbikiTouch/milestone/18?closed=1"> 0.9.16 (12031)</a> - 03/08/2019
* Fixed: bug in intro with Chinese translation
* New: shortcut to toggle navbar

## <a href="https://github.com/toneiv/UbikiTouch/milestone/17?closed=1"> 0.9.15 (12012)</a> - 02/08/2019
* Fixed: bottom trigger was not disabled on certains circonstances
* Fixed: rare exception while updating trigger view
* New: ability to define custom icon for each action (from a pack or from your device)
* New: ability to define color of icons for each trigger
* New: ability to copy the menu from right to left and vice versa
* New: tile to hide/show navbar
* New: Chinese translation thanks to Ein Verne &lt;i@einverne.info&gt;

## <a href="https://github.com/toneiv/UbikiTouch/milestone/16?closed=1"> 0.9.14 (11787)</a> - 18/07/2019
* Fixed: shortcut actions was not correctly saved
* New: ability to define default action for each application

## <a href="https://github.com/toneiv/UbikiTouch/milestone/15?closed=1"> 0.9.13 (11718)</a> - 10/07/2019
* Fixed: rare crash with Pie Menu
* Fixed: some devices recognized as emulator

## <a href="https://github.com/toneiv/UbikiTouch/milestone/14?closed=1"> 0.9.12 (11715)</a> - 08/07/2019
* Fixed: Actions were deleted when importing settings
* Various bug fixes

## <a href="https://github.com/toneiv/UbikiTouch/milestone/13?closed=1"> 0.9.11 (11710)</a> - 06/07/2019
* Fixed: "prevent bottom keyboard conflicts" could not be disabled

## <a href="https://github.com/toneiv/UbikiTouch/milestone/12?closed=1"> 0.9.10 (11692)</a> - 01/07/2019
* New: presets available to define triggers and menu in one click
* New: ability to choose the menu origin point: contact point, screen center or trigger center
* New: separate options for left, right and bottom triggers
* New: triggering chosen action when the finger reaches the swipe length set without lifting the finger. Warning, this will not work with a "Coordinate action", in this case the action is only triggered when the finger is lift.
* New: option to keep bottom trigger active with keyboard
* New: option to follow system vibration pattern
* New: paste clipboard action
* New: navigation bar is automatically restore if needed on lock screen
* Improvement: better management in navigation bar
* Improvement: better management of the triggering of side actions when the finger is close to the edge for the bottom trigger
* Ukrainian translation thanks to Alex Bass <zokibada@gmail.com>
* Fixed: trigger area appeared for a short period of time on restart although autostart is disabled
* Various bug fixes

## <a href="https://github.com/toneiv/UbikiTouch/milestone/11?closed=1"> 0.9.7 (10864)</a> - 14/06/2019
* Fixed: rare exception when trigger area is moved with keyboard

## <a href="https://github.com/toneiv/UbikiTouch/milestone/10?closed=1"> 0.9.6 (10859)</a> - 13/06/2019
* Fixed: trigger area length getting increased when keyboard is opened
* Fixed: russian translation not recognized

## <a href="https://github.com/toneiv/UbikiTouch/milestone/9?closed=1"> 0.9.5 (10827)</a> - 13/06/2019
* Russian translation thanks to Игорь Иринин <vinodel73@gmail.com>

## <a href="https://github.com/toneiv/UbikiTouch/milestone/8?closed=1"> 0.9.4 (10803)</a> - 12/06/2019
* "Recent apps" fixed to be faster
* Added shortcuts to make automation functions accessible to third-party applications 
* Various corrections in translations
* Fixed for "Protected Apps" setting on Huawei phones
* Various bug fixes

## <a href="https://github.com/toneiv/UbikiTouch/milestone/7?closed=1"> 0.9.3 (10716)</a> - 07/06/2019
* Fixed for rare crash in "Wave menu"
* Fixed for rare crash while saving data in db
* Various bug fixes

## <a href="https://github.com/toneiv/UbikiTouch/milestone/6?closed=1"> 0.9.2 (10645)</a> - 03/06/2019
* Default edge height ratio change from 80% to 60% to avoid faulty interaction with keyboard
* Improved configuration and management of night mode

## <a href="https://github.com/toneiv/UbikiTouch/milestone/5?closed=1"> 0.9.1 (10607)</a> - 31/05/2019
* New Action: Lock screen (Android Pie and up)
* New Action: Take screenshot (Android Pie and up)

## <a href="https://github.com/toneiv/UbikiTouch/milestone/4?closed=1"> 0.9.0 (10592)</a> - 28/05/2019
* New Toggle Action: Auto brightness on off
* New Media Action: Open volume dialogue

## <a href="https://github.com/toneiv/UbikiTouch/milestone/3?closed=1"> 0.8.6 (10575)</a> - 20/05/2019
* Bug fixes for Oppo and Huawei in System Manager access
* Corrected tablet device compatibility
* Edited home icon
* Various bug fixes

## <a href="https://github.com/toneiv/UbikiTouch/milestone/2?closed=1"> 0.8.5 (10550)</a> - 17/05/2019
* Back button added to the tutorial
* More explicit transparency settings
* Gestures now works in Settings app
* Quick Settings added

## <a href="https://github.com/toneiv/UbikiTouch/milestone/1?closed=1"> 0.8.4 (10507)</a> - 13/05/2019
* Options availability in the free version
* Bug fixes and performance improvements

## 0.8.3 - 06/05/2019
* First open beta version
