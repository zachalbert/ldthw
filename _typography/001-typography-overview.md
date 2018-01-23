---
title: 'Typography: Overview'
date: 2017-01-01 20:37:11 Z
layout: post
---

In the following series of lessons, you're going to learn some fundamentals about working with typography. You'll also learn a framework to create a typographic system from scratch, which will allow you to pick fonts and set up rules for any new design project.

It's said that the web is 95% type. While that number is decreasing as other forms of media take center stage, you cannot escape working with text as a designer.

Working with text is also very difficult, as typographic skill can feel like an arcane art. You will learn some rules of thumb in these lessons which will help you avoid common mistakes, but they won't make you a master. Like everything in design, it will take focused observation, practice, and experimentation to really get a handle on working with typography.

Since typography can be so challenging, my advice is to lean into it and just become a typography nerd if you aren't already. Learn to love the nuances of typography and devote yourself to mastering them.

### Important Concepts

Before we begin, there are a few important concepts to learn.

Typography is the study of working with **pre-designed letters**. Lettering and font design deal with the creation of new letterforms, which we are not going to get into in these lessons as they represent an art form unto themselves. There is a certain amount of overlap between the subjects though, so some of what you learn here can be carried forward if you choose.

It's also important to state the difference between a font and a typeface. Yes, it's a little pedantic, but if you ever work with another designer, they'll appreciate your precision. A **typeface** is the overall design of letterforms in a specific style by a font foundry or font designer, like "Garamond" or "Helvetica". A **font** is a specific instance of a single typeface that enables the typeface to be used. For example, the *fonts* "Times New Roman Bold 16pt" and "Times New Roman Italic 20pt" are both part of the *typeface* "Times New Roman."

Finally, learn the difference between **legibility** and **readability**. Legibility deals with a reader's *ability* to read a passage of text. A legible passage is large enough to see, has sufficient contrast with the background it's on, and there is sufficient space around each letter so they can be made out individually. Readability, on the other hand, deals with the reader's *desire* to read a passage of text. A readable passage is legible, but is also set in an aesthetically pleasing way that doesn't strain the reader's eye. 20 pages of legalese terms of service documentation is a good example of text that is legible, but not readable.

### A Brief History of Typography

The use of reusable characters probably stretches all the way back to the second century BC, in the use of identical cuneiform characters to create identical characters in wet clay.

The first instance of moveable type, where characters were arranged and pressed into paper, was originally invented by the Chinese in the 10<sup>TH</sup> century AD. They used ceramic characters, and later wood and bronze.

The first instance of lead based moveable type and the mechanical printing press was invented by Johannes Gutenberg in 1439, who printed the Christian Bible as the first mass-produced printed work (known as the *Gutenberg Bible*). This began a cultural revolution by drastically reducing the costs of printing. The printing revolution led to widespread growth in literacy.

Designers typically consider this the root of typographic art, as typefaces could be reproduced more easily. Many typefaces created during this era are still in use today, such as the classic old-style serif face Garamond.

Lead-based typography continued until the next big revolution in printing with the invention of personal computers and desktop publishing in the 1980s. Fonts, originally sets of physical characters, became digital files which were designed to be displayed on a screen or printed.

For additional history and stylistic advice on working with typography, I'd recommend further reading in [Elements of Typographic Style by Robert Bringhurst](https://www.amazon.com/Elements-Typographic-Style-Robert-Bringhurst/dp/0881791326).

### Typographic Character

The design of individual letters will lend a particular character to a text. Following [the Law of Past Experience]({{ site.baseurl }}{% link _gestalt/050-gestalt-law-past-experience.md %}), readers will group new experiences with similar previous experiences.

For instance, American readers may be familiar with the American Declaration of Independence. Penned in a calligraphic style, it would look a bit strange to see the same document set using a modern, playful typeface like Comic Sans. It would look equally strange to see office memos set using a historical blackletter.

![Original Declaration of Independence](https://en.wikipedia.org/wiki/United_States_Declaration_of_Independence#/media/File:United_States_Declaration_of_Independence.jpg)

<!-- TODO: Show a portion of the declaration of independence set in comic sans, and an office memo about washing the dishes set in some type of blackletter -->

<!--more-->
## Exercise
This first exercise will take you through a few basics of working with type in Figma. This will be a random assortment of tasks which are necessary prerequisites for you to be able to complete future exercises.

1. Open a new design document.
2. With the <span data-keyCombo="text">text tool</span> selected, click once to create an auto-resizing text block. Paste the following lorem ipsum text: `Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nullam commodo rhoncus dapibus.`
3. An auto-width text block will continually expand or contract based on the amount of text. Convert this text block to a fixed-width block by dragging one of the drag handles on the corner of a selected text block. Force the text to wrap to 2 lines by making the text block more narrow. Some situations require fixed-width blocks, like setting paragraphs of text. Auto-width can be easier to work with for small amounts of text.
4. Next, increase the size of the text to 18, and make it center-aligned.
5. Now increase the line height of the text to 150%. You can access the line height underneath the font size selector. Hover your mouse over each input in the text section of the design panel if you're having trouble finding it.
6. Increase the letter spacing to 5%.
7. Finally, make the text all caps. While you can do this manually by typing with caps lock, let Figma do the hard work for you. Under the ellipsis menu to the right of the "Text" heading in the design panel (the "Advanced Type" dialog), look for the **Uppercase** button underneath the **Transform** heading and turn it on.
8. Play around with a few of the other options available in the Advanced Type dialog so you know what you can do.

This was a brief overview of some of the things you can do to text in Figma, which will prepare you for what you're going to be doing in the upcoming lessons. You don't need to save this file for future lessons.
