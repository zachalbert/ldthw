---
title: 'Typography: Base Line Height'
date: 2017-01-01 20:37:11 Z
layout: post
---

In the [last exercise]({{ site.baseurl }}{% link _typography/025-typography-base-size.md %}), you picked a base font size for your typographic system. In this exercise, you're going to decide on your **base line height**. These two numbers form the DNA of your typographic system.

## Why Line Height is Important

The line height for your body copy establishes a rhythm and cadence to the lines of text on the page. Because these are often abundant in design, it makes sense to mirror this rhythm in other areas of your design. When you do, you will end up with a design that feels incredibly stable and intentional, like the difference between a piece of classical music and jazz improv. (Not that jazz is bad — there are certainly times when your design goal will be to create a less stable rhythmic structure.)

## Reading Speed and Fatigue

Line height affects reading speed, and is tied to the length of your text lines. You will learn about [line length]({{ site.baseurl }}{% link _typography/045-typography-line-length.md %}) in a few lessons. The quick takeaway is that the longer your lines of text, the more line height you'll need to aid the reader in scanning to find the beginning of the next line. The negative space between lines can serve as a visual guide that makes it easier and faster to read.

When lines of text are too close together, it can be hard to find your place and can feel "heavy" and increase reading fatigue. Well-set typography should feel effortless to read.

On the other hand, if your line height is too loose, it will be hard to perceive the lines of text as "connected" and can similarly detract from reading speed.

## Rule of Thumb: 1.2–1.5

Line height has a fairly strict rule of thumb that's easy to follow, so commit this measurement to memory: **1.2—1.5 of your body copy size**.

Opt for the lower end of the range if you have shorter line lengths, or the higher end for longer line lengths. If your design has a lot of "breathing room" (a term designers use to describe design with lots of negative space), a looser line height will tend to fit better.

### Narrow It Down

Here are a few things you can try to narrow your choice down to a specific measurement.

First, look at your inspiration library and examples of competitive products or websites.

Then, remember the prime rule: **seeing is believing**. Set a few blocks of text with a range of line heights within the 1.2—1.5 range and see if anything stands out as obviously better.

### Units and Measures

One thing to note about line heights is the unit is pretty flexible. By default, Figma displays line heights in percentages. If your body copy is 16px, then 1.5 is the same as 150%, which is the same as 1.5em, which is the same as 24px. When setting up a type system, I recommend sticking with pixel values so you know exactly what the final output is. In Figma, all you need to do is replace "%" with "px" to switch to pixel values.

Finally, have a bias for whole numbers — and especially even numbers. This is a trick of the trade that isn't strictly necessary, but will make your life easier. A line height of 24px, for instance, will make it much easier to establish vertical rhythm than a line height of 27.5px. Vertical rhythm depends on you using multiples of the same number throughout your design system (such as 8 or 12), and 24 is much easier to multiply and divide with than 27.5.

There's nothing technically wrong with weird numbers for your line height. You won't receive any citations from the design police for setting your body copy to 27.5349px. However, your work is being displayed on a device with whole pixels, and a weird number forces the browser renderer to round up or down to the nearest whole display pixel. For better control and predictability, stick with whole numbers.

### Typographers Notation

One thing you will eventually encounter is typographer's shorthand notation for a text block's measurements — for example, 16/24. The numerator, 16, refers to the font size. The denominator, 24, refers to the line height. It's an easy and quick way to communicate type setting measurements to other designers.

<!--more-->
## Exercise
In the [last exercise]({{ site.baseurl }}{% link _typography/025-typography-base-size.md %}), you picked a base font size. In this exercise, you'll pick your base line height. These two values form the foundation for your typographic system.

1. In the same document you've been working in for the last few lessons, select the frame containing the text where you set the base font size. Create a couple of duplicates (for three frames total) so you can try a few different line heights.
2. Experiment with 3 different line heights within the range of acceptable line heights. I will pick 120%, 135%, and 150%.
3. Notice the difference between each. Try to *actually* read the text, and note which seems easier. Pay attention to how quickly your eye is able to find the next line of text. Looser line heights like 150% create horizontal "channels" of whitespace to make it easier to visually trace back to the next line of text. However, if it's too loose, the lines can seem unrelated to each other. While tighter line heights like 120% can make it harder to find the beginning of the next line, they will also keep lines of text more pressed together which can lead to a feeling of solidity. If the line height is *too* tight, you'll need to watch out for interactions between the descenders of some letters (like lowercase "g") with the ascenders of letters on the line below (like an uppercase "K"). If you get too much interaction between ascenders and descenders, it will tend to lead the eye in the wrong direction.
4. I will pick 150%. While percentages are more common when picking line heights, we're going to convert this line height to a specific pixel value. This will make it easier for us to build a typographic system that is internally consistent. Replace "150%" with "16px * 1.5". This will yield 24px.
5. Next, convert the percentage value to pixels. Simply replace "150%" with "24px" in the line height field. You should see no change, since they are equivalent.
6. There is another advantage to a line height of 24. It allows us to make use of an 8pt grid system (since 24 is a multiple of 8). This grid system is used in Material design and Android devices, many web apps, and is a good constraint when starting out. If this is unfamiliar to you, don't worry — you'll be learning more about this type of grid system in the lessons on [layout grids]({{ site.baseurl }}{% link _layout/005-layout-grids-overview.md %}). Remove any extra frames in your design document, and set all your paragraphs to the same line height of 24px.

You are done when you have a single frame with both paragraphs of text using your base font size and base line height. Keep this file handy for the next lesson, where you're going to start building on the foundation you've established.
