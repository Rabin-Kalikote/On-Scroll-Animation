# Setup wow.js

## 1. Link to the CSS animation library

Link to Animate.css

```html
<link rel="stylesheet" href="css/animate.css">
```

## 2. Link and activate wow.js

```html
<script src="js/wow.min.js"></script>
<script>
  new WOW().init();
</script>
```

# Reveal CSS Animations

## 1. Make an element revealable

Add the CSS class .wow to a HTML element: it will be invisible until the user scrolls to reveal it.

```html
<div class="wow">
  Content to Reveal Here
</div>
```

## 2. Choose the animation style

Pick an animation style in Animate.css , then add the CSS class to the HTML element

```html
<div class="wow bounceInUp">
  Content to Reveal Here
</div>
```

# You’re done!

Now your animations will be revealed when the user scrolls.

Sources: [Wow.js](https://wowjs.uk/) and [Animate.css](https://daneden.github.io/animate.css)
