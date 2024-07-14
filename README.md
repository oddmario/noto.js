# 🚀 Noto.js
## Google Noto Emojis for the Web ☄️

![GitHub License](https://img.shields.io/github/license/oddmario/noto.js)
![GitHub commit activity](https://img.shields.io/github/commit-activity/m/oddmario/noto.js)
![GitHub Issues or Pull Requests](https://img.shields.io/github/issues/oddmario/noto.js)
![GitHub Issues or Pull Requests](https://img.shields.io/github/issues-pr/oddmario/noto.js)

a project inspired by the Twitter/X Twemoji project — https://github.com/twitter/twemoji — **but** for the Google Emoji set instead

<p align="center">
  <img width="700" height="auto" src="https://i.ibb.co/sJTdxKQ/Screenshot-from-2024-07-14-14-30-20.png">
</p>

-----

## Usage
You may include Noto.js from the [jsDelivr CDN](https://www.jsdelivr.com/), or you may alternatively host it locally by hosting the `dist/noto-vX.Y.min.js` file on your server and embedding it onto your application from there.

To include Noto.js from jsDelivr, append the following line inside your `<head></head>` tag:
```html
<script src="https://cdn.jsdelivr.net/gh/oddmario/noto.js/dist/noto-v1.0.min.js"></script>
```

You can then start making your web page look prettier by using the one and only function of Noto.js, `notojs.parse`:
```js
notojs.parse(document.body) // finds any emojis inside the DOM body and converts them to Google Noto emojis
notojs.parse(document.querySelector("#mycooldiv")) // finds any emojis inside the #mycooldiv DOM element and converts them to Google Noto emojis
```

### Simple is it not?

## License
- Code licensed under the MIT License: http://opensource.org/licenses/MIT
- Graphics provided by the Google Noto project: https://github.com/googlefonts/noto-emoji