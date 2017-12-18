---
title: 'Typography: Color'
date: 2017-01-01 20:37:11 Z
layout: post
todo:
- Hanging punctuation
- Ligatures
---

* Text color
* affordances of links
* Underlined text is historically a link style. While your links don't *have* to use underlines, avoid underlining non-link text. When present, underlines almost always communicate that text is clickable.
* Navigation links are often visually different from links that appear in paragraph text. Readers are normalized to this, so when building a type system, start by deciding on a link style for paragraphs only.
* Link styles in paragraph text should be differentiated enough so that it's obviously different. If you're using dark text, don't pick a dark link color that is so subtle readers may not notice the link. It doesn't need to be garish, but it shouldn't require significant effort to pick out the links from a page.
* [Color accessiblity guidelines](https://www.w3.org/TR/WCAG20/)

### headings

<!--more-->
## Exercise
This final exercise will cover color and link styles in your type system.

1. Open the file you worked on in the [last lesson]({{ site.baseurl }}{% link _typography/050-typography-vertical-spacing.md %}).
2. Select all of your body copy and caption text. Using a [color contrast checker](https://webaim.org/resources/contrastchecker/), pick a color with a contrast ratio of at least 7:1 for maximum accessibility. On a pure white background, it should be at least as dark as #595959. Pure black text provides a contrast ratio of 21:1, so you have quite a bit of freedom between those extremes. Going with a lighter text color can reduce the "heavy" feeling if your body font is chunky (thicker letterforms and serifs). However, if your body copy is thin or light, you should compensate with a darker color. It's a good idea to stick with a neutral grayscale for body copy. I went with #2B2B2B.
3. You can get away with a lower contrast ratio of 4.5:1 for heading fonts, or anything darker than #767676. You can also experiment with other hues too, such as picking colors from your brand. Be careful though. Err on the side of stronger contrast ratios for maximum legibility and accessibility. For the sake of simplicity I also chose #2B2B2B for my headings.
4. Next, you're going to pick your link color. Link colors need to follow the same rules of contrast for body copy, but also need to stand out from the surrounding text for a contrast ratio of 3:1. Highlight a couple of random words in the first paragraph of text. As you learned in the [lessons on affordances]({{ site.baseurl }}{% link _affordances/001-affordances-intro.md %}), it's important to differentiate interactive elements from non-interactive elements. I'm going to pick a red: #E8350E, which has a contrast ratio of 3.34:1. I'm also going to give it an underline to make its status as a link obvious. You can access underlines in the advanced type options dialog.
5. Once you've picked a unique link style, you'll do the same thing for the link's hover state. Hover states are important because they provide obvious feedback to the user. However, keep in mind that hover states don't work on mobile devices so don't rely on them too heavily. Hover states are typically subtle variations on the default link style. For instance, adding an underline where none existed before, vice versa, or darkening the link color by 10%. It's difficult to pick the perfect hover state without actually testing and interacting with it, so be prepared to adjust your hover style if you find that it's too extreme or not extreme enough once implemented. I chose a slightly darker red, #C72400, and removed the underline.

You now have a complete typographic system! If you wanted to develop it even further, you could add blockquote styles, list styles, or additional levels of subheadings.

This system should serve as a solid foundation for a fictional travel site, and you can replicate the process for any brand you're designing for. Changing the goals and inspiration you start with will lead to a different, but still internally consistent type system.

My final piece of advice is to learn the system, but never let it rule you and never turn your brain off. Systems like this will make the process faster, but they are just starting places. Once you apply the type system to a design, don't hesitate to change the underlying rules to achieve the aesthetic you feel is most appropriate for the job. Try to change the rules in a consistent manner, but don't hesitate to throw the rules out if they aren't serving you any longer.

In future lessons on layout, you'll learn how to build a layout system that mimics your typographic system. This will create an incredibly stable, consistent effect in your UI.
