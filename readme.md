## Swim Safe

**Description**

A rails app built to scrape xml and html data from the city of Toronto website.  The website should display historical data and weather of all Toronto Beaches for the season (June to August).  The app should be able to get your current location and provide data for the beach closest to you.  The app should provide information about the blue flag criteria.  The app should use familiar icons from the city of Toronto website.  The app should provide a google map with each beach

**Getting started**

This app has 2 data sources which will be scraped on a daily basis.  The app will


1. Open data in XML format from the city: http://app.toronto.ca/tpha/ws/beaches.xml?v=1.0

2. Backup scrape to populate historical data is available from static html pages here:
http://app.toronto.ca/tpha/beach/9.html



**To do's**

* UI/UX layouts
* Write website content
* Rack cron task to pull data from XML
* Feed data into database
* Build data backup solution
* HTML scraper for historical data (need data from June 1)
* Recreate swim safe logos as svg for nicer display in app
* Pull in weather data to provide forecast
* Pull in historical weather data
* Build in Google maps with overlay with safety overlays
* Get analytics package running
* Finalize app name


**Done**

1. XML scraper
2. Swim safe icon set


