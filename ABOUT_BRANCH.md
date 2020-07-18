# About npm-build

This branch is meant to support building of BG for class platform deployment using `npx` or `npm i -g`

The aim is to be able to include sharp which allows us to use WebP, which saves bandwidth and reduces lag relative to JPEG.

Currently it does not work because it's hard to pack using webpack and create cross-platform or choose at runtime between mutliple platform node native modules for sharp (*.node files).


