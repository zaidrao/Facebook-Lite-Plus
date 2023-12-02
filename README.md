# Facebook Lite Plus
Facebook Lite Plus is lite weight android app for login into Facebook accounts with many featurs.

- [DESCRIPTION](#description)
- [FEATURES](#features)
- [IMAGES](#images)
- [FUTURE UPDATES](#future-updates)
- [DOWNLOAD](#download)
#
# DESCRIPTION 
Facebook Lite Plus is an android application which provides you a good interface to login multiple facebook accounts with multiple mode and some other customizations.
This app doesn't collect any of your information all information provided by you directly collected by facebook. It is verified from Google play protect.
This app is in beta phase so maybe you can encounter with bugs and crashes.
#
# FEATURES
- Improve ui.
- Support multiple accounts login.
- Multiple methods of login.
- You can store and define account info for each account separately.
- Improve cookies method.
- Two modes of Facebook style in mobile and cookies method.
- You can export/import accounts in/from file.
- You can import accounts from cookies file make sure file follow define patterns.
#
# UPDATE 1.3
* Added support to Android 14
* Remove support to Android 5

* Added Auto Two Factor tool using WebView.
* Added Temp Mail generator 
* Added OTP generator
* Added Proxy system
* Improve cookies login system
* Support flexible cookies file
* Improve manny bugs
* Improve some basic functionalities

* Added login system for each user for better user experience.
- You have to login compulsory in order to use new features
- Don't share your login account to another device you may lose your account 

Pattern supported by files:
- 2F file pattern: UID|PASS, UID|PASS|COOKIES|UA - In auto 2F file only uid pass is needed but if you want sperate ua for each account you have to follow above pattern.
- Cookies Import file pattern: UID|PASS|COKIES, UID|PASS|COOKIES|UA

Auto 2 factor:
- This feature in beta phase, I don't have enough ids for testing so you can test it and share your experience.
- In order to use this feature you need to login first.
- You also need to give app overly permission to see the WebView and progress.
- it use background service so it will not get terminate, you should also uncheck the Lite plus from your battery optimization setting.
- You can select account file.
- Select output folder where processed account save.
- You can use user agent, if use single the single one apply on each session, if use multiple user agent from file then every account login use random user agent from file.
- In advance setting you can set timeout request means it can wait till timeout in every step of 2 factor if the timeout then it skip current processed id and goto next one, by default it is one minute ( If you have slow connection then increase it and if you have good speed you can decrease it)
- Wait in each step time is also important if your device is slow then you should set it high and vice versa.
# IMAGES
![alt text](https://github.com/zaidrao/Facebook-Lite-Plus/blob/main/Images/pic1.jpg)
#
![alt text](https://github.com/zaidrao/Facebook-Lite-Plus/blob/main/Images/pic2.jpg)
#
![alt text](https://github.com/zaidrao/Facebook-Lite-Plus/blob/main/Images/pic3.jpg)
#
#
# FUTURE UPDATES
In future if I got good response from you I'll definitely update it.
If you encounter any bug, error and crash you can contact me on facebook.
#
# DOWNLOAD
Click the download button to download latest release app.

<!-- BEGIN LATEST DOWNLOAD BUTTON -->
[![Download apk](https://custom-icon-badges.herokuapp.com/badge/-Download-blue?style=for-the-badge&logo=download&logoColor=white "Download apk")](https://github.com/zaidrao/Facebook-Lite-Plus/releases/download/15/Lite+.1.5.apk)
<!-- END LATEST DOWNLOAD BUTTON -->
