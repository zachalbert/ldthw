---
layout: post
title:  "Color Variants: The Alpha Channel"
date:   2017-01-01 13:37:11 -0700
tags:
- color
---
In the last few exercises, you explored creating tints, shades, and tones. In this exercise, we're going to talk about the alpha channel, which controls the opacity of a color.

Opacity can be used in a variety of circumstances. It is commonly for overlay effects, such as drop shadows or adding text or icons on top of a chaotic image. Even if the goal is a subtle gray drop shadow, using a pure gray color will look different depending on the background it's placed on. Using pure whites or blacks plus a low alpha value will allow you to achieve the same effect in a more consistent and flexible way.

In this exercise, you're going to create an icon color that appears consistent no matter what background it's placed on.

<!--more-->
## Exercise

1. In a new design document, draw a rectangle that is roughly 500 x 1000. Create a second copy of the rectangle just to the right of the first.
2. Make the fill color of the first rectangle `#CFCFCF`. The second rectangle should have a fill of `#564D66`.
3. Near the top of the first rectangle, draw a roughly 100 x 100 star by clicking the `shape tools` dropdown in the top bar. Set the fill to `#9B9B9B`.
4. Create a copy of the star and move it to the top of the second rectangle. Even though it's the same color as the first star, notice how much more it stands out against the dark background? In mathematical terms, the contrast ratio between the first star and its background is 1.3, but 4.0 between the second and its background.
5. This isn't a very versatile icon as a result. On some backgrounds it's going to be barely visible, and on others it's going to stick out like a sore thumb. The solution is to use opacity. Select both stars, and create copies by `alt/option` dragging them directly beneath the first set.
6. With both stars selected, change the fill color to pure black, by reduce the alpha to 12%.
7. Notice that the second star is virtually the same color as the first? The biggest change is to the second star, which contrasts with its background in close to the same way as the first. Mathematically, the contrast ratios are now 1.3 and 1.2, which is much more consistent.
8. With both stars still selected, create a third set of copies beneath the second. Now, change the fill color to pure white, with an alpha value of 30%. In the same way as the second set, the third set has a more even contrast across different backgrounds.

You have now explored the different ways to modify a single color. In the next series of exercises, you're going to learn about combining different colors together to create color palettes that are harmonious and achieve a desired effect.
