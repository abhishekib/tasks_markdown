# <ins>**`Task Plans`**</ins>

## `Mafatiuljinan [Personal account for apple]`

- Check with manish how we can add category deeplink.
- ~~add favourite button option at left of the category.~~
- gujarati language seperation.
- fix remainder deletion option.

#

## `Royal Calender [Migration from React-native to Flutter]`

- Check what is the issue with Flutter local notification.
- fix the left and right navigation of calender date change.
- review client's requirement and update the application accordingly.

#

## `LDAS [ Anit | Abhishek | Chittadeep ]`

- Coordinate with Anit Regarding tasks.

#

## `810 Studio`

- Fix issue in building release build for Android.

#

## `Good Channel [ Chittadeep | Akshat ] [Personal account for apple]`

- Coordinate with Chittadeep and Akashat if there any help needed.

#

## `Yaad Plug`

- Further Handling is done by chittadeep.

#

## ~~`Lawyyar [Buisness account for apple] [Kousik] [ Priorify ]`~~

- ~~Done~~

#

## ~~`Amarkosh Flutter App`~~

- ~~Done~~

#

## ~~`Soom.net [Chittadeep | Kausik] [Personal account for apple]`~~

- ~~Currently no changes till client's requirement.~~

#

## ~~`Messaging app [emergostat] [ Kausik ] [Personal account for apple]`~~

- ~~Done~~

#

## ~~`RxRemainder [ Kausik ] [Personal account for apple]`~~

- ~~Done~~

#

## ~~`New Ecommerce App [ Flutter Flow ] [PerSense Client]`~~

- ~~Start New Project~~

#

## ~~`StepWhere [Chittadeep | Kausik] [Personal account for apple]`~~

~~- Paused.~~

<!-- ---
- fix audio issue when going to next post.
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

Date: **06-10-2025**\
Project: **AmarkoshFlutter**\
Dev Name: **Abhishek Kumar**\
Status: **Ongoing**

**Project report:**

- Had Meeting with Client regarding changes.
- Guided Client to fix building issue in his system.
- Guided client to properly merge the updated codes with notification permission and jitsi meeting.

**Github**: [**Link**](https://github.com/IBArtsTech/AmarkoshFlutter)\
**Reyflow**: [Link](https://www.reyflow.com/ib-tech/browse/FLUTT-39/)\
**Docsheet**: [Link](https://docs.google.com/spreadsheets/d/1-kOjWfqsCxJySr2h_PI0iW4x8IpBcJTA0avpKStH4SA/edit?gid=0#gid=0)\
**Application Build**: [NA]\
**Credentials**:

- Student: Email: bhavya_t || Password: test
- Tutor: aarti_t || Password: test

---

Date: **06-10-2025**\
Project: **Mafatihuljinan Hybrid App**\
Dev Name: **Abhishek Kumar**\
Status: **Ongoing**

**Project report:**

- enable the connectivity listener for Network check.
- Add logic to detect when device comes back online and trigger sync of offline actions
- Replace manual offline action storage with SyncService implementation
- Add pending favorites key and models to SyncService for proper offline handling
- Implement automatic sync when connectivity is restored
- Fixed issue where remainder category postId key is not getting saved in localdb.
- updated api method to follow new key updated for properly api sync.

**Github**: [**Link**](https://github.com/IBArtsTech/Mafatihuljinan_Revamp)\
**Reyflow**: [Link](https://reyflow.com/ib-tech/browse/FLUTT-1/)\
**DOC Sheet:** [**Link**](https://docs.google.com/spreadsheets/d/1-v-_y38vYsRMK5h60Kvaj7t0Er4dlFJnl1Eg0d04Yo8/edit?gid=0#gid=0)\
**Application Build**: [NA]\
**Credentials**:\
**\-** **userid:** **allworkdone** || [**allworkdone27@gmail.com**](mailto:allworkdone27@gmail.com)
**\- password**: **1234**

---

Date: **06-10-2025**\
Project: **Taxi Driver App**\
Dev Name: **Abhishek Kumar**\
Status: **Ongoing**

**Project report:**

- Fixed issue where application is crashing.
- Applied FVM to manage flutter version specific for current project.
- reverted some configuration to older flutter versions.
- tested application build running and tested app stability.
- updated version number from 2.0.1 to 13

**Github**: [**Link**](https://github.com/IBArtsTech/RoyalCalendarFlutter)\
**Reyflow**: [Link](https://www.reyflow.com/ib-tech/browse/FLUTT-48/)\
**Application Build**: [Uploaded to Playstore]

---

Date: **03-10-2025**\
Project: **LDAS Flutter**\
Dev Name: **Abhishek Kumar**\
Status: **Ongoing**

**Project report:**

- Renamed application label from "HERE SDK POC" to "Tracknav" in AndroidManifest.xml
- Updated package imports from here_sdk_reference_application_flutter to tracknav
- Added HERE SDK 4.0 plugin path to .gitignore
- Increased Gradle memory allocation from 1536M to 4096M
- Added Flutter LLDB integration files for iOS debugging
- Updated various dependencies including cupertino_icons, flutter_lints, and test packages
- Removed HERE SDK specific branding and references throughout the codebase
- Updated project configuration and documentation to reflect new application name
- Add nearbyPoisEndpoint constant to Constants class
- Update import paths from here_sdk_reference_application_flutter to tracknav
- Implement nearby POIs API call with query parameters for location-based search
- Format code for better readability
- applied all the changes from kousik.
- provided co-authorship to chittadeep, kousik, anit.

**Github**: [**Link**](https://github.com/abhishekib/here_sdk.git) || [link](https://github.com/abhishekib/LDAS_Flutter)\
 **Reyflow**: [Link](https://www.reyflow.com/ib-tech/browse/FLUTT-17/)
**Credentials**: E: `test@gmail.com` || P: `123456`

---

Date: **24-09-2025**\
Project: **Messaging App**\
Dev Name: **Abhishek Kumar**\
Status: **Ongoing**

**Project report:**

- Upgraded Build Version to 1.0.0+13
- Updated Gradle Version to 8.11.1
- Upgraded AGP version to 8.7.0
- Fixed 16KB Memory Page Size.

**Demo login**: N/A\
**GitHub url**: [Link](https://github.com/IBArtsTech/MessagingApp_Revamp.git)\
**Reyflow:** [Link](https://reyflow.com/ib-tech/browse/FLUTT-24/)

---
