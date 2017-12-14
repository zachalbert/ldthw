---
title: 'Color Models 2: RGB vs CMYK'
date: 2017-01-01 20:37:11 Z
tags:
- gestalt
- color harmonies
layout: post
todo:
- Find a good image with a public license that shows the visible spectrum, rgb, and
  cmyk color spaces
---

This lesson deals with the differences between `RGB` and `CMYK` color models. There is no accompanying exercise, because at the time of this writing, most design software *that specializes in UI* doesn't allow designers to work in `CMYK` mode — with the notable exception of the Adobe Creative Suite of products like Photoshop and Illustrator. Despite this , it's still important for a designer to understand the differences.

### CMYK Mode

`CMYK` is used in designs intended to be printed with ink. Whereas `RGB` deals with mixing red, green, and blue light together to produce a full spectrum of colors, `CMYK` deals with mixing cyan, magenta, yellow, and black to produce the color spectrum. Here's a table to help you remember the differences.

| Model | Primary colors | Color space | Used in… |
|-|-|-|-|
| `RGB` | **R**ed, **G**reen, **B**lue | Additive | Digital screens, and anywhere light is mixed to create the color spectrum |
| `CMYK` | **C**yan, **M**agenta, **Y**ellow, **B**lack | Subtractive | Print media, paint, and anywhere light is *reflected* off a physical surface to create the color spectrum |

`CMYK` is a **subtractive** color space, because the color we perceive is the light that is reflected — or subtracted — from the surface. When all colors are combined in a subtractive model, black is the result. In printing, black (which is the `K` in `CMYK`) is often added to the translucent printing inks achieve richer blacks.

`RGB` uses an **additive** color space, because light is added together to create a specific color. When all colors are combined in an additive model, white is the result.

### Gamuts

Here's why this matters. Different color spaces have different ranges of possible colors. The possible colors is known as the color space's "gamut." While most colors are achievable in both models, the `RGB` color space has a broader gamut that contains the entire gamut of `CMYK`. It doesn't cover *all* possible colors our eye can see, but allows for significantly brighter colors than the `CMYK` space.

The reason why you need to know about this is that you may encounter a situation where you need to design for both a digital *and* print environment — the classic example being a logo. If you pick colors that are only possible in the `RGB` color space, then the logo will appear dull and dark when printed.

### Takeaway

Consistency is extremely important in branding. If you have any serious need to design for print, you'll need to use Adobe software and should probably find a graphic designer specializing in print design to help you out. Print design contains a lot of complexity that we won't be getting into (at least for the current version!).

In the next lesson, we're going to break what you think you know about primary colors. It's going to blow your mind.
