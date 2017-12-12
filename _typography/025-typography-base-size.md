---
layout: post
title:  "Typography: Base Font Size"
date:   2017-01-01 13:37:11 -0700
---
* The size and line height of your body copy is the heart of an internally consistent system
* This will focus on your base font size, and all other sizes will be based on the decisions you make here.
* Refer to [units of measure]({{ site.baseurl }}{% link _basics/015-units-of-measure.md %})
* Start with system defaults (14, 16, 17), vary from there
* Font sizes should vary by device, but when starting out, pick sizes that work across a range of devices to minimize complexity
* Think about context: will the reader be reading lots of text? Or will they be reading sparingly? Mobile or desktop primarily?
* Look at a few examples. Designing a news site — look at a lot of news sites.

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
