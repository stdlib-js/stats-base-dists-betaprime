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

# Beta Prime

[![NPM version][npm-image]][npm-url] [![Build Status][test-image]][test-url] [![Coverage Status][coverage-image]][coverage-url] <!-- [![dependencies][dependencies-image]][dependencies-url] -->

> Beta prime distribution.



<section class="usage">

## Usage

```javascript
import betaprime from 'https://cdn.jsdelivr.net/gh/stdlib-js/stats-base-dists-betaprime@deno/mod.js';
```

You can also import the following named exports from the package:

```javascript
import { BetaPrime, cdf, kurtosis, logcdf, logpdf, mean, mode, pdf, quantile, skewness, stdev, variance } from 'https://cdn.jsdelivr.net/gh/stdlib-js/stats-base-dists-betaprime@deno/mod.js';
```

#### betaprime

Beta prime distribution.

```javascript
var dist = betaprime;
// returns {...}
```

The namespace contains the following distribution functions:

<!-- <toc pattern="*+(cdf|pdf|mgf|quantile)*"> -->

<div class="namespace-toc">

-   <span class="signature">[`cdf( x, alpha, beta )`][@stdlib/stats/base/dists/betaprime/cdf]</span><span class="delimiter">: </span><span class="description">beta prime distribution cumulative distribution function.</span>
-   <span class="signature">[`logcdf( x, alpha, beta )`][@stdlib/stats/base/dists/betaprime/logcdf]</span><span class="delimiter">: </span><span class="description">evaluate the natural logarithm of the cumulative distribution function for a beta prime distribution .</span>
-   <span class="signature">[`logpdf( x, alpha, beta )`][@stdlib/stats/base/dists/betaprime/logpdf]</span><span class="delimiter">: </span><span class="description">beta prime distribution logarithm of probability density function (PDF).</span>
-   <span class="signature">[`pdf( x, alpha, beta )`][@stdlib/stats/base/dists/betaprime/pdf]</span><span class="delimiter">: </span><span class="description">beta prime distribution probability density function (PDF).</span>
-   <span class="signature">[`quantile( p, alpha, beta )`][@stdlib/stats/base/dists/betaprime/quantile]</span><span class="delimiter">: </span><span class="description">beta prime distribution quantile function.</span>

</div>

<!-- </toc> -->

The namespace contains the following functions for calculating distribution properties:

<!-- <toc pattern="*+(entropy|kurtosis|mean|median|mode|skewness|stdev|variance)*"> -->

<div class="namespace-toc">

-   <span class="signature">[`kurtosis( alpha, beta )`][@stdlib/stats/base/dists/betaprime/kurtosis]</span><span class="delimiter">: </span><span class="description">beta prime distribution excess kurtosis.</span>
-   <span class="signature">[`mean( alpha, beta )`][@stdlib/stats/base/dists/betaprime/mean]</span><span class="delimiter">: </span><span class="description">beta prime distribution expected value.</span>
-   <span class="signature">[`mode( alpha, beta )`][@stdlib/stats/base/dists/betaprime/mode]</span><span class="delimiter">: </span><span class="description">beta prime distribution mode.</span>
-   <span class="signature">[`skewness( alpha, beta )`][@stdlib/stats/base/dists/betaprime/skewness]</span><span class="delimiter">: </span><span class="description">beta prime distribution skewness.</span>
-   <span class="signature">[`stdev( alpha, beta )`][@stdlib/stats/base/dists/betaprime/stdev]</span><span class="delimiter">: </span><span class="description">beta prime distribution standard deviation.</span>
-   <span class="signature">[`variance( alpha, beta )`][@stdlib/stats/base/dists/betaprime/variance]</span><span class="delimiter">: </span><span class="description">beta prime distribution variance.</span>

</div>

<!-- </toc> -->

The namespace contains a constructor function for creating a [betaprime][betaprime-distribution] distribution object.

<!-- <toc pattern="*ctor*"> -->

<div class="namespace-toc">

-   <span class="signature">[`BetaPrime( [alpha, beta] )`][@stdlib/stats/base/dists/betaprime/ctor]</span><span class="delimiter">: </span><span class="description">beta prime distribution constructor.</span>

</div>

<!-- </toc> -->

```javascript
var BetaPrime = require( 'https://cdn.jsdelivr.net/gh/stdlib-js/stats-base-dists-betaprime' ).BetaPrime;

var dist = new BetaPrime( 2.0, 4.0 );

var mu = dist.mean;
// returns ~0.667
```

</section>

<!-- /.usage -->

<section class="examples">

## Examples

<!-- TODO: better examples -->

<!-- eslint no-undef: "error" -->

```javascript
import objectKeys from 'https://cdn.jsdelivr.net/gh/stdlib-js/utils-keys@deno/mod.js';
import betaprime from 'https://cdn.jsdelivr.net/gh/stdlib-js/stats-base-dists-betaprime@deno/mod.js';

console.log( objectKeys( betaprime ) );
```

