# About

L-Ed is a **modern**, **lightweight** and **open-source** 2D level editor.

Links: [Official website](https://deepnight.net/tools/led-2d-level-editor/) | [Haxe API (on GitHub)](https://github.com/deepnight/led-haxe-api)

# Building from source

## Prerequisites

 - **[Haxe compiler](https://haxe.org)**: you need an up-to-date and working Haxe install  to build L-Ed.
 - **[NPM](https://www.npmjs.com/)**: this package manager is used for various install and packaging scripts

Install all required dependencies:
 - open a command line inside the `app` folder,
 - run `npm i`

Install required haxe libs:
 - `haxelib git heaps https://github.com/HeapsIO/heaps.git`
 - `haxelib git hxnodejs https://github.com/HaxeFoundation/hxnodejs.git`
 - `haxelib git hxelectron https://github.com/tong/hxelectron.git`
 - `haxelib git deepnightLibs https://github.com/deepnight/deepnightLibs.git`

## Compiling

Run either: 

 - `haxe app.hxml` (release version)
 - `npm run compile` from the app folder (same effect as above)
 - `haxe app.debug.hxml` (debug version)