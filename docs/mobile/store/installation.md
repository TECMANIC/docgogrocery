---
layout: default
title: Installation
nav_order: 1
parent: Store App Setup
grand_parent: Mobile App Configuration
---
# Store App Installation
## Package Information

    App name: GoGrocer Store App
    Package name: com.gogroceruser.app
    Technology: Flutter (Cross Platform)

***

## Installation Guide 

### Requeriments to Install {{ site.prodname }} Store App

* Flutter properly Installed on your computer <small>**(follow the steps [here](https://docs.flutter.dev/get-started/install/windows))**</small>.

* To setup Flutter with VSCode <small>**(follow the steps [here](https://docs.flutter.dev/get-started/editor?tab=vscode))**</small>.

* Run the below commands in the Visual Studio Code Terminal
    
        flutter create -i swift -a java GoGrocer Vendor
        cd GoGrocer Vendor
        flutter clean
        flutter run
        

* To generate apk

        flutter clean
        flutter build apk --release 

<p class="text-center">
    <a href="/docs/mobile/store/" class="btn btn-purple">Return to Store App Articles</a>
</p>

-----------
Your problem isn't included in the documentation? [Ask our experts](/sendingTicket)