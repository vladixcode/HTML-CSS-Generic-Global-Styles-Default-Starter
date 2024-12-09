# HTML&CSS Generic Global Styles Default Starter

This web project is part of the Udemy course: [HTML&CSS Tutorial and Projects Course (Flexbox&Grid)](https://www.udemy.com/course/in-depth-html-css-course-build-responsive-websites/) by coding addict [John Smilga](https://www.udemy.com/user/janis-smilga-3/) from [CodingAddict](https://www.codingaddict.io/)

This is an example of a default generic global styles intended to be used in any other HTML/CSS project to avoid repetition of creating same or similar global styles and variables when new project is started.

Those styles include most generic global styles related to color (primary and secondary) and colors shades, shadows, fonts etc. and their related CSS variables. Also styles for headings, section titles, small/large text/paragraphs, buttons, alerts, forms and inputs, images, loading spinners and similar contextual building blocks of a webpage.

### Live demo:

https://vladixcode.github.io/HTML-CSS-Generic-Global-Styles-Default-Starter/

## Goals:

- Save time on project setup.
- Less lines of CSS.

### Normalize

Small CSS file that provides cross-browser consistency in the default styling of HTML elements.

Alternative/Fancier way of doing this

```css
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
```

- Go to [Docs ](https://necolas.github.io/normalize.css/)
- Select the latest version
- Create normalize.css
- Setup the link in the html

```html
<link rel="stylesheet" href="./normalize.css" />
```

## Fonts

#### Select Fonts

- [fontpair](https://www.fontpair.co/)
- [pagecloud](https://www.pagecloud.com/blog/best-google-fonts-pairings)

#### Grab the CSS

- [typescale](https://type-scale.com/)

Make some adjustments

## Colors

```css
:root {
  /* primary */
  /* grey */
  --black: #222;
  --white: #fff;
  --red-light: #f8d7da;
  --red-dark: #842029;
  --green-light: #d1e7dd;
  --green-dark: #0f5132;
}
```

#### Select Primary

Manual Approach

- [coolors](https://coolors.co/)
- [happyhues](https://www.happyhues.co/)
- select your own color
- get shades [shadowlord](https://noeldelgado.github.io/shadowlord/#73fdad)

Library/Faster Approach

- [bootstrap](https://getbootstrap.com/docs/5.0/customize/color/#color-sass-maps)
- [tailwind](https://tailwindcss.com/docs/customizing-colors#color-palette-reference)

#### Select Grey

- [tailwind](https://tailwindcss.com/docs/customizing-colors#color-palette-reference)

#### Just go with happyhues

- [happyhues](https://www.happyhues.co/)

#### Box Shadow

- [tailwind](https://tailwindcss.com/docs/box-shadow)
