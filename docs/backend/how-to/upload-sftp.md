---
layout: default
title: Upload using SFTP Protocol
parent: How To
grand_parent: Backend Configuration
nav_order: 1
---
# Upload files to your server using FTP or SFTP (Secure FTP).
<hr />

Selecting FTP or SFTP Software can be a challenge if this is your first time doing it. But, no worries, we are here to help you and recommend one of the best cross-platform software that exists. We are talking about [FileZilla](https://filezilla-project.org/). 

This software is open-source software licensed under GPL, which means that you only need to download the binaries and install them in your terminal. Of course, this product only covers the main features. If you would like more advanced features you can review [FileZilla Pro](https://filezilla-project.org/filezilla_pro.php).

Here is a screenshot of how the user interface may looks.
![FileZilla User-Interface](/assets/images/howto/using-filezilla.jpeg)

Now we are going to cover the basics so you can connect to your server using FTP or SFTP Protocol.
## Connecting to your server using SFTP Procotocol
We recommend this protocol to stablish a secure connection to your host to upload files. Because, when you connect through this protocol you ensure that uploading files gets the best encryption possible until it reaches the destination.

To complete the steps we are going to mention, focus on this section in the user-interface
![Input here the information](/assets/images/howto/quickconnect-sftp.png)

1. In the field Host, enter sftp.yourdomain.com, substituting “yourdomain.com” with your own domain name. Write in lowercase only, and do not use “www” in front of the domain name.
2. Enter your Username, some servers are configured using your domain name (yourdomain.com), also without “www”. If there are any doubts ask your system's administrator or check server configuration.
3. Enter your Password. This should be the one you choose for SFTP/SSH when activating access in the control panel.
4. Enter the Port number. For SFTP, default port this is 22.
5. Click on Quickconnect or press Enter to connect to the server.

If SFTP Protocol would not be available in your server, you can connect over FTPS **(just use ftps:// before your domain name to use FTPS Protocol)** which still adds a layer of security when connecting to a remote host. If not possible, then do it over FTP protocol.
## Connection using FTP Protocol
If you would like to connect over FTP Protocol, repeat steps above but use ftp as a subdomain, using always lowercase only, and avoiding the use of "www" in front of the domain name.

-----------
Your problem isn't included in the documentation? [Ask our experts](/sendingTicket)