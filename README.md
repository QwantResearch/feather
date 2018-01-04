# Qwant Feather Icons

![Icons List](https://raw.githubusercontent.com/QwantResearch/qwant-feather-icons/master/examples/demo.png)

## What is this ?

This is a collection of simply open source icons. Each icon is designed on a 24x24 grid for Qwant website.


## Compile sources

```bash
git clone git@github.com:QwantResearch/qwant-feather-icons.git
cd qwant-feather-icons
yarn build
```

Include `feather.min.js` with a `<script>` tag. This file is located in the `dist` directory of the package.

## Quick Start

```html
<!DOCTYPE html>
<html lang="fr">
  <head>
    <title>Qwant</title>
  </head>
  <body>

    <!-- All available icons -->
    <i name="3col-view-color"></i>  <!-- All active icon -->
    <i name="3col-view-mono"></i>  <!-- All icon -->
    <i name="chevron-down"></i>
    <i name="chevron-up"></i>
    <i name="chevron-left"></i>
    <i name="chevron-right"></i>
    <i name="cross"></i>
    <i name="globe"></i>  <!-- Web icon -->
    <i name="image"></i>
    <i name="list"></i>
    <i name="music"></i>
    <i name="news"></i>
    <i name="search"></i>
    <i name="settings"></i>
    <i name="shopping"></i>
    <i name="social"></i>
    <i name="videos"></i>

    <script src="feather.min.js"></script>
    <script>
      feather.replace()
    </script>
  </body>
</html>
```

## Usage

To use an icon on your page, add a `name` attribute with the icon name to an element.

```html
<i name="social"></i>
```

Then call the `feather.replace()` method.

```html
<script>
  feather.replace()
</script>
```

All elements that have a `name` attribute will be replaced with SVG markup corresponding to their `name` attribute value.