</section>

<!-- /.examples -->

<!-- Section for related `stdlib` packages. Do not manually edit this section, as it is automatically populated. -->

<section class="related">

</section>

<!-- /.related -->

<!-- Section for all links. Make sure to keep an empty line after the `section` element and another before the `/section` close. -->


<section class="main-repo" >

* * *

## Notice

This package is part of [stdlib][stdlib], a standard library with an emphasis on numerical and scientific computing. The library provides a collection of robust, high performance libraries for mathematics, statistics, streams, utilities, and more.

For more information on the project, filing bug reports and feature requests, and guidance on how to develop [stdlib][stdlib], see the main project [repository][stdlib].

#### Community

[![Chat][chat-image]][chat-url]

---

## License

See [LICENSE][stdlib-license].


## Copyright

Copyright &copy; 2016-2022. The Stdlib [Authors][stdlib-authors].

</section>

<!-- /.stdlib -->

<!-- Section for all links. Make sure to keep an empty line after the `section` element and another before the `/section` close. -->

<section class="links">

[npm-image]: http://img.shields.io/npm/v/@stdlib/stats-base-dists-betaprime.svg
[npm-url]: https://npmjs.org/package/@stdlib/stats-base-dists-betaprime

[test-image]: https://github.com/stdlib-js/stats-base-dists-betaprime/actions/workflows/test.yml/badge.svg?branch=main
[test-url]: https://github.com/stdlib-js/stats-base-dists-betaprime/actions/workflows/test.yml?query=branch:main

[coverage-image]: https://img.shields.io/codecov/c/github/stdlib-js/stats-base-dists-betaprime/main.svg
[coverage-url]: https://codecov.io/github/stdlib-js/stats-base-dists-betaprime?branch=main

<!--

[dependencies-image]: https://img.shields.io/david/stdlib-js/stats-base-dists-betaprime.svg
[dependencies-url]: https://david-dm.org/stdlib-js/stats-base-dists-betaprime/main

-->

[chat-image]: https://img.shields.io/gitter/room/stdlib-js/stdlib.svg
[chat-url]: https://gitter.im/stdlib-js/stdlib/

[stdlib]: https://github.com/stdlib-js/stdlib

[stdlib-authors]: https://github.com/stdlib-js/stdlib/graphs/contributors

[umd]: https://github.com/umdjs/umd
[es-module]: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Modules

[deno-url]: https://github.com/stdlib-js/stats-base-dists-betaprime/tree/deno
[umd-url]: https://github.com/stdlib-js/stats-base-dists-betaprime/tree/umd
[esm-url]: https://github.com/stdlib-js/stats-base-dists-betaprime/tree/esm
[branches-url]: https://github.com/stdlib-js/stats-base-dists-betaprime/blob/main/branches.md

[stdlib-license]: https://raw.githubusercontent.com/stdlib-js/stats-base-dists-betaprime/main/LICENSE

[betaprime-distribution]: https://en.wikipedia.org/wiki/Beta_prime_distribution

<!-- <toc-links> -->

[@stdlib/stats/base/dists/betaprime/ctor]: https://github.com/stdlib-js/stats-base-dists-betaprime-ctor/tree/deno

[@stdlib/stats/base/dists/betaprime/kurtosis]: https://github.com/stdlib-js/stats-base-dists-betaprime-kurtosis/tree/deno

[@stdlib/stats/base/dists/betaprime/mean]: https://github.com/stdlib-js/stats-base-dists-betaprime-mean/tree/deno

[@stdlib/stats/base/dists/betaprime/mode]: https://github.com/stdlib-js/stats-base-dists-betaprime-mode/tree/deno

[@stdlib/stats/base/dists/betaprime/skewness]: https://github.com/stdlib-js/stats-base-dists-betaprime-skewness/tree/deno

[@stdlib/stats/base/dists/betaprime/stdev]: https://github.com/stdlib-js/stats-base-dists-betaprime-stdev/tree/deno

[@stdlib/stats/base/dists/betaprime/variance]: https://github.com/stdlib-js/stats-base-dists-betaprime-variance/tree/deno

[@stdlib/stats/base/dists/betaprime/cdf]: https://github.com/stdlib-js/stats-base-dists-betaprime-cdf/tree/deno

[@stdlib/stats/base/dists/betaprime/logcdf]: https://github.com/stdlib-js/stats-base-dists-betaprime-logcdf/tree/deno

[@stdlib/stats/base/dists/betaprime/logpdf]: https://github.com/stdlib-js/stats-base-dists-betaprime-logpdf/tree/deno

[@stdlib/stats/base/dists/betaprime/pdf]: https://github.com/stdlib-js/stats-base-dists-betaprime-pdf/tree/deno

[@stdlib/stats/base/dists/betaprime/quantile]: https://github.com/stdlib-js/stats-base-dists-betaprime-quantile/tree/deno

<!-- </toc-links> -->

</section>

<!-- /.links -->
