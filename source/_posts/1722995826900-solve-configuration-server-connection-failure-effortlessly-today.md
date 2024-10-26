---
title: Solve ‘Configuration Server Connection Failure’ Effortlessly Today
date: 2024-10-20T09:30:41.854Z
updated: 2024-10-26T05:54:50.527Z
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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135369/19272" target="_top" id="2135369">
  <img src="//a.impactradius-go.com/display-ad/19272-2135369" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135369/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 3) Select**Fix it** . Windows will try to detect and fix known issues with Teredo.

![](https://images.drivereasy.com/wp-content/uploads/2021/05/fix-it.jpg)

 4) Once complete, you will need to click the**Check again** button. If there’s no issue detected, you can launch your game to check if the ‘Unable to connect to the live configuration servers’ issue disappears.

## 3\. Reinstall the Teredo Adapter

 It’s possible that the method above doesn’t fix the Teredo-related issue, and you can try reinstalling the Teredo Adapter using Command Prompt. Here’s how:

 1) In the Search bar, type**cmd** and select**Run as administrator** .

![command prompt admin](https://images.drivereasy.com/wp-content/uploads/2021/05/run-as-admin-cmd.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2006919/19272" target="_top" id="2006919">
  <img src="//a.impactradius-go.com/display-ad/19272-2006919" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2006919/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 2) Type **the following command** and press **Enter** .

netsh interface Teredo set state disable

![](https://images.drivereasy.com/wp-content/uploads/2021/05/disable-Teredo.jpg)

 3) On your keyboard, press the**Windows + R** key at the same time, and type**devmgmt.msc** . Then press**Ente** r.

![uninstall graphics driver](https://images.drivereasy.com/wp-content/uploads/2021/03/device-manager.jpg)

 4) Click **View** \> **Show hidden devices** .

![](https://images.drivereasy.com/wp-content/uploads/2021/05/show-hidden-devices.jpg)

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
<a href="https://aligracehair.sjv.io/c/5597632/1948881/19272" target="_top" id="1948881">
  <img src="//a.impactradius-go.com/display-ad/19272-1948881" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1948881/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 5\. Enable Xbox Live Networking Service & Xbox Live Auth Manager

 To make sure your game runs properly, you’d better check the Xbox Live Networking and Xbox Love Auth Manager services are both running properly. Here’s how:

 1) On your keyboard, press the Windows key + R key at the same time, and enter**services.msc** .

![](https://images.drivereasy.com/wp-content/uploads/2020/01/services-run-box.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2080328/19272" target="_top" id="2080328">
  <img src="//a.impactradius-go.com/display-ad/19272-2080328" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2080328/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 2) Scroll down the bottom, and make sure**Xbox Live Auth Manager** and**Xbox Live Networking Service** are running. If not, right-click the service and click**Start** .

![](https://images.drivereasy.com/wp-content/uploads/2021/05/services-on.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2006914/19272" target="_top" id="2006914">
  <img src="//a.impactradius-go.com/display-ad/19272-2006914" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2006914/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://instagram-video-files.techidaily.com/new-improve-instagram-video-loading-times-effectively/"><u>[New] Improve Instagram Video Loading Times Effectively</u></a></li>
<li><a href="https://fox-helps.techidaily.com/new-in-2024-accelerating-sound-on-phones-best-free-apps/"><u>[New] In 2024, Accelerating Sound on Phones Best Free Apps</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/new-picsart-guide-adding-motion-blur-to-facial-shots-for-dynamic-images/"><u>[New] Picsart Guide Adding Motion Blur to Facial Shots for Dynamic Images</u></a></li>
<li><a href="https://program-issues.techidaily.com/solved-cod-modern-warfare-keeps-crashing/"><u>[SOLVED] COD: Modern Warfare Keeps Crashing</u></a></li>
<li><a href="https://program-issues.techidaily.com/best-solutions-for-cult-of-the-lambs-gameplay-issues-and-pc-crashes/"><u>Best Solutions for Cult of the Lamb's Gameplay Issues and PC Crashes</u></a></li>
<li><a href="https://program-issues.techidaily.com/comprehensive-fix-for-uninterrupted-fluid-gaming-experience-in-valheim-pc-edition/"><u>Comprehensive Fix for Uninterrupted, Fluid Gaming Experience in Valheim PC Edition</u></a></li>
<li><a href="https://program-issues.techidaily.com/connecting-to-steam-servers-successfully-tips-and-tricks/"><u>Connecting to Steam Servers Successfully: Tips and Tricks</u></a></li>
<li><a href="https://program-issues.techidaily.com/eight-essential-fixes-for-a-smooth-run-of-guardians-of-the-galaxy-on-pc/"><u>Eight Essential Fixes for a Smooth Run of Guardians of the Galaxy on PC</u></a></li>
<li><a href="https://program-issues.techidaily.com/how-to-fix-unable-to-connect-on-kodi-and-access-media-library-data/"><u>How To Fix 'Unable To Connect' On Kodi & Access Media Library Data</u></a></li>
<li><a href="https://techidaily.com/how-to-hard-reset-motorola-razr-40-without-password-drfone-by-drfone-reset-android-reset-android/"><u>How to Hard Reset Motorola Razr 40 Without Password | Dr.fone</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-to-change-spotify-location-after-moving-to-another-country-on-vivo-y77t-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change Spotify Location After Moving to Another Country On Vivo Y77t | Dr.fone</u></a></li>
<li><a href="https://fox-helps.techidaily.com/in-2024-mastering-audio-transformation-complete-morphvox-techniques/"><u>In 2024, Mastering Audio Transformation Complete MorphVOX Techniques</u></a></li>
<li><a href="https://program-issues.techidaily.com/mastering-the-fixes-for-battlenet-access-problems-the-definitive-2024-edition/"><u>Mastering the Fixes for Battle.net Access Problems: The Definitive 2024 Edition</u></a></li>
<li><a href="https://program-issues.techidaily.com/step-by-step-solutions-for-the-finals-not-launching-problem/"><u>Step-by-Step Solutions for the 'Finals Not Launching' Problem</u></a></li>
<li><a href="https://program-issues.techidaily.com/success-how-to-fix-and-play-modern-warfare-on-your-pc-this-year/"><u>Success! How to Fix and Play Modern Warfare on Your PC This Year</u></a></li>
<li><a href="https://win-forum.techidaily.com/the-big-four-in-social-media-a-look-at-facebook-twitter-instagram-and-youtube/"><u>The Big Four in Social Media: A Look at Facebook, Twitter, Instagram & YouTube</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/transform-your-tongue-with-mondlys-techniques/"><u>Transform Your Tongue with Mondly's Techniques</u></a></li>
<li><a href="https://article-files.techidaily.com/unveiling-the-power-of-grading-insights-from-dr-john-doe-for-2024/"><u>Unveiling the Power of Grading Insights From Dr. John Doe for 2024</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/updated-2024-approved-fcpx-not-working-try-resetting-a-simple-solution-to-common-issues/"><u>Updated 2024 Approved FCPX Not Working? Try Resetting A Simple Solution to Common Issues</u></a></li>
</ul></div>

