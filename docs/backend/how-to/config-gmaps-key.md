---
layout: default
title: Configure Google Maps API
parent: How To
grand_parent: Backend Configuration
---
# How to set up {{ site.prodname }} to work with Google Maps API

**You MUST follow all the steps correctly to access Google Maps API Services available**

   1. First you must visit this link [https://developers.google.com/maps/get-started](https://developers.google.com/maps/get-started)
   2. Create your account & set up your Billing method as well (mandatory)
   3. Setup your project in [https://developers.google.com/maps/get-started#create-project](https://developers.google.com/maps/get-started#create-project)
   4. Make sure Maps API is enabled from here: [https://developers.google.com/maps/get-started#enable-api-sdk](https://developers.google.com/maps/get-started#enable-api-sdk)
   5. Create an API Key: [https://developers.google.com/maps/get-started#api-key](https://developers.google.com/maps/get-started#api-key)
   6. To test your Google MAPS API Key, you must insert the generated key in the following URL Pattern **WITHOUT BRACES** in a software like Postman. 

    https://maps.googleapis.com/maps/api/geocode/json?latlng=-27.0000,133.0000&key={YOUR_API_KEY} 

If you receive a response, your API is now operative and you can copy the key to your {{ site.prodname }} WebPanel. That will avoid errors in backend while adding delivery boys, stores and areas.

You can complete the set up of your Backend to use Google Maps API, by following this steps:

1. You must log in with your credentials in admin panel. After that, locate on your navbar the option **Web and App Settings**. If you followed this steps. You should see an screen like the one below.
![Web and App Settings](/assets/images/howto/changewappconf.png)

2. Click on Map Settings Nav Links to your right. This will scroll your webpage to Map Settings Section and looks like the screenshot below. Click on the edit button.
![Map Settings Section](/assets/images/howto/mapsettingsarea.png)

3. Select Google Map Option Box and enter your key in the input designed for it.
![Enter your GMaps API Key](/assets/images/howto/editmapsettings.png)

4. Click on Google Map On Button to save the API Key in the database.

<p class="text-center">
    <a href="/docs/backend/how-to/" class="btn btn-purple">Return to Articles</a>
</p>

-----------
Your problem isn't included in the documentation? [Ask our experts](/sendingTicket)

