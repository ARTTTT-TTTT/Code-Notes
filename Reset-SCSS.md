# _reset.scss

```scss
/*
  Modern Reset
  See https://hankchizljaw.com/wrote/a-modern-css-reset/

  Note: This file uses some CSS variables and thus cannot be wholly updated via copy+paste.
*/

/* Box sizing rules */
*,
*::before,
*::after {
  box-sizing: border-box;
}

/* Remove default margin */
body,
h1,
h2,
h3,
h4,
p,
figure,
blockquote,
dl,
dd {
  margin: 0;
}

ul,
ol {
  list-style: none;
  margin: 0;
  padding: 0;
}

/* Set core root defaults */
html {
  scroll-behavior: smooth;
}

/* Set core body defaults */
body {
  font-family: var(--font-family);
  font-size: (--font-size-base);
  line-height: var(--line-height-base);
  text-rendering: optimizeSpeed;
  min-height: 100vh;
}

/* A elements that don't have a class get default styles */
a:not([class]) {
  text-decoration-skip-ink: auto;
}

a,
a:hover,
a:focus,
a:active {
  text-decoration: none;
  color: inherit;
}

/* Make images easier to work with */
img,
picture {
  display: block;
  max-width: 100%;
}

/* Inherit fonts for inputs and buttons */
input,
button,
textarea,
select {
  font: inherit;
}

/* Remove all animations, transitions and smooth scroll for people that prefer not to see them */
@media (prefers-reduced-motion: reduce) {
  html {
    scroll-behavior: auto;
  }

  *,
  *::before,
  *::after {
    animation-duration: 0.01ms !important;
    animation-iteration-count: 1 !important;
    scroll-behavior: auto !important;
    transition-duration: 0.01ms !important;
  }
}
```

---

# app.scss

```scss
:root {
  /* Palette */
  --primary-color: #22223b;
  --secondary-color: #4a4e69;
  --tertiary-color: #9a8c98;
  --quaternary-color: #c9ada7;
  --quinary-color: #f2e9e4;

  /* Colors */
  --success-color: #28a745;
  --error-color: #dc3545;
  --warning-color: #ffc107;
  --info-color: #17a2b8;

  /* Fonts */ /* based on the following type-scale https://type-scale.com/?size=16&scale=1.200&text=MDN%20Web%20Docs&font=Inter&fontweight=400&bodyfont=body_font_default&bodyfontweight=400&lineheight=1.75&backgroundcolor=%23ffffff&fontcolor=%23000000&preview=false */
  --font-family: "Kanit", sans-serif;
  --font-size-base: 1rem;
  --smaller-font-size: 0.833rem;
  --tiny-font-size: 0.694rem;
  --line-height-base: 1.5;
  --heading-font-family: "Kanit", sans-serif;
  --h1-font-size: 3rem;
  --h2-font-size: 2.5rem;
  --h3-font-size: 2rem;
  --h4-font-size: 1.5rem;
  --h5-font-size: 1.25rem;
  --h6-font-size: 1rem;

  /* Spacing */
  --spacing-unit: 1rem;
  --spacing-sm: 0.5rem;
  --spacing-md: 1.5rem;
  --spacing-lg: 2rem;
  --spacing-xl: 3rem;

  /* Border */
  --border-radius: 0.25rem;
  --border-width: 1px;
  --border-color: #dee2e6;

  /* Grid and Layout */
  --max-width: 1440px;
  --gutter: 1rem; /* Space between content and browser window */
}
```

---