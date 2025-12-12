With OS 8.1, we've focused in on:

* Following through on OS 8 release goals
* Improving Support for Your Devices
* Addressing Your Feedback with over 1,100 issue reports fixed

To get elementary OS 8.1 now, head to elementary.io for the download

# Privacy, Security & Consent

* Secure Session is now the default session
* Secure Session provides a better experience for most people and supports a broader range of modern hardware features
* Password Authentication dialogs will dim the screen and prevent focus stealing in Secure Sessions

* You can fall back to the Classic Session if you still need it
* Resolved issues that prevented apps from starting when switching between Classic and Secure sessions

* New AppArmor profiles that resolve Flatpak sandbox issues—especially with Steam or running apps in a Guest session

# Multitasking & Window Management

* Brought back dock features that folks said they missed from Plank
* Multiple running dots for apps with multiple open windows
* Adjusted the color of running dots for apps on other workspaces
* cycle through open app windows when you hold a drag-n-drop over its app icon
* Pressure Reveal

* Support for the Background Portal

* Workspace switcher directly in the Dock
* Plus button to add new workspace
* Click workspaces to switch to them
* Drag-n-drop to rearrange workspaces
* Clicking on a workspace that’s already open shows the Multitasking View
* The Dock stays in the Multitasking View
* Launch apps from the Dock directly into the Multitasking View

* Shake animation when you try to open a new window on a single-window app with middle-click
* App launchers will register your clicks if your pointer is below the dock
* non-flatpak sideloaded apps that don't correctly match their launchers can now sometimes be matched by the Dock

* Option to enable Hotcorners while an app is fullscreened
* Applications Menu with Super while playing a fullscreen game, for example

# Getting The Apps You Need

* New AppCenter features to accommodate cross-platform apps from Flathub
* Percentage-based app ratings from https://odrs.gnome.org
* When developers provide screenshots for multiple platforms, we show the ones for elementary OS
* support for app addons
* show when a game supports playing with controllers
* revamped licensing information to make it easier to understand and with more details
* Support for "contribute" links

* Changed the label of the action button for free apps from "Free" to "Install"
* Label next to the action button for apps which contain in-app purchases

* Search is much faster and results will now show in two columns

# Staying Up to Date

* Streamlined updates code in AppCenter to make app updates faster and more reliable
* Installed apps are sorted by release date instead of alphabetically
* Recent releases for all installed apps
* Releases dialog got a redesign

* We show how large a system update will be before you download it
* There’s a progress bar while downloading
* We skip held-back packages—such as phased or staged updates

* The updates check has been rewritten to make sure it no longer runs in Demo Mode, only happens once daily, and won’t slow down your initial login
* No longer automatically download updates when on metered internet connections and send a notification instead
* There's an action to jump directly to the System Updates page from System Settings’ context menu in the Dock or Applications Menu or via search

# Designing for Inclusivity

* We believe that we succeed when we build open computing experiences that seek to be more inclusive
* We did another round of accessibility testing with Florian Beijers
* Installer has more accessible labels
* Password quality feedback in Installer and Initial Setup will be read aloud by the screen reader
* OS 8.1 can be installed and set up completely blind in most cases

* Also gathered feedback from Aaron Hewitt
* Notifications and the Shortcut Overlay both got screen reader support
* Improved screen reader support in Calendar, System Settings, AppCenter

* Improvements to keyboard navigation
* On the Lock Screen where we’ll automatically select the Classic session if accessibility features are used that don’t yet work in the Secure session
* Media keys—like volume keys and rockers—now work on the Lock Screen
* Main menus are now properly marked in most apps and can be opened with F10

* You can create custom keyboard shortcuts for apps, their actions, or execute custom commands
* System Settings will warn you if your desired keyboard shortcut conflicts with system shortcuts like "Copy", "Paste", or "New Tab"

* Dark Mode schedule snoozing. When you manually toggle Dark Mode while using a timed or sunset-to-sunrise schedule, your schedule will resume on the next schedule change instead of being canceled
* Dark Mode screenshots and brand colors in AppCenter when available
* The Lock Screen now supports Dark Mode

* Reduce Motion setting covers more animations across the desktop and in apps

* Increased text color contrast in Terminal
* Transparent elements like the Dock, Notifications, and Window Switcher all respect the "Panel Translucency" setting in System Settings
* display filters aren’t captured in screenshots

* A ton of translation updates! Special thanks to new Chinese localizers

# Improving Support for Your Devices

* Latest HWE from Ubuntu, including Linux 6.14 and Mesa 25
* improved performance—especially while gaming or moving files
* reduced power consumption for certain AMD and Intel chipsets and GPUs
* support for Intel "Lunar Lake" processors
* Support for more webcams, USB network devices, joysticks and gamepads, wifi devices, microphones, and more

