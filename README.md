[javascript-detect-element-resize](https://github.com/sdecima/javascript-detect-element-resize)
 fork form [bvaughn/react-virtualized](https://github.com/bvaughn/react-virtualized/) extracted into its own repository and npm project.
```
/**
 * Detect Element Resize.
 * https://github.com/sdecima/javascript-detect-element-resize
 * Sebastian Decima
 *
 * Forked from version 0.5.3; includes the following modifications:
 * 1) Guard against unsafe 'window' and 'document' references (to support SSR).
 * 2) Defer initialization code via a top-level function wrapper (to support SSR).
 * 3) Avoid unnecessary reflows by not measuring size for scroll events bubbling from children.
 * 4) Add nonce for style element.
 **/
 ```
