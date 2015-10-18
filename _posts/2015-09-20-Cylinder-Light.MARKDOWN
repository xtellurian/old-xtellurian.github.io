---
layout: post
title: A Dynamic Cylindrical Lamp
date: 2015-09-20 05:15:13.000000000 +11:00
categories: [hardware, arduino]
tags: [diy]
status: publish
type: post
published: true
---

![A promising start]({{ site.url }}/assets/light1.jpg)

Want to make your own custom dynamic LED light?
## Ingredients:

* LEDs. As always, NeoPixels are the tri-colour LED of choice, due to their simple single-wire serial, and excellent choice of form-factors. I've used Sparkfun's [Flexible LED array](https://www.sparkfun.com/products/13304) because of its LED density, and the cool flexible PCB means I can easily make a cylindrical array.
* Arduino. I used an Uno for development, because its so easy to work with, but I'll me moving to a Pro-Micro for the final product, because its much smaller and can be hidden away inside the light.
* [Adafruit UART Bluetooth Module](http://www.adafruit.com/product/2479) (for remote controll from your phone).
* Outer Shell. Your going to need something to diffuse the light coming from your LEDs because point-sources suck! If you want to bust out, I recommend a nice piece of diffusing acrylic. It can get a little expensive if you can't find something second hand, but who say's the aesthetic is cheap?
* Inner shell/ frame. If you're using a flexible LED strip or matrix, then consider using a piece of PCV tubing for the internal structure. Otherwise, you could make do with wooden dowel or even one large piece of pine/ light timber.
* Outer Frame. Some pieces of workable wood, and some tools for woking it.
* 'Tronics, including DC power jacks, a decent 5V power supply (I'm using a 10A supply), some multi-core, etc.

## Code:

You can get download the Arduino code at my [github repository](https://github.com/xtellurian/LightAlarm).

If you want to control it via bluetooth, for now, you can use Adafruit's Android or iOS app to send colours and change modes.
