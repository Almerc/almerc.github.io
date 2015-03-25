---
layout: post
title: Soldering and Screaming
---

Guitar stompboxes were once an addiction of mine. Collecting and building a monster pedal board to experiment and combine effects, often resulting in a cacophony of psychadelic noise, was a lot of fun and I spent an obscene amount of money trying to build my dream setup for jamming on. Recently I came across a website for pedal kits [Fuzzdogs pedal parts](http://shop.pedalparts.co.uk/) and was interested to get inside the stompbox and learn a bit how they work , improve my soldering skills and hopefully end up with a useable Tubescreamer to play with.  

The [Tubescreamer](http://shop.pedalparts.co.uk/Tube_Screamer_TS808__TS9/p847124_7462506.aspx) kit I received is modeled on  the Ibanez TS808 and TS9 ,Stevie Ray Vaughan signature sound, which go for around £150. If I could put one together for £35 (including the case) and get close to that sound it'd be a bargain and the knowledge would be invaluable if I needed to repair or do a mod project in future.  

I'm fairly new to soldering electronics so spotting how small the the pcb board was (50 x 37mm!) and how many components there were was pretty daunting. Luckily for me Fuzzdogs kit came with very clear [downloadable instructions](http://pedalparts.co.uk/docs/TubeScreamer2.pdf) with an easy to follow circuit diagram and components labeled on the pcb. The only major thing you need to identify is which resistor is which. This can be done by using a helpful [colour code chart](http://www.digikey.co.uk/en/resources/conversion-calculators/conversion-calculator-resistor-color-code-4-band) OR ,if you're eyes are hurting from squinting to make a judgment call on whether the ring is red,orange or brown, then you could also use a [Multimeter](http://en.wikipedia.org/wiki/Multimeter) to double check.

I highly recommend using a [Helping Hands with a magnifying glass](http://www.amazon.co.uk/dp/B00NY8YBAA?psc=1) to hold the pcb still whilst you do the work. This saves a lot of frustration when
placing and soldering components and inspecting any dodgy solder work.

####Reading resistors and soldering components on the pcb

![PedalAssemble]({{ site.baseurl }}/images/pedal1.jpg "PedalAssemble")

Next came the moment of truth. Testing the circuit. For this Fuzzdog recommends wiring up the battery and the input and output jacks before getting carried away with all the switch,knobs etc. This turned out to be incredibly sage advice as the led light lit up but no fuzzy goodness came out of the pedal. Time to debug.

I had deduced the led circuit and power wiring was fine due to the led switching on but by going back over the circuit/pcb diagram I found a couple of reasons why I was so fuzzless. 1. I had missed a very small jumper wire over the points labeled 'accent' to complete the circuit and 2. A transistor was the wrong way round. Rookie mistake on my part but important lessons learned about transistors and gave me a chance to practice some desoldering technique. Another essential tool helped me with this ,the [desoldering pump](http://en.wikipedia.org/wiki/Desoldering#Desoldering_pump).

####Debugging the circuit

![PedalAssemble]({{ site.baseurl }}/images/pedal2.JPG "PedalAssemble2")

####Wiring the switch and dc power

![PedalAssemble]({{ site.baseurl }}/images/pedal3.JPG "PedalAssemble3")

####Wiring and re-wiring the knobs to fit in the case

![PedalAssemble]({{ site.baseurl }}/images/Pedal4.JPG "PedalAssemble4")

####A working Tubescreamer

![PedalAssemble]({{ site.baseurl }}/images/Pedal5.JPG "PedalAssemble5")

As part of the kit Fuzzdog had given some mod options including extra components for asymettrical clipping and space on the board for a more bass mod which I plan to do in future when I feel like I've exhausted the multitude of settings I have to play with already. I've also asked a mate for a design to go over the bright green sprayed case. I'll post the last pic of the final design when it's complete. 

Do you have any tips or had experience making a similar kit?
