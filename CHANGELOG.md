# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]
### Added
- #919 - Enabled bookmark synchronization
- #916 - Added the ability to save and delete bookmarks
- #356 - Added the ability to delete history
- #208 - Added normal browsing dark mode (advised to use attrs from now on for most referenced colors)
- #957 - Added telemetry for the context menu
- #1036 - Added telemetry for Find in Page
- #1049 - Added style for progress bar with gradient drawable
- #1165 - Added doorhanger to the toolbar
- #1002 - Added ability to restore tab after crash
- #1195 - Adds telemetry for quick action sheet
- #627 - Sets engine preferred color scheme based on light/dark theme
- #904 - Added tab counter in browser toolbar
- #1312 - Added the ability to edit bookmarks
- #1236 - Added the ability to create bookmark folders
- #1237 - Added the ability to delete bookmark folders
- #1238 - Added the ability to edit bookmark folders
- #1239 - Added the ability to move bookmark folders
- #1068 - Adds the ability to quickly copy the URL by long clicking the URLBar
- #1170: Allow user to add a new site exception to site permissions
- #1430 - Adds the Fenix Snackbar
- #1397 - Adds favicons to the history view
- #1375 - Added setting for turning off history suggestions
- #1139 - Resolved a 170ms delay on cold start
- #176 - Added a swipe to delete gesture on home screen
- #1539 - Added bookmarks multi-select related features
- #1603 - Remove deprecated success path for Firefox Accounts login
- #619 - Sets toolbar behavior based on accessibility and if session is loading
- #1571 - Added a snackbar for undoing bookmark deletion
- #1079 - Managing site permissions exceptions
- #1312 - Added clear textfield buttons for editing bookmarks
- #1312 - Added a missing edit action for bookmark selections
- #974 - Added telemetry for bookmarks
- #113 - Added QR code scanner
- #975 - Added telemetry for preference switches
- #1955 - Added a confirmation dialog for QR code and barcode searches
- #1874 - Added a "Turn on Sync" fragment for Firefox Accounts login and sign up
- #2308 - Update the deprecated BitmapDrawable constructor
- #1311 - Enable downloads in custom tabs.
- #1874 - Added TOP info panel dialog for custom tabs.
- #1411 - Added disabled style for disabled permissions items in site info panel.
- #1735 - Adds API to see the release channel
- #2318 - Added Firefox Accounts Pairing feature to "Turn On Sync" options
- #2390 - Adds Onboarding for Fenix
- #2531 - Adds link to privacy policy in settings

### Changed
- #1429 - Updated site permissions ui for MVP
- #1599 - Fixed a crash creating a bookmark for a custom tab
- #1414 - Fixed site permissions settings getting reset in Android 6.
- #1994 - Made app state persist better when rotating the screen
- #654 - Updated Refresh button to turn into Stop button while menu is open.
- [AC #2725](https://github.com/mozilla-mobile/android-components/issues/2725) Updated tracking protectionPolicy to [recommend](https://github.com/mozilla-mobile/android-components/blob/master/components/concept/engine/src/main/java/mozilla/components/concept/engine/EngineSession.kt#L156)
### Removed
