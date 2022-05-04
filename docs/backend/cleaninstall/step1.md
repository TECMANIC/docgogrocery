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

After this, you have different courses of action. You can select the most comfortable for you. We will explain the most and easy common ways you can complete the task.

### Upload using HTTP File Manager
{: .mx-3 }
 Log-in to your web hosting services and access the File Manager provided within.
 {: .mx-3 }

There are different kinds of user interfaces on the Internet so we suggest you ask your Hosting Provider if there are further questions on how to upload zip file to the main folder. Usually when you upload the file this way root folder can be named "/" or "public_html" and file will be there.
{: .mx-3 }

Extract the files and you will have a similar view like the one it shows next.
{: .mx-3 }

![Requirements Verification Screen](/assets/images/backend_installer/uploadhttp.png)
{: .text-center }

### Upload using FTP or SFTP Software
{: .mx-3}

Select the FTP or SFTP Client you know is secure or the best option for you. We include a separate article to explain [How To Upload Files using FTP or SFTP Protocol](/docs/backend/how-to/upload-sftp.html)  
{: .mx-3}

## Access to the Web Installer through your Web Browser

Web Installer automatically detects your server meets minimal requirements before to continue. If everything works correctly, you should see this screen when you access http://[% DOMAIN %]/grocer/verification

![Requirements Verification Screen](/assets/images/backend_installer/req_ok.jpeg)
{: .text-center }