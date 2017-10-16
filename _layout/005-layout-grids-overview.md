---
id: 005
layout: post
title:  "Layout Grids: Overview"
date:   2017-01-01 13:37:11 -0700
tags:
- gestalt
- grids
- layout
- responsive web design
---
Grids have a very long history of use in design and book layout. They provide simple rules that make it much easier to lay design elements out in a rational, proportionate way. While a grid doesn't have to be rigidly followed all of the time, using them for most design decisions will greatly reduce the time and effort to produce a high quality layout.

Layouts produced using a coherent grid system will seem to have "rhythm." In the same way that musicians (usually) strive for a consistent, reliable rhythm, designers should do so as well. Unless you're deliberately trying to break the mold.

Grids also allow you to take advantage of many useful Gestalt laws. For instance, following a consistent grid will allow multiple side-by-side columns of text to align. The [Law of Closure](LINKME) comes into play, and we perceive a more orderly structure to the layout. Grids can also make decisions about spacing easier, making it easier to stick to the [Law of Proximity](LINKME).

The most powerful feature of grid-based design is that it is much easier to design for flexible screen widths. On the web, this is called **Responsive Web Design**. Grid systems are also used in mobile design to accommodate a range of device sizes. One way to think about this is to imagine your content as a liquid, being poured into a layout that provides structure.

Most popular grid systems has twelve columns. Twelve is a great default which makes it easy to come up with many different layout configurations.

![Layout configurations with a twelve column grid](/images/layout-grids-overview-01.png)

In this series of exercises, you're going to learn how to design for a responsive screen environment using a twelve column grid, like those used in the popular frameworks [Bootstrap](https://getbootstrap.com/) and [Foundation](https://foundation.zurb.com/). You're also going to use grid rows to help make spacing decisions easy and consistent.

<!--more-->
## Exercise

1. Create a new design document, and draw a mobile sized `frame`. Select the <span data-keyCombo="frame">frame tool</span>, then open the "Phone" section in the inspector panel on the right. Choose the size that best fits the phone you have. I'm going to use the iPhone preset, which is 375 x 667.
2. With the frame selected, add a layout grid from the inspector on the right. If successful, you should see five lightly colored vertical stripes in your frame now.
3. The visible portion of a colored stripe is called a `column`, and the spaces between columns are called `gutters`. A design object, like a block of text or an image, can span one or more columns. However, objects should also use whole column widths. For example, a text block can be 4 columns wide, or 5 columns wide, but not 4<sup>1</sup>&frasl;<sub>2</sub> columns or 4 columns + 1 gutter.
4. Start by drawing 3 rectangles in the 3 central columns. All 3 should be 100px tall, and each should span the entire width of a single column. While you can draw shapes that span more than one column, always begin and end your shapes within a column.
5. Below that, draw a single rectangle that spans all 3 central columns. The left and right edges of the 3-column rectangle should align with both the left and right single-column rectangles. This simple exercise should show you how easy it is to keep everything lined up.
6. It's a good idea to turn your grid on and off while you work, since the lines can be distracting if you're not actively moving or resizing objects. To <span data-keyCombo="show-hide-grid">hide the grid</span>, go to `View > Show Layout Grid`. With the frame selected, you can also hide an individual layout grid with the eyeball icon.
7. Finally, if you have a smartphone, download Figma Mirror from either the [iOS App Store](https://itunes.apple.com/us/app/figma-mirror/id1152747299?mt=8) or the [Google Play Store](https://play.google.com/store/apps/details?id=com.figma.mirror&hl=en). Figma mirror will sync the design on your computer to your phone, allowing you to see changes happen in real time. This is an incredibly useful tool, since a design may look different than you expected in the final output device.

Next up, you're going to adjust your layout grid settings to match a twelve column grid system. You'll keep working in this same file throughout the next several exercises, so make sure to hang onto it.
