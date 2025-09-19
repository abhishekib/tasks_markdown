# <ins>**`Task Plans`**</ins>

## `Amarkosh Flutter App`

- Deploy this app setup with iPad , iPhone & MacOS all platforms.

#

## `Mafatiuljinan [Personal account for apple]`

- Upload in IOS.
- add iPad target for building.

#

## `Royal Calender [Migration from React-native to Flutter]`

- Further follow up with Calender integration and modification.
- add hijri date to the calender items.

#

## `Good Channel [ Chittadeep | Akshat ] [Personal account for apple]`

- Coordinate with Chittadeep and Akashat if there any help needed.

#

## `LDAS [ Anit | Abhishek ]`

- Meeting today.

#

## `Lawyyar [Buisness account for apple] [Kousik] [ Priorify ]`

- Memory Page sizing. [22-09-2025]

#

## `Yaad Plug`

- Further Handling is done by chittadeep.

#

## `New Ecommerce App [ Flutter Flow ] [PerSense Client]`

- Start New Project

#

## `Soom.net [Chittadeep | Kausik] [Personal account for apple]`

- Currently no changes till client's requirement.

#

## `RxRemainder [ Kausik ] [Personal account for apple]`

- ~~App must support 16 KB memory page sizes~~

#

## `Messaging app [emergostat] [ Kausik ] [Personal account for apple]`

- App must support 16 KB memory page sizes fix it

#

## ~~`StepWhere [Chittadeep | Kausik] [Personal account for apple]`~~

~~- Paused.~~

<!-- ---
- fix audio issue when going to next post.
- fix audio is not pausing when we switch to next post.
- when we go to next post the audio doesn't play
- add feature when user click on the item it will go to particular index.
- add favourite icon state. - will be handled by chittadeep
- favourite deletion app for existing installed application - will be handled by chittadeep
- refresh favourite icon and when going in screen.
- add favourite icon at the appbar.
- add remainder option for `Amaal`.
- fix remainder audio not highlighting lyrics.
- check for External url deeplink navigation after manish implimentation.

---

- fix arabic highlighting issue for local text search.
- In gujarati text is not properly wrapped fix that issue.
- next post category show category
- Insert home icon
- Fix bookmark .
- `only show arabic` switch in the tab bar of lyrics.
- if there is only one data present in the tab data then highlight that data.
- add deeplinking api in search

---

- Check for bouncing issue in ios when lyrics auto scroll is initialized only in IOS.
- add scroll bar for scrolling across the list - New 04-06-2025
- search on lyrics and when tap on it, it will scroll to that index - Done
- continue with Bookmark Api integration
- remainder api integration.
-

#

### Less Proprity

