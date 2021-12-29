<!-- omit in toc -->
# ![AllTrans](https://raw.githubusercontent.com/akhilkedia/AllTrans/master/app/src/main/res/mipmap-hdpi/ic_launcher.png)AllTrans™ - Completely Translate Apps

Like Chrome's translation of webpages, but for Android apps. It replaces **ALL TEXT IN AN APP** from one language to another at runtime.

Say for example an app is in German. A user selects the app name, and the required language conversion (say German to English).
Then whenever the user uses the required app, all the text, **ANYWHERE** in the app, are replaced by their English equivalents.
This is something similar to the way Google Translate works in Chrome.

Works with Android 11!

[![LicenseGPLv3](https://img.shields.io/badge/License-GPL%20v3-green.svg)](http://www.gnu.org/licenses/gpl-3.0) [![Donate](https://img.shields.io/badge/Donate-PayPal-blue.svg)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=UY6TVJXST724J) ![GitHub All Releases](https://img.shields.io/github/downloads/akhilkedia/AllTrans/total?style=social) [![Play](https://img.shields.io/endpoint?color=green&logo=google-play&logoColor=green&url=https%3A%2F%2Fplayshields.herokuapp.com%2Fplay%3Fi%3Dakhil.alltrans%26l%3DInstalls%26m%3D%24installs)](https://play.google.com/store/apps/details?id=akhil.alltrans)


## Table of Contents

- [Table of Contents](#table-of-contents)
- [What AllTrans does](#what-alltrans-does)
- [ScreenShots and Videos](#screenshots-and-videos)
	- [Below are some screenshots of AllTrans translating apps from Korean to English](#below-are-some-screenshots-of-alltrans-translating-apps-from-korean-to-english)
	- [Below are some of the screenshots of AllTrans app](#below-are-some-of-the-screenshots-of-alltrans-app)
	- [Videos](#videos)
- [How to install AllTrans](#how-to-install-alltrans)
- [How to use AllTrans](#how-to-use-alltrans)
- [How to get Microsoft Azure Translate Key](#how-to-get-microsoft-azure-translate-key)
- [Note - No New Yandex Translate Keys](#note---no-new-yandex-translate-keys)
- [TroubleShooting](#troubleshooting)
	- [No app is being translated in any app](#no-app-is-being-translated-in-any-app)
	- [Translated app is stuck in opening screen](#translated-app-is-stuck-in-opening-screen)
	- [The Translated app is "Force Close"](#the-translated-app-is-force-close)
	- [Other apps are being translated, but some particular app is not](#other-apps-are-being-translated-but-some-particular-app-is-not)
	- [A game app is not being translated](#a-game-app-is-not-being-translated)
	- [The app "Telegram" is not being translated](#the-app-telegram-is-not-being-translated)
	- [If you still have problems like "Force Close" or parts of an app not being translated](#if-you-still-have-problems-like-force-close-or-parts-of-an-app-not-being-translated)
- [Featured In](#featured-in)
- [Donations](#donations)
- [License](#license)

## What AllTrans does

It replaces **all text in an app** in a language from one language to another at runtime.

Say for example an app is in German. A user selects the app name, and the required language conversion (say German to English).

Then whenever the user uses the required app, all the text, **ANYWHERE** in the app, are replaced by their English equivalents.

This is something similar to the way Google Translate works in Chrome.

**Note** - Due to a technical limitation, this won't work with many games. Nothing can be done about this.

## ScreenShots and Videos

### Below are some screenshots of AllTrans translating apps from Korean to English

![](https://raw.githubusercontent.com/akhilkedia/AllTrans/master/screenshots/Joint1S.png)

![](https://raw.githubusercontent.com/akhilkedia/AllTrans/master/screenshots/Joint2S.png)

![](https://raw.githubusercontent.com/akhilkedia/AllTrans/master/screenshots/Joint3S.png)

### Below are some of the screenshots of AllTrans app

![](https://raw.githubusercontent.com/akhilkedia/AllTrans/master/screenshots/Screen1S.png)

![](https://raw.githubusercontent.com/akhilkedia/AllTrans/master/screenshots/Screen2S.png)

![](https://raw.githubusercontent.com/akhilkedia/AllTrans/master/screenshots/Screen3S.png)

### Videos

A video (in English) showing how to use AllTrans by Gadget Hacks on Youtube [https://www.youtube.com/watch?v=sKDtkmISi6k](https://www.youtube.com/watch?v=sKDtkmISi6k). This video is for an older version of the app, you no longer need API keys.

[![Alt text](https://img.youtube.com/vi/sKDtkmISi6k/0.jpg)](https://www.youtube.com/watch?v=sKDtkmISi6k)

## How to install AllTrans

1. This application requires android version 4.4 or later. You probably already have it. (Android KitKat or later - so far Kitkat, Lollipop, MarshMallow, Nougat, Oreo, Pie, Q, R.).
1. Make sure you have [Xposed Framework](https://forum.xda-developers.com/showthread.php?t=3034811) installed and running.
   - [LSPosed](https://github.com/LSPosed/LSPosed) and [EdXposed](https://forum.xda-developers.com/xposed/development/official-edxposed-successor-xposed-t4070199) are recommended.
   - **If you do not have an unlocked bootloader or Magisk, AllTrans is now fully compatible with [VirtualXposed](https://virtualxposed.com/) and [Taichi](https://github.com/taichi-framework/TaiChi/releases), so AllTrans can now be used on all devices!!! No need of unlocked bootloader, no need of Magisk, etc.!**
1. Install the latest version of AllTrans from [Google Play Store](https://play.google.com/store/apps/details?id=akhil.alltrans). You can alternatively download the apk from [Xposed Module Repository](http://repo.xposed.info/module/akhil.alltrans) or from LSPosed Repository inside LSPosed app.
1. Reboot your phone.

## How to use AllTrans

1. Make sure "AllTrans" app is enabled in "Xposed Installer -> Modules".
1. Launch "AllTrans" app.
1. Choose the "Translate from Language" and "Translate to Language".
1. In the "Apps to Translate" tab, find the app you want to translate, click the checkbox next to it.
1. Close and restart the app you want translated - it should be translated!

## How to get Microsoft Azure Translate Key

If you use Microsoft Translate instead of Google, you **need** you to sign up for **free** a key from Microsoft Translate. See instructions below on how to get the keys.
Microsoft Translate requires a credit card to sign up. (But don't worry, nothing will be charged.)

1. Sign up for a Microsoft Azure account.
If you don't already have an Azure account, sign up for a [Microsoft Azure account](http://azure.com).
1. After you have an account, sign into the [Azure Portal](http://portal.azure.com). Sign up for a subcription by following the steps below.
   1. Click "Subscriptions". It has a key icon.
   1. Click the "+ Add" at the top
   1. Choose a "pay-as-you-go" subscription. Will require a credit card, but don't worry, nothing will be charged.
   1. Verify your identity, add in the credit card information. You will not be charged.
   1. In "Add Technical Support", select "No technical support". **You will have to pay if you select any other**. Accept the "Agreement", and click "Sign up".
   1. Click "Home" at the top after you finish signing up.
1. Add a translate API resource by following the steps below.
   1. Select the "+ Create a resource" option.
   1. In the search box saying "Search the Marketplace" type "translator" on the left, and select "Translator" from the search results.
   1. Click the blue "Create" button.
   1. Under the "Resource group" field, click "Create new", then type in any name, it does not matter.
   1. **In the "Resource group region" field, select any region, it does not matter**
   1. In the "Resource group" field, type in any name, it does not matter.
   1. **In the "Region" Section, select "Global"**
   1. Type in any name in "Name" field, type in any name, it does not matter.
   1. In the "Pricing Tier" section, select the "F0 (2M Up to 2M characters translated per month)". **You will have to pay if you select any other**.
   1. Click "Next: Tags", then click "Next: Review + Create", then click "Create".
   1. Wait 1 minute for Microsoft to process your request, then go to "Home".
1. Copy your key from Microsoft and add it to AllTrans by following the steps below.
   1. Under the "Recent Resource" section, click the name of the resource you just created.
   1. Click "Keys and Endpoint" on the left. It has a key icon.
   1. Copy "KEY 1". This is the key you need to add to AllTrans.

The subscription key is something like "3d2c..." (some english numbers and alphabets).

## Note - No New Yandex Translate Keys

A previous version of this application encouraged use of Yandex API keys. Yandex has stopped giving free translate API keys. If you already have a key, it may continue to work, it may not. It is recommended to shift to using a Microsoft API key.

## TroubleShooting

### No app is being translated in any app

- If no app is being translated, check if "AllTrans" is enabled in "Xposed Installer -> Modules"
  - If you are using "Taichi", check "AllTrans" is enabled in "+ -> Manage Modules".
  - If you are using "Taichi"/"VirtualXposed", also make sure the app to be translated in installed using "Taichi"/"VirtualXposed".
- If you are using "Google" to translate (the default), make sure you have set "Translate From Langauge" and "Translate To Language" and downloaded the translation files.
- If you are using "Microsoft" to translate, make sure "Microsoft Subscription Key" is correct, and the "Resource Region" setting is "Global" when you made the key.

### Translated app is stuck in opening screen

- If this is the first time you started translating this app, click on the app's name in "Apps to Translate" tab, and in "Other Settings" fill in "Delay Before Replcaing With Translated Text" to "2000".

### The Translated app is "Force Close"

- Click on the app's name in "Apps to Translate" tab, and in "Other Settings" fill in "Delay Before Replcaing With Translated Text" to "2000".
- Click on the app's name in "Apps to translate" tab, and in "Other Settings" fill in "Delay Before Starting to Translate WebViews" to "2000".

### Other apps are being translated, but some particular app is not

- Click on the app's name in "Apps to translate" tab, and in "Other Settings" fill in "Delay Before Starting to Translate WebViews" to "2000".
- If some parts of the app are still not being translated, click on the app's name in "Apps to translate" tab, and enable "Aggressive Mode".

### A game app is not being translated

- Due to technical limitations, "AllTrans" will not work with many games. Nothing can be done about this.

### The app "Telegram" is not being translated

- In "Apps to Translate", click on "Telegram", click "OverRide Global Settings", set "Translate From Langauge" and "Translate To Language", and **Enable "Aggresive Mode"**

### If you still have problems like "Force Close" or parts of an app not being translated

Contact me for support. When you do, I will need atleast the following information -

1. The name of the app, along with a **link to download the app** from some APK store like "Google Play Store", "CoolApk", etc.
1. Your phone's Android version.
1. A "logcat" of you trying to open the app which gives you problems. You can use apps freely available on the Play Store for this, such as [This one](https://play.google.com/store/apps/details?id=com.nolanlawson.logcat)

Once you have the above, contact me on the  [XDA support thread](https://forum.xda-developers.com/xposed/modules/xposed-alltrans-completely-translate-t3539878).
You can also report issues on the  [Project's "Github"](https://github.com/akhilkedia/AllTrans).

## Featured In

AllTrans has been featured by many outlets, in many languages. AllTrans has been covered in English by -

- [XDA Developers](https://www.xda-developers.com/alltrans-is-an-xposed-module-that-completely-translates-apps/)
- [Android Police](https://www.youtube.com/watch?v=LFTH5PCZygs)
- [Gadget Hacks](https://android.gadgethacks.com/how-to/automatically-translate-any-android-app-into-any-language-0176033/)
- [DroidViews](https://www.droidviews.com/auto-translate-apps-on-your-android-into-any-language/)
- [Mi News](http://in.c.mi.com/thread-259647-1-0.html?mobile=no)
- [GetDroidTips](https://www.getdroidtips.com/translating-android-apps-language/)
- [steemit](https://steemit.com/alltrans/@vishalsingh4997/alltrans-module-that-changes-languages-in-real-time-12c241bfd79f7est)

## Donations

If you like this project, buy me a cup of coffee! :)

[![paypal](https://www.paypalobjects.com/en_US/i/btn/btn_donateCC_LG.gif)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=UY6TVJXST724J)

## License

This program is AllTrans
Copyright (C) 2017  Akhil Kedia

This program is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.

This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU General Public License for more details.

You should have received a copy of the GNU General Public License along with this program. If not, see <http://www.gnu.org/licenses/>.
