# Meme API

![Meme API](https://user-images.githubusercontent.com/17960677/100463045-3f2b8380-30f1-11eb-87c0-62d45b67bbaa.png)

>**A complete meme library for node.js**

## List of Available Meme Sources

* 9gag
* Funny Quotes and Memes
* iFunny
* Memedroid

## Example

The Following Code snippet will help you understand how to use this.

```js
var Meme = require("meme-api");
var meme = new Meme();

(async function() {
  await meme.random("9gag"); // A random meme from 9gag
  await meme.feed("9gag"); // A list of memes from 9gag
})();
```

## Contributing

Thank you for your interest in contributing, If you feel like there's something missing or any new feature can be added, just create a PR and I will see the rest.

## Help

You can contact me on social media, Everything about me can be found [here](https://theabbie.github.io)

## Installation

### Requirements

* Node.Js installed

### Dev Dependencies

* Axios

## Credits

Thanks to all the available meme sources and the ones which will be used in future.

## Contact

Contact me anywhere, just visit [my portfolio](https://theabbie.github.io)

## License

This project is licensed under MIT License, See [LICENSE](/LICENSE) for more information



