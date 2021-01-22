
# General web development tips

Here are some tips that may help you get started with web development.

- [General web development tips](#general-web-development-tips)
  - [Do not use TextEdit on Mac for editing code](#do-not-use-textedit-on-mac-for-editing-code)
  - [CSS Flexbox](#css-flexbox)
  - [JS Tutorials](#jstutorials)
  - [JS statements: `let` vs. `var` vs. `const`](#js-statements-let-vs-var-vs-const)

## Do not use TextEdit on Mac for editing code

It defaults to rich text format (RTF) instead of the plain text we need. It also doesn't provide syntax highlighting. If you absolutely must use it, change the default format to plain text ([instructions here](https://support.apple.com/guide/textedit/change-textedit-preferences-txted1063/mac)).

## CSS Flexbox

CSS can be a bear to use. Here is one resource that might help you to at least learn about [the CSS flexbox layout](https://css-tricks.com/snippets/css/a-guide-to-flexbox/).

## JS Tutorials

Learning JS can also be challenging. Here is [one tutorial series that may help](https://javascript.info/).

## JS statements: `let` vs. `var` vs. `const`

To make our code more modular, reusable, and error-free we should limit variable scope to the relevant parts of the code.
In part, we do this by using [`let` statements](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/let) instead of [`var`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/var) by default so as to not set global variables.
We can also use [`const`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/const) to create read-only references.