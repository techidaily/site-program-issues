---
title: Solve ‘Configuration Server Connection Failure’ Effortlessly Today
date: 2025-02-12T17:37:19.824Z
updated: 2025-02-15T03:09:06.909Z
tags:
  - win11
  - win10
  - win7
categories:
  - ProgramIssues
description: This Article Describes Solve ‘Configuration Server Connection Failure’ Effortlessly Today
excerpt: This Article Describes Solve ‘Configuration Server Connection Failure’ Effortlessly Today
thumbnail: https://thmb.techidaily.com/672b93a029ff6e4433ec19a377fab4ffa2a67286a950d0a63433c57fd863da90.jpg
---

## Solve ‘Configuration Server Connection Failure’ Effortlessly Today

Many Forza Horizon 4 players are reporting that they get the error message ‘**Unable to connect to the live configuration servers** ‘ on both Xbox and PC. If you’re also experiencing the same issue, you can try the following fixes.

![](https://images.drivereasy.com/wp-content/uploads/2021/05/network-error-1200x722.jpg)

 Before you try the following solutions, make sure you have an internet connection. If you’re experiencing internet issues, you can refer to[how to fix slow internet on a Windows PC](https://tools.techidaily.com/drivereasy/download/) .

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## Try these fixes

* [1. Sign in again](https://tools.techidaily.com/drivereasy/download/)
* [2. Check the status of Teredo (Windows 10)](https://www.drivereasy.com/knowledge/unable-to-connect-to-the-live-configuration-servers-error/#h-2-check-the-status-of-teredo-windows-10)
* [3. Reinstall the Teredo Adapter](https://tools.techidaily.com/drivereasy/download/)
* [4. Turn on Windows Firewall](https://tools.techidaily.com/drivereasy/download/)
* [5. Enable Xbox Live Networking Service & Xbox Live Auth Manager](https://tools.techidaily.com/drivereasy/download/)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/MmTJlcwgyrQ?si=x3hba82M0tT57fj7" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. Sign in again

 This error might be temporary and the fix can be as easy as signing in again. Just sign out of your current account on the main menu, and sign in again. This should fix the ‘Unable to connect to the live configuration servers’.

 If you’re on Steam, the**“Sign out”** option should appear when you start the game.

![sign out steam](https://images.drivereasy.com/wp-content/uploads/2021/05/sign-out.jpg)

 But if this method doesn’t do the trick, you can try the next fix below.

## 2\. Check the status of Teredo (Windows 10)

 If you’re getting the ‘Unable to connect to the live configuration servers’ error, it may be caused by a Teredo issue. Here’s how:

 1) Click the Start menu (the Windows logo key) in the lower-left corner of the main screen.

 2) Select**Settings** \>**Gaming** , and then select**Xbox Networking** .

![](https://images.drivereasy.com/wp-content/uploads/2021/05/Xbox.jpg)

 3) Select**Fix it** . Windows will try to detect and fix known issues with Teredo.

![](https://images.drivereasy.com/wp-content/uploads/2021/05/fix-it.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/cKRBWf1EDZo?si=CTNd4q450biit4eM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 4) Once complete, you will need to click the**Check again** button. If there’s no issue detected, you can launch your game to check if the ‘Unable to connect to the live configuration servers’ issue disappears.

## 3\. Reinstall the Teredo Adapter

 It’s possible that the method above doesn’t fix the Teredo-related issue, and you can try reinstalling the Teredo Adapter using Command Prompt. Here’s how:

 1) In the Search bar, type**cmd** and select**Run as administrator** .

![command prompt admin](https://images.drivereasy.com/wp-content/uploads/2021/05/run-as-admin-cmd.jpg)

 2) Type **the following command** and press **Enter** .

netsh interface Teredo set state disable

![](https://images.drivereasy.com/wp-content/uploads/2021/05/disable-Teredo.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Q-mXUpVQijU?si=f1MzflPJ8-bD2_iQ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 3) On your keyboard, press the**Windows + R** key at the same time, and type**devmgmt.msc** . Then press**Ente** r.

![uninstall graphics driver](https://images.drivereasy.com/wp-content/uploads/2021/03/device-manager.jpg)

 4) Click **View** \> **Show hidden devices** .

![](https://images.drivereasy.com/wp-content/uploads/2021/05/show-hidden-devices.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Jng92DT1n_Y?si=LvxQhsEJoymsM2iZ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 5) Double-click on **Network adapters** .

 6) Right-click any Teredo adapter and select **Uninstall** .

 7) Go back to the**Command Prompt** (Admin) window, and enter the following command.

netsh interface Teredo set state type=default

 8) Now launch your game and check if the error message ‘Unable to connect to the live configuration servers’ is gone for now.

## 4\. Turn on Windows Firewall

 You may have turned Windows Firewall to prevent some games from crashing, but this game requires that Windows Firewall is turned on because it will need the Teredo IPsec connection.

 1) In the Search bar, type**cmd** and select**Run as administrator** .

![command prompt admin](https://images.drivereasy.com/wp-content/uploads/2021/05/run-as-admin-cmd.jpg)

 2) Type **the following command** and press **Enter** .

netsh advfirewall set allprofiles state on

3) Close the Command Prompt.

 Launch your game again to test the issue, and if this method doesn’t do the trick, check the one below.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/PD0vq5qAYkw?si=5H3KWtCfUOYg1Nlv" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 5\. Enable Xbox Live Networking Service & Xbox Live Auth Manager

 To make sure your game runs properly, you’d better check the Xbox Live Networking and Xbox Love Auth Manager services are both running properly. Here’s how:

 1) On your keyboard, press the Windows key + R key at the same time, and enter**services.msc** .

![](https://images.drivereasy.com/wp-content/uploads/2020/01/services-run-box.jpg)

 2) Scroll down the bottom, and make sure**Xbox Live Auth Manager** and**Xbox Live Networking Service** are running. If not, right-click the service and click**Start** .

![](https://images.drivereasy.com/wp-content/uploads/2021/05/services-on.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/2En1CHbiYwA?si=jZKzTr9EIT2ShjGK" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

3) Close the window and launch your game.

---

 Did the fixes above help you out? If the ‘Unable to connect to the live configuration servers’ error persists, you may need to hard reset your router or Xbox One, and uninstall and reinstall the game.

* [Application Errors](https://tools.techidaily.com/drivereasy/download/)
* [games](https://tools.techidaily.com/drivereasy/download/)
* [Xbox](https://tools.techidaily.com/drivereasy/download/)

<ins class="adsbygoogle"
     style="display:block"
     data-ad-format="autorelaxed"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="1223367746"></ins>

<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="8358498916"
     data-ad-format="auto"
     data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://snapchat-videos.techidaily.com/new-enhance-snaps-with-cultural-pop-culture-learn-anime-on-snapchat-for-2024/"><u>[New] Enhance Snaps with Cultural Pop-Culture Learn Anime On Snapchat for 2024</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-elevate-your-channelenas-expensive-check-out-our-11-free-name-generators-guide-for-2024/"><u>[Updated] Elevate Your Channel'enas Expensive? Check Out Our 11 Free Name Generators Guide for 2024</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-in-2024-collabcanvas-mosaic-magic-on-instagram-devices/"><u>[Updated] In 2024, CollabCanvas Mosaic Magic on Instagram Devices</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/updated-in-2024-cutting-edge-from-srt-to-subtitle-system/"><u>[Updated] In 2024, Cutting Edge From SRT to Subtitle System</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-in-2024-evaluating-rival-tools-to-superior-sharex/"><u>[Updated] In 2024, Evaluating Rival Tools to Superior ShareX</u></a></li>
<li><a href="https://fox-links.techidaily.com/updated-in-2024-transform-every-moment-top-ideas-for-enriching-life-through-podcasts/"><u>[Updated] In 2024, Transform Every Moment Top Ideas for Enriching Life Through Podcasts</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/2024-approved-expert-tips-to-correct-video-transmission-problem-on-mobile-messengers/"><u>2024 Approved Expert Tips to Correct Video Transmission Problem on Mobile Messengers</u></a></li>
<li><a href="https://video-capture.techidaily.com/2024-approved-revolutionize-your-viewing-habits-with-these-6-advanced-netflix-recording-steps-on-macos/"><u>2024 Approved Revolutionize Your Viewing Habits with These 6 Advanced Netflix Recording Steps on macOS</u></a></li>
<li><a href="https://program-issues.techidaily.com/dayz-shooter-downloader-fast-and-simple-installation-guide/"><u>DayZ Shooter Downloader: Fast and Simple Installation Guide</u></a></li>
<li><a href="https://some-guidance.techidaily.com/enhance-your-broadcasts-with-manycam-leading-live-video-platform-and-digital-webcam-innovator/"><u>Enhance Your Broadcasts with ManyCam, Leading Live Video Platform and Digital Webcam Innovator</u></a></li>
<li><a href="https://program-issues.techidaily.com/fixing-the-rogue-company-game-crash-issues-on-windows-computers/"><u>Fixing the Rogue Company Game Crash Issues on Windows Computers</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/new-maximize-your-reach-learn-how-to-make-viral-reaction-videos-with-filmora/"><u>New Maximize Your Reach Learn How to Make Viral Reaction Videos with Filmora</u></a></li>
<li><a href="https://program-issues.techidaily.com/resolved-how-to-get-your-iphone-detected-by-itunes-in-windows-11/"><u>Resolved: How to Get Your iPhone Detected by iTunes in Windows 11</u></a></li>
<li><a href="https://program-issues.techidaily.com/resolved-reduced-frame-rates-in-farming-simulator-22-on-pc/"><u>Resolved: Reduced Frame Rates in Farming Simulator 22 on PC</u></a></li>
<li><a href="https://program-issues.techidaily.com/resolving-continuous-freezing-and-crashing-problems-with-the-world-of-tanks-blitz-app/"><u>Resolving Continuous Freezing and Crashing Problems with the World of Tanks Blitz App</u></a></li>
<li><a href="https://program-issues.techidaily.com/resolving-the-must-close-due-to-an-error-in-geforce-experience-for-smooth-gaming/"><u>Resolving the 'Must Close Due to an Error' In GeForce Experience for Smooth Gaming</u></a></li>
<li><a href="https://program-issues.techidaily.com/resolving-the-mysterious-black-display-problems-with-zoom-on-your-computer-the-2024-how-to-manual/"><u>Resolving the Mysterious Black Display Problems with Zoom on Your Computer - The 2024 How-To Manual</u></a></li>
<li><a href="https://program-issues.techidaily.com/troubleshooting-geforce-setup-issues-fixing-closure-errors-effectively/"><u>Troubleshooting GeForce Setup Issues - Fixing Closure Errors Effectively</u></a></li>
<li><a href="https://program-issues.techidaily.com/warzone-fix-boosting-your-pc-gameplay-and-avoiding-crashes-in-2eryears-tech-guide/"><u>Warzone Fix: Boosting Your PC Gameplay & Avoiding Crashes in 2erYear's Tech Guide</u></a></li>
</ul></div>

