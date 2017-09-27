---
layout: post
title:  "Layout Grids: Overview"
date:   2017-01-01 13:37:11 -0700
tags:
- gestalt
- grids
- layout
---
Grids have a very long history of use in design and book layout. They provide simple rules that make it much easier to lay design elements out in a rational, proportionate way. While a grid doesn't have to be rigidly followed all of the time, using them for most design decisions will greatly reduce the time and effort to produce a high quality layout.

Layouts produced using a coherent grid system will seem to have "rhythm." In the same way that musicians (usually) strive for a consistent, reliable rhythm, designers should do so as well — most of the time. Based on your goals, it sometimes make sense to break the mold entirely.

Grids also allow you to take advantage of many useful Gestalt laws. For instance, following a consistent grid will allow multiple side-by-side columns of text to align. The [Law of Closure](LINKME) comes into play, and we perceive a more orderly structure to the layout. Grids can also make decisions about spacing easier, in such a way that prevents you from violating the [Law of Proximity](LINKME).

Used on the web, grid systems can also be _nested_, and customized on the fly. This allows for some incredibly complex layouts that morph in real time in response to the screen size. Creating designs for the web that adapt to any screen size is called responsive design. In this series of exercises, you're going to learn how to design for a responsive environment.

On the web, there are many popular grid system frameworks. A grid framework is a prebuilt grid with default settings that allows a designer or programmer to quickly get up to speed. The most popular grid system is a part of the [Bootstrap](https://getbootstrap.com/) CSS framework. It isn't the only one, but because of its ubiquity, we're going to set up our design files to work within a Bootstrap environment.

When designing for native mobile apps, grid systems can be simpler. A 12-column grid is overkill for tiny screens, but it's still a good idea to use a 2–5 column grid with clear outer margins to make the task of alignment easier. 

<!--more-->
## Exercises

1. Create a new design document, and draw a `frame` (the suggested size is 1024 x 1024, but it doesn't have to be exact).
2. With the frame selected, add a layout grid. You should see lightly colored vertical stripes on your frame now.
3. Now, try drawing some rectangles within the frame. Notice how the shapes snap to the layout grid when drawing?
4. The visible portion of the stripes is known as the `column`, and the space between columns is called the `gutter`. While you can draw shapes that span more than one column, always begin and end your shapes within columns. Start by drawing 3 rectangles in the 3 central columns. All 3 should be of equal height, and each should span the entire width of a single column.
5. Above that, draw a single rectangle that spans all 3 central columns. The left and ridge edges of the 3-column rectangle should align with both the left and right single-column rectangles.

In the next lesson, we're going to customize our layout grids to work with a 12-column grid system, like the one used in Bootstrap.
