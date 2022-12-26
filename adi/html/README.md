# Environment for HTML/CSS

## Update packages to latest version

```shell
$ npx npm-check-updates -u
$ npm install 
```

## BEM: Block Element Modifier

**Block**: standalone component that is meaningful on its own.
**Element**: part of block that has no standalone meaning.
**Modifier**: a different version of a block or an element.
```css
.block {}
.block__element {}
.block__element--modifier {}
```