* Fractional display scaling is now available in the Secure Session

* Resolved several reported issues with multi-monitor
* Installer is now always re-centered on screen, fixing issues with screen layouts that change while it’s loading—including with some virtual machines

* Open context menus in more places using a long-press gesture, like in the Dock
* Brand new Gesture Controller in our window manager which has enabled new features for multi-touch, like swiping up in Multitasking View to close windows
* Quick Settings shows a message when you turn on the onscreen keyboard in a Secure Session since it's currently only available in a Classic session

* Bluetooth Settings has been redesigned, while also improving keyboard navigation and screen reader support
* Fixed issues when a pairing request requires entering passcodes—like with some keyboards
* Fewer unnamed devices when discovering
* Enabling and disabling Bluetooth on devices that have been hardware locked should now work reliably
* Airplane Mode no longer disables Bluetooth or wired networks

* Fixed issues where the Installer would crash when doing custom installs with complex partitioning schemes

* Power menu shows the device model if available
* Power settings shows a warning about increased energy usage with certain options

# Addressing Your Feedback

* Successfully addressed over 1,100 filed issue reports since OS 8 released
* 72% bug fixes
* 18% new features
* 10% tech debt, engineering tasks, software quality, etc

* Blur-behind effect for translucent desktop elements like the Dock, Notifications, and the window switcher

* Locale settings has options aligned more cleanly and improved links to additional settings
* Screencast Portal has an improved design for selecting which display or window should be captured, as well as respecting options for capturing the pointer
* Encryption step of the Installer was redesigned to fit on a single page
* Picture-in-Picture windows now have rounded corners
* Notifications have rounder corners to match the Dock and their close animation now matches the associated swipe gesture

* Keyboard focus indicators will disappear when not being used

* Folder icons were redesigned by popular demand
* Icons featuring a computer mouse have been redesigned to include a scroll wheel
* Icons featuring a mouse pointer have been updated to match the new pointer design
* Fall back to Adwaita icons when an app is missing a non-standard icon name

## Notifications

* Deny access for apps to send notification bubbles in System Settings, even if they don't report notification usage
* Do a better job finding app icons for non-Flatpak sideloaded apps
* System Settings allows configuring its own notifications
* Improved the behavior of apps like Terminal to make sure we withdraw stale notifications
* Screenshot notifications open the Image Viewer when clicked and have an option to show the image in Files

## System Settings

* Two new Network settings: whether a network should be automatically connected to when available and whether to reduce background data usage when connected to that network
* Jump to System Settings when middle-clicking networking toggle buttons in the panel

* Sound menu fixed loading album art from certain apps like Google Chrome
* Quick Settings added a page where you can see which other people are logged in and quickly switch between accounts
* Prevent Sleep from Quick Settings

* Settings pages with sidebars remember the width you adjusted them to
* Added the phrase "about this device" as a search term for the System page
* Sync more of your settings—like panel transparency, orientation lock, and power settings—to the Lock Screen

## New Default Apps

* Shipped a System Monitor app, including with optional panel indicators

* Shipped Maps
* Explore and Transit maps, showing your current location, searching for locations
* Handling `geo://` uri links—features like opening a Calendar event’s location
* Application settings has a setting to select your default Maps app

## Updated Apps

* Music includes new features for managing the queue
* Queue and the last played track will be saved and restored when you open and close the app
* Remove individual tracks via their respective context menus or clear the entire queue
* Search the queue by track name
* Performance has been improved for large queues
* Album artwork will now show in media controls in the panel

* Files now supports the `admin://` uri protocol
* New file submenu now respects the hierarchy of folders in Templates
* Properties windows now show a more precise date and time for file modification and there’s a new setting for Date & Time format

* Code can now clone git repositories, switch to remote git branches, handle uncommitted changes when switching branches
* Symbols sidebar shows more information about Vala and C symbols in their tooltips
* Create edit marks by clicking in the source view gutter. Jumped between via the context menu or with the keyboard shortcuts
* Terminal pane now does a better job syncing with your Terminal app settings like Natural Copy/Paste

* Terminal uses the same tab bar widget as Web, Files, and Code
* Option to hide the tab bar when there’s only a single tab open
* expanded paste protection to cover the `doas` and commands that include options to skip confirmation
* improved detection of commands that contain newlines and react to drag-n-drop operations
* paste protection will now better warn you when a single paste contains multiple alarming elements
* option to disable paste protection

* GNOME Web brings improved performance and web compatibility as well as a redesigned bookmarks sidebar
