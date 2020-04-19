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
* Added ability to download from unsupported sites: It will attempt to download from the site, but success won't be guaranteed.</li>

### 1.1
* Added support for the following websites:
  * stripchat
  * xhamsterlive
* Added macOS version

### 1.0
* Released