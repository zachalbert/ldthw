---
title: 'Typography: Base Line Height'
date: 2017-01-01 20:37:11 Z
layout: post
---

* Line height, and the foundational importance of that measurement in the layout
* Importance of appropriate line height on readability and legibility, plus finding the next line of text.
* Rule of thumb: 1.2 - 1.5
* While you can keep your line height in percentages, round up or down to a whole number so you can use the metric for layout purposes more easily.
* Rhythm


### headings

<!--more-->
## Exercise
In the [last exercise]({{ site.baseurl }}{% link _typography/025-typography-base-size.md %}), you picked a base font size. In this exercise, you'll pick your base line height. These two values form the foundation for your typographic system.

1. In the same document you've been working in for the last few lessons, select the frame containing the text where you set the base font size. Create 2 duplicates so you can try a few different line heights.
2. Experiment with 3 different line heights within the range of acceptable line heights. I will pick 120%, 135%, and 150%.
3. Notice the difference between each. Try to *actually* read the text, and note which seems easier. Pay attention to how quickly your eye is able to find the next line of text. Looser line heights like 150% create horizontal "channels" of whitespace to make it easier to visually trace back to the next line of text. However, if it's too loose, the lines can seem unrelated to each other. While tighter line heights like 120% can make it harder to find the beginning of the next line, they will also keep lines of text more pressed together which can lead to a feeling of solidity. If the line height is *too* tight, you'll need to watch out for interactions between the descenders of some letters (like lowercase "g") with the ascenders of letters on the line below (like an uppercase "K").
4. I will pick the middle option of 135%. While percentages are more common when picking line heights, we're going to convert this line height to a specific pixel value. This will make it easier for us to build a typographic system that is internally consistent. Replace "135%" with "18px * 1.35". This will yield 24.3px.
5. Next, we're going to deal with that .3px. While there's nothing technically wrong with a decimal value on line heights, they will make your job significantly more difficult. It's easier to round up or down to a whole number, and even numbers are better than odd. Your typographic system and layout system will use multiples of this line height value, so "24" will be a much easier number to work with. Simply type "24px" in the line height field.
6. There is another advantage to a line height of 24. It allows us to make use of an 8pt grid system (8 is a multiple of 24). This is one type of grid system used in Material design and Android devices, and is a good constraint when starting out. If this is unfamiliar to you, don't worry — you'll be learning more about this type of grid system in the lessons on [layout grids]({{ site.baseurl }}{% link _layout/005-layout-grids-overview.md %}).

You are done when you have a single frame with both paragraphs of text using your base font size and base line height. My frame uses a font size of 18 and a line height of 24. Keep this file handy for the next lesson, where you're going to start building on the foundation you've established.
