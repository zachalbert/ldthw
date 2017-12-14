---
title: 'Layout Grids: Rows'
date: 2017-01-01 20:37:11 Z
tags:
- grids
- layout
id: 16
layout: post
video: layout/layout-04-rows.mp4
---

In the last exercise, you set up 4 frames for a responsive web design project using a mixture of fluid and fixed width layout grids. Now, you're going to add a new layout grid of horizontal rows which will make it easier to control the vertical space between design elements. Use the same design file that you set up in the [last exercise]({{ site.baseurl }}{% link _layout/015-layout-grids-fixed-width.md %}).

The layout grid you're going to use in this exercise will use proportionally similar measurements as the grids you've already created. This makes it dead simple to enforce consistent spacing everywhere, which will create a remarkably stable aesthetic in your layouts.

<!--more-->
## Exercise

1. Open the design file you created in the last exercise, and select your mobile frame.
2. Click the `+` icon to add a new layout grid. You should have 2 now.
3. Leave the 12 column grid in place, and open the settings dialog for the new layout grid you just added.
4. Switch from `Grid` to `Rows` in the segmented button at the top.
5. Set the following options, in this order:

| Type | Top |
| Columns | Auto |
| Height | 8* |
| Gutter | 8 |
| Offset | 0 |

*We're using 8 here, since our gutter width of 24 is a multiple of 8. A row and gutter height of 8 will give you a lot of control over the layout, but will also make it easy to match your gutters perfectly. This enables layouts that look so stable it'll make you want to cry.*

6. You should now have 2 overlapping layout grids that look like plaid. It's now much easier it is to enforce consistent spacing between elements horizontally and vertically. For instance, draw a 3x3 grid of rectangles to represent a photo grid. Try to keep the space even between rectangles, and above and below them. Your rectangles should each be 4 columns wide, and have 3 grid rows of space above and below (3 rows x 8px = 24px, which is the same measurement as your vertical gutters).
7. Delete your rectangle grid, then add row grids to your other 3 frames. Use the same settings that you used for your mobile frame, since your row settings don't need to change at new breakpoints.

In the next lesson, we're going to dive deeper into understanding how constraints work. Constraints make it possible to design flexible UI components that adapt easily to new widths, and are the perfect companion to a well-ordered layout grid system.
