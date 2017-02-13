---
layout: inner
date: '2017-02-13 05:21 +0100'
ads: true
comments: true
lead_text: title
published: true
title: Evaluate your aerobic capacity with the Ruffier-Dickson index
---
The [Ruffier-Dickson index](https://es.wikipedia.org/wiki/Test_de_Ruffier#Variante:_.C3.8Dndice_de_Ruffier-Dickson) is a test to measure aerobic endurance, and thus a person's fitness level.

This index is a variant of the Ruffier index, defined by the French doctor [James-Edward Ruffier](https://fr.wikipedia.org/wiki/James-Edward_Ruffier).

According Wikipedia, the index is widely used in France. Actually the wiki article has not been translated to English as of now. 

This test is based on a formula that serves to obtain a coefficient that gives us an assessment about our fitness level. Said coefficient is obtained by performing 30 squats in 45 seconds. Here you can see an example:
{% include youtubeplayer.html id="2cevtUsyGX4" start=54 %}

To calculate the index, the following parameters are defined:


- <div>`P_0` = Heart rate right before the exercise begins </div>
- <div>`P_1` = Heart rate just when exercise finishes </div>
- <div>`P_2` = Heart rate after one minute recovery </div>

<div>`I_d = ((P_1-70) + 2 * (P_2-P_0)) / 10`</div>


<div>The test defines also four different fitness levels, depending on the value of `I_d`</div>

<div>`0 < I_d <= 3` excellent </div>
<div>`3 < I_d <=6` normal </div>
<div>`6 < I_d <=8` weak </div>
<div>`I_d >= 8` Inappropriate </div>

Now you can measure your Ruffier-Dickson index with my [new app](https://apps.garmin.com/es-ES/apps/3448594e-c17a-4c78-8ccf-5ec0cb2d10be). 

<img src="/images/cardiogram_512.png" width="400">
{% include freepik.html %}


Using the app is pretty straight forward. 

Just stay in rest position and press start. the following three phases will be automatically triggered:


- <div>15 seconds rest time, for estimation of `P_0`</div>
- <div>45 seconds exercise time. Here you have to perform 30 squats. At the end of this phase `P_1` will be estimated</div>
- <div>60 seconds recovery time, after which `P_2` and `I_d` are estimated</div>

Hint: you can use [this metronome](http://a.bestmetronome.com/) to help you keep the rhythm. You need to set the the *beats for minute* at 40 bpm, and do one squat per beat (or, alternatively, at 80bpm, for up & down beats). Press start and you are good to go. 

During the test, the watch will show you the phase you actually are in, and how many seconds remain till next phase:

<img src="/images/2017-02-13_04h16_30.png" width="400">


Once finished, the app will show the estimated index:

<img src="/images/2017-02-13_04h18_19.png" width="400">


After syncing your will find the Garmin Connect all calculated parameters:

<img src="/images/2017-02-13_04h57_02.png" width="200">


And of course, the heart rate chart during the 2 minutes of the test:

<img src="/images/2017-02-13_04h56_53.png" width="400">


What I like about the test: It is fast and easy. You can repeat the test every 4 weeks, and see how your fitness level evolves. 
<div>The formula makes sense: you will have a bad fitness level if your `P_1` was too high (exercise caused a huge increase in HR), or if `P_2` is not close to `P_0` after rest. </div>

<div>What I don't like: the one fits all approach. There might be fit people with higher than average HR values. Because their `P_1` is compared to a fix value, "70", they will have a higher (worst) `I_d` compared with people whose HR is average, even if they are not fitter. </div>

In the end, if you are beginning to exercise and want to know if you are fit enough for the task, talk to a doctor. 
<div>But, if you are already excercising, checking once in a while you `I_d` can give you an indication on how your fitness level evolves. </div>

As usual feel free to contact me for questions and requests. 

Cheerio!