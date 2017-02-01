---
layout: inner
title: test
permalink: /test/
ads: true
published: true
---

One of the things I missed when I replaced my Suunto ambit2s by a Garmin FR230, was the [Sunset/Sunrise app](http://www.movescount.com/apps/app10000003-SunriseSunset). 
I usually jog at night, so I tend to look for illuminated places. Only during weekends, if I am lucky, I get to run in the forest. 
Living in Germany, days are very short in winter. So the app was very handy to figure out how much time left I had before it got dark. 

I found [this](http://souptonuts.sourceforge.net/code/sunrise.c.html) c program by [Mike Chirico](http://souptonuts.sourceforge.net/) which calculates sunrise & sunset time for given gps coordinates, and used it as basis for my [Sunrise/Sunset](https://apps.garmin.com/es-ES/apps/d4253bb4-1aaf-4538-be8f-5e2e864708ea#0) app. 

The app is actually a data field. This means, that you can use this field in any activity you have available in your watch. You just need to add the data field to one of the data screens.

You can 
{% include youtubePlayer.html id=rjnrgGX79ag start=480 %}


Pool swim is a [ConnectIQ app](https://apps.garmin.com/es-ES/apps/f134a024-6ee4-47d3-8aec-3a397e3c9733) for the Garmin FR230, FR235 and FR630. 

![swimming-pool-image](/images/swimming-pool.png){:class="img-responsive"}
{% include freepik.html %}

My previous running watch was a Suunto ambit2s. I used to combine the running watch with a Pebble smartwatch which I used as my day-to-day watch. 

But, the Pebble stopped working, and, feeling that the ambit was more watch that I needed (I am just a recreational runner), I got rid of it and bought a Garmin FR230 to fullfill both needs. Besides I am a tech geek and ConnectIQ platform was appealing. 

Then this year I have begun to swim... and given the lack of swim support of the FR230, I found the perfect excuse to write my first ConnectIQ app.

The app provides support for FR230, FR235 and FR630.
These are watches meant for runners. Therefore, Garmin did not include the swim pool mode. 

you can find the user guide [here]({{ site.url }}/downloads/pool_swim_user_guide.pdf) .
I know user guides are no fun. But I really recommend you to take a look. Most of the answers users have asked me since I released the apps are answered there. 

Just in case you don't read it, just a couple of hints:


 + the app, unlike most of you think, does not work on accelerometers. it works on the compass. 
 + For proper function, the app needs to figure out your pool's orientation. This happens during the first 10 seconds of the activity. **Please do not press start if you are not going to swim inmmediately**. Just saying.
 + **When you have a short break, press stop to pause the activity** (f.i. when resting, adjusting goggles, ...). Otherwise it is likely that the compass will eventually trigger a lap. 

Feel free to use the comment section below to ask any questions. 
Remember that you don't need to create a Disqus account in order to comment: just write your comment, click on the "Name" field below, and the option "I'd rather post as a guest" will pop up.

Last, but not least, I offer ads and affiliate links on the site. These links help me get more gadgets that I can show you here :) . And remember that you will still pay the same price for the product. 

Cheerio! 


