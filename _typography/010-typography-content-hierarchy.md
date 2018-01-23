---
title: 'Typography: Content Hierarchy'
date: 2017-01-01 20:37:11 Z
layout: post
---
Now that you've established your typographic goals and found some inspiration, the first step to building a type system is to arrange your text blocks within a frame. You will start that process in the exercise below. First, some theory.

### Content is King

As the old saying goes, content is king. Our typographic system will be driven first and foremost by the needs of the content. Our typographic choices must *serve* the meaning of the content, rather than the other way around.

It can be tempting to become enamored of a cool typeface or interesting treatment that reduces readability, but unless your audience is other designers and type nerds, average users won't appreciate your choices.

You'll begin this exercise by copying your source text into separate paragraph blocks, which will allow you to apply separate styles to each paragraph. Some modern design apps (like Adobe Illustrator) allow for multiple paragraph styles within a single text block element, but Figma requires each style to be applied to a unique text block.

### When to Use Lorem Ipsum

Lorem ipsum is latinized gibberish that designers sometimes use to simulate body copy. It can be convenient since it *looks like* real language, but the downside is that it's meaningless. It's best to avoid using lorem ipsum text for this reason.

Sometimes though, you need to begin the design process before you have real text to work with. In that case, try to find some example text that has real meaning. In the following exercise, we're going to use information from a wikipedia page for Fiji to simulate language we might see in our fictional travel magazine. It's not as good as designing for a real article, but is better than gibberish.

### The Typographic Hierarchy

If you aren't familiar with HTML, you're going to learn a few HTML tags. They provide us with useful labels for our various heading styles. For instance, the H1 tag stands for "Heading 1", which is the most important heading in a given HTML document. We'll use H1 to refer to our article title. An H2 is the next most important heading. Most documents don't have need of more than 3 or 4 heading levels, but HTML provides up to 7 levels.

These levels are commonly referred to as the "typographic hierarchy". This concept helps you pick styles, since your H2 should look more important than your H3, which should also look more important than your H4. There should also be significant contrast between each level so the reader can clearly tell the difference.

### The Content Hierarchy

Your content also has a hierarchy. The title is the most important, and meant to be read first. Bolded words in the middle of a paragraph are meant to be seen as more important than their surrounding text.

When you build a typographic system, your goal is to let your typographic hierarchy (meaning, your style choices) mirror your content hierarchy. You will see mention of these two hierarchies throughout the following exercises.

<!--more-->
## Exercise
1. Open the design document you started in the [last exercise]({{ site.baseurl }}{% link _typography/005-typography-goals-inspiration.md %}). In this exercise, you're going to be laying out all the content you'll need to build a typographic system.
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
