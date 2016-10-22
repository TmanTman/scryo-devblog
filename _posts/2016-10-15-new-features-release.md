---
layout: post
title: New features released on Scryo
---

This post will quickly go through all the new features of Scryo. It's super exciting to share this
with you! Months ago I could only imagine all these features and now here it is.

The core feature around which Scryo was designed is whiteboard calling. It allows two people
to have a call between them, each using their own smartphone, tablet or computer. On-screen they have a realtime shared
whiteboard, and with the live audio connection they can discuss whatever they're doing as in a normal phone call.
Check it out:

<iframe width="560" height="315" src="https://www.youtube.com/embed/ueMS6f_ZXuE" frameborder="0" allowfullscreen></iframe>

I built it for myself, but to test it for other people I gave it to a teacher to use
with his pupils. The feedback after the experiment was

 - It's not ideal to learn how to use the canvas only once you're in a call
 - It's only necessary to use the live whiteboard calling once in while. That's long enough
 to forget that you have the app.

I had already known that Scryo can be really useful if it had a messaging feature as well.
But sending an image doesn't really get a complex concept across. Besides, there is already
apps that can take pictures, edit and send it. So I focused on building a whiteboard recording
feature, to record whatever you draw on your canvas on-screen as well as your voice, and send
that as a message:

<iframe width="560" height="315" src="https://www.youtube.com/embed/ZqXeiBPysvk" frameborder="0" allowfullscreen></iframe>

Soon, it should also be possible to send this recording to someone via an external messenger, such
as Whatsapp. (For the curious, that can be done once the support for canvas recording lands
in Chrome 52 on [Crosswalk](https://crosswalk-project.org/), probably December 2016).

Since I had to build a messaging infrastructure into my app, it was minimal work to add
the feature to send images:

<iframe width="560" height="315" src="https://www.youtube.com/embed/e1b9dD3ygTo" frameborder="0" allowfullscreen></iframe>

And lastly, if you can send images inside Scryo, then it would make sense to be able to
send it to anyone, even if they don't have Scryo:

<iframe width="560" height="315" src="https://www.youtube.com/embed/FA7D4B6Mg5k" frameborder="0" allowfullscreen></iframe>

This caters especially to sending to someone on iOS, where the app is not yet available.

At this stage there are multiple paths forward. If I sit down and think of new features, I can think of probably 20. But
using the app makes it clearer what the way forward should be. So for the next couple of weeks, I'll be engaged with a focus group
again to see how these new features can help them!

Best regards,

Tielman
