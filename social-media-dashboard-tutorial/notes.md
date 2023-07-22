## Functional requirements and notes

Light/Dark mode toggle -- takes system preference by default, but can override with toggle

- What HTML markup (accessible) -- https://scottaohara.github.io/a11y_styled_form_controls/src/radio-button--switch

Use fieldset, legend, radio inputs

- Switching between light/dark mode via JS and prefers-color-scheme media query -- https://developer.mozilla.org/en-US/docs/Web/CSS/@media/prefers-color-scheme

- Three option toggle: light/dark/system preference -- https://codepen.io/renddrew/pen/bRomab?editors=1100

CSS variables (custom properties) -- https://css-tricks.com/updating-a-css-variable-with-javascript

Accessibility
- Use correct heading tags
- Screenreader-only text for card titles/username -- https://www.accessibility-developer-guide.com/examples/hiding-elements/visually/
 

### Accesssible toggle in HTML, CSS and JS with explanatory notes (frontend mentor challenge)
- Check Github repo for link to website with accessible form control elements

* Search code for UI elements on Codepen


#### Block Element Modifier

Block = card
Element = icon, platform, count, change
Modifier = facebook, twitter, etc

Start with block name
card
card__icon
card__icon--facebook
card__username

card__count
card__count--big, card__count--small
card__label
card__change
card__change--up
card__change--down

This convention works well with Sass' nesting