### Javascript

## DOM

- document represents web page loaded in the browser. serves as entry point into content.

## Destructuring

## async & fetch

## modules. lets you split big code bases across multiple files.

- top level await. need await to run an async function but JS complains if trying to await outside of an async function. add `type="module"` to the script tag.
- modules also create their own scope. accessing data within `<script></script>` tag is fine from global, but `<script type="module"></script>` cannot be accessed in the same way.
- to access modules and their scope then need to use `import && export`

## debugging

- add `debugger;` into script to put in a break point or via dev tools
- step over into next line/function. check scope

## try catch error handling

- use throw to throw error
- `try {} catch (err) {}`
- some error types (rangeError, referenceError, syntaxError, typeError, URIError, EvalError, internalError)
