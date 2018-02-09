---
title: 'Typography: Base Font Size'
date: 2017-01-01 20:37:11 Z
layout: post
---
Now that you've picked the fonts you want to use in your design, it's time to start thinking about sizing and spacing. This is where you'll really start to build a typographic system.

## Building a System

The difference between a typographic "system" and a bunch of random choices is that your system will be internally consistent. Sizes and spacing at one size will mimic sizes and spacing at another. It will also make new decisions much easier, once your system is established.

There are 2 root measurements that form the DNA of your typographic system — **base font size** and **base line height**. These base measurements will apply to paragraphs of body copy, and all other text in your content hierarchy will mirror it.

## Rules of Thumb

When deciding on your base font size, here are a few things to keep in mind.

### Start With Defaults

System defaults are a good starting point, since users are most familiar with these. System defaults will feel "natural."

Refer to the lesson on [units of measure]({{ site.baseurl }}{% link _basics/015-units-of-measure.md %}) for a refresher on the different types of units in the table below.

| Device | Default Font Size |
|-|-|
| Web | 16px |
| iOS | 17pt |
| Android | 14sp (15sp on desktop)[^1] |

[^1]: Android actually uses many sizes depending on user preference and device, so refer to the [Material Guidelines](https://material.io/guidelines/style/typography.html) for in-depth information about font sizes.

### Think of Viewing Context

After starting with the default, you may still have cause to vary it.

For instance, if you're designing a dashboard for a wall-mounted display intended to be viewed from far away, then you'll want to increase your base size. On the other hand, if you're designing an experience for mobile with limited text, you may want to err on the side of smaller text.

However, you should rarely go smaller than the default sizes for your base font size for legibility reasons. It's okay to use smaller sizes for levels of your content hierarchy that support the main text (such as image captions), but do so sparingly and carefully.

### Get Inspiration

It's also a good idea to see what others are doing. If you're designing a news website, check out a bunch of other news websites to see what the average body copy size is. If you're designing a mobile app, compare your screens to other similar apps.

**However: don't simply copy the patterns you see.** The goal of gathering inspiration is to make an *informed decision*. If your readers are used to small text for similar products, then it may be the best idea to buck that trend if you're trying to stand out. Or, you may want to borrow the patterns from *one domain*, and apply them to another for effect.

You can use browser extensions like [Fontface Ninja](https://fontface.ninja/) to quickly inspect the fonts and sizes used on websites. For mobile apps, you can take a screenshot and use tools like [WhatTheFont](https://www.myfonts.com/WhatTheFont/), [IdentiFont](http://www.identifont.com/), and [Matcherator](https://www.fontspring.com/matcherator) to attempt to identify fonts from an image.

### Test Early, Test Often!

The final, and most important rule of thumb is to test your design often on the actual device you're designing for. Use tools like [Figma Mirror](https://www.figma.com/mirror) to see your design updated on your mobile device in real time as you design. If you're designing a website, export your design as a PNG and open it in a browser to get a feel for how it looks. If you're designing a banner ad, then drop it on top of a screenshot of the website it'll be viewed on.

Often, type sizes that look good on screen look wrong when you actually see them in context, so make this a habitual part of your design process.

<!--more-->
## Exercise
To complete this exercise, you will probably need to refer to the lesson on [units of measure]({{ site.baseurl }}{% link _basics/015-units-of-measure.md %}).

1. In the [last exercise]({{ site.baseurl }}{% link _typography/021-typography-picking-typefaces-2.md %}), you landed on a couple of typefaces you can use for heading and body copy. In this exercise, you're going to be picking a base font size for your body copy, which will inform all other sizing decisions. Open up the design document you've been working in for the past few lessons.
2. Select both of the longer paragraphs of body text. Here are the things you should consider when making this decision:
  * System default — what is the system default? Readers will be used to default sizes, so it's a good starting place. System defaults tend to range from 14px - 18px. iOS uses 17pt, the web uses 16px, and Android uses a range of sizes, generally from 13sp-15sp.
  * Context — is the reader likely going to be using this at work? At home? On the go? For our fictional travel site, we will optimize for reading on a range of device widths in a variety of contexts. [^1]
  * X-height — does the typeface you chose have a tall or short x-height? The shorter the x-height is, the larger you'll need to make your font size to ensure readability. Two typefaces can look very different, even if they share the same font size.
  * Brand — do similar brands use larger or smaller font sizes? I use the browser extension [Fontface Ninja](https://fontface.ninja/) to quickly inspect font choices used on websites.
3. Try a couple sizes out before landing on one. Like in the last exercise on picking typefaces, seeing is believing. Duplicate your art board to try different body copy sizes, then make sure you <span data-keyCombo="view-100%">view the design document at 100%</span>.
4. You can pick a different font size in your design file. If you want to follow along exactly though, I am going to pick 18pt. It's slightly larger than the browser default of 16, which will create less eye strain when reading long-form articles. Change the two paragraphs of body copy to your chosen value, but don't worry about the other blocks of text yet.

[1]: While it is possible to change your font sizes depending on the device size, this greatly increases the complexity of your type system and makes implementation more challenge. For now, start with a size that works well on mobile and larger desktop displays.

You're all done with this when you've picked a single size for your body copy. In the next lesson, you're going to pick the second foundational number for your typographic system — the base line height. Keep this design file handy.
