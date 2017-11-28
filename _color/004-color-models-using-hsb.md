---
id: 004
layout: post
title:  "Color Models 1: Using HSB Mode"
video: color/color-models-01-using-hsb.mp4
date:   2017-01-01 13:37:11 -0700
tags:
- color
---
* Why HSB is better
* How you're going to learn more about it later, but short term, just f'in use it.

On a digital display, there are *millions* of possible colors. The labels we typically use to talk about colors are grossly inadequate from a design perspective. Even some of the more specific labels you might see at a paint store like "forest green" could refer to a thousands of possible greens.

Using these color labels is like telling the postal service you live "somewhere in the lower east side of Manhattan" and hoping they send your mail to the right location. You *could* get more specific and provide GPS coordinates to ensure accuracy, but it would also be impossible for a human to decipher without an electronic tool. A street address, however, is both accurate and easy for a human to understand with minimal assistance.

### HSB is Like a Street address

Digital color uses what is called the `RGB` color space, which is an acronym for **red**, **green**, and **blue**. `RGB` notation looks like this: `forest green = rgba(0, 117, 31, 100)`. While it is very accurate, it's not very human readable. `RGB` notation is like a set of GPS coordinates.

On the other hand, `HSB` mode also points to an `RGB` address, but is much easier to understand for humans. The components of `HSB` are **hue**, **saturation**, and **brightness**. It's like providing a street address instead of GPS coordinates.

### Changing Modes

<!--more-->
## Exercises

1. Draw a circle of any size, and <span data-keyCombo="copy">copy</span> and <span data-keyCombo="paste">paste</span> this hex value into the shape's fill color: `#47D9BF`.
2. Next, click the color tile next the hex value you just pasted. This will open the color picker dialog.
3. Change the mode dropdown to `RGB`, if it isn't already set. The 3 inputs to the right of this dropdown represent the red, green, and blue channels — which dictate the mixture of each in the final color. The fourth input on the far right is the alpha channel, which deals with the opacity of the color.
4. Now, in the first input (which represents red), use the up and down arrow keys to try changing the color from teal to red. You'll quickly notice that it's impossible using the red channel alone. Confused? You're not alone.
5. Next, you're going to solve the confusion. Change the color mode from `RGB` to `HSB`. While the two modes are interchangeable from the perspective of a computer, `HSB` is a significantly easier to read and understand to humans. The 3 inputs to the right of the mode dropdown represent **h**ue, **s**aturation, and **b**rightness (the fourth is the alpha channel, just like with `RGB` mode).

| **Hue** | *Hue represents the specific color, which we use terms like "red" or "blue" to describe. Measured from 0° - 360°.* |
| **Saturation** | *The purity of the color, measured from 0–100%. A fully saturated color is bright and vibrant, and a fully desaturated color is pure gray.* |
| **Brightness** | *The amount of light in the color, measured from 0–100%. 0% brightness is pure black, and 100% is the brightest form of the color.* |

6. Now in `HSB` mode, use the up/down arrow keys in the first input to adjust the hue to a red color. You can either use a very low number (close to 0°), or a very high number (close to 360°). Hue corresponds to the degrees of a circle.
7. Now change the hue to green. The purest green hue is 120°.
8. Now change the hue to blue using only the hue input. Can you find the purest form of blue? If you're mathematically inclined, you might notice that the purest blue follows a pattern.
9. In the second input (saturation), make the blue fully saturated at 100%, then fully desaturated. A fully desaturated color is also called a "neutral" tone.
10. In the third input (brightness), increase and decrease it fully. Try to achieve pure black using only the brightness input.
11. Finally, using only the saturation and brightness inputs, try to achieve pure white, pure black, and a middle gray.

This has been a brief introduction to modes of picking color. You're going to dive deeper into these topics in future lessons, but for right now, make sure you're using HSB mode.
