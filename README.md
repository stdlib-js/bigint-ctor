<!--

@license Apache-2.0

Copyright (c) 2021 The Stdlib Authors.

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

# BigInt

[![NPM version][npm-image]][npm-url] [![Build Status][test-image]][test-url] [![Coverage Status][coverage-image]][coverage-url] <!-- [![dependencies][dependencies-image]][dependencies-url] -->

> [BigInt][mdn-bigint] factory.

<!-- Section to include introductory text. Make sure to keep an empty line after the intro `section` element and another before the `/section` close. -->

<section class="intro">

</section>

<!-- /.intro -->

<!-- Package usage documentation. -->

<section class="installation">

## Installation

```bash
npm install @stdlib/bigint-ctor
```

</section>

<section class="usage">

## Usage

```javascript
var BigInt = require( '@stdlib/bigint-ctor' );
```

#### BigInt( value )

Returns a [`BigInt`][mdn-bigint] primitive.

<!-- run-disable -->

```javascript
var v = BigInt( '1' );
// returns <bigint>
```

TODO: document properties/methods

</section>

<!-- /.usage -->

<!-- Package usage notes. Make sure to keep an empty line after the `section` element and another before the `/section` close. -->

<section class="notes">

## Notes

-   Unlike conventional constructors, the function does **not** support the `new` keyword.
-   The function is only supported in environments which support [`BigInt`][mdn-bigint]. In non-supporting environments, the value is `undefined`.

</section>

<!-- /.notes -->

<!-- Package usage examples. -->

<section class="examples">

## Examples

<!-- eslint no-undef: "error" -->

```javascript
var hasBigIntSupport = require( '@stdlib/assert-has-bigint-support' );
var BigInt = require( '@stdlib/bigint-ctor' );

var v;

if ( hasBigIntSupport() ) {
    v = BigInt( '1' );

    // Print the value type:
    console.log( typeof v );
    // => 'bigint'

    // Serialize the BigInt as a string:
    console.log( v.toString() );
    // => '1'
} else {
    console.log( 'Environment does not support BigInts.' );
}
```

</section>

<!-- /.examples -->

<!-- Section to include cited references. If references are included, add a horizontal rule *before* the section. Make sure to keep an empty line after the `section` element and another before the `/section` close. -->

<section class="references">

</section>

<!-- /.references -->

<!-- Section for related `stdlib` packages. Do not manually edit this section, as it is automatically populated. -->

<section class="related">

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

## License

See [LICENSE][stdlib-license].


## Copyright

Copyright &copy; 2016-2021. The Stdlib [Authors][stdlib-authors].

</section>

<!-- /.stdlib -->

<!-- Section for all links. Make sure to keep an empty line after the `section` element and another before the `/section` close. -->

<section class="links">

[npm-image]: http://img.shields.io/npm/v/@stdlib/bigint-ctor.svg
[npm-url]: https://npmjs.org/package/@stdlib/bigint-ctor

[test-image]: https://github.com/stdlib-js/bigint-ctor/actions/workflows/test.yml/badge.svg
[test-url]: https://github.com/stdlib-js/bigint-ctor/actions/workflows/test.yml

[coverage-image]: https://img.shields.io/codecov/c/github/stdlib-js/bigint-ctor/main.svg
[coverage-url]: https://codecov.io/github/stdlib-js/bigint-ctor?branch=main

<!--

[dependencies-image]: https://img.shields.io/david/stdlib-js/bigint-ctor.svg
[dependencies-url]: https://david-dm.org/stdlib-js/bigint-ctor/main

-->

[chat-image]: https://img.shields.io/gitter/room/stdlib-js/stdlib.svg
[chat-url]: https://gitter.im/stdlib-js/stdlib/

[stdlib]: https://github.com/stdlib-js/stdlib

[stdlib-authors]: https://github.com/stdlib-js/stdlib/graphs/contributors

[stdlib-license]: https://raw.githubusercontent.com/stdlib-js/bigint-ctor/main/LICENSE

[mdn-bigint]: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/BigInt

</section>

<!-- /.links -->
