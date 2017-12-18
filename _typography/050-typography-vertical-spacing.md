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

1. For this exercise, we're going to use a simple grid. You will learn more about [advanced layout grids]({{ site.baseurl }}{% link _layout/005-layout-grids-overview.md %}) in a future lesson, but the basic grid will save you lots of time. Start by selecting the frame that contains your text blocks (select the name of the frame in the upper left corner).
2. Add a grid by selecting the plus icon in the "Layout Grid" section of the design panel.
3. Open the layout grid options panel by clicking the icon to the left of your newly created grid.
4. Make sure the "Grid" type is selected, then give is a size consistent with the divisor you used to increase line heights. If you've been following the examples, that will be "8".
5. Next, select the first instance of your longer paragraphs of text (beginning with "Fiji has a significant amount…"). Keeping it within your rulers, move it so that the top edge of the bounding box lands on one of the newly created grid lines. It should snap.
6. Also, select the advanced text options from the ellipsis in the design panel. Make sure the "Auto Resize" is set to "Height". This will ensure the bounding box will always follow the natural line height of your lines of text.
7. Next, select the H3 directly above your paragraph. Follow the same procedure of snapping the top edge to one of the grid lines, and ensure the auto resize option is set to height. You may notice that the text box begins *and* ends on a grid line, since the line height is always divisible by 8 in our type system.
8. Now you need to decide on how much space you want to separate H3 subheaders from the paragraphs underneath. They are related, so should be fairly close. With the 8px grid, 3 grid blocks is equal to our base line height (8 x 3 = 24). I will separate the H3 and paragraph underneath with 3 empty grid rows. 3 rows looks the best to me and will ensure a consistent rhythm, but there would be nothing wrong with picking a different number.
9. For the next instance of H3 and paragraph text, separate them also by 3 grid rows.
10. Next, decide on the space above your H3s. Since you've used 3 rows of space to separate related elements, *double* it to 6 rows. The results in 3 empty rows of space between the first H3 and paragraph, and 6 empty rows after that paragraph. This uses the law of proximity to communicate to the reader that there is a logical connection between H3s and the paragraph that follows, but a logical break when a new H3 is introduced.
11. The H1 and the H2 are related, since they are functioning as the title and subtitle in our article. Use the same rule established between H3s and paragraphs to show connection — 3 blank rows of space. Though 3 was initially arbitrary, once you make the decision, follow it as a rule.
12. Next, we need to pick the blank space between the subtitle (H2) and the first H3. While we could use 6 rows to indicate a break, that looked too tight to my eye since the H1 and H2 use larger font sizes. Instead, use 9 rows to communicate separation greater separation between the title / subtitle block and the main body of the article.
13. I used 12 rows of blank space at the top of the page to create a large "frame" of negative space around the article.
13. Finally, as a finishing touch, copy the [image from the Wikipedia article](https://en.wikipedia.org/wiki/Fiji#/media/File:The_Point_(Fiji).jpg) into the document. Resize it, holding `shift` to maintain proportions, so it's the same width as the text column. Move it underneath the last paragraph of text, with 6 rows of empty space above it. You will probably have to make your frame taller than 1024 to fit it all.
14. Move your caption underneath the image. It should be pretty close to the image, perhaps separated by 1-2 rows of space. In most cases, you won't easily be able to control the height of images once implemented, so don't worry if your image height doesn't line up perfectly on the grid. It's okay to approximate that.

The next and final lesson will cover text color. You're almost done! Keep this design file handy.
