# Study Meta Viewport Tag

🖥 demos for the behavior of the meta viewport tag

## When does `shrink-to-fit` happen?

When the page loads, it has already taken up the size of the overflow element and has shrunk the viewport to fit the overflowing content.

The further widening of the content is no longer fitted, as in the [shrink-to-fit-demo](./shrink-to-fit-demo/index.html), neither `setTimeout` nor changes triggered by the button will result in further layout viewport size fitting.

However, real-world situations are much more complex. 