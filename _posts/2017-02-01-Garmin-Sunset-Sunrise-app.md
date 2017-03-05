---
layout: inner
date: '2017-02-01 23:32 +0100'
published: true
title: Garmin Sunset/Sunrise App
categories: apps
tags: garmin apps connectiq
ads: true
comments: true
lead_text: >-
  This is a Garmin data field showing how long you have before next sunrise or
  sunset, whichever comes first
---

One of the things I missed when I replaced my [Suunto ambit2s](http://a-fwd.com/es=danpinblo01-21&it=danpinblo03-21&fr=blodedanpin0d-21&de=danpinblo0d-21&uk=danpinblo-21&com=danpinblo-21&e=RR3Mjl7n30G6nQDUx3AT7&asin-com=B00C3REKUE){:target="_blank"} by a [Garmin FR230](http://a-fwd.com/es=danpinblo01-21&it=danpinblo03-21&fr=blodedanpin0d-21&de=danpinblo0d-21&uk=danpinblo-21&com=danpinblo-21&e=RR3Mjl7n30G6nQDUx3AT7&asin-com=B016PAPI3W){:target="_blank"}, was the [Sunset/Sunrise app](http://www.movescount.com/apps/app10000003-SunriseSunset){:target="_blank"}. 
I usually jog at night, so I tend to look for illuminated places. Only during weekends, if I am lucky, I get to run in the forest. 
Living in Germany, days are very short in winter. So the app was very handy to figure out how much time left I had before it got dark. 

You can find the app [here](https://apps.garmin.com/es-ES/apps/d4253bb4-1aaf-4538-be8f-5e2e864708ea#0){:target="_blank"}. 

<img src="{{site.baseurl}}/images/sunset (2).png" width="400">
{% include freepik.html %}


If you are curious about how the app works, take a look at [this c program](http://souptonuts.sourceforge.net/code/sunrise.c.html){:target="_blank"}  by [Mike Chirico](http://souptonuts.sourceforge.net/){:target="_blank"} which calculates sunrise & sunset time for given gps coordinates. 

The app is actually a data field. This means, that you can use this field in any activity you have available in your watch. You just need to add the data field to one of the data screens.

This great video by [Moxy monitor team](http://www.moxymonitor.com/){:target="_blank"} shows you how to add a ConnectIQ data field to an activity screen:
{% include youtubeplayer.html id="rjnrgGX79ag" start=360 %}

Once you have installed the app, there are some settings you can deal with. 

Settings can be adjusted by using garmin express (you have to connect your watch to your PC), or, my favourite method, Garmin Connect app in your smartphone. 
In GC app, open Garmin devices menu, and browse till your installed data fields, where you will find Sunset/Sunrise app:

<img src="{{{site.baseurl}}/images/Screenshot_2017-01-31-05-36-10.png" width="400">

In the configuration menu you will find these three settings:

<img src="{{{site.baseurl}}/images/Screenshot_2017-01-31-05-36-22.png" width="400">


+ **24h format**: obvious, isn't it? Depending on the setting, you will see 17:45 or 5:45PM. 
+ **show remaining time?**: if activated, it will show how long you have before next sunrise or sunset, whichever comes first.  Let's say sunset will be at 18:00. The time right now is 16:30. If you activate this setting, the data field will show ~~"-1:30"~~ "1:30" (one hour, thirty minutes before sunset - in v1.5 I have removed the minus sign. Due to a CIQ bug, the chosen font was rather small, see (https://forums.garmin.com/showthread.php?363186-Font-size-reduced-in-simple-data-field-when-returned-a-char&highlight=char+size+simple+data+field){:target="_blank"} ). 
+ **turn back alarm?**: If activated, the watch will vibrate and play a tone at the time you should be turning back. Coming back to the previous example, if your activity begins at 16:30 and you have therefore 90minutes before sunset, the alarm will be triggered after 45 minutes (at 17:15). Alarm is only triggered if sunset comes next. There will be no alarm if you are running at night and sunrise is approaching. 


Feel free to use the comment section below to ask any questions. 
Remember that you don't need to create a Disqus account in order to comment: just write your comment, click on the "Name" field below, and the option "I'd rather post as a guest" will pop up.

Last, but not least, I offer ads and affiliate links on the site. These links help me get more gadgets that I can show you here :) . And remember that you will still pay the same price for the product. 

Cheerio!
