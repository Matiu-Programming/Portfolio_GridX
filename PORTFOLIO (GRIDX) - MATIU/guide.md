# Essential Stuff

## Html import links

Google font

```css
@import url('https://fonts.googleapis.com/css2?family=Inter:wght@100;200;300;400;500;600;700;800;900&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@100;200;300;400;500;600;700;800&display=swap');
```

Remix icon

```html
<link href="https://cdn.jsdelivr.net/npm/remixicon@3.4.0/fonts/remixicon.css" rel="stylesheet"/>
```

Root

```css
:root {
  /**
  * typography
  * */
  --f-family-inter: "Inter", sans-serif;
  --f-family-poppins: "Poppins", sans-serif;
  /**
  * weight
  * */
  --f-weight-400: 400;
  --f-weight-500: 500;
  --f-weight-600: 600;
  --f-weight-700: 700;
  --f-weight-800: 800;
  /**
  * colors
  * */
  --bs-color-inner-black: hsl(0, 0%, 6%);
  --bs-color-inner-white: hsl(0, 0%, 100%);
  --bs-color-inner-gray: hsl(0, 0%, 74%);
  --bs-color-inner-gray-dark: hsl(0, 0%, 40%);
  --bs-color-inner-button: hsl(0, 0%, 20%);
  --bs-color-inner-purple: hsl(229, 90%, 66%);
  --bs-color-gradient-me: linear-gradient(
    90deg,
    #5b78f6 -15%,
    #c2ebff 58%,
    #5b78f6 97%
  );
  --bs-color-main-gradient-box: linear-gradient(
    120deg,
    rgba(255, 255, 255, 0.178),
    rgba(255, 255, 255, 0.011)
  );
  --bs-color-main-box: hsl(0, 0%, 6%);
  /**
  * radius
  * */
  --radius-30: 30px;
  --radius-50: 50%;
  /**
  * transition
  * */
  --transition-inner: ease-in-out 0.5s;
  /**
  * spacing
  * */
  --space-section: 70px;
}
```
