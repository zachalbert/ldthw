---
layout: post
title:  "Layout Grids: Matching Your Type Scale"
date:   2017-01-01 13:37:11 -0700
tags:
- grids
- layout
---
In this exercise, you're going to set up new frames that mirror a typographic system. You should make sure you've gone through [the lessons on typography](LINKME) to understand how to create and use a typographic system.

A huge benefit to matching up your typographic and layout systems is that it will be much easier to achieve a design that has stability, is aesthetically pleasing, and takes advantage of Gestalt principles. By leaning on Gestalt principles, you can non-verbally communicate to viewers how an interface is meant to be understood.

It's surprisingly easy to do this. The three main requirements:

1. Use consistent and proportionate line heights for *all* of your text styles
2. Space design elements and text using multiples of those same line heights
3. Follow the rule of proximity to create "perceptual groups" between related design elements

Can you tell which of the following layouts uses a consistent typographic and layout system?

![thing](/images/layout-grids-match-type-scale-01.png)

The main measurement in a typographic system that you should care about for layout purposes is your line height, or leading.

Use leading to arrive at gutter widths and row heights.

Set up a new [type scale template](LINKME to the typography exercise where you draw out H1s, H2s, etc), and use up your type using these settings:

18px / 24px (1.333)

<!--more-->
## Exercise
1. Build out a type scale for H1, H2, H3, P, Small. Use the base font size of 18px, and a base line height of 24px.
2. Create components out of each.
3. On the mobile artboard, build a low fidelity modal component. It should have a title, a few sentences of paragraph text, a primary "OK" button, a secondary "Cancel" button, and a close button.
4. Create a component out of the modal, and create new instances on each of your 4 artboards.
5. On the mobile artboard, the modal should be full width (6 columns), 8 columns for tablet, 6 for desktop, and 4 for desktop HD. Scaling these components will likely break the layout. Don't worry about this yet.
6. On the mobile artboard, use constraints until the layout works across all sizes.
