---
title: 'Typography: Consistent Line Heights'
date: 2017-01-01 20:37:11 Z
layout: post
---

* Use the base line-height measurement to give everything in the design consistent vertical spacing
[ show an example with many columns of text, and how they all line up]
* Keep them multiples of each other, and look at every level of the content hierarchy
* Make headings have multiple lines
* Will be a perfect lead in to using grids
* Gestalt law of continuation for internal alignment, etc.

### headings

<!--more-->
## Exercise
In the [last exercise]({{ site.baseurl }}{% link _typography/035-typography-scale.md %}), you established a typographic scale and used it to pick font sizes for each level of your content hierarchy. In this exercise, you're going to establish line heights for each of those levels.

1. The goal when picking line heights for each level of your content hierarchy is *internal consistency*. That means that when you have multiple columns of text, they will align with each other without you having to think about it which creates a feeling of stability to a layout. There are many other benefits that will become clear the more you work with internally consistent line heights. The first step in doing this is to pick a divisor of your base line height. Since our base line height is 24, we could use 24, 12, 8, 6, 4, 3, 2, or 1. I recommend limiting yourself to 24, 12, or 8. The smaller the number, the more control you'll have, but the messier your type system will be. I will pick **8** as my main divisor. 12 would also be okay, but probably won't give you enough fine grained control.
2. Start by selecting your H3.
3. Before adjusting the line height, make sure you are looking at multiple lines of text. Reduce the width so that some of the H3 text wraps onto a second line.
4. Set the H3's line height to your base line height (24) plus your divisor of 8. That yields a line height of 32. Do a quick check to make sure the ratio is close to your base ratio of 1.3̅. 32 / 24 = 1.3̅ is right on the money.
5. Next, select your H2 and make sure it wraps to 2 lines. It uses the size 32. Add your divisor **twice** to the base line height, which yields 40. The ratio here is 1.25, since 40 / 32 = 1.25. That's close to our base ratio. If you try adding the divisor *three times*, yielding 48, that will give you a ratio of 48 / 32 = 1.5. 1.5 is farther from our base ratio, so stick with a line height of 40. Change all your H2 line heights to 40.
6. Now select your H1 and reduce the width so it wraps. The H1 is 42px, so follow the same process of adding the divisor to the base line height until you get close to the base ratio. I found that adding the divisor 4 times came out to 56 ( 24 + 8 + 8 + 8 + 8 = 56 ). The line height ratio is 56 / 42 = 1.3̅. Again — perfect! Change your H1 line heights to 56.
7. Finally, select your caption text and force it to wrap to at least 2 lines. This time, since it's only 14px, you'll need to subtract your divisor from the base line height. 24 - 8 = 16, which yields a ratio of 16 / 14 = 1.14. It's not exact, but closer than the next size up. Change your caption text line height to 16.

WHEW! That was a lot of math. You're *almost* done. In the next lesson you're going to learn about how wide to make your text boxes.
