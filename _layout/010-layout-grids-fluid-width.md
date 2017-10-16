---
id: 010
layout: post
title:  "Layout Grids: Fluid Width"
date:   2017-01-01 13:37:11 -0700
tags:
- grids
- layout
- responsive web design
---
In this exercise, you're going to adjust the layout grid in the frame you created in the [last exercise](LINKME) to work with popular twelve column grid systems. You'll be loosely modeling your design file after the grid system used in the most ubiquitous framework, [Bootstrap](https://getbootstrap.com/), which will increase the likelihood a software developer can implement your design with ease.

### Fixed vs Fluid

You can either use a **fixed width** grid system, which stays the same size no matter what, a **fluid width** grid system, which shrinks and grows in tandem with the screen size, or both. Most popular frameworks use a combination of both types by changing the grid's properties at certain screen sizes. This provides maximum control to the designer. Here's a rough guide on the most appropriate grid type:

| Use case | Layout grid type | Benefits |
|-|-|-|
| UI heavy website, like an app | Fluid width | *Allows your design to maximize available real estate, which is useful when you have a complex interface.* |
| Text heavy website, like a blog | Fixed width | *Allows rigid control over line length, so you can ensure an optimum reading experience at larger screen sizes.* |
| Text heavy *responsive* website* | Both (Fluid at mobile sizes, Fixed at tablet sizes and larger) | *The most common, which allows for tailored experiences across all mobile device sizes, becoming fixed at larger sizes when it's more important to control line length for an optimal reading experience.* |

In this exercise, you're going to start by adjusting your layout grid to work for a mobile environment.

<!--more-->
## Exercise

1. Start by deleting the rectangles you drew in the last exercise. Also ensure that the frame size matches the size of your mobile device. If you don't see your mobile device listed under the frame presets, you can google "screen resolution for NAME_OF_YOUR_DEVICE".
2. The first thing you're going to do is adjust the number of columns to 12. With the mobile frame selected, click the icon to the left of the layout grid you created in the last exercise to open the options dialog. If you can't see the grid on your frame, make sure it's <span data-keyCombo="show-hide-grid">visible</span>.
3. In the layout grid options dialog, use the following settings.

| Setting | Value |
|-|-|
| Type | Stretch |
| Columns | 12 |
| Width | Auto |
| Gutter | 24* |
| Margin | 12* |

*Wondering where 24 and 12 came from? Your gutter width should match the line height of your paragraph text, which will allow your typography to perfectly match the structure of your layout. Margins for fluid grids are typically half the width of the gutter. In this case, you're going to be designing for the popular 8pt grid system, which is a great place to start for beginners, since screen widths are based on multiples of 8. 24 is a multiple of 8 too, and makes many things much easier. It will become increasingly clear why this is a powerful number to start with, so bear with me for now. However, know that 24 is essentially arbitrary, and you can use different layout settings if you prefer. If you learn more, I would suggest [googling it](https://www.google.com/search?q=8+pt+grid).*

4. You should now see 12 skinny columns in your frame, with 24px wide gutters.
5. Anywhere in the frame, draw a 100px high rectangle that spans 8 columns (beginning from the left side of column #3, and ending on the right side of column #10). You may need to zoom up to ensure your rectangle matches your column widths exactly.
![8 column rectangle](/images/layout-grids-fluid-width-01.png)
6. With the rectangle selected, look for the "Constraints" section in the inspector on the right. Select "Left & Right" from the first dropdown, and "Top & Bottom" from the second.
7. This is just a brief introduction to the power of constraints. You're going to learn much more about constraints in future lessons. As a quick introduction however, you can now see that the rectangle you just drew will follow your layout grid perfectly, no matter the size of your frame. Test this by resizing your frame horizontally and vertically. Notice how the rectangle is always 8 columns wide? This mimics how layouts are implemented in code.
8. Revert your frame back to its original size. You can either hit <span data-keyCombo="undo">undo</span>, or select the frame and pick the correct size preset from the inspector.

This frame and layout grid not only works across many different mobile sizes, but it will also work perfectly for a fluid width layout at any screen size. If your goal is to make a desktop-sized app with a fluid layout, all you need to do is resize your frame to 1024px wide.

In the next exercise, you're going to create a series of frames and corresponding fixed width layout grids that will give you the power to control your line length.
