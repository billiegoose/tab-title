<!-- TITLE/ -->

<h1>tab-title</h1>

<!-- /TITLE -->


<!-- BADGES/ -->



<!-- /BADGES -->


<!-- DESCRIPTION/ -->

Sets process.title in node, document.title in browserify

```js
const title = require('tab-title')
title('My App Rocks')
```

I wrote it because I was making a massively peer-to-peer isomorphic app,
and needed a fast way to differentiate instances by their UUIDs. Tab titles
turned out to be incredibly convenient.

<!-- /DESCRIPTION -->


## Installation

Download node at [nodejs.org](http://nodejs.org) and install it, if you haven't already.

Then in the terminal, run:

```sh
npm install tab-title --save
```

<!-- LICENSE/ -->

<h2>License</h2>

Unless stated otherwise all works are:

<ul><li>Copyright &copy; William Hilton</li></ul>

and licensed under:

<ul><li><a href="http://spdx.org/licenses/Unlicense.html">The Unlicense</a></li></ul>

<!-- /LICENSE -->


_Parts of this file are based on [package-json-to-readme](https://github.com/zeke/package-json-to-readme)_

_README.md (and other files) are maintained using [mos](https://github.com/mosjs/mos) and [projectz](https://github.com/bevry/projectz)_
