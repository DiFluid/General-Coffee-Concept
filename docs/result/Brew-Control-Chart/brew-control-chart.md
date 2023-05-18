---
layout: default
parent: Result
nav_order: 3
---

# Brew Control Chart
_🗺️ The treasure map to your golden coffee_

## Introduction
Brew Control Chart is a good tool for visualizing your brew result and point the direction for improvements if you know how to move on it. It's like a treasure map guide you to the gold. By marking your current location (Start) and your target location (Treasure), and successfully move your point to the target position, you will finally be able to find your golden coffee.

There is already plenty of articles introducing the history of this chart, so we are not going deep in this part. You can read more about it from the articles in [reference](#reference)

Today we are just focusing on how to use this map:
 - [Where am I](#where-am-i)
 - [Where to go](#how-to-read-it)
 - [Time to move](#time-to-move)
 

## 📍 Where am I?
_How to get my coffee onto chart_
 
The Brew Control Chart evaluate your coffee from two dimention:
1. [TDS - Total Disolved Solid, represents how much substance you have in your yield](../Coffee-Concentration-TDS/index.md)
2. [EXT - Extraction Rate, represents how much substance you have extracted from dose](../Extraction-Rate-EXT/index.md)

You can get the TDS (Total Disolved Solid) easily by using a refractometer like DiFluid R2 Extract.

<p align='center'>
 <img src="./static/R2-Test.jpeg" alt="R2 Test" width="400"></img>
</p>

And EXT (Extraction Rate) could then be easily calculated as long as you have the other weight info:

`EXT = YIELD * TDS / DOSE`

Now I'm going to use one of my morning brew for the demonstration for the following paragraph:
 - **Dose**: 15 Gram
 - **Water***: 225 Gram
 - **Yield**: 216.15 Gram
 - **TDS**: 1.17%
 - **EXT**: 16.86%
  
<p align='center'>
 <img src="./static/My%20Morning%20Brew.png" alt="Simple Brew Chart with Ethan's morning brew" width="400"></img>
</p>

You will see my result is posting on the left part of this brew control chart. While this point position is a relative position to the golden-cup standard you choose. If you refer to the pro-view of this graph, you will see the range of the this standard (here we choosed the latest SCA standard) plotted as a white square range.

<p align='center'>
 <img src="./static/SCA%20Standard%20Range.png" alt="SCA Standard Range" height="400"></img>
</p>

This square range will change while you switching between different standard, if you want to know about these standards, you can refer to (TODO: golden cup standard introduction).

Here we will just going on with the SCA standard as a reference. Just bear one thing in mind, follow your taste.

## 🧭 Where to go?
_What can I learn from chart?_

After getting your point settled on the 'map', you will then wondering which direction should I move. But hold on for a moment, and taste your coffee first. Although there are already many standards like SCA Golden Cup Standard giving an ideal extraction rate range, you should rely on your own taste to determine if it's good or not.

While you are reviewing your coffee, let's take a brief view on the two axis of 'map'.
1. **Verticle Axis** - This is the axis showing the strength of your coffee, if you think your coffee is too weak (taste like water) or too strong (flavorful and heavy)

<p align='center'>
 <img src="./static/Brew%20Control%20Chart%20Verticle%20Axis.png" alt="Brew Control Chart Verticle Mark" width="400"></img>
</p>

1. **Horizontal Axis** - The over/under-extraction may lead to sour/bitter taste. If you are feeling undesirable sour/bitter taste, then consider moving your point in the reverse direction of it.

<p align='center'>
 <img src="./static/Brew%20Control%20Chart%20Horizontal%20Axis.png" alt="Brew Control Chart Horizontal Mark" width="400"></img>
</p>

Okay, now you must be ready to determine your target point according to your subjective review? Still using my morning brew above as an example, it tastes a bit sour but okay for it's strength, so I'm planning to move the point rightwards a bit. The target is marked as a green point below.
<p align='center'>
 <img src="./static/My Morning Brew with Target.png" alt="Simple Brew Chart with a target" width="400"></img>
</p>

## 🏃‍♂️ Time to move
_How to move my point on chart?_

Got your target? Great, let's head for it! Here's two basic move you can conduct on this chart:
 
 <span style="color: red;">TODO: Do we need a detailed explanation for these two action about why it will work like this?</span>

 1. Change [Brew Ratio](): Change the dose or water weight along or together, but make sure don't increase or decrease them together, which won't change the **RATIO** of them.

<p align='center'>
 <img src="./static/Change%20Brew%20Ratio.png" alt="Change Brew Ratio" width="400"></img>
</p>

 2. Change [Brew Time](): Beside subjective control, [grind size](), brew tools, brew method, and many other parameters will all affect your brew time, we will talk about them in seperate articles (WIP). You could control it through speed up/ slow down brew process manually for simple.
 
<p align='center'>
 <img src="./static/Change%20Brew%20Time.png" alt="Change Brew Time" width="400"></img>
</p>

You may notice you don't have a way to move on the verticle or horizontal axis only, so in most time you have to combine these two basic action to achieve your target.

Let's get back to my morning brew example, so I want to move my point rightwards, which requires to change **[Brew Ratio]() lower** and **[Brew Time]() longer**.

Let me fall back my brew time to **2:10** and cut dose to **15 Gram**, and try it again. Indeed for demonstration, I conducted two brew with the first one decreasing the brew time only:

![Decrease Brew Time]() <span style="color: red;">TODO: Video or GIF</span>

And the second one decrease brew ratio depending on the last shot.

![Decrease Brew Ratio]() <span style="color: red;">TODO: Video or GIF</span>

Then you could see that the actions above all took effect and we successfully moved our step on this map. After reaching the desirable point, don't forget to take another review.

## Reference
 - [Towards a Common Coffee Control Chart](https://www.baristahustle.com/blog/towards-a-common-coffee-control-chart/)
