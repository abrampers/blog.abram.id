+++
title = "WWDC19: Best Dub-Dub ever!"
author = ["Abram Perdanaputra"]
date = 2019-06-24T17:55:00+07:00
tags = ["tech", "conference"]
draft = false
+++

<div class="ox-hugo-toc toc local">
<div></div>

- [What is WWDC?](#what-is-wwdc)
- [WWDC Scholarship?](#wwdc-scholarship)
- [WWDC19](#wwdc19)
- [Lesson learned](#lesson-learned)
- [Final thoughts](#final-thoughts)

</div>
<!--endtoc-->

This year, I’m very lucky to be one of the WWDC19 Scholarship Winner from Indonesia to attend Apple’s event of the year. It’s obviously the best Dub-Dub ever since it’s my first time here! Dub-Dub 19 is an event packed with awesome things and I’m going to tell my story from the complete beginning. Here we go!

<a id="org98cdda5"></a>

{{< figure src="https://cdn-images-1.medium.com/max/6048/1*mMUmHriJt0p8Y2Z46gBZGw.jpeg" caption="Figure 1: HMIF ITB @ WWDC19 (Nicho, Abram, and Faza)" >}}


## What is WWDC? {#what-is-wwdc}

> The Apple Worldwide Developers Conference (WWDC, also known as Dub Dub) is a conference held annually by Apple Inc. in San Jose, California. Apple uses the event to showcase its new software and technologies for software developers. Attendees can participate in hands-on labs with Apple engineers and attend in-depth sessions covering a wide variety of topics. — Wikipedia

Enough from Wikipedia, for me, WWDC is an event where developers gather and obtain plenty of insights from Apple about their software. Even better, it’s an event where students (or recently graduated High School students) can apply and actually receive the scholarship to go to this event without spending a single penny.


## WWDC Scholarship? {#wwdc-scholarship}

The ****scholarship**** term here means that Apple will get you the WWDC ticket for ****free****. I repeat, ****for free****.

To submit, we have to create a Swift Playground that can be experienced in 3 minutes in iPad’s Swift Playgrounds or Xcode’s Playground. After submission, application will be judged based on:

-   Technical accomplishment
-   Creativity of ideas
-   Content of written response


### Application {#application}

On a beautiful morning on Thursday, March 15, 2019 Apple announced that they had opened WWDC Scholarship Submission and that all submissions are meant to be submitted before Sunday, March 24, 2019 at 5.00 PM PDT. Wow, 7 days to work on the submission? ****Challenge accepted****! I was quite surprised because they only gave us 7 days to work on the submission while previously the submission was up to two weeks long.

At first, I had an idea to create a real-time style transfer application in Swift Playground using UIKit, CoreML and probably camera for the real-time transfer, but after 5 days of working on it, the CoreML model decided to not cooperate. It always gave an error without any description. Frustrating.

This problem forced me to find something outstanding that works and was good enough to distinct me from other applicants. And some **Metal** struck my mind. “Why don’t I try to use [Metal](https://developer.apple.com/metal/) just like how I used OpenGL for my Computer Graphics assignment?” And after 2 sleepless nights, I did just that.

I’ve created a simple introduction to **Metal** using MetalKit named **Metalify**. Here's the [playground](https://github.com/abrampers/WWDC19-Submission) if you'd like to try it on your own.

<a id="orgfbd2a2b"></a>

{{< figure src="https://cdn-images-1.medium.com/max/2544/1*O64rdYG16VbLC7NK%5FcnA9g.png" caption="Figure 2: Scholarship email!" >}}

On another beautiful morning — Monday, April 15, 2019 — I received this email and my heart stopped for a second. Man! I got this. I was one of 350 students worldwide that got the scholarship. That was the best day of my college life yet 🤖.

As a scholarship winner, they told me that we would get free WWDC ticket, free lodging on the San Jose State University dorm, and free breakfast and lunch meal.


## WWDC19 {#wwdc19}


### Swag {#swag}

Fast forward to the Dub Dub week, we got to check in at the convention center and received some Dub Dub Swag for us to wear for the rest of the week. We got a reversible bomber jacket, a Scholarship Winner T-Shirt, and a few random pins including Indonesian Flag’s pin.

<a id="orgfb52590"></a>

{{< figure src="https://cdn-images-1.medium.com/max/6048/1*7sfvKXgFy2aoxf9QTMHpKQ.jpeg" caption="Figure 3: Bomber jacket + small Tim Cook pin" >}}


### Scholarship kickoff {#scholarship-kickoff}

After checking in, all the scholarship winner were scheduled to attend scholarship kickoff where Esther Hare [@EEhare](<https://twitter.com/eehare?lang=en>) was there to give a little talk. She encouraged us to talk to as many people as we can, whether it’s fellow scholars, developers, or even Apple engineers. And the coolest thing here is that there were plenty of Apple engineers standing by for us to talk to. I was very excited since I never had any chance to get to meet, better yet, talk to the engineers that build Apple. Besides, there were plenty of food trucks and drinks all over the place..

<a id="org68970ff"></a>

{{< figure src="https://cdn-images-1.medium.com/max/12000/1*Vu7eITgS5sivMkDNtPuOPw.jpeg" >}}

<a id="orgd37f799"></a>

{{< figure src="https://cdn-images-1.medium.com/max/2250/1*ogZQRMEFWxEP8y9bQvQ2jw.jpeg" caption="Figure 4: Beautiful weather @ Discovery Meadow with Indonesian scholarship winners" >}}

After the kickoff, a few of Indonesian scholars gather around and did a vlog about the Dub Dub. Here we go!

{{< youtube Ry0ezsPNt6I>}}


### Keynote {#keynote}

The long awaited keynote was there and many people called this ‘the most packed WWDC Keynote ever’. This includes the announcement of the brand new Mac Pro, iPad OS, iOS 13, macOS Catalina and the SwiftUI & Combine which were the star for the rest of the week.

<a id="orga5419d3"></a>

{{< figure src="https://cdn-images-1.medium.com/max/3264/1*7IDRGBs7cyfjNYCb4eQ9Sg.jpeg" >}}

The most exciting part of the Keynote was the announcement of SwiftUI. There, Craig Federighi showed how [SwiftUI](https://developer.apple.com/documentation/swiftui), with its declarative traits + [Combine](https://developer.apple.com/documentation/combine) (Apple’s framework for Async programming) made multi-platform development seems so easy and fluid.

Project Catalyst had also brought huge possibilities since it enables developer to bring iPad Apps (built using UIKit) to run in Mac (typically built using AppKit). iPads can now be used as a \*sidecar \*to Mac. These two features will bring iPads closer to Macs and vice versa.


### Scholarship Lounge {#scholarship-lounge}

Scholars were given the privilege to chill and have a chit chat with fellow scholars throughout the week at the scholarship lounge. Here, we were given a wired 10MBps connection to try all the Betas they announced.

<a id="orgbf9c01b"></a>

{{< figure src="https://cdn-images-1.medium.com/max/11228/1*HgGxRO1iodwpL36HH254nA.jpeg" caption="Figure 5: Scholarship lounge: Our home" >}}


### Pro studio {#pro-studio}

<a id="org9a8ebdd"></a>

{{< figure src="https://cdn-images-1.medium.com/max/8064/1*kmCk6hBke2b9lhluc6R04g.jpeg" caption="Figure 6: The recently announced Mac Pro" >}}

All the Dub Dub attendee got the chance to visit the Pro Studio across the Convention Center to see the newly announced Mac Pro in action. In this building, they showcased a few workflows dome with the Mac Pro. Photo editing workflow, real-time 8K raw video rendering, creating music orchestra, and 3D Editing. Having seen all these things and as someone who didn’t really understand it, Mac Pro seemed like a real deal.


### Sessions and Labs {#sessions-and-labs}

For the rest of the week, there were plenty of sessions and labs conducted all over the Convention Center. Sessions are more like seminars conducted by Apple where they showcase best practices, reveal new features in more detail, and give a bit of demo. Labs are the place to go if you have a bug, question, or a feature request and give it right to the engineers that work on that particular feature. Awesome! We could actually ask the person who was in charge of the product. What a way to solve a bug.

<a id="orga3bad91"></a>

{{< figure src="https://cdn-images-1.medium.com/max/8064/1*ZsvETrvysoT60qinnSB5yw.jpeg" >}}

<a id="org0e353d0"></a>

{{< figure src="https://cdn-images-1.medium.com/max/8064/1*G0I23P7UxXG8%5FcbAa94LIA.jpeg" >}}

<a id="org47c832c"></a>

{{< figure src="https://cdn-images-1.medium.com/max/2000/1*lT-EgnL2S5TZziXPU5-j9w.jpeg" >}}


### Games, Sporting Events, and WWDC Bash! {#games-sporting-events-and-wwdc-bash}

The sport activities was the High Intensity Interval Training by Aaptiv, WWDC 5K Run, and Yoga with Glo. They provided all the equipment for the training and let us have all the equipment. Note: They kinda gave us a $100 yoga mat LOL!

Throughout the week they conducted an AR game called SwiftStrike. It is a bowling game where the player had to hit down the opponent’s pin. At the end of the week, they conducted the SwiftStrike Championship and the funny thing is both the winner and the runner up are Indonesian 🇮🇩.

On the last night, Apple also invited the Weezers to the WWDC Bash (some kind of get-together concert) where we can chill out, enjoy the concert, and play games!

<a id="org3d5dbfd"></a>

{{< figure src="https://cdn-images-1.medium.com/max/2250/1*AiXv107iWKkFjHNFwlXAFQ.jpeg" >}}

<a id="org0121d4d"></a>

{{< figure src="https://cdn-images-1.medium.com/max/2250/1*a3GP1NeLhRs4ZSV0wcYW9Q.jpeg" >}}

<a id="org2bc6ed5"></a>

{{< figure src="https://cdn-images-1.medium.com/max/2000/1*-YJKq5HbYbGyURfclQbyBw.jpeg" caption="Figure 7: HIIT Morning Workout, SwiftStrike, and WWDC19 Bash!" >}}


## Lesson learned {#lesson-learned}

Meeting all those people in Dub Dub opened my mind about how I look at myself. Never think that we’re the smartest person in the room. I actually met the person that made the La Liga iOS App and all of these things pushed me to keep striving for greatness.

Second thing, as a developer we tend to focus on highly technical things. Here, I realized that the ability to communicate with other people is essential for a developer’s success. Trying to share and communicate what we have in mind will help us a lot in our everyday life.

The third and final thing is to never, ever underestimate a person, stay humble and respect everyone.


## Final thoughts {#final-thoughts}

After all, WWDC is a networking opportunity for many people. We can always see the sessions online, but the chance to speak with random people when queueing for the line is special. We never know what a short conversation with some random guy at Dub Dub can bring us.

> **Pro tip**: Bring your business card and talk to as many people as you can @ WWDC

<a id="org319346d"></a>

{{< figure src="https://cdn-images-1.medium.com/max/8064/1*d2QcqQotYDs202ALyQAdqg.jpeg" >}}

<a id="orgd6d1346"></a>

{{< figure src="https://cdn-images-1.medium.com/max/8064/1*vX4kZveZpYSZ4W9krHvhFw.jpeg" >}}

<a id="orgad7d8b8"></a>

{{< figure src="https://cdn-images-1.medium.com/max/8064/1*jr4w2Xikvy-La1rBAEWq2g.jpeg" >}}

<a id="orgdbfbf48"></a>

{{< figure src="https://cdn-images-1.medium.com/max/8064/1*Jo4PpChs5Mev8yYoKoAQng.jpeg" caption="Figure 8: Don't be shy and make new friends @ WWDC" >}}

This article can’t 100% express how I felt before and after WWDC, but I hope this will inspire many people to find their way to WWDC.

Hope to see more of Indonesians (especially ****HMIF ITB****) @ Dub Dub 2020!


### Links {#links}

-   [My WWDC19 Submission](https://github.com/abrampers/WWDC19-Submission)
-   [YouTube video](https://www.youtube.com/watch?v=Ry0ezsPNt6I)


### References {#references}

-   Pictures by [@SwapnanilDhol](https://twitter.com/SwapnanilDhol) and Apple
