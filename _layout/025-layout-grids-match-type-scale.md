---
layout: post
title:  "Layout Grids: Matching Your Type Scale"
date:   2017-01-01 13:37:11 -0700
tags:
- grids
- layout
---
In this exercise, you're going to set up new frames that mirror a typographic system. You should make sure you've gone through [the lessons on typography](LINKME) to understand how to create and use a typographic system.

A huge benefit to matching up your typographic and layout systems is that it will be much easier to achieve a design that has stability, is aesthetically pleasing, and takes advantage of Gestalt principles. By leaning on Gestalt principles, you can non-verbally communicate to viewers how an interface is meant to be understood.

It's surprisingly easy to do this, once you know how. After this exercise, you'll understand how to:

1. **Use consistent and proportionate line heights for *all* of your text styles.** This means text will always align, no matter where it's placed in the interface.
2. **Space design elements and text using multiples of those same line heights.** This means that interface elements will follow the same spacing rules as your typography, which will make your design appear stable and intentional.
3. **Follow the rule of proximity to create "perceptual groups" between related design elements.** Following the rule of proximity is a best practice regardless of whether you're creating a unified typographic and layout system, but it is much easier to follow under such a system.

Can you tell which of the following layouts uses a consistent typographic and layout system? The differences are subtle, but if you can't tell at first, *look at the negative space*. When you focus your eyes not on the design elements, but the space between those elements, the difference between the two layouts should be much more clear.

![thing](/images/layout-grids-match-type-scale-01.png)

<!--more-->
## Exercise

1. In this exercise, you're going to use the frames that you set up in the [last exercise](LINKME). Create five separate text elements using the following settings:

| Text | Font size | Line height |
|------|-----------|-------------|
| Heading 1 | 68px | 75px |
| Heading 2 | 45px | 60px |
| Heading 3 | 30px | 45px |
| Paragraph text | 20px | 30px |
| Small text | 13px | 15px |

*Note: in Figma, the default line height uses percentages. This is good, but it's best to use pixels while learning how type systems work so you can see the underlying proportions easier. Make sure to type "px" after the number to switch to pixel-based measurements.*

2. Draw the following layout using gray rectangles

1. Once you have created your 5 text elements, add them to the
2. Create components out of each.
3. On the mobile artboard, build a low fidelity modal component. It should have a title, a few sentences of paragraph text, a primary "OK" button, a secondary "Cancel" button, and a close button.
4. Create a component out of the modal, and create new instances on each of your 4 artboards.
5. On the mobile artboard, the modal should be full width (6 columns), 8 columns for tablet, 6 for desktop, and 4 for desktop HD. Scaling these components will likely break the layout. Don't worry about this yet.
6. On the mobile artboard, use constraints until the layout works across all sizes.
