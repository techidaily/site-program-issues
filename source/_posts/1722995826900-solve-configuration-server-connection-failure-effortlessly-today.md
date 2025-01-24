---
title: Solve ‘Configuration Server Connection Failure’ Effortlessly Today
date: 2025-01-21T22:54:47.931Z
updated: 2025-01-24T08:46:36.247Z
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/QPAKth3O_5c?si=M69YSY0Mk_gsdU0Q" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. Sign in again

 This error might be temporary and the fix can be as easy as signing in again. Just sign out of your current account on the main menu, and sign in again. This should fix the ‘Unable to connect to the live configuration servers’.

 If you’re on Steam, the**“Sign out”** option should appear when you start the game.

![sign out steam](https://images.drivereasy.com/wp-content/uploads/2021/05/sign-out.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/SgRVYjqB70s?si=My_2cDvJVdincQRu" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 But if this method doesn’t do the trick, you can try the next fix below.

## 2\. Check the status of Teredo (Windows 10)

 If you’re getting the ‘Unable to connect to the live configuration servers’ error, it may be caused by a Teredo issue. Here’s how:

 1) Click the Start menu (the Windows logo key) in the lower-left corner of the main screen.

 2) Select**Settings** \>**Gaming** , and then select**Xbox Networking** .

![](https://images.drivereasy.com/wp-content/uploads/2021/05/Xbox.jpg)

 3) Select**Fix it** . Windows will try to detect and fix known issues with Teredo.

![](https://images.drivereasy.com/wp-content/uploads/2021/05/fix-it.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/GyfJUhsz_AY?si=x2HjoLX1B89oEPgZ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 4) Once complete, you will need to click the**Check again** button. If there’s no issue detected, you can launch your game to check if the ‘Unable to connect to the live configuration servers’ issue disappears.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/HtM7d4dpN1I?si=2vN_xgVGD4eYGORu" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3\. Reinstall the Teredo Adapter

 It’s possible that the method above doesn’t fix the Teredo-related issue, and you can try reinstalling the Teredo Adapter using Command Prompt. Here’s how:

 1) In the Search bar, type**cmd** and select**Run as administrator** .

![command prompt admin](https://images.drivereasy.com/wp-content/uploads/2021/05/run-as-admin-cmd.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/S0b9szh8vEk?si=NlGzpJ6MN_SJNk5A" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

## 5\. Enable Xbox Live Networking Service & Xbox Live Auth Manager

 To make sure your game runs properly, you’d better check the Xbox Live Networking and Xbox Love Auth Manager services are both running properly. Here’s how:

 1) On your keyboard, press the Windows key + R key at the same time, and enter**services.msc** .

![](https://images.drivereasy.com/wp-content/uploads/2020/01/services-run-box.jpg)

 2) Scroll down the bottom, and make sure**Xbox Live Auth Manager** and**Xbox Live Networking Service** are running. If not, right-click the service and click**Start** .

![](https://images.drivereasy.com/wp-content/uploads/2021/05/services-on.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Zgwn5kVI5V4?si=1j6j4OuSSndFieXU" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://twitter-clips.techidaily.com/2024-approved-how-to-download-gif-images-from-twitter/"><u>2024 Approved How to Download GIF Images From Twitter</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/2024-approved-how-to-rectify-silent-streams-with-obs/"><u>2024 Approved How to Rectify Silent Streams with OBS</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/approved-key-information-every-asmr-aficionado-should-know/"><u>2024 Approved Key Information Every ASMR Aficionado Should Know</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-pros-recommended-slow-motion-camera-apps-ios-and-android-edition/"><u>2024 Approved Pro's Recommended Slow Motion Camera Apps IOS & Android Edition</u></a></li>
<li><a href="https://program-issues.techidaily.com/6-top-fixes-for-a-non-functional-obs-microphone-updated-guide-2024/"><u>6 Top Fixes for a Non-Functional OBS Microphone - Updated Guide 2024</u></a></li>
<li><a href="https://program-issues.techidaily.com/boosting-your-gaming-experience-overcoming-low-fps-challenges-in-the-latest-formula-one-video-game-on-pc/"><u>Boosting Your Gaming Experience: Overcoming Low FPS Challenges in the Latest Formula One Video Game on PC</u></a></li>
<li><a href="https://program-issues.techidaily.com/1723003797147-continuous-pc-crashes-while-playing-watch-dogs-legion-solved/"><u>Continuous PC Crashes While Playing Watch Dogs: Legion - Solved</u></a></li>
<li><a href="https://win-top.techidaily.com/conversion-facile-et-gratuite-de-fichiers-3gp-en-format-mpeg-sur-le-web-service-gratuit-par-movavi/"><u>Conversion Facile Et Gratuite De Fichiers 3GP en Format MPEG Sur Le Web - Service Gratuit Par Movavi</u></a></li>
<li><a href="https://program-issues.techidaily.com/essential-fixes-for-when-the-outer-worlds-keeps-crashing-on-pc/"><u>Essential Fixes for When 'The Outer Worlds' Keeps Crashing on PC</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-i-transferred-messages-from-vivo-y27-5g-to-iphone-12xs-max-in-seconds-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How I Transferred Messages from Vivo Y27 5G to iPhone 12/XS (Max) in Seconds | Dr.fone</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/in-2024-keep-up-with-friends-moments-best-live-stream-tools-revealed/"><u>In 2024, Keep Up With Friends' Moments Best Live-Stream Tools Revealed</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-network-locked-sim-card-inserted-on-your-infinix-hot-30i-phone-unlock-it-now-by-drfone-android/"><u>In 2024, Network Locked SIM Card Inserted On Your Infinix Hot 30i Phone? Unlock It Now</u></a></li>
<li><a href="https://program-issues.techidaily.com/1723005757058-resolving-technical-issues-with-yakuza-6-pc-version-no-more-crashes/"><u>Resolving Technical Issues with Yakuza 6 PC Version - No More Crashes!</u></a></li>
<li><a href="https://tech-haven.techidaily.com/the-social-implications-of-censorship-in-automated-dialogue-systems/"><u>The Social Implications of Censorship in Automated Dialogue Systems</u></a></li>
<li><a href="https://program-issues.techidaily.com/the-truth-behind-the-postponement-of-guilty-gear-strive-launch/"><u>The Truth Behind the Postponement of Guilty Gear Strive Launch</u></a></li>
<li><a href="https://android-location-track.techidaily.com/top-10-best-spy-watches-for-your-itel-s23-drfone-by-drfone-virtual-android/"><u>Top 10 Best Spy Watches For your Itel S23 | Dr.fone</u></a></li>
<li><a href="https://program-issues.techidaily.com/top-methods-for-enhancing-your-ark-sanctuary-fps-performance-on-pc/"><u>Top Methods for Enhancing Your ARK: Sanctuary FPS Performance on PC</u></a></li>
<li><a href="https://program-issues.techidaily.com/uninterrupted-gaming-remedying-frequent-breakdowns-of-ffxiv-for-pc-users/"><u>Uninterrupted Gaming - Remedying Frequent Breakdowns of FFXIV for PC Users</u></a></li>
<li><a href="https://program-issues.techidaily.com/your-guide-to-shopping-for-televisions-online-top-6-retailers-revealed/"><u>Your Guide to Shopping for Televisions Online: Top 6 Retailers Revealed</u></a></li>
</ul></div>

