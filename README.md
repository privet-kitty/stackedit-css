# stackedit-css

> [!NOTE]
> This repository is not official.

This repository maintains the CSS files extracted from Benoit Schweblin's [StackEdit](https://github.com/benweet/stackedit/) for external use.


## Build

```bash
npm install
npm run build
```

## Import

CSS files can be imported from [jsDelivr](https://www.jsdelivr.com/).

```html
<head>
    <link href='https://cdn.jsdelivr.net/npm/stackedit-css@{{version}}/dist/style.css' rel='stylesheet' />
</head>
```

Note that the `{{version}}` should be replaced with the version you want to use.

## Publish

```bash
version=$(npm version patch)
git push origin $version
npm publish
```