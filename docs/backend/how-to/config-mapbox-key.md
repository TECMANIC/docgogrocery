---
layout: default
title: Configure MapBox API
parent: How To
grand_parent: Backend Configuration
---
# How to set up {{ site.prodname }} to work with MapBox API

**You MUST follow all the steps correctly to access MapBox API Services available**

   1. Create and enter your credentials in [https://account.mapbox.com/](https://account.mapbox.com/). After accesing you should see an user interface like this one.

   ![MapBox UI](/assets/images/howto/accmapbox.png)

   2. Click on Create Token. You will be asked to name it and assign the permissions or URL restrictions for the token. After setting the configuration, you must click on Create Token button.


After you see the new token on your web interface, your API Token is now operative and you can copy the token to your {{ site.prodname }} WebPanel using the button assigned to copy it to your clipboard. That will avoid errors in backend while adding delivery boys, stores and areas.

Now, you can complete the set up of your Backend to use MapBox API, by following this steps:

1. You must log in with your credentials in admin panel. After that, locate on your navbar the option **Web and App Settings**. If you followed this steps. You should see an screen like the one below.
![Web and App Settings](/assets/images/howto/changewappconf.png)

2. Click on Map Settings Nav Links to your right. This will scroll your webpage to Map Settings Section and looks like the screenshot below. Click on the edit button.
![Map Settings Section](/assets/images/howto/mapsettingsarea.png)

3. Select MapBox OptionBox to access the interface to input the key in.
![Enter your MapBox API Key](/assets/images/howto/editmapbsettings.png)

4. Click on MapBox On button to save the API Key in the database.

<p class="text-center">
    <a href="/docs/backend/how-to/" class="btn btn-purple">Return to Backend Articles</a>
</p>

-----------
Your problem isn't included in the documentation? [Ask our experts](/sendingTicket)

