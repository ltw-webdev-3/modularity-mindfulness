---
summary: 'A simple review exercise exploring grids, type systems & modular CSS'
time: '1 hour'
deliverables: '1 HTML file, 4 CSS files, images'
---

# Modularity mindfulness

## Overview

- *Fork this repository.*
- Create the layout denoted in the screenshots using everything you know.
- Use [Gridifier](http://gridifier.web-dev.tools/), [Typografier](http://typografier.web-dev.tools/) & [Modulifier](http://modulifier.web-dev.tools/) as much as possible—there should be very little CSS in `main.css`
- All the images are included the the `images` folder for you.
- Text can be found inside the `content.txt` file.
- *Run it through Markbot and make sure it passes all the checks.*

---

## Details

- *Typefaces:* `Noto Sans`, `Noto Sans Japanese` (see below…)
- *Colours:* `#000`, #e2e2e2`, `#8bc9d9`, `#0084a6`, `#005e76`
- *Expected class names:* `.btn`, `.btn-ghost`
- Include a hover state on the main navigation links & the buttons.
- Include all relevant accessibility features.
- *Gridifier settings:* defaults
- *Typografier settings:* defaults
- *Modulifier settings:* select all

### Including Noto Sans Japanese

The “Noto Sans” Japanese characters font isn’t available on main Google Fonts yet, so we have to use the early access system.

In your HTML, add another CSS `<link>` tag and point the `href` here:

```
https://fonts.googleapis.com/earlyaccess/notosansjapanese.css
```

In your CSS you can specify the typeface using:

```css
font-family: "Noto Sans Japanese", sans-serif;
```

---

## Goal

Visually match the images in the “screenshots” folder and create the interaction shown in the linked video.

- Final screenshots in the “screenshots” folder.
- [**Watch this video to see how it interacts.**](https://video-assets.learntheweb.courses/web-dev-3/modularity-mindfulness.mp4)

---

## Hand in

Drop this folder into your Markbot application. Make sure to fix all the errors. And submit for grades using Markbot.
