LeakGirls is a badly written, bloated, overpriced piece of software. If you really want to record cam girls, just search the web for 'stream recorder'. There are tons of _free_ programs out there that don't crash constantly and that don't take up 273 MB.

&nbsp;

If for some godawful reason you still want to use this s████y program, rather than giving money to a spammer, you can [download a cracked version for free here](https://disk.yandex.com/d/Q7zvb0Lm06WtZQ). I still don't recommend you do for all of the reasons I just mentioned but, if you really want to use this program for some reason, at least you can without giving money to someone who's always posting spam on Reddit.

&nbsp;

Please feel free to share this link, re-upload the cracked version somewhere else or whatever. I don't even care if you take credit for the crack. Just make sure you include the following message somewhere obvious:

**Stop posting spam on Reddit and I'll stop making cracked versions of LeakGirls!**



# LeakGirls - Cam site Video Downloader

LeakGirls is a computer application that is capable of easily downloading videos any cam site.

## Features

* Can download from any cam site
* Easy to use: you just need a model's profile link
* Can download several streams at the same time
* Cross platform: works on Mac, Linux and Windows
* Monitor feature: Automatically downloads all the model's future shows
* Can choose between 3 video formats: mp4, ts or mkv

## Tested websites

* Chaturbate
* MyFreeCams
* BongaCams
* RoyalCams
* Cam4
* StripChat
* XHamsterLive
* Camster
* Camsoda
* Naked.com
* Streamate
* cam.com
* camlive.com
* spankbang.com

You can also check the list here: [https://leakgirls.com/Supported/](https://leakgirls.com/Supported/)

## Downloading

You can download it from the relase page, or on the official website [here](https://leakgirls.com/Downloads/).

## Installing

Simply extract the zip folder.

* All versions: You will need google chrome or chromium installed
* Linux: You need to install ffmpeg and curl
* Mac: For the first time you run, open terminal in the folder you extracted and run `bash install.sh`

## Official website

[https://leakgirls.com](https://leakgirls.com)

## Author

Ícaro Augusto

* [https://icaroaugusto.com](https://icaroaugusto.com)
* Discord: **IcaroAugusto#3303**
* Discord group: [click here](https://discord.gg/aerWHnv)

## Changelogs

### 3.6 (26/02/2021)
* Fixed issues with camsoda.

### 3.5 (13/02/2021)
* Fixed the scroll bug that happened when you had too many models added. It should scroll back to the same position when refreshing the list (This previously had been fixed only on the Linux version).
* Made a few changes to the stream downloader to handle connection failures better. This should fix the issue of short videos particularly on Stripchat.
* Added the option to separate models by folder, similar to the previously added option to separate the cam sites. This is now the default behavior and can be changed in settings.

### 3.4 (02/12/2020)
* Added the option to separate videos from each cam site in their own directory inside the videos folder, this is now the default behavior (can be changed in settings).
* Fixed the model scroller returning to start when refreshing status.
* Fixed issues with camster.com and naked.com.

### 3.3 (30/09/2020)
* Fixed issues with camsoda.
* Added support for spankbang.com.
* Changed how the sites are represented in the girls.json file:
  * The site's name instead of its index is stored now.
  * This will improve the compatibility of the girls.json file with future updates when adding support for a new cam site.
  * For this update, you can't reuse your girls.json file.

### 3.2 (19/08/2020)
* Fixed issues with camsoda.
* Added support for camlive.com.

### 3.1.3 (08/07/2020)
* Fixed issues with camsoda (again).

### 3.1.2 (08/07/2020)
* Fixed issues with camsoda, camster and naked.

### 3.1.1 (08/07/2020)
* Added the "stream timeout" setting again. Default is 15 seconds, increase it if you or the models you're recording have an unstable connection and you're getting several smaller videos.


### 3.1 (06/07/2020)
* Model's cam site is now added to file name. This fixes issues related to having models with the same name, but from different sites.
* You can now download from unlisted sites again. To do that, select the "other" option and add the full link to the stream page. It will grab the stream link using chrome.
* Fixed the "stuck in downloading" issue. If the video size doesn't increase in 15 seconds, download will stop automatically.

### 3.0 (04/07/2020)

* This is a large update, several things have been changed, read on.
* No longer uses streamlink.
  * Streamlink doesn't actually convert videos while/after downloading, wasn't aware of that. All videos were actually ts videos with just a mp4/mkv extension.
  * I wrote a simple hls downloader to use with LeakGirls, code is open and you can check it [here](https://github.com/IcaroAugusto/node-hls-downloader).
  * If you select the mp4 or mkv format, videos will automatically be converted with ffmpeg after being downloading.
  * If you select the ts format, nothing will be done.
* No longer uses Chrome to grab links
  * Now grabs stream links directly using http/websockets, this increases performance considerably especially when monitoring a lot of models.
  * Chrome is still necessary because of MyFreeCams
    * LeakGirls checks if the MFC model is online first using websockets.
    * Only if the model is online, it uses Chrome to grab the link as it is necessary to avoid being ip blocked from the site.
    * This results performance gains compared to the previous method of using Chrome to check if the model is online.
* Changes to the program
  * Removed the "stream timeout" setting as it is no longer necessary.
  * Added maximum and minimum resolution settings, default is 720p for maximum.
  * Increased the size of the model status box.
  * Model data is saved as json now, it should make it easier to edit manually.
  * Now instead of copying the model's profile link, you have to copy their username and select the respective camsite.
  * All program dependencies (chrome, node, ffmpeg etc) now come packaged in all versions. This removes the need to install anything extra to run LeakGirls.
* MacOS changes
  * Mac version has been updated to 3.0 too, unlike in the previous versions.
  * No longer has to run an install script, all you have to do now is double click the executable right after unzipping.
  * On the first run, both LeakGirls and Chrome will ask for permission to run and access folders.
    * If you don't grant Chrome permission, you will not be able to download from MFC.
    * If you do the above and want to enable it later, you have to run Chrome manually by running the app in Dependencies/chrome/Chromium.app

### 2.2.5 (11/06/2020)
* Fixed an issue in which it was failing to download some videos from camsoda.

### 2.2.4 (07/06/2020)
* Fixed an issue in which the program was failing to download 1080p streams from xhamsterlive and stripchat.
* Did some internal changes to increase success rate on myfreecams.

### 2.2.3 (20/04/2020)
* Made the safeguard added in the last update optional. It's disabled by default, you can enable it in the settings menu and set the period (minimum is 10 seconds) in which to check for the file size increase.

### 2.2.2 (19/04/2020)
* Added a safeguard: if the video file size hasn't increased in the last 10 seconds it will stop streamlink. This should ensure it doesn't say 'downloading' without actually downloading anything.

### 2.2.1 (17/04/2020)
* Fixed an issue in which the program would show 'downloading' even after a stream has effectively ended

### 2.2 (16/04/2020)
* Fixed issues with stripchat
* Fixed issues with xhamsterlive
* Fixed a bug in which the program would show 'downloading' then 'idle' quickly after without downloading anything
* Fixed 'recording other models' issue with camster.com and naked.com. The issue was because camster/naked would redirect you to another model's room if the given one were offline, causing the program to record another model
* Made some changes that should increase MyFreeCams coverage

### 2.1 (15/04/2020)
* LeakGirls now uses Streamlink instead of ffmpeg, this allows it to download encrypted streams
* Fixed issues with camster.com
* Fixed issues with naked.com
* LeakGirls will now avoid 4k streams, it will download the highest resolution available up to 1080p (full hd)
* Mac version isn't updated to 2.1 yet

### 2.0 (02/04/2020)
* Added a confirmation when removing girls
* Fixed window resizing issues
* Added a new settings menu, current settings are:
  * Ability to select in which folder to save the video
  * Select the date format in the video file name

### 1.9.2 (21/03/2020)
* Fixed issues with MyFreeCams

### 1.9.1 (10/03/2020)
* Fixed Mac version!

### 1.9.1 (02/03/2020)
* Fixed issues stripchat
* Fixed issues xhamsterlive
* Mac issues will be fixed in version 2.0

### 1.9 (07/02/2020)
* Fixed issues with cam4

### 1.8 (27/01/2020)
* Fixed issues with myfreecams, they will still block you if you download several streams at once, no way around it for now.
* Fixed issues with stripchat and xhamsterlive
* Fixed issues with program not working properly on computers with non latin characters
* Removed some unused node.js modules, decreasing program size

### 1.7.1 (22/01/2020)
* Fixed ui refreshing bug

### 1.7 (21/01/2020)
* Added a select all option.
* Added some quick links to the website.
* Added a version check: Every time you run the program, it will check if there is a new version.
* Updated Mac version (Mac was still on version 1.5 while others were on 1.6).

### 1.6 (05/01/2020)
* This is a big update, huge parts of the program have been rewritten.
* This aims to fix all the bugs reported so far, make it less prone to bugs and easier to fix future bugs.
* Almost everything from the javascript part has been moved to the pascal part, this let me get rid of the IPC system that was the source of almost all bugs.
* Stop download now also stops monitoring if it is active.

### 1.5
* Fixed a bug with Chaturbate streams not being downloaded.

### 1.4
* Added an option to select the video file format, you can choose between: mp4, ts and mkv.
* Fixed a few bugs related to deleting camgirls:
  * Deleting a camgirl while monitoring or downloading her, would keep downloading/monitoring in the background. Now if you delete a camgirl that is being monitored/downloaded, it will stop the operation.
  * Deleting a camgirl while one or more girls below them in the list were being downloaded or monitored would cause the status ui to display incorrectly (eg. showing "downloading" while in fact she was "idle").

### 1.3
* Monitor button will now automatically begin monitoring again after a successful download. This means you can select the models you want, hit monitor girls and leave the program running 24/7 and it will download all their future shows.
* Added support for the following websites:
  * cam
  * streamate

### 1.2
* Improved performance on slower computers
* Added support for the following websites:
  * camster
  * camsoda
  * naked
* Added ability to download from unsupported sites: It will attempt to download from the site, but success won't be guaranteed.

### 1.1
* Added support for the following websites:
  * stripchat
  * xhamsterlive
* Added macOS version

### 1.0
* Released
