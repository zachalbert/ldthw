---
title: 'Typography: Vertical Spacing'
date: 2017-01-01 20:37:11 Z
layout: post
---

* Rule of proximity
* Follow the content Hierarchy
* Grids make it easier. Simple grid??

### headings

<!--more-->
## Exercise
In the [last exercise]({{ site.baseurl }}{% link _typography/045-typography-line-length.md %}), you established a common width for your text column. In this exercise, you will come up with consistent vertical spacing between text blocks. You will learn guidelines based on the [Gestalt Law of Proximity]({{ site.baseurl }}{% link _gestalt/010-gestalt-law-proximity.md %}). The basic idea behind this law is that elements that are closer to each other are perceived as related.

1. For this exercise, we're going to use a simple grid. You will learn more about [advanced layout grids]({{ site.baseurl }}{% link _layout/005-layout-grids-overview.md %}) in a future lesson, but even the basic grid will save you lots of time. Start by selecting the frame that contains your text blocks (by selecting the name of the frame in the upper left corner).
2. Add a grid by selecting the plus icon in the "Layout Grid" section of the design panel.
3. Open the layout grid options panel by clicking the icon to the left of your newly created grid.
4. Make sure the "Grid" type is selected, then give is a size consistent with the divisor you used to increase line heights. If you've been following along, that will be "8".
5. Next, select the first instance of your longer paragraphs of text (beginning with "Fiji has a significant amount…"). Keeping it within your rulers, move it so that the top edge of the bounding box lands on one of the newly created grid lines. It should snap.
6. Also, select the advanced text options from the ellipsis in the design panel. Make sure the "Auto Resize" is set to "Height". This will ensure the bounding box will always follow the natural height of your lines of text.
7. Next, select the H3 directly above your paragraph. Follow the same procedure of snapping the top edge to one of the grid lines, and ensure the auto resize option is set to height. You may notice that the text box begins *and* ends on a grid line, since the line height is always divisible by 8 in our type system.
8. Now you need to decide on how much space you want to separate H3 subheaders from the paragraphs underneath. They are related, so should be fairly close. With the 8px grid we have, 3 grid blocks is equal to our base line height. I will separate the H3 and paragraph underneath with 3 empty grid rows.
9. Do the same for the next instance of H3 and paragraph text.
10. Next, decide on the space above your H3s. Since we've used 3 rows of space to separate related elements, *double* it to 6 rows. The results in 3 empty rows of space between the first H3 and paragraph, and 6 empty rows above the H3. In this way, you're going to keep increasing the spacing increment to communicate which elements of text are related, and which are not.
11. The H1 and the H2 are related, since they are functioning as the title and subtitle in our article. I will use the same rule established between H3s and paragraphs — 3 blank rows of space.
12. Next, we need to pick the blank space between the subtitle (H2) and the first H3. While we could use 6 rows, that looked too tight to my eye. Instead I used 9 to communicate separation between the title / subtitle block and the main body of the article.
13. I used 12 rows of blank space between the top of the page and the title to relate the title and subtitle more to the content underneath than the edge of the page.
13. Finally, as a finishing touch, copy [image from the Wikipedia article](https://en.wikipedia.org/wiki/Fiji#/media/File:The_Point_(Fiji).jpg) into the document. Hold `shift` while resizing so it's the same width as the text column. Move it underneath the last paragraph of text, separated by 6 rows of empty space. You will probably have to make your frame taller to fit it all.
14. Move your caption underneath the image. It should be pretty close to the image, perhaps separated by 1-2 rows of space. In most cases, you won't be able to control the height of images in the eventual output, so don't worry if your image height doesn't line up perfectly on the grid. It's okay to approximate that.

When finished, you should have a finished example article for a fictional travel website. While you haven't designed the rest of the site, you have built a robust typographic and spacing system that you can base everything else on.

While it probably seems like a lot of work to get here, you can repeat this process for any layout you need to do. What's more, in future lessons on layout, I'll show you how to use this same system to create a layout system that mirrors your typographic system.

The next and final lesson will cover a few miscellaneous typographic items to make your system even more robust.
