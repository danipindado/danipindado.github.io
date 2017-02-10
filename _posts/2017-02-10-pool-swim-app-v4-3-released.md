---
layout: inner
date: '2017-02-10 00:09 +0100'
published: true
title: Pool Swim app v4.3 released
ads: true
comments: true
lead_text: Imperial units are now supported. Heading calibration improved.
tags: garmin apps connectiq
categories: apps
---
Today I have released v4.3 of the Pool Swim app. 

The main topic is the support of imperial units. I have also fixed an issue which might cause affect the heading calibration. Hopefully some people will see the length detection improved. 

**Imperial units support**
A new application setting "_distance unit_" has been added. Application settings are those which are configured using Garmin Connect App in your Smartphone or Garmin Express in your PC. 

GC App:

<img src="{{site.baseurl}}/images/garmin express.png" width="400">


Garmin express:

<img src="{{site.baseurl}}/images/Screenshot_2017-02-09-22-17-35.png" width="400">


You will find two options there: meters and yards. 
From now on, the application setting "_pool length_" depends on the units chosen. This means, you don't need to convert to meters anymore. If you are swimming in a pool whose length is 30 yd, just set:


-pool length: 30
-distance unit: yards

If you set the pool length using the watch menu, the distance units will depend on the distance chosen:


- 25m, 33.33m, 50m => meters
- 25yds => yards

_Why am I not using the unit settings from your garmin connect profile?_
Because of you :) some users have told me, they tend to run in miles, but swim in meters. If I'd use the setting from the interface, then swim units would automatically be yards. By letting you configure the units, you get more flexibility. 

_How is this information displayed in Garmin Connect?_
Pretty much the same as before. ConnectIQ does not permit to modify the unit string on the fly. Therefore you won't see "m" anymore, but "u" :). 
There is an additional field called "distance unit" which shows the units valid for this activity (by the way, I have added also a field showing app version):

<img src="{{site.baseurl}}/images/Screenshot_2017-02-10-00-22-30.png" width="400">


Now, if you see the activity in your PC/MAC, you will not be able to see the "distance unit". Instead of "m" or "yd", number zero is displayed:

<img src="{{site.baseurl}}/images/imperial_GC.png" width="400">


I am innocent! This is a known Garmin Connect issue, which is documented [here](https://forums.garmin.com/showthread.php?362066-Fit-Contributor-output-string-to-Activity-Summary&highlight=setData+string). 
I considered, that maybe I shouldn't show the field. But given that the data is shown in the Garmin Connect App, I have decided to leave the fields there. Who knows, maybe Garmin guys will eventually fix it (Error was reported in September, therefore do not expect that this happens soon...)

_What happens with 3rd party sites?_
Nothing. This feature does not affect 3rd party sites. I have created additional data which is only shown in Garmin Connect. 3rd party sites access native data present in the FIT file, which is still there, nothing has changed. 
Which distance units are shown in the site, will depend on your profile. 
Take a look at this example. I have configured metric units in my www.sporttracks.mobi profile. 
If i swim two lengths in a 25yd pool, once the activity gets automatically synced, sporttracks will show 46m:

<img src="{{site.baseurl}}/images/sporttracks.png" width="400">


**Calibration improvement**
Pool Swim app was featured this weekend in [La bolsa del corredor](http://www.sport.es/labolsadelcorredor/pool-swim-app-connect-iq-natacion-piscina-garmin-forerunner-230-235/), one of the most important sports blogs in Spain. One blog reader, Luis, installed the app, and contacted me after having some issues with the length detection. 
A 18 emails afterwards and a couple of hours of fit file analysis, I think I might have found an issue causing lack of calibration in some activities. I cross my fingers. I hope this version will improve the accuracy for those of you who had issues. 

Remember that I make the app for free, it is just a hobby which somehow it is taken more time than I expected at the beginning. 

For any purchase using the amazon links in the site, i get a small tip back. And you still pay the same price. 

That's all for now. I hope you enjoy using the app. 

Cheerio!
