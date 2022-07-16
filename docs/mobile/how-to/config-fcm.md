---
layout: default
title: Configure Firebase Cloud Messaging (FCM) 
parent: How To
grand_parent: Mobile App Configuration
---
# How to set up {{ site.prodname }} to work with Firebase Cloud Messaging (FCM)

1. Go to [https://console.firebase.google.com/](https://console.firebase.google.com/)
2. Create a new Project with your App name & click Continue
![We recommend you use your App Name to easily identificate your project](/assets/images/mobile/howto/fcmst1.png)

3. Select your analytics account & Click Create Project
![Please provide your analytics account](/assets/images/mobile/howto/fcmst2.png)

4. Click Android icon to create your app i.e. User App
![Click on Android Icon to generate the code for Android Platform](/assets/images/mobile/howto/fcmst3.png)

5. Type your Customer App Package name (it can't be changed so choose wisely). When you complete all needed information, click on Register app.
![Please select package name carefully due it can't be changed after selected](/assets/images/mobile/howto/fcmst4.png)

6. Download the google-services.json file as it's important for Customer App Setup.
![Download the JSON file being generated](/assets/images/mobile/howto/fcmst5.png)

7. SIMILARLY, create other 2 apps as well, Store & Driver App, follow the steps and choose unique package names & download the JSON files for all 3 apps.
![Repeat the procedure for the 2 apps left](/assets/images/mobile/howto/fcmst6.png)

<p class="text-center">
    <a href="/docs/backend/how-to/" class="btn btn-purple">Return to Articles</a>
</p>

-----------
Your problem isn't included in the documentation? [Ask our experts](/sendingTicket)

