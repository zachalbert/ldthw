---
layout: post
title: 'Layout Grids: Fixed Width'
date: '2017-01-01 13:37:11 -0700'
tags:
  - grids
  - layout
  - typography
  - responsive web design
---

In the [last exercise](LINKME), you set up a fluid width grid. That type of grid will stretch and shrink in proportion to the different device widths that view it. That may work fine for certain cases like web apps, but you'll want to use a fixed width grid for text-heavy designs like blogs and content sites.

When designing for written content, it's important to conform to a [sensible typographic measure](LINKME), or line length. A fixed width grid will allow you to control for optimal line length much easier than with a fluid width grid.

# Fixed Grids Are Tied to Screen Widths

By definition, fixed width layout grids are associated with specific screen widths. For instance, a fixed grid that is 960px wide will only fit inside a screen at least that wide. If the screen size is 1200px wide, then the fixed grid will still be 960px wide. That means you can trust that your layout won't get any wider, no matter how big the screen is.

# Breakpoints

Here's the problem with fixed width grids, though. In the example where you have a layout grid which is 960px, it's too wide for smaller screens like tablets and mobiles. Optimal widths are completely different for mobile, tablet, desktop, smart watch, and cinema displays. You can solve this problem with breakpoints.

A breakpoint is a CSS rule used in responsive websites that allows you to change things about your design at different screen sizes. Breakpoints can also change the properties of a layout grid. This allows you to define different grid settings based on screen size, or even switch between a fixed and fluid width grid.

A common convention is to use a fluid width grid for smaller devices, and fixed width grids for larger devices. Standards have emerged for breakpoints sizes that cover the vast majority of devices. While you can technically define a breakpoint at any screen size, it's a good idea to follow the standards until you have a very good reason to break them. Here are the grid settings for Bootstrap, which you're going to use in the exercise.

Screen Width                                              | Layout Dimensions        | Outer margin
:-------------------------------------------------------- | :----------------------- | :----------------
< 576px (most mobile devices)                             | fluid width, 100% wide   | 15px on each side
> 576px (mobile landscape orientation)                    | fixed width, 540px wide  | 15px on each side
> 768px (tablets)                                         | fixed width, 720px wide  | 15px on each side
> 992px (desktops and laptops)                            | fixed width, 960px wide  | 15px on each side
> 1200px (larger, higher resolution desktops and laptops) | fixed width, 1140px wide | 15px on each side

_According to the [Bootstrap v4.0 docs](https://getbootstrap.com/docs/4.0/layout/grid/)_

<!--more-->
## Exercises

In this exercise, you're going to learn how to set up your frames for a responsive web design project. You're going to follow Bootstrap conventions, though you can break these conventions once you know how it all fits together. If you do choose to veer from the conventional layout settings, before you commit, make sure your programmer (or you) have the ability to customize the grid system you're using.

1. Create a new design document, and select the `frame` tool or hit `F`.
2. In the design panel on the right, open the "Desktop" presets, and select a mobile device of your choice. Pick the device most likely to be used by your intended audience ([search google for up-to-date statistics on device sizes](https://www.google.com/search?&q=mobile+device+size+statistics)).
3. You should see a mobile-sized frame. Now, select the frame tool again. This time, select a tablet preset (768px).
4. Create a third frame, this time using the desktop preset (1024px).
5. Finally, create a fourth frame using the desktop HD preset (1440px). You should now have 4 progressively larger frames.
6. Select the smallest frame, which is your mobile screen view. Add a new layout grid.
7. Refer to the [previous exercise](LINKME TO FLUID GRID LESSON) if you need a refresher on how to set up a fluid grid. Use the following settings. *Note that you're using 6 columns instead of the expected 12, since using 12 columns at mobile sizes results in columns so tiny they're useless.*

| columns | 6 |
| width | auto |
| gutter | 30 |
| type | stretch |
| margin | 15 |

8. Now, add a *fixed* layout grid to your tablet frame. Use the following settings for this layout grid. Once you've set it up, Test that it works by making the frame wider. The grid should stay centered with growing or shrinking.

| columns | 12 |
| width (change the type field first) | 34 |
| gutter | 30 |
| type | center |
| offset | - |

10. Now use the follow layout settings for your desktop frame:

| columns | 12 |
| width (change the type field first) | 52 |
| gutter | 30 |
| type | center |
| offset | - |

11. And finally, use these settings for your desktop HD frame:

| columns | 12 |
| width (change the type field first) | 68 |
| gutter | 30 |
| type | center |
| offset | - |

You should now have layout grids on each of your four frames. If you have an eye for detail, you may have noticed that the total width of the layout grids aren't *exactly* lined up to the Bootstrap measurements in the table provided. For instance, the tablet grid is only 738px instead of 740px, the desktop grid is 6px too skinny, and desktop HD is 6px too wide. These slight variations are a result of trying to keep column widths from being placed on fractions of pixels (or sub-pixels), and aren't anything to worry about.

Now you're set up to create a responsive design that is easy to layout horizontally. In the next lesson, you're going to add rows to your frames to make vertical layout easier. Save this design file for that.
