---
title: 'Typography: Spacing Multiples'
date: 2017-01-01 20:37:11 Z
layout: post
---

This is the last official step to establish the measurements for your typographic system. All of your text blocks should have internally consistent line heights, and should be the same width as your paragraphs — which use optimal line lengths. The final step is decide on how much negative space to leave between each block of text.

## Rule of Proximity

The [Gestalt Law of Proximity]({{ site.baseurl }}{% link _gestalt/010-gestalt-law-proximity.md %}) indicates that objects close to each other are perceived as more related than objects farther away.

You will take advantage of this rule when spacing out your text blocks. For instance, a subtitle should be closer to the paragraph of text that follows it than the paragraph of text above to indicate relatedness.

## Spacing Multiples

You have already established vertical rhythm with your line heights, so you're going to carry this idea further when spacing out your text blocks.

Begin by spacing out the two most closely related things — usually a subtitle and paragraph. Space them by something that's consistent with your base line height. Since our base line height is 24px, you could pick 24px. You could also pick 8, or 12. Whatever number you pick will be your **spacing multiple**. Here's how you use a spacing multiple.

Let's say you decide on 24px of separation between your two most closely related elements. If other elements have a similar relationship (for instance, a title and subtitle or an image and its caption), then you'll use the same number to space them out — 24px.

However, if looking at two elements that are unrelated, such as a subtitle and the paragraph of text above it, then double your spacing multiple to 48px. In this way, you can communicate the relationships between objects based on which spacing multiple you use.

## Grids Make Things Easier

After the lessons on typography, you'll be learning about layout grids. Layout grids make spacing elements significantly easier, however the same principles apply.

Until you learn more about layout grids, there are two quick ways to make spacing easier.

The first is to select one object, hold `alt/option`, then hover over another object. Figma will quickly show you how far apart the objects are.

A more permanent way to do the same thing is to create your own "low-budget" grids with throwaway rectangles. If your spacing multiple is 24px, then draw a rectangle that is 24x24. You can then create many copies of this rectangle to help space objects out quickly.

<!-- TODO: show 2 screenshots of alt/option hover to show distance, or the low budget ruler option -->

<!--more-->
## Exercise
1. For this exercise, you're going to create some low-budget spacer rectangles. Start by creating a rectangle that is 24px x 24px (the same size as the base line height). Give it a bright color so you don't forget to remove it later.
2. Begin by separating both of your H3s from the paragraph of text beneath them by 24px. You can use your spacer rectangle to make this faster.
3. Next, use 2 spacers worth above both H3s (or, 48px).
4. Continue in this manner to space everything out. When finished, remember to separate your content from the top of the frame too with the largest multiple to make sure all of the content is perceived as a perceptual group. Here's a table to show the spacing I picked.

| **Top edge of frame** |
| *5 spacers (120px)* |
| **Title** |
| *1 spacer (24px)* |
| **Subtitle (H2)** |
| *3 spacers (72px)* |
| **H3** |
| *1 spacer (24px)* |
| **Paragraph** |
| *2 spacers (48px)* |
| **H3** |
| *1 spacer (24px)* |
| **Paragraph** |
| *2 spacers (48px)* |
| **Photo** |
| *1 spacer (24px)* |
| **Photo Caption** |
| *5 spacers (120px)* |
| **Bottom edge of frame** |

Voilà! You are completely done setting the measurements for your type system. You can continue this process to add other levels to your typographic hierarchy, as long as those levels remain consistent with the others. The next and final lesson will cover text and link color. You're almost done! Keep this design file handy.
