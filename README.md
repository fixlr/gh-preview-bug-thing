# gh-preview-bug-thing

```js
function thisProbablyWorks() {
  return true;
}
```

```coffee
thisProbablyWorks = ->
  true
```

## Appears to be broken:

1. Edit this file on GH, in the web browser.
2. Add the following `coffee` snippet.
3. Click "Preview"
4. Watch the endless spinning!  WHEEEEEE.

```coffee
//= require path/to/assets
```