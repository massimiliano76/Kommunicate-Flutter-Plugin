## 1.1.4
  * Added method to get total unread messages count
  
## 1.1.3
  * Added settings to change toolbar, statusbar and rich message theme color in android
  * Added option to set teamId in android 
  * Added an option to show/hide different message menu options in iOS.
  * Now, chat bar's attachment color config will be applied to the bottom part of the chat bar as well in iOS
  * Fixed issue with localization crash in android
  * Added a check for whitespace and newline characters in the user ID in iOS
  
## 1.1.2
  * Fixed issue where kommunicate plugin podspec file was not being found by the plugin
  * Fixed issue where plugin methods were not accessible on channel kommunicate_flutter
  * Updated iOS SDK version to 5.9.0

## 1.1.1
  Changed the package name from "kommunicate_flutter_plugin" to "kommunicate_flutter"

  Migration to version 1.1.1 from 1.1.0

  * Change the plugin name in pubspec.yaml from "kommunicate_flutter_plugin" to "kommunicate_flutter"
  * Change the imports from:
      import 'package:kommunicate_flutter_plugin/kommunicate_flutter_plugin.dart';
       to:
      import 'package:kommunicate_flutter/kommunicate_flutter.dart';
      
## 1.1.0
* Added new functions for Authentication:
  - isLoggedIn(): To check weather the user is logged in or not
  - login(kmUser): login the user to Kommunicate
  - loginAsVisitor(): login the user without pre existing details. The user will be logged in as a Visitor

* Added new Conversation methods:
  - openConversations(): Open the conversation List for the logged in user
  - openParticularConversation(String clientConversationId): Open the conversation for the passed clientConversationId

## 0.0.1

* TODO: Describe initial release.
