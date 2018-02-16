---
title: 'Typography: Type Scale'
date: 2017-01-01 20:37:11 Z
layout: post
---
Building on the [last exercise]({{ site.baseurl }}{% link _typography/030-typography-base-line-height.md %}) wherein you established your base line height, you're now going to establish a type scale. A type scale is a limited set of font sizes that increase in consistent proportions. You have seen an example of a type scale if you've ever used a word processor like Word or Google Docs.

## The Classic Scale

You've probably seen the classic type scale, which uses the font sizes 8, 9, 10, 11, 12, 14, 18, 24, 30, 36... and so on.

Establishing a type scale is immensely useful because it helps you strike a balance between control, ease of use, and sufficient contrast between each level of your content hierarchy. Without a type scale, it can be challenging to decide on the font sizes you'll need, often leading to arbitrary and inconsistent decisions.

## Sufficient Contrast

A type scale will help you ensure there is sufficient contrast between each level of your content hierarchy. Titles should command more attention than subtitles, and subheadings should stand out enough from paragraphs of text to enable quick scanning of a text.

As you explore different scales, keep contrast in mind. Contrast is more important than faithfulness to your scale. For instance, you may decide that subheadings (such as H3s and H4s) look better at the same size as your body copy, but set in uppercase with a bolder weight. As long as those subheadings stand out obviously from the body copy, then you can feel satisfied.

## Designing A Type Scale

The first step is to map out the limited set of font sizes you want to use.

Your type scale will be based on your **base ratio**, which is your line height divided by your font size. Since we've established a 16/24 type system in the last couple of lessons, our base ratio is **1.5** (since 24 / 16 = 1.5).

From this point on, planning out your type system is just a matter of multiplication. Here's an example:

| Content Hierarchy | Formula | Final Font Size |
|-|-|-|
| Level 1 (base) | — | **16px** |
| Level 2 | 16px * 1.5 | **24px** |
| Level 3 | 16px * 1.5 * 1.5 | **36px** |

You can follow the same pattern to find other levels in your type scale, which you will do in this exercise.

<!--more-->
## Exercise
1. Open up the design document you've been using in the last several typography lessons.
2. Figure out what your base ratio is — if you've been following along and are designing a 16/24 type system, your base ratio is 1.5.
3. To figure out the next size up in your type scale, multiply your **base font size** by your **ratio**. Multiply by your ratio *again* to get the next size up, and so on. The following table illustrates how this works. Create a text object in your design document for each level in your hierarchy.

| Content Hierarchy Level | Formula (base font size * ratio) | **Final Font Size** |
|-|-|-|
| Paragraph text | — | **16px** |
| H3 text | 16px * 1.5 | **24px** |
| H2 text | 16px * 1.5 * 1.5 | **36px** |
| H1 text | 16px * 1.5 * 1.5 * 1.5 | **54px** |
| Big text | 16px * 1.5 * 1.5 * 1.5 * 1.5 | **81px** |
| Small text | 16px / 1.5 | ~10.67px (likely rounded up to 11px or 12px) |

4. Notice that there are both "big" and "small" levels in the content hierarchy. "Big" corresponds to text like extra large titles, drop caps, and "small" refers to things text like captions, annotations, etc. Since small text can be hard to read, it's okay to take some artistic license and make it a bit larger than the math dictates. You can also set small text in uppercase characters, which can make small point sizes more legible.
5. Now that you have a type scale, change all of your text blocks to match.
6. Once done, then it's time to put on your analysis hat and figure out if any sizes look off to you. Remember that your goal is sufficient contrast between each level of your content hierarchy, and the tools at your disposal are font size, font weight, italics, capitalization, and typeface. If a subheader looks too big for instance, try bumping it to the next level down in the type scale and using other font styling options to differentiate it. I chose to make my H2 and H3 the same size, but I gave my H2 an italicized version of my display face, Playfair.

When done, all the text blocks in your frame should conform to your type scale and maintain sufficient contrast from each other. In the next lesson, you're going to pick an appropriate line height for those same text blocks. Keep this file handy.
