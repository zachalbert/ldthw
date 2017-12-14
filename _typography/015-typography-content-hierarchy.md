---
title: 'Typography: Content Hierarchy'
date: 2017-01-01 20:37:11 Z
layout: post
---

* Content is king
* Content has a conceptual hierarchy (title is more important than a caption), so mirror this hierarchy visually.
* Use enough contrast between levels.
* We're going to use HTML nomenclature in addition to more common labels. In websites, headings use a variety of heading "tags", like H1 to denote the most important heading on a page, H2 to denote to denote the next most important, and so on. This is useful so that search engines can "understand" what your page is about, but it also helps developers who will be turning your design into code.
* In current software, text blocks can only have minimal styles within a single block.
* Take a block of copy, and turn it into separate blocks, ready to be set.
* Don't worry about styling yet. It's a good idea to pick a generic typeface for your initial type layout.

<!--more-->
## Exercise
1. Open the design document you started in the [last exercise]({{ site.baseurl }}{% link _typography/010-typography-goals.md %}). In this exercise, you're going to be laying out all the content you'll need to build a typographic system.
2. Select the <span data-keyCombo="frame">frame tool</span>, and create a new "Desktop" sized frame, or draw a frame that is 1024x1024.
3. In Figma, each element in your content hierarchy will need its own block of text. I will provide you with some text you can use for this exercise, copied from [Wikipedia's article on Fiji](https://en.wikipedia.org/wiki/Fiji#Tourism).

For each of the rows in the following table, copy the text into a new fixed-width text block in your design document in order. Don't worry too much about the width of the text blocks yet, but make sure they fit within the desktop frame you created in the previous step.

| Text Block Type | Level in Content Hierarchy | Tag in HTML | Default Size[^1] | Sample Text[^2] |
|-|-|-|-|
| Fixed-width | Title | `<h1>` | 36 | Traveling to Fiji |
| Fixed-width | Subtitle | `<h2>` | 24 | The Tourism Industry in Fiji |
| Fixed-width | Secondary Subtitle | `<h3>` | 20 | CNN named Fiji’s Laucala Island Resort as one of the fifteen world’s most beautiful island hotels |
| Fixed-width | Body | `<p>` | 16 | Fiji has a significant amount of tourism with the popular regions being Nadi, the Coral Coast, Denarau Island, and Mamanuca Islands. The biggest sources of international visitors by country are Australia, New Zealand and the United States. Fiji has a significant number of soft coral reefs, and scuba diving is a common tourist activity. |
| Fixed-width | Secondary Subtitle | `<h3>` | 20 | The Main Attractions |
| Fixed-width | Body | `<p>` | 16 | Fiji's main attractions to tourists are primarily white sandy beaches and aesthetically pleasing islands with all-year-round tropical weather. In general, Fiji is a mid-range priced holiday/vacation destination with most of the accommodations in this range. It also has a variety of world class five-star resorts and hotels. More budget resorts are being opened in remote areas, which will provide more tourism opportunities. CNN named Fiji’s Laucala Island Resort as one of the fifteen world’s most beautiful island hotels. |
| Fixed-width | Small | `<small>`, `<figcaption>` | 14 | Coconut palms line the beaches of Fiji[^3] |

[^1]: These defaults are supplied for you so you can easily distinguish the different levels in the hierarchy. They are arbitrary, temporary sizes.
[^2]: You can use your own text if you'd prefer.
[^3]: The image this caption refers to can be found [here](https://en.wikipedia.org/wiki/Fiji#/media/File:The_Point_(Fiji).jpg)

You're done when you have a fixed-width text block for each paragraph of text in the table above. Hang on to this file, because we're going to begin the process of de-uglifying it in the next lesson.
