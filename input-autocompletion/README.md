# Input Autocompletion

> This project is a proof-of-concept (PoC) to show that CSS Variables can be used to simplify more complex functions, such as providing autocompletion to an input.

My attempt to re-create the input element with inline autocompletion in plain HTML/CSS with minimal Javascript.

## How it works?

It uses CSS `::before` pseudo element to show the autocomplete text inside the text input along with the original entered value.

I've also used CSS Variable `--autocomplete` for the autocomplete text, which allows dynamically changing the autocomplete text just by changing the CSS Variable value.

## Demo

You can find a working prototype here: https://deshmukhmayur.github.io/playground/input-autocompletion/

Or on Codepen: https://codepen.io/deshmukhmayur/pen/xaKMqQ

**Note:**
The demo only works for the following words:

```text
Apple, Background, Color, Display, Element, Flex, Global, Helvetica, Input, Justify, Keyboard, Language, Monitor, NotoSans, Overflow, Padding, Query, Roboto, Stylesheets, Transition, Ubuntu, Viewport, Width, XboxOne, Yellow, Z-index
```

To add more words, the `words` array needs to be updated.

## License

This PoC is licensed under [MIT](LICENSE) License.
