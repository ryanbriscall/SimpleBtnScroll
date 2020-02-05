# A simple button-based page scroll script

A tiny script for scrolling the page using buttons.  Less swiping on mobile.

[View Demo](https://codepen.io/ryanbriscall/pen/YzXKjBN)

For a quick one-time lightweight single-page web (mobile?) app with compatible and portable inline assets.

Simply copy/paste the code into your very long page.

## Code

1. HTML buttons:

   ```html
   <div style="position: fixed; right: 0.5em; top: 50%; margin-top: -3em">
   <button type="button" style="display: block; min-width: 50px; min-height: 50px;" onclick="window.scrollTo(0,window.pageYOffset-window.innerHeight);">⬆️</button>
   <button type="button" style="display: block; min-width: 50px; min-height: 50px;" onclick="window.scrollTo(0,window.pageYOffset+window.innerHeight);">⬇️</button>
   </div>
   ```

## Usage

1. Press the buttons ⬆️ and ⬇️.

## Changelog

### 1.0.0

 - Initial release.

## License

Licensed under the MIT, see the `LICENSE` file for more details.