- One time Remainder Notification.
- Check if we can scroll to the place where the audio was playing and the lyrics is visible
- namaz time remainder [link](https://chat.deepseek.com/a/chat/s/762cb4ab-0711-4a67-ab44-06b8c20383de)
- Update Remainder handling and UI update accordingly
- Add youtube screen above the about us page and apply player to show youtube shorts. [Link](https://www.youtube.com/@azadarmedia12/shorts)
- Json based local data migration
- local Notification tune addition. -->

---

<br>
<br>
<br>

---

Date: **18-09-2025**\
Project: **Mafatihuljinan Hybrid App**\
Dev Name: **Abhishek Kumar**\
Status: **Ongoing**

**Project report:**

- Replace `bookmarks()` calls with `bookmarks.value =` assignments to properly update the observable list in BookmarkController
- Add explicit bookmark list updates after login success in LoginController for Google, Apple, and standard login flows
- Refactor BookmarkProvider sync logic to clear existing bookmarks and add fresh data from server instead of merging with local data
- Remove obsolete code that extracted Realm object data before operations
- Improve data consistency during bookmark synchronization between local and remote sources
- add ReminderController dependency to category detail and login controllers
- replace direct LocalNotificationServices calls with reminder controller methods
- implement reminder fetching and syncing during user login flows
- update bookmarks and reminders lists after successful login
- support both online and offline reminder synchronization
- updated Prayer time Base url , Route and Parsing Methods.
- Support both 'post_id' and 'postid' fields for postId extraction
- Create Category directly from API data instead of searching local DB
- Save API data to local database to avoid future searches
- Fix concurrent modification errors by copying reminder lists before deletion
- Convert ReminderView to StatefulWidget for refresh functionality
- Add refresh button with loading indicator in app bar
- Prevent concurrent modification errors during reminder deletion

**Github**: [**Link**](https://github.com/IBArtsTech/Mafatihuljinan_Revamp)\
**Reyflow**: [Link](https://reyflow.com/ib-tech/browse/FLUTT-1/)\
**DOC Sheet:** [**Link**](https://docs.google.com/spreadsheets/d/1-v-_y38vYsRMK5h60Kvaj7t0Er4dlFJnl1Eg0d04Yo8/edit?gid=0#gid=0)\
**Application Build**: [Link](https://project.ibartstech.com/Parvez/Mafa/Mafatihuljinan-18-09-2025.apk)\
**Credentials**:\
**\-** **userid:** **allworkdone** || [**allworkdone27@gmail.com**](mailto:allworkdone27@gmail.com)
**\- password**: **1234**

---

Date: **18-09-2025**\
Project: **Royal Calender Flutter**\
Dev Name: **Abhishek Kumar**\
Status: **Ongoing**

**Project report:**

- replace Mobkit Calendar with Syncfusion Calendar for improved functionality
- update calendar appearance with custom header, navigation arrows, and date styling
- integrate support for the current day highlighting and rounded date corners
- remove unused dependencies: dbus, geoclue, and others
- add new dependencies: syncfusion_flutter_calendar, syncfusion_localizations
- downgrade geolocator and update intl for compatibility
- bump Flutter SDK version to 3.35.1 for enhanced features and fixes

**Github**: [**Link**](https://github.com/IBArtsTech/RoyalCalendarFlutter)\
**Reyflow**: [Link](https://www.reyflow.com/ib-tech/browse/FLUTT-36/)\
**Application Build**: [NA]<!-- (https://project.ibartstech.com/Parvez/RoyalCalendar/RoyalCalender-17-09-2025.apk) -->

---

Date: **18-09-2025**\
Project: **RxRemainder Flutter**\
Dev Name: **Abhishek Kumar**\
Status: **Ongoing**

**Project report:**

- Update compileSdk and targetSdk to 35
- Upgrade sqflite dependency from 2.3.0 to 2.4.1
- Configure database for 16KB page size compatibility with PRAGMA settings
- Set journal mode to WAL and synchronous mode to NORMAL for better performance
- Enable NDK version in app/build.gradle
- Update Android application plugin version from 8.5.0 to 8.6.0
- Fix TabBarTheme usage in light_theme.dart
- Update multiple package versions in pubspec.lock including characters, clock, collection, fake_async, flutter_ringtone_player, and leak_tracker dependencies
- Update app version from 1.0.15+15 to 1.0.16+19

**Github**: [**Link**](https://github.com/IBArtsTech/RxReminderFlutter)\
**Reyflow**: [Link](https://www.reyflow.com/ib-tech/browse/FLUTT-37/)\
**screenShot**: [Link](https://prnt.sc/jCWHminiK-13)

---

Date: **16-09-2025**\
Project: **LDAS Flutter**\
Dev Name: **Abhishek Kumar**\
Status: **Ongoing**

**Project report:**

- uploaded project to github with module configuration.
- **Github**: [**Link**](https://github.com/abhishekib/here_sdk.git) || [link](https://github.com/abhishekib/LDAS_Flutter)\
  **Reyflow**: [Link](https://www.reyflow.com/ib-tech/browse/FLUTT-17/)\

  ***

Date: **27-08-2025**\
Project: **Zoku React Native**\
Dev Name: **Abhishek Kumar**\
Status: **Ongoing**

**Project report:**

- g

**Github**: [**Link**](https://github.com/IBArtsTech/TheZokuAppMobile)\
**Reyflow**: [**Link**](https://www.reyflow.com/ib-tech/browse/MOBIL-29/)\
**Application Link:** [AppStore TestFlight]\
**Credentials:** Email:`abhishekk@ibarts.in` || PW: Abhishek@123

---

Date: **14-08-2025**\
Project: **Lawyyar App**\
Dev Name: **Abhishek Kumar**\
Status: **Ongoing**

**Project report:**

- fg

**Github**: [**Link**](https://github.com/IBArtsTech/LawyyarFlutter)\
**Reyflow**: [**Link**](https://reyflow.com/ib-tech/browse/FLUTT-4/)\
**Application Link:** [NA]

<!-- Misc: Updated Royal Calender to Api Level 35 with Build number 32

Date: **01-08-2025**\
Project: **Yaad School**\
Dev Name: **Abhishek Kumar**\
Status: **Ongoing**

**Project report:**

- fixed Playstore issue for health related unknow manifest code.
- uploaded new build on Playstore closed testing with build number 11

**Github**: [**Link**](https://github.com/IBArtsTech/YadSchool_React)\
**Application Build**: [Uploaded to playstore for closed testing]

---

Good Channel: Helped Chittadeep in Fixing Application flow and api flow.

Date: **17-07-2025**\
Project: **LDAS App**\
Dev Name: **Abhishek Kumar**\
Status: **Ongoing**

**Project report:**

- Merged Kausik's and Chittadeep's code in main branch.
- refactor(welcome_screen): remove unused package import
- change NDK version to "27.0.12077973" for compatibility
- update dependencies and SDK versions
- import here_sdk core for additional functionality
- add method to place a marker at the user's current location
- update camera to focus on the current position marker
- introduce floating action button to center map on current location
- implement \_focusOnCurrentLocation method to adjust camera on button press

**Github**: [**Link**](https://github.com/IBArtsTech/LDAS_Flutter)\
**Reyflow**: [Link](https://reyflow.com/ib-tech/browse/FLUTT-17/)\
**Application Build**: [Will be Provided by Chittadeep]

---

Date: **11-07-2025**\
Project: **StepWhere**\
Dev Name: **Abhishek Kumar**\
Status: **Ongoing**

**Project report:**

- Tried to Debug issue for In App Purchase
- Applied Debugging methods to find out Store Kit issue.
- Tried Updating in app purchase store kit and in app purchase plugin.
- Created POC for In App Purchase for testing issue for `product not fount`
- Applied all the plugins and bundle modification.
- added product id and other configuration for inapp purchase to work.
- created new product for purchase as consumable.

Note: Still stuck in the issue. `IAPError(code: storekit_no_response, source: app_store, message: StoreKit: Failed to get response from platform., details: null)`

**Github**: [**Link**](https://github.com/IBArtsTech/StepWhereFlutter)\
**POC Github:** [Link](https://github.com/abhishekib/in_app_purchase)
**Reyflow**: [Link](https://reyflow.com/ib-tech/browse/FLUTT-12/)\
**Application Build**: [NA IOS Work]\
**Credentials**:\
**\-** **email** - [smartshoe22@gmail.com](mailto:smartshoe22@gmail.com) || **pass** - Stepwhere@2024 -->
