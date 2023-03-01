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

<section class="installation">

## Installation

```bash
npm install @stdlib/datasets-img-acanthus-mollis
```

Alternatively,

-   To load the package in a website via a `script` tag without installation and bundlers, use the [ES Module][es-module] available on the [`esm` branch][esm-url].
-   If you are using Deno, visit the [`deno` branch][deno-url].
-   For use in Observable, or in browser/node environments, use the [Universal Module Definition (UMD)][umd] build available on the [`umd` branch][umd-url].
-   To use as a general utility for the command line, install the corresponding [CLI package][cli-section] globally.

The [branches.md][branches-url] file summarizes the available branches and displays a diagram illustrating their relationships.

</section>

<section class="usage">

## Usage

```javascript
var image = require( '@stdlib/datasets-img-acanthus-mollis' );
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

```javascript
var image = require( '@stdlib/datasets-img-acanthus-mollis' );

var img = image();
console.log( img );
```

</section>

<!-- /.examples -->

* * *

<section class="cli">

## CLI

<section class="installation">

## Installation

To use as a general utility, install the CLI package globally

```bash
npm install -g @stdlib/datasets-img-acanthus-mollis-cli
```

</section>

<!-- CLI usage documentation. -->

<section class="usage">

### Usage

```text
Usage: img-acanthus-mollis [options]

Options:

  -h,    --help                Print this message.
  -V,    --version             Print the package version.
```

</section>

<!-- /.usage -->

<section class="examples">

### Examples

```bash
$ img-acanthus-mollis | <image_viewer>
```

</section>

<!-- /.examples -->

</section>

<!-- /.cli -->

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

Copyright &copy; 2016-2023. The Stdlib [Authors][stdlib-authors].

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
[chat-url]: https://gitter.im/stdlib-js/stdlib/

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

[@stdlib/buffer/ctor]: https://github.com/stdlib-js/buffer-ctor

<!-- <related-links> -->

[@stdlib/datasets/img-allium-oreophilum]: https://github.com/stdlib-js/datasets-img-allium-oreophilum

<!-- </related-links> -->

</section>

<!-- /.links -->
