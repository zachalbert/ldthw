---
layout: post
title:  "Contrast of Hue"
date:   2017-01-01 13:37:11 -0700
tags:
- gestalt
- color harmonies
---
Contrast of hue is demonstrated by placing 3 triadic colors next to each other. The effect is strongest with primary colors, weakened with secondary colors, and weakened even further with tertiary colors.

### RGB, not RYB

The idea that red, yellow, and blue are primary colors is a misconception. It's true that `RYB` are effective primaries when mixing colors with opaque paint, but [it doesn't work with digital color]({{ site.baseurl }}{% link _color/030-color-models-rgb-vs-ryb.md %}).

### Color Vision

When discussing the contrast of hue, it's useful to understand how color vision works. In order to keep things practical, this will be a gross oversimplification of how color vision works.

The physical structure of your eye contains both rods and cones. There are three types of cones — long, medium, and short — and each type is more sensitive to a particular wavelength of light than the others. These cones *roughly* correlate to **red** light, **green** light, and **blue** light — though there is significant overlap. A primary color is a particular wavelength that activates one cone, while also having the least influence over the other two. There are three primaries because our eyes contain three cones.

That is a simplification of a complex topic involving the physics of light, the biological structure of our eyes, and the neurological processes that turn light waves into coherent images. However, since digital displays emit light and mix color in an additive fashion, `RGB` is a close approximation of how we perceive colors in the natural world.

### Making It Useful

You can use the concept of hue contrast to strengthen and energize triadic color harmonies. You will often see these types of color palettes used in brands associated with children. At the same time, if you're using a triadic palette that is too overwhelming, try rotating the triad away from the primary colors to reduce the hue contrast. Red, green, and blue will tend to have more contrast than the secondary colors cyan, magenta, and yellow.

<!--more-->
## Exercises

1. Open up the design document with all 7 contrast frames that you started in the [contrast overview lesson]({{ site.baseurl }}{% link _color/070-contrast-overview.md %}).
2. Zoom into the "hue-contrast" frame.
3. Select the frame, and change its background color to a medium gray: #C0C0C0. A gray background will minimize the influence of surrounding colors on the colors you're going to be looking at.
4. Draw a rectangle that is 160px wide, and 200px tall. Use the design panel on the right to move the rectangle to the x and y coordinates of 60, 0, respectively.
5. Next, duplicate that rectangle and move the second to x: 60, y: 200.
6. Duplicate the rectangle again, and move the third to x: 60, y: 400. You should now have 3 rectangles stacked on each other.
7. Make the color of the top rectangle pure red (hue 0°, full saturation and brightness). The middle rectangle should be pure green (hue 120°), and the bottom rectangle blue (hue 240°).
8. These 3 rectangles illustrate the purest form of hue contrast. Next, you're going to rotate the triad two full steps to "secondary" colors. Select all 3 rectangles, and `alt/option` drag them to the right, leaving 100px of space between.
9. From top to bottom, change this second column's fill colors to cyan (hue 180°), magenta (hue 300°), and yellow (hue 60°).
10. This second column of colors also displays hue contrast, though it is less extreme than the contrast from the "primary" colors red, green, and blue.
11. You're going to create a third column of colors by shifting the triad yet again, but this time you'll be shifting it a single step. Select all three rectangles in the second column, `alt/option` drag them to the right, again leaving 100px of space between the second and third columns.
12. In this third column, from top to bottom, change the fill colors to orange (hue 30°), blue-green (hue 150°), and violet (hue 270°).
13. This third column of colors also demonstrates hue contrast, but also to a lesser degree.

In the next lesson, you're going to learn about the contrast of saturation. Keep this design file handy.
