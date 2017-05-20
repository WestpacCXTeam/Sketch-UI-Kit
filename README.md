# UI-Kit
A complete set of design assets to help you create high quality, consistent, experiences across all our digital brands.

[![The UI Kit](https://gel.westpacgroup.com.au/downloads/visual-design/important/ui-kit-poster-frame-2.png)](https://player.vimeo.com/video/216140143?autoplay=1&quality=1080p)

## Getting Started
Each element in this UI Kit corresponds to the coded element found in the GUI. They follow the same naming convention and general structure: Module - Element - Style - Size. All the elements in the Sketch file are re-usable symbols with overrides for text, icons, multiple states etc. Where possible elements have been made responsive making it easier to re-size them in multiple grid layouts. This will help designers quickly create responsive designs that align with the digital brand and the GUI elements.

## Before you start
1. Have a good look through the GEL and the GUI https://gel.westpacgroup.com.au. Familiarise yourself with the GUI elements so you understand how to use them properly in your design. There’s a lot so take your time. We’ve tried to keep text to a minimum but please read what is says. Don’t just look at the pictures.
2. It’s important to understand how the responsive grid works e.g. offsets, spans, nesting etc. Have a look at a GUI demo page. It's a good way to get your head around how the fluid grid works at different breakpoints. https://gel.westpacgroup.com.au/GUI/WBC/examples/tabcordions/4.1.0/ex8/demo/?v=0.2.0
3. Make sure you’ve installed all the fonts in the Global-Assets folder.
4. You’ll need the latest version of Sketch to open all this stuff.
5. Install the Sketch-Palettes plugin by Andrew Fiorillo. https://github.com/andrewfiorillo/sketch-palettes This will allow you to load the correct colour palettes for each of our brands.
6. If you haven't already done it we recommend setting up this application keyboard short cut: Collapse Artboards and Groups - Alt + Cmd + C - It will save you alot of time. http://sketchshortcuts.com/
7. Subscribe to the GUI update email. We'll let you know when new versions of the UI Kit are released. https://gel.westpacgroup.com.au/GUI/
  
## Spacing elements
All the GUI elements and spacing are based on a unit of 6. This puts visual consistency, scale and rhythm into the design. You’ll notice this in things like the button heights and input field heights etc. We also use a 6px baseline grid to vertically space and size elements.

## Going Multi-Brand
Using a combination of Symbols, Layer Styles and Text Styles each element in the UI Kit is aligned to our multi-brand design system. Adjusting these styles to reflect the new brand will update all symbol instances in your design. Please note: The UI Kit does not use Craft Library. There are several reason for this:
1. Text styles and colours saved in Craft work independently of Sketch’s text styles and document colours. You’d have to use Craft library to access the global text styles and colours in your design system, instead of the built-in Sketch interface. As a result duplicate styles and colours could exist in Sketch and Craft causing confusion and errors.
2. Craft doesn't support Sketch's very powerful Layer Styles. Deal breaker.

We're also investigating Brand.AI as a potential soution to sharing a design system in Sketch however like Craft it's got some challenges.

## Using brand embellishments
Each brand in the UI Kit has a Graphics folder. This contains a Sketch file full of graphic elements like Westpac Energy Bars and St.George Fraxels. We use these graphics (sparingly) to form what we call the embellishment layer. This gives each brand a unique, instantly recognisable look and feel. It's very important that these elements are applied correctly in accordance with the digital brand guidelines. https://www.westpac.com.au/digital-governance/

## Doing a Markup
We currently use Zeplin or InVision for sharing files with developers. These work OK however they don't allow us to use the explicit name of an element. For example when specifying elements from the GUI we refer to them by their name - Striped Row Table or Primary Soft Button. This is all the developer needs to know. The CSS will take care of the styles. We’re still investigating how this can be achieved using Zeplin or InVision.

## Building a Prototype
We don't currently have a tool of choice for prototyping. You can use anything you want. Proto.io and InVision are popular but there are loads more tools out there. Whatever floats your boat.

## Exporting svg’s
We’re working with the developers on a process to export svg’s from Sketch. The current Sketch svg export plugins don’t do a very good job. The next release of Sketch also addresses this issue. We'll update this Readme file when we have a robust solution that the developers are happy with.

## FAQ’s

### What is the UI Kit?
The UI Kit is a Sketch document containing all the elements found in the GUI. These elements are identical to the HTML elements used in the GUI framework. You can use these elements in your designs as and when you need them.
A huge amount of time and effort has gone into developing these elements to ensure they're on brand, accessible, aligned with the HTML GUI and work in our multi-brand design system.

### Why should I use the UI Kit?
If you don’t use it or choose to ignore or alter these styles, people will get upset, there will be wide spread confusion, deadlines will be missed, costs will blow out, you will have to attend even more meetings and all will not be well with the world. If you use these styles you will be a happy bunny and everyone will love you.

### I’m designing a native app. Do I still use the UI Kit?
There’s no reason not to. The visual style of the GUI elements applies to all user interfaces. This is our digital brand. In some cases you may prefer to use native UI elements. This is OK, just be aware that your design needs to align with the digital brand and it's part of larger customer journey which must be consistent.

### What if the element I need is not in the UI Kit?
The GUI only covers the core UI elements common to most user interfaces. Every project generally requires bespoke components that are not available in the GUI. If that’s the case, knock yourself out, just don't re-invent what's already been done.

### Can I add cool embellishment to the UI elements like bevels and textured backgrounds?
No.

### Can I tweak and change things just slightly?
Not unless you have a really good rationale explaining the problem you're trying to solve? Your project is part of a customer journey. Every change and variation to the UI fragments the customer journey and dilutes the brand integrity.

### Why Sketch?
Because that’s what designers want to use. Sketch has become the tool of choice for both UX and Visual designers.

### Who do I contact for help?
If you have any questions or want to share some ideas, please get in contact with the GEL team via gel@westpac.com.au. If you have a Slack account, join the conversation at https://westpac-digital.slack.com. There’s also loads of information and resources in the site: https://gel.westpacgroup.com.au

## More reading
1. The Typography system. Why we’ve done it, how it works and why you should use it. https://gel.westpacgroup.com.au/resources/design/typography/
2. Our UI icon library. How to use icons, when to use icons and… when not to use icons: https://gel.westpacgroup.com.au/resources/design/iconography/
3. The colour system. Why we’ve done it, how it works and why you should use it: https://gel.westpacgroup.com.au/resources/design/colour/

## License

Copyright (c) Westpac. Licensed under the [GNU GPLv3](https://raw.githubusercontent.com/WestpacCXTeam/Visual-Starter-Pack/master/LICENSE).
