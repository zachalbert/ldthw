---
layout: post
title:  "Typography: Type Scale"
date:   2017-01-01 13:37:11 -0700
---
* What it is, why it's important
* The classic type scale
* use your base ratio to determine your type scale
* Map your content hierarchy to your newly created scale
* Look for enough contrast between each of the levels. Size is not the only way to increase or decrease contrast — you can play around with different weights, italics, capitalization, and letter spacing too.

### headings

<!--more-->
## Exercise
In the [last exercise]({{ site.baseurl }}{% link _typography/030-typography-base-line-height.md %}), you picked a base line height. You're going to use your base font size and line height to establish a type scale to size all of your other text blocks.

1. Open up the design document you've been using in the last several typography lessons.
2. Each level in your content hierarchy should increase in size based on the ratio between your base font size and base line height. Figure out what your ratio is with the formula `ratio = base line height / base font size`. In my case, the ratio is 1.333333333 (24 / 18 = 1.333333333). Hereafter the ratio will be summarized as 1.3̅.
3. To figure out the next size up in your type scale, multiply your **base font size** by your **ratio**. Multiply by your ratio *again* to get the next size up, and so on. The following table illustrates how this works.

| Content Hierarchy Level | Formula (base font size * ratio) | **Final Font Size** |
|-|-|-|
| Paragraph text | — | **18px** |
| H3 text | 18px * 1.3̅ | **24px** |
| H2 text | 18px * 1.3̅ * 1.3̅ | **32px** |
| H1 text | 18px * 1.3̅ * 1.3̅ * 1.3̅ | 42.6px, rounded down to **42px** |
| Caption text | 18px / 1.3̅ | 13.5px, rounded up to **14px** |

There are a few interesting things to note in this type scale.
* You could use the same formulas to create additional levels in the content hierarchy. You also don't have to increase font sizes by a single step at a time, either. You could let H3s be 24, or 32, or keep them at 18 but using a bold font style to differentiate them from paragraph text.
* For the H1, we got a number with a decimal place. While there's nothing majorly wrong with a number like that, it's easier to work with whole numbers. Devices can still only display text in whole pixel values, but with modern devices, pixel density is fine enough that you can get away with strange numbers if you really want to. No design system should be a prison, even if it's a system you created for yourself. You always have the option to exercise creative license.
* We also rounded the caption text up. I did that so the text didn't get too small to read. While 14px is still legible for most readers, it's potentially too small for some. It's best to err on the side of larger text when in doubt.
* Because our ratio is a long number, I summarized it in the table above as 1.3̅. However, when calculating these values, I found that I had to type the full ratio of 1.333333333 to yield whole numbers.
* If you picked different numbers for your base font size and line height, you will arrive at different final values. That's okay — learn the formulas so you can replicate this system in the future.

4. Now that you have a type scale, change all of your text blocks to match.

When done, all the text blocks in your frame should have a size that matches your type scale. In the next lesson, you're going to pick an appropriate line height for those same text blocks. Keep this file handy.
