<!--

@license Apache-2.0

Copyright (c) 2018 The Stdlib Authors.

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

   http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

-->


<details>
  <summary>
    About stdlib...
  </summary>
  <p>We believe in a future in which the web is a preferred environment for numerical computation. To help realize this future, we've built stdlib. stdlib is a standard library, with an emphasis on numerical and scientific computation, written in JavaScript (and C) for execution in browsers and in Node.js.</p>
  <p>The library is fully decomposable, being architected in such a way that you can swap out and mix and match APIs and functionality to cater to your exact preferences and use cases.</p>
  <p>When you use stdlib, you can be absolutely certain that you are using the most thorough, rigorous, well-written, studied, documented, tested, measured, and high-quality code out there.</p>
  <p>To join us in bringing numerical computing to the web, get started by checking us out on <a href="https://github.com/stdlib-js/stdlib">GitHub</a>, and please consider <a href="https://opencollective.com/stdlib">financially supporting stdlib</a>. We greatly appreciate your continued support!</p>
</details>

# Acanthus mollis

[![NPM version][npm-image]][npm-url] [![Build Status][test-image]][test-url] [![Coverage Status][coverage-image]][coverage-url] <!-- [![dependencies][dependencies-image]][dependencies-url] -->

> [_Acanthus mollis_][@blossfeldt:1928a].

<section class="intro">

Image of Karl Blossfeldt's gelatin silver print [_Acanthus mollis_][@blossfeldt:1928a].

<!-- <image align="center" src="./data/image.jpg" alt="Acanthus mollis"> -->

<div class="image" align="center">
    <img src="https://cdn.jsdelivr.net/gh/stdlib-js/stdlib@30236137d43c6a0dc458588e66527f6762e10634/lib/node_modules/%40stdlib/datasets/img-acanthus-mollis/data/image.jpg" alt="Acanthus mollis">
    <br>
</div>

<!-- </image> -->

[_Acanthus mollis_][@blossfeldt:1928a] is a plant with tall, straight stem and spiky, black tipped leaves.

</section>

<!-- /.intro -->



<section class="usage">

## Usage

To use in Observable,

```javascript
image = require( 'https://cdn.jsdelivr.net/gh/stdlib-js/datasets-img-acanthus-mollis@umd/browser.js' )
```

To vendor stdlib functionality and avoid installing dependency trees for Node.js, you can use the UMD server build:

```javascript
var image = require( 'path/to/vendor/umd/datasets-img-acanthus-mollis/index.js' )
```

To include the bundle in a webpage,

```html
<script type="text/javascript" src="https://cdn.jsdelivr.net/gh/stdlib-js/datasets-img-acanthus-mollis@umd/browser.js"></script>
```

If no recognized module system is present, access bundle contents via the global scope:

```html
<script type="text/javascript">
(function () {
    window.image;
})();
</script>
```

#### image()

Returns a [buffer][@stdlib/buffer/ctor] containing image data.

```javascript
var img = image();
// returns <Buffer>
```

</section>

<!-- /.usage -->

<section class="examples">

<!-- TODO: more creative example. -->

## Examples

<!-- eslint no-undef: "error" -->

```html
<!DOCTYPE html>
<html lang="en">
<body>
<script type="text/javascript" src="https://cdn.jsdelivr.net/gh/stdlib-js/datasets-img-acanthus-mollis@umd/browser.js"></script>
<script type="text/javascript">
(function () {

var img = image();
console.log( img );

})();
</script>
</body>
</html>
```

</section>

<!-- /.examples -->



<!-- <license> -->

## License

Digital image courtesy of the Getty's [Open Content Program][getty-open-content]. The data files (databases) are licensed under an [Open Data Commons Public Domain Dedication & License 1.0][pddl-1.0] and their contents are licensed under [Creative Commons Zero v1.0 Universal][cc0]. The software is licensed under [Apache License, Version 2.0][apache-license].

<!-- </license> -->

<!-- Section for related `stdlib` packages. Do not manually edit this section, as it is automatically populated. -->

<section class="related">

* * *

## See Also

