---
layout: post
title:  "Color Models 2: RGB vs CMYK"
date:   2017-01-01 13:37:11 -0700
tags:
- gestalt
- color harmonies
---
This lesson deals with the differences between `RGB` and `CMYK` color models. There is no accompanying exercise, because at the time of this writing, most UI design software doesn't allow designers to work in `CMYK` mode — with the notable exception of the Adobe Creative Suite of products like Photoshop and Illustrator.

`CMYK` is used in design intended to be printed with ink. Whereas `RGB` deals with mixing red, green, and blue light together to produce a full spectrum of colors, `CMYK` deals with mixing cyan, magenta, yellow, and black to produce the color spectrum. Here's a table to help you remember the differences.

| Model | Primary colors | Color space | Used in… |
|-|-|-|-|
| `RGB` | **R**ed, **G**reen, **B**lue | Additive | Digital screens, and anywhere light is mixed to create the color spectrum |
| `CMYK` | **C**yan, **M**agenta, **Y**ellow, **B**lack | Subtractive | Print media, paint, and anywhere light is *reflected* off a physical surface to create the color spectrum |

`CMYK` is called a **subtractive** color model, because the color we perceive is the light that is reflected — or subtracted — from the pigments. When all colors are combined in a subtractive model, black is the result.

`RGB` is the opposite, called **additive**, because light is added together to create a specific color. When all colors are combined in an additive model, white is the result.

### Gamuts

Here's why this matters. The different models have different color spaces, or ranges of possible colors. This is known as the "gamut." While most colors are achievable in both models, the `RGB` color space has a broader gamut. It still falls short of representing all possible colors our eye can see, but allows for brighter colors than the `CMYK` space.

### Main Takeaway

The reason why you need to know about this is that you may encounter a situation where you need to design for both a digital *and* print environment — the classic example being a logo. If you have any serious need for print design, it's best to find a graphic designer to help you out, as we won't be getting into graphic design specifics in this writing.

If you want a quick and dirty solution, then just make sure you print anything you design for screens and paper. Compare it to the screen to ensure that your design is consistent.

In the next lesson, we're going to start talking about mixing different hues together to create color harmonies.
