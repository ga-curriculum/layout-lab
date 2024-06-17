# ![Layout Lab - Exercise](./assets/hero.png)

## Layout Lab

Time for some practice laying out elements using Flexbox and CSS Grid!

For this lab, you'll use the following image as a reference: 

<img src="./assets/john-shoshone-card.png" alt="reference card">

Use a combination of Flexbox and CSS Grid to reproduce either the vertical or horizontal version. Layout the individual elements as close as possible - however, it does not have to be perfect! You are not being graded on matching fonts exactly or duplicating every glyph, font, or image exactly. The primary focus here is that you get experience using CSS Grid/CSS Flexbox and responsive design.

For an extra challenge, you can try to reproduce both layouts! 

### Hints

- Take some time before you start coding to think about how you're going to structure your HTML! 

- Elements can be made to appear circular by using `border-radius: 50%;`.

- You can use emojis in place of the stars/phone icon/message icon for simplicity. (If you want an extra challenge, you can also opt to use a free icon library like Font Awesome instead).

- Use any appropriate image you desire as the profile picture. Perhaps use [picsum.photos](https://picsum.photos/) for a fast solution?

- You may want to start with a default CSS reset, which can be copied directly into your `css/styles.css` file before starting:

```css
html {
  box-sizing: border-box
}

/* The Universal Selector */
*, /* All elements*/
*::before, /* All ::before pseudo-elements */
*::after { /* All ::after pseudo-elements */
  /* height & width will now include border & padding by default
     but can be over-ridden as needed */
  box-sizing: inherit;
}

body {
  background-color: gray;
/* Use a system font, if none are available use an available sans-sarif   font */
  font-family: system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI",
    Roboto, Oxygen-Sans, Ubuntu, Cantarell, "Helvetica Neue", sans-serif;
  margin: 0;
}
```