-   <span class="package-name">[`@stdlib/datasets-img-allium-oreophilum`][@stdlib/datasets/img-allium-oreophilum]</span><span class="delimiter">: </span><span class="description">allium oreophilum (pink lily leek).</span>

</section>

<!-- /.related -->

<!-- Section for all links. Make sure to keep an empty line after the `section` element and another before the `/section` close. -->


<section class="main-repo" >

* * *

## Notice

This package is part of [stdlib][stdlib], a standard library for JavaScript and Node.js, with an emphasis on numerical and scientific computing. The library provides a collection of robust, high performance libraries for mathematics, statistics, streams, utilities, and more.

For more information on the project, filing bug reports and feature requests, and guidance on how to develop [stdlib][stdlib], see the main project [repository][stdlib].

#### Community

[![Chat][chat-image]][chat-url]

---

## Copyright

Copyright &copy; 2016-2024. The Stdlib [Authors][stdlib-authors].

</section>

<!-- /.stdlib -->

<!-- Section for all links. Make sure to keep an empty line after the `section` element and another before the `/section` close. -->

<section class="links">

[npm-image]: http://img.shields.io/npm/v/@stdlib/datasets-img-acanthus-mollis.svg
[npm-url]: https://npmjs.org/package/@stdlib/datasets-img-acanthus-mollis

[test-image]: https://github.com/stdlib-js/datasets-img-acanthus-mollis/actions/workflows/test.yml/badge.svg?branch=main
[test-url]: https://github.com/stdlib-js/datasets-img-acanthus-mollis/actions/workflows/test.yml?query=branch:main

[coverage-image]: https://img.shields.io/codecov/c/github/stdlib-js/datasets-img-acanthus-mollis/main.svg
[coverage-url]: https://codecov.io/github/stdlib-js/datasets-img-acanthus-mollis?branch=main

<!--

[dependencies-image]: https://img.shields.io/david/stdlib-js/datasets-img-acanthus-mollis.svg
[dependencies-url]: https://david-dm.org/stdlib-js/datasets-img-acanthus-mollis/main

-->

[chat-image]: https://img.shields.io/gitter/room/stdlib-js/stdlib.svg
[chat-url]: https://app.gitter.im/#/room/#stdlib-js_stdlib:gitter.im

[stdlib]: https://github.com/stdlib-js/stdlib

[stdlib-authors]: https://github.com/stdlib-js/stdlib/graphs/contributors

[cli-section]: https://github.com/stdlib-js/datasets-img-acanthus-mollis#cli
[cli-url]: https://github.com/stdlib-js/datasets-img-acanthus-mollis/tree/cli
[@stdlib/datasets-img-acanthus-mollis]: https://github.com/stdlib-js/datasets-img-acanthus-mollis/tree/main

[umd]: https://github.com/umdjs/umd
[es-module]: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Modules

[deno-url]: https://github.com/stdlib-js/datasets-img-acanthus-mollis/tree/deno
[umd-url]: https://github.com/stdlib-js/datasets-img-acanthus-mollis/tree/umd
[esm-url]: https://github.com/stdlib-js/datasets-img-acanthus-mollis/tree/esm
[branches-url]: https://github.com/stdlib-js/datasets-img-acanthus-mollis/blob/main/branches.md

[getty-open-content]: http://www.getty.edu/about/opencontent.html

[pddl-1.0]: http://opendatacommons.org/licenses/pddl/1.0/

[cc0]: https://creativecommons.org/publicdomain/zero/1.0

[apache-license]: https://www.apache.org/licenses/LICENSE-2.0

[@blossfeldt:1928a]: http://www.getty.edu/art/collection/objects/35443/karl-blossfeldt-acanthus-mollis-german-1928/

[@stdlib/buffer/ctor]: https://github.com/stdlib-js/buffer-ctor/tree/umd

<!-- <related-links> -->

[@stdlib/datasets/img-allium-oreophilum]: https://github.com/stdlib-js/datasets-img-allium-oreophilum/tree/umd

<!-- </related-links> -->

</section>

<!-- /.links -->
