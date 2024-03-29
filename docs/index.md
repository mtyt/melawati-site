---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults
# I set the font size for the Oddity logo to 0 te temporarily remove it
layout: default
---

# Introducing...
 <p style="font-family:Melawati; font-size:0px">O d d i t y</p>
![Oddity picture](/assets/img/Oddity.jpg)
The Melawati Modular Oddity!

It's a semi-chaotic rhythm generator.

When the gate at the input is high, the module will calculate a path down to one of the 8 gate outputs, turning left or right at every junction (at every knob). The left or right bias can be tweaked by turning the knob in the desired direction. 

With all knobs centered, the odds of any of the 8 gate outs being high (when the gate input is high) is equal. This will give a perfectly random rhythm.

If the top knob is turned all the way to the left. 100% of gate signals will be "passed on" to the left side of the module (the first 4 outputs). The next knob will repeat this process, and pass the signal on to one of the two knobs below, based on the position of it's probability knob.

You can think of it as a modular pachinko machine with tweakable odds. Or a series of Bernoulli gates.

Additional features: 

1. Split mode: Re-assign the first stage as a split instead of a choice, in that the first junction will pass the signal on to both knobs. This will result in 2 active gate signals at the 8 outputs simultaneously (one on the left, one on the right).

2. Pattern mode: Bypass all knobs and instead play the last 16 gates on a loop. You can set the pattern size \[2-3-4-5-6-7-8-16\] during play using the rotary switch on the top left. The control for pattern mode is a 3 way switch which lets you read the pattern, bypass the pattern (but not overwrite it), or overwrite to the pattern. So you can lock the perfect groove, go back to chaos for fills and freakyness, but fall back to the previously saved pattern. The ideal groovebox.

## [Order now](mailto:melawatimodular@gmail.com)!
We are currently assembling the very first series of Oddity modules in our attic workshop.
You can already order a sweet Oddity module of the first batch for EUR 289.00 incl. VAT (+shipping)
by [sending us an email (melawatimodular@gmail.com)!](mailto:melawatimodular@gmail.com)

We will give you payment details and let you know when we can ship the module.
<div class="video-container">
<iframe src="https://drive.google.com/file/d/1FSJEjaDIyNVwu5K3IIR1cOkFSme4CK9F/preview" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
</div>
<br>


## Nerdy tech-talk and specs:
- The module width is 20 HP (101.6 mm), depth is about 25 mm
- Power through the 10-pin standard connector. We used a shrouded header for your convenience! We'll even ship you the cable (if we don't forget)
- The input is zener-diode protected and will limit any incoming voltage to 0-5V.
- The outputs are protected by diodes in order to protect the internal circuits if you
mess up your patch and route outputs to outputs. Just in case.
- The signals are processes by a microcontroller. It doesn't have infinite speed so if you
start inputting signals with extremely high clock rates, things will get funky - but funky is nice.