---
layout: default
title: Step 1 - Set up & configure environment
nav_order: 2
parent: Backend Configuration

---

# Step 1 - Uploading and Accesing Web Installer

## Upload the compressed file to your server

You will need to upload zip file to your server and extract it there. There are different options to achieve the task.

1. Unzip the source file you received from your purchase in CodeCanyon.

2. Open the uncompressed folder and locate the ZIP File named "Backend.zip".

After this, you have different courses of action. You can select the most comfortable you feel with. We will explain in detail the options that can help you to complete the task.

### Upload using HTTP File Manager
{: .mx-3 }
 Log-in to your web hosting services and access the File Manager provided within. Upload backend zip file in root folder.
 {: .mx-3 }

There are different kinds of user interfaces on the Internet. Usually, when you upload a file this way, the root folder can be named “/” or “public_html” and you can find the file there. We suggest asking your hosting provider or server admin, if the file can not be located or if you may need further assistance in regards to the path through which uploaded files are addressed.
{: .mx-3 }

Next, extract the files and you will have a similar folder structure to the one in the image.
{: .mx-3 }

![Requirements Verification Screen](/assets/images/backend_installer/uploadhttp.png)
{: .text-center }

### Upload using FTP or SFTP Software
{: .mx-3}

Select the FTP or SFTP Client you know is secure or the best option for you. We include a separate article to explain how to use one if this is your first time [How To Upload Files using FTP or SFTP Protocol](/docs/backend/how-to/upload-sftp.html)  
{: .mx-3}

## Access to the Web Installer through your Web Browser

Web Installer automatically detects your server meets minimal requirements before to continue. If everything works correctly, you should see this screen when you access http://[% DOMAIN %]/ it should redirect you to http://[% DOMAIN %]/verification, or you can access the last direction yourself to start web installation.

![Requirements Verification Screen](/assets/images/backend_installer/req_ok.jpeg)
{: .text-center }

<p class="text-center">
    <a href="requirements.html" class="btn btn-purple">Prev Step</a>
    <a href="step2.html" class="btn btn-purple">Next Step</a>
</p>