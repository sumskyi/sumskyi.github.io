---
layout: post
title:  "Do not sleep when electricity appears!"
date:   2022-12-18 09:26:54 +0200
<!-- categories: jekyll update -->
---
How to set the phone to wake you up as soon as electricity appears in the house.

TL;DR

***

How to wake up at night to do something as soon as the electricity comes on.  
An idea came to mind (working and tested).

Because it is uncomfortable to fall asleep with the light on, and when the light is turned on in the middle of the night, it will not wake me up at all.  
And you have to work while you have it, but there is a way to wake up properly.

Solution for Android.
---------
1. You download (playmarket banned them) [Automagic_1_38_0.apk][automagic_apk] and install, run, and give the program all (reasonable) permissions, when it asks for something.  
Don't worry, and allow it.

2. The song is downloaded according to your taste, like [путін - хуйло][khuilo]  
Here is a concise and original one with a length of `0:34 seconds`. Checked.  
![putin khuilo](https://i.ibb.co/6NFskB7/Screenshot-2022-12-18-at-17-59-27.png)  
<br/>
<img src="https://scontent.flwo6-1.fna.fbcdn.net/v/t39.30808-6/319832605_645702994002269_928645429315344335_n.jpg?_nc_cat=103&ccb=1-7&_nc_sid=8bfeb9&_nc_ohc=78A4iY1RPdkAX_g4ZoC&_nc_ht=scontent.flwo6-1.fna&oh=00_AfCQ2VC4LfO6WPJPmz07knTODcyj5OSZQVdTn6v4aRallA&oe=63A49F1C" width="300" />

3. The behavior model of the application is as follows:
- Event (trigger)
- Conditions (restrictions)
- Action (what to do)

4. How I did it, conditions and technical rationale:
- the electricity turns on, suddenly! And you are sleeping!!
- both the router and the Internet are automatically turned on  
(in my case)
- the phone itself sees that there is a Wi-Fi connection and connects to it

5. At this stage, the trigger on the phone works - yes, there is Internet, which means there is electricity, the trigger clicks.

6. It is necessary to register triggers in this program and how to react to them.

7. In the picture:
![Automagic Schema](https://scontent.flwo6-1.fna.fbcdn.net/v/t39.30808-6/320569238_1527817767716367_6933223202660753450_n.jpg?_nc_cat=107&ccb=1-7&_nc_sid=8bfeb9&_nc_ohc=FRBbOLvmoXMAX_wPtcn&_nc_ht=scontent.flwo6-1.fna&oh=00_AfBkgxGQ2rpA_OwVAD1T_hSIvCOX_HKfXciEOMFVsTMeGA&oe=63A37BCE)
- Wi-Fi, which points to respond to
- we wait 20 seconds (for example, when Wi-Fi is already available, and the provider has not yet working)
- "putin - khuilo", this is what we need, a cheerful song will play - see the screenshots, how it is set up.  

Voila! And before, people did not sleep at night because of this at all.

{% include disqus.html %}

[automagic_apk]: https://automagic4android.com/automagic/download/Automagic_1_38_0.apk
[khuilo]: https://useraudio.net/search/%D0%BF%D1%83%D1%82%D0%B8%D0%BD-%D1%85%D1%83%D0%B9%D0%BB%D0%BE
