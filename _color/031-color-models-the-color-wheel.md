---
title: 'Color Models 4: the Color Wheel'
date: 2017-01-01 20:37:11 Z
tags:
- gestalt
- color harmonies
layout: post
video: color/color-models-04-the-color-wheel.mp4
todo:
- show both versions of the color wheel, either in this lesson or the last
- Show how the rotate copies tool works in sketch, or wait for updates to figma and
  update this video
---

In this exercise, you're going to be creating a color wheel from scratch. The color wheel is an abstraction, which maps the visible spectrum of light onto 360° of a circle.

In the [last exercise]({{ site.baseurl }}{% link _color/030-color-models-rgb-vs-ryb.md %}), we discussed 2 types of color wheel that use both `RYB` and `RGB` primaries. From here on out, you're going to be using the `RGB` version of the wheel.

### A Note About Numbers

While design tools *do* provide you with a way to visually adjust every color component, you can also use the number values to adjust color. If you're not a numbers person, bear with me and make a good effort to learn the underlying numerical values. While the numbers aren't strictly necessary to get good at manipulating color, they are a shortcut.

The following lessons will make heavy use of numerical values so that you can start to build an intuitive understanding of which values lead to which colors.

### Warm And cool

You may have heard the terms "warm" or "cool" to describe color. Warm refers to reds, oranges, and yellows, whereas cool refers to greens, blues, and violets. Warm colors are energetic and tend to dominate a viewer's attention, almost appearing to advance forward in space. Cool colors have the opposite effect. They are calming, and tend to recede in visual space.

The color wheel makes it very easy to understand how to change a color to increase or decrease its energy. While not divided perfectly in half, you can easily see that all warm colors are grouped together on one side of the wheel, and all cool colors are grouped together on the other side. To make a color more energetic, you simply need to shift it towards the warm side of the color wheel.

<!--more-->
## Exercise

1. In a new design document, draw a 100px x 100px circle. Give it a pure red fill color, or `#FF0000`.
2. Next, `alt/option` drag a copy of the circle straight down, leaving a 300px gap. Hold the `shift` key while dragging to constrain it to the same axis.
3. Now <span data-keyCombo="group">group</span> your two circles so that you can move them together.
4. With your group selected, <span data-keyCombo="duplicate">duplicate</span> it. In the design panel on the right, find the rotation input. Either type `30` to rotate the group by 30°, or hit the up key 3 times while holding `shift`.
5. Repeat this procedure 4 more times: duplicate, then increase the rotation by 30°. You're done when the 100px circles go all the way around.
<!--SKETCH: has the rotate copies tool-->
6. Select all 12 circles, and ungroup them. We're going to refer to circles as hours on a clock for ease of explanation from here on out.
7. Select the circle at the 1 o'clock position, then open the fill color options dialog. Make sure you're in `HSB` mode, then in the first input, increase the hue by 30°. Again, you can type it, or use `shift` and your arrow keys. Saturation and brightness should both be at 100%, but set them if not. The result should be an orange color.
8. Going clockwise for the remaining circles, increase the hue by 30° each time until you get to the 11 o'clock position.
9. Leave 12 o'clock as is – pure red. Red is where the color spectrum wraps around, so 360° is the same as 0°.
10. When finished, you should have 12 circles representing the full color spectrum. Group all circles together and name your group "color-wheel" (double click on the group name in the layers panel).

You now have an `RGB` color wheel, which you will use in future exercises. You're going to be using this same design file, so hang on to it.
