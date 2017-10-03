---
layout: post
title:  "Layout Grids: Rows"
date:   2017-01-01 13:37:11 -0700
tags:
- grids
- layout
---
In the last exercise, you set up 4 frames for a responsive web design project using a mixture of fluid and fixed width columns. Now, you're going to add a new layout grid of horizontal rows which will make it easier to control the vertical space between design elements. Use the same design file that you set up in the [last exercise](LINKME TO FIXED GRID LESSON).

Combining horizontal and vertical layout grids that use proportionally similar measurements lets you achieve a design that is extremely rhythmic and stable. In this exercise, your row grid is going to use the same measurements as the gutters in your column grid, based on Bootstrap measurements.

<!--more-->
## Exercise

1. Open the design file you created in the [last exercise](LINKME), and select your mobile frame.
2. Click the `+` icon to add a new layout grid. You should have 2 now.
3. Leave the 6 column grid in place, and open the options for the new layout grid.
4. Switch from `Columns` to `Rows`.
5. Set the following options, in this order:

| Type | Top |
| Columns | Auto |
| Height | 30 |
| Gutter | 30 |
| Offset | 0 |

6. You should now have 2 overlapping layout grids that looks like plaid. Try drawing a grid of rectangles on the frame, like you might see in a collage of photos. Notice how easy it is to ensure the space on all four sides of the rectangle is equal?
7. Rows can be even more granular than this. In the settings provided above, you set your row height to the same measurement as your column's gutter width. While this will work in most cases, you will frequently need finer grained control. To do this, open your row grid settings and change both the `Height` and `Gutter` measurements from 30 to 15. Because 15 evenly goes into 30, you'll still be able to achieve a rhythmic layout.
8. Now that you have your row grid working on your mobile frame, do the same thing for your other 3 frames: table, desktop, and desktop HD. Use the following settings:

| Type | Top |
| Columns | Auto |
| Height | 15 |
| Gutter | 15 |
| Offset | 0 |

Now that you've learned to set up frames for responsive web design, in the next lesson you're going to match a typographic system to fit the layout grids perfectly. This process is the holy grail which will let you design clean, well-ordered, and internally consistent layouts that fit your typography perfectly.
