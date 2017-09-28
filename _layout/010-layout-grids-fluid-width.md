---
layout: post
title:  "Layout Grids: Fluid Width"
date:   2017-01-01 13:37:11 -0700
tags:
- grids
- layout
- responsive web design
---
In this exercise, you're going to set up a frame to work with Bootstrap's grid system.

> Side note: If you are going to be working with a web developer, it's a good idea to double check that they are willing and able to use Bootstrap's grid system. If they're using a different grid system, then you'll need to adjust the settings provided in this exercise.

The first layout grid you're going to set up is a fluid width grid. Fluid width grids grow and shrink with the screen, and are popular choices when you want to maximize screen real estate, like for most web apps. The alternative to the fluid width grid is the fixed layout grid. This is used when you want to limit the width of your content, like with text-heavy layouts. You'll set up a fixed layout grid in the next exercise.

There are a few key details about the Bootstrap Grid. You can read more about it in the [documentation](https://getbootstrap.com/docs/4.0/layout/grid/) if you want, but the relevant details have been extracted for you below. You'll use these details to create your fluid width layout in the exercise.

| Columns        | 12                   |
| Width          | 100% of screen size  |
| Gutter   | 30px                 |
| Margin   | 15px on each side    |

_According to the [Bootstrap v4.0 docs](https://getbootstrap.com/docs/4.0/layout/grid/)_

<!--more-->
## Exercise

1. Create a new design document, and select the `frame` tool or hit `F`.
2. In the design panel on the right, open the "Desktop" presets, and select "Desktop (1024 x 1024)". This will automatically create a 1024 x 1024 frame for you.
3. With that frame selected, add a layout grid by clicking the `+`.
4. Still in the design panel, click the icon on the left of your newly-created layout grid.
5. In the modal window that appears, make sure you have "Columns" selected rather than "Rows".
6. Change your column count to 12.
7. Your width should remain set to "auto".
8. Change your gutter width to 30.
9. Make sure the type is set to "Stretch".
10. Change your margin to 15.
11. You now have a working, fluid-width grid system that can be implemented seamlessly with Bootstrap. Follow the next steps to see it in action.
12. Draw a rectangle in your frame that spans 6 columns, with a height of 100px. Place it anywhere within the frame, but make sure the left and right edges snap to the columns in the layout grid.
13. With the rectangle selected, under the "Constraints" section in the design panel, change the topmost dropdown to say "Left & Right".
14. These constraints will ensure that your shape will remain 6 columns wide, no matter the size of your frame. See it in action by selecting the frame and changing its width.

In the next lesson, you're going to create a fixed layout grid, which works better for text-heavy layouts.
