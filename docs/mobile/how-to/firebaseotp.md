---
layout: default
title: Configure Firebase OTP (OTP) 
parent: How To
grand_parent: Mobile App Configuration
---
# How to set up {{ site.prodname }} to work with Firebase One Time Password (OTP)

**You MUST follow all the steps correctly to implement Firebase OTP Authentication**

## Generate sha1 and sha256 key from Android Studio
1- Open your android module on your IDE. i.e: Android Studio. <br />
![Opening module on IDE](/assets/images/mobile/howto/openmodas.jpg)

2- Click on gradle tab, then navigate through folders shown and click on signinReport. <br />
![Process to gradle](/assets/images/mobile/howto/howtogradle.png)

3- That will show an screen like the one below. It contains SHA-1 & SHA-256 keys. You must copy them for later use on your Firebase Console<br />
![Generate SHA-1 & SHA-256 Keys](/assets/images/mobile/howto/gradlegenkeys.png)

4-  Wait until your gradle process finishes.

## Open your Firebase Console
1- Visit [console.firebase.google.com](https://console.firebase.google.com) and select your project.
![Select your project on Firebase Console](/assets/images/mobile/howto/consoleselproj.jpg)

2- After that, the interface will show you some options for your project. You must click on settings icon, like the image below.
![You must copy your keys to your app. To do that, go to App Settings](/assets/images/mobile/howto/consoleprojset.jpg)

3- Click on Add Fingerprint. Then copy your SHA-1 & SHA-256 keys and click on save after adding each one them.
![You must copy your keys to your app. To do that, go to App Settings](/assets/images/mobile/howto/consolesetkeys.jpg)


## Access Authentication Section
Now we must activate authentication services. To do that, follow the next steps.

1- Click on Authentication from sidebar.
![Select your project on Firebase Console](/assets/images/mobile/howto/consoleauth1.jpg)

2- Click on Sign-in method.
![Select your project on Firebase Console](/assets/images/mobile/howto/consoleauth2.jpg)

3- Click on Phone. It will show a modal window to enter the information. Click on save to finish adding phone
![Select your project on Firebase Console](/assets/images/mobile/howto/consoleauth3.jpg)

## Open Google Cloud Console

1- First, you have to access your Google Cloud Console [https://console.cloud.google.com/](https://console.cloud.google.com/). You must select the project you are going to configure. You will see an screen like the one below. 
![Google Console Cloud Initial Screen](/assets/images/mobile/howto/cloudstep1.jpg)

2-Select the project.
![Selecting the Project](/assets/images/mobile/howto/cloudstep2.jpg)

3- Select APIs and Services. Then select Library.
![Selecting Library Feature](/assets/images/mobile/howto/cloudstep3.jpg)

4- Proceed to type Android Device Verification. Click on the option.
![Accesing Android Device Verification Feature](/assets/images/mobile/howto/cloudstep4.jpg)

5- You must check if the option is enabled. If not, you must enable it by clicking on Manage button.
![Enabling API Feature](/assets/images/mobile/howto/cloudstep5.jpg)

6- Return to main screen and select your project again. You must download JSON File and then replace it with your existing one.
![Downloading JSON File](/assets/images/mobile/howto/cloudstep6.jpg)

<p class="text-center">
    <a href="/docs/mobile/how-to/" class="btn btn-purple">Return to Mobile Articles</a>
</p>

-----------
Your problem isn't included in the documentation? [Ask our experts](/sendingTicket)

