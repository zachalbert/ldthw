---
title: 'Typography: Color'
date: 2017-01-01 20:37:11 Z
layout: post
todo:
- Hanging punctuation
- Ligatures
---
In the last series of exercises, you went through the process of establishing a typographic system. In this exercise you're going to learn about two types of color as applied to typography — color (as in hue, saturation, and brightness), and typographic color, which refers to the overall density of a typographic design.

## Typographic Color

The term "typographic color" is used to describe the darkness or density of a block of text. It's influenced by a variety of factors, including but not limited to the font weight, typeface design (tall x-height and open counters result in lighter color), line height, letter spacing, and line length.

Your goal should be to achieve an even typographic color — not too light, which readers may have to squint to read, but not too dark, which can feel heavy and unreadable.

Once you go through all the steps of creating a typographic system, it's important to take a step back and observe the color, then iterate based on what you see. It can be hard to see the forest for the trees when building out a type system.

## The Other Color

The actual color (as in hue) of the text is also incredibly important to keep in mind for accessibility reasons. Pure black text on a white background is incredibly bold and stark, which isn't always right for your brand. At the same time, if your text is too light, it can make it hard to read for users who are visually impaired or in an older age bracket.

### Accessibility

As we age, our eyesight grows dimmer and blurrier. Don't fall into the trap many younger designers fall into of using a subtle gray for your text that looks good on a high contrast Macbook pro monitor, that elder audiences can barely read.

Fortunately, the World Wide Web Consortium provides us with extremely clear guidelines on color contrast. You can read more about the [color accessibility guidelines here](https://www.w3.org/TR/WCAG20/). When in doubt, aim for a minimum of a 4.5:1 contrast ratio for body copy. You can easily check your contrast ratio with contrast ratio checker tools like [this one](https://webaim.org/resources/contrastchecker/).

### Link Affordance

Another area where color is incredibly important is with links. A clear text link affordance means offsetting it visually from its surroundings. That could mean underlining the text, but usually means picking a color that contrasts significantly with the body copy.

At one point on the web, links were always blue underlines. These days, link styles vary wildly — so the main thing to keep in mind is **contrast**.

<!--more-->
## Exercise
This final exercise will cover link styles in your type system.

1. Open the file you worked on in the [last lesson]({{ site.baseurl }}{% link _typography/050-typography-spacing-multiples.md %}).
2. Select all of your body copy and caption text. Using a [color contrast checker](https://webaim.org/resources/contrastchecker/), pick a color with a contrast ratio of at least 7:1 for maximum accessibility. On a pure white background, it should be at least as dark as #595959. Pure black text provides a contrast ratio of 21:1, so you have quite a bit of freedom between those extremes. Going with a lighter text color can lighten the "typographic color" if your body font is chunky (thicker letterforms and serifs). However, if your body copy is thin or light, you should compensate with a darker color. It's usually a good idea to stick with a neutral grayscale for body copy rather than something more chromatic. I went with #2B2B2B.
3. You can get away with a lower contrast ratio of 4.5:1 for heading fonts, or anything darker than #767676. You can also experiment with other hues too, such as picking colors from your brand. Be careful though. Err on the side of stronger contrast ratios for maximum legibility and accessibility. For the sake of simplicity I also chose #2B2B2B for my headings.
4. Next, you're going to pick your link color. Link colors need to follow the same rules of contrast for body copy, but also need to stand out from the surrounding text for a contrast ratio of 3:1. Highlight a couple of random words in the first paragraph of text. As you learned in the [lessons on affordances]({{ site.baseurl }}{% link _affordances/001-affordances-intro.md %}), it's important to differentiate interactive elements from non-interactive elements. I'm going to pick a red: #E8350E, which has a contrast ratio of 3.34:1. I'm also going to give it an underline to make its status as a link obvious. You can access underlines in the advanced type options dialog.
5. Once you've picked a unique link style, you'll do the same thing for the link's hover state. Hover states are important because they provide obvious feedback to the user. However, keep in mind that hover states don't work the same on mobile devices so don't rely on them too heavily. Hover states are typically subtle, usually darker variations on the default link style or toggling the underline. It's difficult to pick the perfect hover state without actually testing and interacting with it, so be prepared to adjust your hover style if you find that it's too extreme or not extreme enough once implemented. I chose a slightly darker red, #C72400, and removed the underline.
6. Continue to zoom out, analyze, then tweak your type system until:
 * There is sufficient contrast between each level of the hierarchy
 * There is an even, balanced "color" (or density)
 * All your link styles stand out
 * Your typographic choices "fit" with your inspiration and goals you established at the very beginning.

You now have a complete typographic system! If you want to develop it even further, you could additional levels to the hierarchy like styles for blockquotes and pull quotes, list styles, drop caps, or additional levels of subheadings.

This system should serve as a solid foundation for a fictional travel site, and you can replicate the same process for any brand you're designing for. Changing the goals and inspiration you start with will lead to a different, but internally consistent type system.

Final advice: **learn the rules, but never let them rule you.** Systems like this will make the process faster, but they are just starting places and are never an excuse to turn your brain off. Once you apply the type system to a design, don't hesitate to change the underlying rules to achieve the aesthetic you feel is most appropriate for the job. Try to change the rules in a consistent manner, but don't hesitate to throw the rules out if they aren't serving you any longer.

In future lessons on layout, you'll learn how to build a layout grid system that mimics your typographic system. This will create an incredibly stable, consistent effect in your UI that will help you feel able to achieve any layout you can imagine.
