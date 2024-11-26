---
title: Expert Tips for Fixing 'Unable to Reach Configuration Servers Online'
date: 2024-11-22T19:49:54.672Z
updated: 2024-11-26T16:11:35.833Z
tags:
  - win11
  - win10
  - win7
categories:
  - ProgramIssues
description: This Article Describes Expert Tips for Fixing 'Unable to Reach Configuration Servers Online'
excerpt: This Article Describes Expert Tips for Fixing 'Unable to Reach Configuration Servers Online'
thumbnail: https://thmb.techidaily.com/a02a9911f50368d686754fe93fbecd3af42fa753760f192f422f0660350e151b.jpg
---

## Solve ‘Configuration Server Connection Failure’ Effortlessly Today

Many Forza Horizon 4 players are reporting that they get the error message ‘**Unable to connect to the live configuration servers** ‘ on both Xbox and PC. If you’re also experiencing the same issue, you can try the following fixes.

![](https://images.drivereasy.com/wp-content/uploads/2021/05/network-error-1200x722.jpg)

 Before you try the following solutions, make sure you have an internet connection. If you’re experiencing internet issues, you can refer to[how to fix slow internet on a Windows PC](https://tools.techidaily.com/drivereasy/download/) .

## Try these fixes

* [1. Sign in again](https://tools.techidaily.com/drivereasy/download/)
* [2. Check the status of Teredo (Windows 10)](https://www.drivereasy.com/knowledge/unable-to-connect-to-the-live-configuration-servers-error/#h-2-check-the-status-of-teredo-windows-10)
* [3. Reinstall the Teredo Adapter](https://tools.techidaily.com/drivereasy/download/)
* [4. Turn on Windows Firewall](https://tools.techidaily.com/drivereasy/download/)
* [5. Enable Xbox Live Networking Service & Xbox Live Auth Manager](https://tools.techidaily.com/drivereasy/download/)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/S0b9szh8vEk?si=NlGzpJ6MN_SJNk5A&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. Sign in again

 This error might be temporary and the fix can be as easy as signing in again. Just sign out of your current account on the main menu, and sign in again. This should fix the ‘Unable to connect to the live configuration servers’.

 If you’re on Steam, the**“Sign out”** option should appear when you start the game.

![sign out steam](https://images.drivereasy.com/wp-content/uploads/2021/05/sign-out.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/465CTOm8om0?si=63RxowNMCFA4fPUa&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 But if this method doesn’t do the trick, you can try the next fix below.

## 2\. Check the status of Teredo (Windows 10)

 If you’re getting the ‘Unable to connect to the live configuration servers’ error, it may be caused by a Teredo issue. Here’s how:

 1) Click the Start menu (the Windows logo key) in the lower-left corner of the main screen.

 2) Select**Settings** \>**Gaming** , and then select**Xbox Networking** .

![](https://images.drivereasy.com/wp-content/uploads/2021/05/Xbox.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/yr0yS_Ywrjs?si=QxzYiX1KmUaExmlo&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 3) Select**Fix it** . Windows will try to detect and fix known issues with Teredo.

![](https://images.drivereasy.com/wp-content/uploads/2021/05/fix-it.jpg)

 4) Once complete, you will need to click the**Check again** button. If there’s no issue detected, you can launch your game to check if the ‘Unable to connect to the live configuration servers’ issue disappears.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/RJNYTGHVlLc?si=heERQcpMi77lqToE&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3\. Reinstall the Teredo Adapter

 It’s possible that the method above doesn’t fix the Teredo-related issue, and you can try reinstalling the Teredo Adapter using Command Prompt. Here’s how:

 1) In the Search bar, type**cmd** and select**Run as administrator** .

![command prompt admin](https://images.drivereasy.com/wp-content/uploads/2021/05/run-as-admin-cmd.jpg)

 2) Type **the following command** and press **Enter** .

netsh interface Teredo set state disable

![](https://images.drivereasy.com/wp-content/uploads/2021/05/disable-Teredo.jpg)

 3) On your keyboard, press the**Windows + R** key at the same time, and type**devmgmt.msc** . Then press**Ente** r.

![uninstall graphics driver](https://images.drivereasy.com/wp-content/uploads/2021/03/device-manager.jpg)

 4) Click **View** \> **Show hidden devices** .

![](https://images.drivereasy.com/wp-content/uploads/2021/05/show-hidden-devices.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/U_aNKnMTPjo?si=Og_mEt7NP3Fbsg2n&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/dKjioJQaUh8?si=Ls_AeuvGsSyL5ny2&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 5\. Enable Xbox Live Networking Service & Xbox Live Auth Manager

 To make sure your game runs properly, you’d better check the Xbox Live Networking and Xbox Love Auth Manager services are both running properly. Here’s how:

 1) On your keyboard, press the Windows key + R key at the same time, and enter**services.msc** .

![](https://images.drivereasy.com/wp-content/uploads/2020/01/services-run-box.jpg)

 2) Scroll down the bottom, and make sure**Xbox Live Auth Manager** and**Xbox Live Networking Service** are running. If not, right-click the service and click**Start** .

![](https://images.drivereasy.com/wp-content/uploads/2021/05/services-on.jpg)

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
<li><a href="https://fox-boxes.techidaily.com/new-unlimited-chuckles-craftsmanship-no-monetary-requirement/"><u>[New] Unlimited Chuckles Craftsmanship No Monetary Requirement</u></a></li>
<li><a href="https://program-issues.techidaily.com/solved-how-to-fix-minecraft-not-loading/"><u>[Solved] How to Fix Minecraft Not Loading</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/updated-the-zen-of-zoom-perfecting-your-video-experience/"><u>[Updated] The Zen of Zoom Perfecting Your Video Experience</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-transformative-tech-effortlessly-turning-phones-into-vr-gear/"><u>[Updated] Transformative Tech Effortlessly Turning Phones Into VR Gear</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-starting-off-determining-your-creative-passion/"><u>2024 Approved Starting Off Determining Your Creative Passion</u></a></li>
<li><a href="https://program-issues.techidaily.com/a-step-by-step-guide-resolving-gtfo-related-errors/"><u>A Step-by-Step Guide: Resolving GTFO Related Errors</u></a></li>
<li><a href="https://program-issues.techidaily.com/dying-light-lag-problems-here-are-the-fixes-to-optimize-your-gaming-experience/"><u>Dying Light Lag Problems? Here Are the Fixes to Optimize Your Gaming Experience</u></a></li>
<li><a href="https://program-issues.techidaily.com/fixing-high-disk-and-cpu-load-from-wsappx-a-step-by-step-guide/"><u>Fixing High Disk & CPU Load From WSAPPX: A Step-by-Step Guide</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/forgotten-the-voicemail-password-of-oneplus-11r-try-these-fixes-by-drfone-android/"><u>Forgotten The Voicemail Password Of OnePlus 11R? Try These Fixes</u></a></li>
<li><a href="https://program-issues.techidaily.com/how-to-stop-black-desert-online-from-crashing-on-windows-1087-solved/"><u>How To Stop Black Desert Online From Crashing On Windows 10/8/7 (Solved)</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-3utools-virtual-location-not-working-on-realme-12-5g-fix-now-drfone-by-drfone-virtual-android/"><u>In 2024, 3uTools Virtual Location Not Working On Realme 12 5G? Fix Now | Dr.fone</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/indulge-in-pure-play-celebrating-the-top-10-offline-games/"><u>Indulge in Pure Play - Celebrating the Top 10 Offline Games</u></a></li>
<li><a href="https://solve-manuals.techidaily.com/instala-por-completo-el-sistema-operativo-de-tu-pc-usando-windows-nueva-guia-integral-formateo-y-reinstalacion-paso-a-paso/"><u>Instala Por Completo El Sistema Operativo De Tu PC Usando Windows Nueva Guía Integral: Formateo Y Reinstalación Paso a Paso</u></a></li>
<li><a href="https://extra-support.techidaily.com/making-words-dance-the-art-of-sculpted-photographic-content-for-2024/"><u>Making Words Dance The Art of Sculpted Photographic Content for 2024</u></a></li>
<li><a href="https://program-issues.techidaily.com/say-goodbye-to-interruptions-master-the-art-of-preventing-crashes-in-diablo-immortal-pc/"><u>Say Goodbye to Interruptions: Master the Art of Preventing Crashes in Diablo Immortal (PC)</u></a></li>
<li><a href="https://program-issues.techidaily.com/troubleshooting-frame-rate-drops-in-call-of-duty-modern-warfare-3-202-a-comprehensive-guide/"><u>Troubleshooting Frame Rate Drops in Call of Duty: Modern Warfare 3 (202^) - A Comprehensive Guide</u></a></li>
<li><a href="https://program-issues.techidaily.com/understanding-the-postponement-unraveling-death-stranding-launch-issues/"><u>Understanding the Postponement: Unraveling Death Stranding Launch Issues</u></a></li>
</ul></div>

