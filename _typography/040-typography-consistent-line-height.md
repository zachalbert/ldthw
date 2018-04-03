---
title: 'Typography: Consistent Line Heights'
date: 2017-01-01 20:37:11 Z
layout: post
---

In the [last exercise]({{ site.baseurl }}{% link _typography/035-typography-scale.md %}), you picked font sizes for all text blocks in your design document based on a type scale. In this exercise you're going to be picking line heights for all levels of your content hierarchy.

## Internal Consistency & Alignment

Though I probably sound like a broken record at this point, the goal of a type system is to establish consistency, stability, and rhythm. Establishing internally consistent line heights is one of the clearest ways to achieve these goals.

One way that you can spot a well-set, consistent type system is that when multiple columns of text are laid out next to each other, the baselines align neatly. This takes advantage of the [Gestalt Law of Continuity]({{ site.baseurl }}{% link _gestalt/025-gestalt-law-continuity.md %}), which is the brain's tendency to see lines separated by negative space as connected, like with dotted lines. The baselines of multiple columns will look very stable as long as they line up across the gutter.

<!-- TODO: Add images of columns of text lining up -->

## Break Away From Your Ratio

While you used your base ratio to establish a type scale, as font sizes get larger, the same ratio won't always look good. For instance, a ratio of 1.5 looks okay for paragraph text, but for large title text, it will look far too loose.

As a result, it's best to set your line heights in increments of a number divisible by your base line height. Your base line height establishes the root "rhythm" of your layout, so other elements in your layout need to line up. **Buckle up. We're about to go mathing!**

For anyone who has studied music, a piece with 4/4 timing means that there are 4 beats to a measure. Half notes (2 beats long) can be played twice per measure and will always line up with the other notes. Similarly, if you played a note every 8 beats, it would also line up with the other notes. However, playing a note every 7.5 beats would quickly get out of sync with the rest of the music.

The same principle applies to line heights. With a base line height of 24px, then a block of text with a line height of 48px will line up cleanly. There will be a single line of 48px text for every 2 lines of 24px text.

You could also pick a line height of 32px — this won't line up as cleanly though. To achieve alignment you'll need 3 lines of 32px text (32 * 3 = 96) to align to 4 lines of 24px text (24 * 4 = 96).

Optimize for cleaner multiples when you can, but only if the result is aesthetically pleasing. Remember to never let guidelines like these restrict you from making choices that look best.

<!--more-->
## Exercise
In the [last exercise]({{ site.baseurl }}{% link _typography/035-typography-scale.md %}), you established a typographic scale and used it to pick font sizes for each level of your content hierarchy. In this exercise, you're going to establish line heights for each of those levels.

1. The first step is to pick a number that is divisible by 24. 8 or 12 are both good options. The smaller the number, the more control you'll have, but the harder it will be to create stability and alignment. I will pick **8**.
2. Start by selecting your H3.
3. Before adjusting the line height, make sure you are looking at multiple lines of text. Reduce the width so that some of the H3 text wraps onto a second line, or add some dummy copy to the end of the text block.
4. Set the H3's line height to your base line height (24) plus your divisor of 8. That yields a line height of 32. Continue adding 8 to see what it looks like. I'm going to stick with 32, which looks the most consistent with the body copy.
5. Continue the process for the other levels of the content hierarchy — beginning with the base line height of 24px, add or remove 8 until it looks consistent. Here are the choices I made:

| Content hierarchy | Font size | Line height | Font |
|-|-|-|-|
| H1 | 54px | 72px | Playfair Display Black |
| H2 | 24px | 32px | Playfair Display Italic |
| H3 | 24px | 32px | Montserrat Light |
| Paragraph | 16px | 24px | Montserrat Light |
| Caption | 12px | 16px | Montserrat Light Uppercase |

WHEW! Most of the math is behind you, and you're getting really close to a complete type system. In the next lesson you're going to learn about the width of text blocks.
