---
id: 015
layout: post
title: 'Layout Grids: Fixed Width'
date: '2017-01-01 13:37:11 -0700'
tags:
  - grids
  - layout
  - typography
  - responsive web design
---

In the [last exercise](LINKME), you set up a fluid width layout grid on a mobile frame. That type of grid will stretch and shrink in proportion to the different device widths that view it. That may work fine for certain cases like fluid width web apps or small mobile screens, but you'll want to use a fixed width grid for text-heavy designs like blogs and content sites.

When designing for written content, you can greatly enhance readability by using a [sensible typographic measure](LINKME), or line length. As a reminder, the line length rule of thumb is 45-75 characters. A fixed width grid will allow you to control for that line length much easier than with a fluid width grid.

### Fixed Grids Are Tied to Screen Widths

By definition, fixed width layout grids are associated with specific screen widths. For instance, a fixed grid that is 960px wide (a common size for desktop designs) will only fit inside a screen at least that wide. If the screen size is 1200px wide, then the fixed grid will still be 960px wide. That means you can trust that your layout won't get any wider, no matter how big the screen is.

### Breakpoints

However, what if you wanted your fixed 960px grid to work for a smaller screen, like a tablet (commonly 768px wide)? Unfortunately, the 960px grid won't work since it'll be too wide to fit. You can solve this problem with breakpoints.

A breakpoint is a CSS rule used in responsive websites that allows you to change things about your design at different screen sizes. Breakpoints can also change the properties of a layout grid. This allows you to define different grid settings based on screen size, or even switch between a fixed and fluid width grid. Once defined, breakpoints work automatically to respond to different screen sizes.

A common convention is to use a fluid width grid for smaller devices, and fixed width grids for larger devices. Standards have emerged for breakpoints sizes that cover the vast majority of devices. While you can technically define a breakpoint at any screen size, it's a good idea to follow the standards until you have a very good reason to break them. Here are a common set of measurements to use.

Screen Width                                              | Layout Dimensions        |
:-------------------------------------------------------- | :----------------------- |
< 576px (most mobile devices)                             | fluid width, 100% wide   |
> 576px (mobile landscape orientation)                    | fixed width, 540px wide  |
> 768px (tablets)                                         | fixed width, 720px wide  |
> 992px (desktops and laptops)                            | fixed width, 960px wide  |
> 1200px (larger, higher resolution desktops and laptops) | fixed width, 1140px wide |

<!--more-->
## Exercise

In this exercise, you're going to learn how to set up additional frames for a responsive web design project.

1. In the same document you've been working in, select the frame tool.
2. In the design panel on the right, open the "Tablet" presets, and select the one that is 768px wide.
3. You should see a tablet-sized frame. Now, select the frame tool again.
4. Create a third frame, this time using the desktop preset (1024px).
5. Finally, create a fourth frame using the desktop HD preset (1440px). You should now have 4 progressively larger frames, but only the mobile sized frame should have a layout grid so far.
6. Now, select your tablet frame. You're going to add a *fixed* layout grid to your tablet frame. Add a layout grid, and use the following settings by clicking the icon to the left of the new layout grid. Make sure to adjust the settings in this order, since some features are locked with the default settings.

| Type | Center |
| Columns | 12 |
| Width | 38 |
| Gutter | 24 |
| Offset | - |

9. Test that it works by making the frame wider. The grid should stay centered without getting any wider or narrower. Reset your frame width to 768px once you're sure the grid is set up correctly.
10. Add a layout grid to your desktop frame, and use the follow settings like you did for the tablet frame.

| Type | Center |
| Columns | 12 |
| Width | 58 |
| Gutter | 24 |
| Offset | - |

11. And finally, use these settings for your desktop HD frame:

| Type | Center |
| Columns | 12 |
| Width | 73 |
| Gutter | 24 |
| Offset | - |

You should now have 4 frames, with a fluid width layout grid on your mobile frame, and fixed width on your larger frames. This is a good system to make layout much easier horizontally. In the next lesson, you're going to add another layout grid to your frames to make vertical layout easier. Keep this design file handy.
