### Javascript

## Destructuring

## async & fetch

## modules. lets you split big code bases across multiple files.

- top level await. need await to run an async function but JS complains if trying to await outside of an async function. add `type="module"` to the script tag.
- modules also create their own scope. accessing data within `<script></script>` tag is fine from global, but `<script type="module"></script>` cannot be accessed in the same way.
- to access modules and their scope then need to use `import && export`
