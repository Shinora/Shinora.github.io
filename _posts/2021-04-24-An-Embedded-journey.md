---
layout: post
---

Hello, this 'thread' ( i will start calling them like that because it isnt something i write on one bloc, it is more some little pieces of adventure i share )
is going to be about embedded systems. I has always been attracted to building and doing things with my hands so yeah embedded it that plus some programming which also is a hobby of mine. So yeah seems like a good compromise... 
Years ago i received an arduino and i tried my best to do things with it but i wanted ( and still want ) to create and build fast which is very bad for the learning and unserstanding process. Anyway i stopped and i wanted to pick it again after learning some code and some C. But ark the arduino interface and langage...I don't like it so i thought : let's take off that abstraction layer and look at what's under the hood. That's what i bought a STM32, more exactly a STMF013CT6 or bluepill ( it's a more friendly name ).

![The bluepill](/assets/images/bluepill.png)

OK i figured after that i had to buy a st-link : sure, done thing. And now i have everything, i look at some documentation and wire this thing. Learn a little bit of HAL, just enough to make a blinking led, do that and try to compile the program. Oh i need to mention i was using STMCUBEIDE. OK code compiles fine, but hey that was too easy, i get that weird error :

>Error in initializing ST-LINK device.
>Reason: ST-LINK: Could not verify ST device! Abort connection.

I am still stuck with this, my wireing seems fine, tried the two jumper modes on the controller. 

![Enough]](/assets/gifs/tired.gif)

So yeah maybe that was too much for a start, i will stuck a little bit with arduino, coding in C and getting rid of arduino IDE. Maybe try to resolve that issue with my bluepill or buy a nucleo with st-link in it : it is more reliable and the documentation will be way much better. 
Anyway ill try to post some updates about the arduino and embedded progress. 