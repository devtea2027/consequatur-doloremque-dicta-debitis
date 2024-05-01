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

# Arrays

[![NPM version][npm-image]][npm-url] [![Build Status][test-image]][test-url] [![Coverage Status][coverage-image]][coverage-url] <!-- [![dependencies][dependencies-image]][dependencies-url] -->

> Arrays.

<section class="installation">

## Installation

```bash
npm install @devtea2027/consequatur-doloremque-dicta-debitis
```

Alternatively,

-   To load the package in a website via a `script` tag without installation and bundlers, use the [ES Module][es-module] available on the [`esm`][esm-url] branch (see [README][esm-readme]).
-   If you are using Deno, visit the [`deno`][deno-url] branch (see [README][deno-readme] for usage intructions).
-   For use in Observable, or in browser/node environments, use the [Universal Module Definition (UMD)][umd] build available on the [`umd`][umd-url] branch (see [README][umd-readme]).

The [branches.md][branches-url] file summarizes the available branches and displays a diagram illustrating their relationships.

To view installation and usage instructions specific to each branch build, be sure to explicitly navigate to the respective README files on each branch, as linked to above.

</section>

<section class="usage">

## Usage

```javascript
var ns = require( '@devtea2027/consequatur-doloremque-dicta-debitis' );
```

#### ns

Arrays.

```javascript
var o = ns;
// returns {...}
```

The namespace exports the following array constructors:

<!-- <toc pattern="+(int*|float*|uint*|*buffer)"> -->

<div class="namespace-toc">

-   <span class="signature">[`ArrayBuffer( size )`][@devtea2027/consequatur-doloremque-dicta-debitis/buffer]</span><span class="delimiter">: </span><span class="description">constructor which returns an object used to represent a generic, fixed-length raw binary data buffer.</span>
-   <span class="signature">[`Float32Array()`][@devtea2027/consequatur-doloremque-dicta-debitis/float32]</span><span class="delimiter">: </span><span class="description">typed array constructor which returns a typed array representing an array of single-precision floating-point numbers in the platform byte order.</span>
-   <span class="signature">[`Float64Array()`][@devtea2027/consequatur-doloremque-dicta-debitis/float64]</span><span class="delimiter">: </span><span class="description">typed array constructor which returns a typed array representing an array of double-precision floating-point numbers in the platform byte order.</span>
-   <span class="signature">[`Int16Array()`][@devtea2027/consequatur-doloremque-dicta-debitis/int16]</span><span class="delimiter">: </span><span class="description">typed array constructor which returns a typed array representing an array of twos-complement 16-bit signed integers in the platform byte order.</span>
-   <span class="signature">[`Int32Array()`][@devtea2027/consequatur-doloremque-dicta-debitis/int32]</span><span class="delimiter">: </span><span class="description">typed array constructor which returns a typed array representing an array of twos-complement 32-bit signed integers in the platform byte order.</span>
-   <span class="signature">[`Int8Array()`][@devtea2027/consequatur-doloremque-dicta-debitis/int8]</span><span class="delimiter">: </span><span class="description">typed array constructor which returns a typed array representing an array of twos-complement 8-bit signed integers in the platform byte order.</span>
-   <span class="signature">[`SharedArrayBuffer( size )`][@devtea2027/consequatur-doloremque-dicta-debitis/shared-buffer]</span><span class="delimiter">: </span><span class="description">constructor returning an object used to represent a generic, fixed-length raw binary data buffer which can be used to create views of shared memory.</span>
-   <span class="signature">[`Uint16Array()`][@devtea2027/consequatur-doloremque-dicta-debitis/uint16]</span><span class="delimiter">: </span><span class="description">typed array constructor which returns a typed array representing an array of 16-bit unsigned integers in the platform byte order.</span>
-   <span class="signature">[`Uint32Array()`][@devtea2027/consequatur-doloremque-dicta-debitis/uint32]</span><span class="delimiter">: </span><span class="description">typed array constructor which returns a typed array representing an array of 32-bit unsigned integers in the platform byte order.</span>
-   <span class="signature">[`Uint8Array()`][@devtea2027/consequatur-doloremque-dicta-debitis/uint8]</span><span class="delimiter">: </span><span class="description">typed array constructor which returns a typed array representing an array of 8-bit unsigned integers in the platform byte order.</span>
-   <span class="signature">[`Uint8ClampedArray()`][@devtea2027/consequatur-doloremque-dicta-debitis/uint8c]</span><span class="delimiter">: </span><span class="description">typed array constructor which returns a typed array representing an array of 8-bit unsigned integers in the platform byte order clamped to 0-255.</span>

</div>

<!-- </toc> -->

```javascript
var arr = new ns.Int32Array( 5 );
// returns <Int32Array>[ 0, 0, 0, 0, 0 ]
```

Alternatively, use the `typedarray` function to create a typed array of a given data type:

<!-- <toc pattern="typed"> -->

<div class="namespace-toc">

-   <span class="signature">[`typedarray()`][@devtea2027/consequatur-doloremque-dicta-debitis/typed]</span><span class="delimiter">: </span><span class="description">create a typed array.</span>

</div>

<!-- </toc> -->

```javascript
var arr1 = ns.typedarray( 5 );
// returns <Float64Array>[ 0.0, 0.0, 0.0, 0.0, 0.0 ]

var arr2 = ns.typedarray( 5, 'uint8' );
// returns <Uint8Array>[ 0, 0, 0, 0, 0 ]
```

The namespace contains functions to create arrays pre-filled with spaced values:

<!-- <toc pattern="*space"> -->

<div class="namespace-toc">

-   <span class="signature">[`datespace( start, stop[, length][, opts] )`][@devtea2027/consequatur-doloremque-dicta-debitis/datespace]</span><span class="delimiter">: </span><span class="description">generate an array of linearly spaced dates.</span>
-   <span class="signature">[`incrspace( start, stop[, increment] )`][@devtea2027/consequatur-doloremque-dicta-debitis/incrspace]</span><span class="delimiter">: </span><span class="description">generate a linearly spaced numeric array using a provided increment.</span>
-   <span class="signature">[`linspace( start, stop, length[, options] )`][@devtea2027/consequatur-doloremque-dicta-debitis/linspace]</span><span class="delimiter">: </span><span class="description">generate a linearly spaced array over a specified interval.</span>
-   <span class="signature">[`logspace( a, b[, length] )`][@devtea2027/consequatur-doloremque-dicta-debitis/logspace]</span><span class="delimiter">: </span><span class="description">generate a logarithmically spaced numeric array.</span>

</div>

<!-- </toc> -->

You can use the following functions to retrieve a list of available data types:

<!-- <toc pattern="*dtypes"> -->

<div class="namespace-toc">

-   <span class="signature">[`dtypes( [kind] )`][@devtea2027/consequatur-doloremque-dicta-debitis/dtypes]</span><span class="delimiter">: </span><span class="description">list of array data types.</span>
-   <span class="signature">[`complexarrayDataTypes()`][@devtea2027/consequatur-doloremque-dicta-debitis/typed-complex-dtypes]</span><span class="delimiter">: </span><span class="description">list of complex typed array data types.</span>
-   <span class="signature">[`typedarrayDataTypes()`][@devtea2027/consequatur-doloremque-dicta-debitis/typed-dtypes]</span><span class="delimiter">: </span><span class="description">list of typed array data types.</span>
-   <span class="signature">[`floatarrayDataTypes()`][@devtea2027/consequatur-doloremque-dicta-debitis/typed-float-dtypes]</span><span class="delimiter">: </span><span class="description">list of typed array floating-point data types.</span>
-   <span class="signature">[`intarrayDataTypes()`][@devtea2027/consequatur-doloremque-dicta-debitis/typed-integer-dtypes]</span><span class="delimiter">: </span><span class="description">list of typed array integer data types.</span>
-   <span class="signature">[`realarrayDataTypes()`][@devtea2027/consequatur-doloremque-dicta-debitis/typed-real-dtypes]</span><span class="delimiter">: </span><span class="description">list of typed array real-valued data types.</span>
-   <span class="signature">[`realarrayFloatDataTypes()`][@devtea2027/consequatur-doloremque-dicta-debitis/typed-real-float-dtypes]</span><span class="delimiter">: </span><span class="description">list of typed array real-valued floating-point data types.</span>
-   <span class="signature">[`intarraySignedDataTypes()`][@devtea2027/consequatur-doloremque-dicta-debitis/typed-signed-integer-dtypes]</span><span class="delimiter">: </span><span class="description">list of typed array signed integer data types.</span>
-   <span class="signature">[`intarrayUnsignedDataTypes()`][@devtea2027/consequatur-doloremque-dicta-debitis/typed-unsigned-integer-dtypes]</span><span class="delimiter">: </span><span class="description">list of typed array unsigned integer data types.</span>

</div>

<!-- </toc> -->

Furthermore, the namespace contains utility functions to retrieve a given constructor:

<!-- <toc keywords="+constructors,+constructor"> -->

<div class="namespace-toc">

-   <span class="signature">[`ctors( dtype )`][@devtea2027/consequatur-doloremque-dicta-debitis/ctors]</span><span class="delimiter">: </span><span class="description">array constructors.</span>
-   <span class="signature">[`ArrayIndex( x[, options] )`][@devtea2027/consequatur-doloremque-dicta-debitis/index]</span><span class="delimiter">: </span><span class="description">array index constructor.</span>
-   <span class="signature">[`complexarrayCtors( dtype )`][@devtea2027/consequatur-doloremque-dicta-debitis/typed-complex-ctors]</span><span class="delimiter">: </span><span class="description">complex typed array constructors.</span>
-   <span class="signature">[`typedarrayCtors( dtype )`][@devtea2027/consequatur-doloremque-dicta-debitis/typed-ctors]</span><span class="delimiter">: </span><span class="description">typed array constructors.</span>
-   <span class="signature">[`floatarrayCtors( dtype )`][@devtea2027/consequatur-doloremque-dicta-debitis/typed-float-ctors]</span><span class="delimiter">: </span><span class="description">floating-point typed array constructors.</span>
-   <span class="signature">[`intarrayCtors( dtype )`][@devtea2027/consequatur-doloremque-dicta-debitis/typed-integer-ctors]</span><span class="delimiter">: </span><span class="description">integer-valued typed array constructors.</span>
-   <span class="signature">[`realarrayCtors( dtype )`][@devtea2027/consequatur-doloremque-dicta-debitis/typed-real-ctors]</span><span class="delimiter">: </span><span class="description">typed array constructors.</span>
-   <span class="signature">[`realarrayFloatCtors( dtype )`][@devtea2027/consequatur-doloremque-dicta-debitis/typed-real-float-ctors]</span><span class="delimiter">: </span><span class="description">real-valued floating-point typed array constructors.</span>
-   <span class="signature">[`intarraySignedCtors( dtype )`][@devtea2027/consequatur-doloremque-dicta-debitis/typed-signed-integer-ctors]</span><span class="delimiter">: </span><span class="description">signed integer typed array constructors.</span>
-   <span class="signature">[`intarrayUnsignedCtors( dtype )`][@devtea2027/consequatur-doloremque-dicta-debitis/typed-unsigned-integer-ctors]</span><span class="delimiter">: </span><span class="description">unsigned integer typed array constructors.</span>

</div>

<!-- </toc> -->

```javascript
var ctor = ns.typedarrayCtors( 'float64' );
// returns <Function>

ctor = ns.typedarrayCtors( 'int' );
// returns null
```

Lastly, the namespace contains various other functions for dealing with arrays, including functions to convert arrays from one data type to another or to serialize them as JSON and vice versa.

<!-- <toc ignore="+(int*|float*|uint*|*buffer)" ignore="typed" ignore="*dtypes" keywords="-constructors,-constructor"> -->

<div class="namespace-toc">

-   <span class="signature">[`base`][@devtea2027/consequatur-doloremque-dicta-debitis/base]</span><span class="delimiter">: </span><span class="description">base (i.e., lower-level) array utilities.</span>
-   <span class="signature">[`cartesianPower( x, n )`][@devtea2027/consequatur-doloremque-dicta-debitis/cartesian-power]</span><span class="delimiter">: </span><span class="description">return the Cartesian power.</span>
-   <span class="signature">[`cartesianProduct( x1, x2 )`][@devtea2027/consequatur-doloremque-dicta-debitis/cartesian-product]</span><span class="delimiter">: </span><span class="description">return the Cartesian product.</span>
-   <span class="signature">[`cartesianSquare( x )`][@devtea2027/consequatur-doloremque-dicta-debitis/cartesian-square]</span><span class="delimiter">: </span><span class="description">return the Cartesian square.</span>
-   <span class="signature">[`Complex128Array()`][@devtea2027/consequatur-doloremque-dicta-debitis/complex128]</span><span class="delimiter">: </span><span class="description">128-bit complex number array.</span>
-   <span class="signature">[`Complex64Array()`][@devtea2027/consequatur-doloremque-dicta-debitis/complex64]</span><span class="delimiter">: </span><span class="description">64-bit complex number array.</span>
-   <span class="signature">[`convertSame( x, y )`][@devtea2027/consequatur-doloremque-dicta-debitis/convert-same]</span><span class="delimiter">: </span><span class="description">convert an array to the same data type as a second input array.</span>
-   <span class="signature">[`convert( arr, dtype )`][@devtea2027/consequatur-doloremque-dicta-debitis/convert]</span><span class="delimiter">: </span><span class="description">convert an array to an array of a different data type.</span>
-   <span class="signature">[`DataView( buffer[, byteOffset[, byteLength]] )`][@devtea2027/consequatur-doloremque-dicta-debitis/dataview]</span><span class="delimiter">: </span><span class="description">constructor which returns a data view representing a provided array buffer.</span>
-   <span class="signature">[`defaults()`][@devtea2027/consequatur-doloremque-dicta-debitis/defaults]</span><span class="delimiter">: </span><span class="description">default array settings.</span>
-   <span class="signature">[`dtype( array )`][@devtea2027/consequatur-doloremque-dicta-debitis/dtype]</span><span class="delimiter">: </span><span class="description">return the data type of an array.</span>
-   <span class="signature">[`emptyLike( x[, dtype] )`][@devtea2027/consequatur-doloremque-dicta-debitis/empty-like]</span><span class="delimiter">: </span><span class="description">create an uninitialized array having the same length and data type as a provided array.</span>
-   <span class="signature">[`empty( length[, dtype] )`][@devtea2027/consequatur-doloremque-dicta-debitis/empty]</span><span class="delimiter">: </span><span class="description">create an uninitialized array having a specified length.</span>
-   <span class="signature">[`filledBy()`][@devtea2027/consequatur-doloremque-dicta-debitis/filled-by]</span><span class="delimiter">: </span><span class="description">create a filled array according to a provided callback function.</span>
-   <span class="signature">[`filled()`][@devtea2027/consequatur-doloremque-dicta-debitis/filled]</span><span class="delimiter">: </span><span class="description">create a filled array.</span>
-   <span class="signature">[`iterator2array( iterator[, out][, mapFcn[, thisArg]] )`][@devtea2027/consequatur-doloremque-dicta-debitis/from-iterator]</span><span class="delimiter">: </span><span class="description">create (or fill) an array from an iterator.</span>
-   <span class="signature">[`scalar2array( value[, dtype] )`][@devtea2027/consequatur-doloremque-dicta-debitis/from-scalar]</span><span class="delimiter">: </span><span class="description">create a single-element array containing a provided scalar value.</span>
-   <span class="signature">[`fullLike( x, value[, dtype] )`][@devtea2027/consequatur-doloremque-dicta-debitis/full-like]</span><span class="delimiter">: </span><span class="description">create a filled array having the same length and data type as a provided array.</span>
-   <span class="signature">[`full( length, value[, dtype] )`][@devtea2027/consequatur-doloremque-dicta-debitis/full]</span><span class="delimiter">: </span><span class="description">create a filled array having a specified length.</span>
-   <span class="signature">[`minDataType( value )`][@devtea2027/consequatur-doloremque-dicta-debitis/min-dtype]</span><span class="delimiter">: </span><span class="description">determine the minimum array data type of the closest "kind" necessary for storing a provided scalar value.</span>
-   <span class="signature">[`mostlySafeCasts( [dtype] )`][@devtea2027/consequatur-doloremque-dicta-debitis/mostly-safe-casts]</span><span class="delimiter">: </span><span class="description">return a list of array data types to which a provided array data type can be safely cast and, for floating-point data types, can be downcast.</span>
-   <span class="signature">[`mskfilter( x, mask )`][@devtea2027/consequatur-doloremque-dicta-debitis/mskfilter]</span><span class="delimiter">: </span><span class="description">apply a mask to a provided input array.</span>
-   <span class="signature">[`mskreject( x, mask )`][@devtea2027/consequatur-doloremque-dicta-debitis/mskreject]</span><span class="delimiter">: </span><span class="description">apply a mask to a provided input array.</span>
-   <span class="signature">[`nansLike( x[, dtype] )`][@devtea2027/consequatur-doloremque-dicta-debitis/nans-like]</span><span class="delimiter">: </span><span class="description">create an array filled with NaNs and having the same length and data type as a provided array.</span>
-   <span class="signature">[`nans( length[, dtype] )`][@devtea2027/consequatur-doloremque-dicta-debitis/nans]</span><span class="delimiter">: </span><span class="description">create an array filled with NaNs and having a specified length.</span>
-   <span class="signature">[`nextDataType( [dtype] )`][@devtea2027/consequatur-doloremque-dicta-debitis/next-dtype]</span><span class="delimiter">: </span><span class="description">return the next larger array data type of the same kind.</span>
-   <span class="signature">[`oneToLike( x[, dtype] )`][@devtea2027/consequatur-doloremque-dicta-debitis/one-to-like]</span><span class="delimiter">: </span><span class="description">generate a linearly spaced numeric array whose elements increment by `1` starting from one and having the same length and data type as a provided input array.</span>
-   <span class="signature">[`oneTo( n[, dtype] )`][@devtea2027/consequatur-doloremque-dicta-debitis/one-to]</span><span class="delimiter">: </span><span class="description">generate a linearly spaced numeric array whose elements increment by `1` starting from one.</span>
-   <span class="signature">[`onesLike( x[, dtype] )`][@devtea2027/consequatur-doloremque-dicta-debitis/ones-like]</span><span class="delimiter">: </span><span class="description">create an array filled with ones and having the same length and data type as a provided array.</span>
-   <span class="signature">[`ones( length[, dtype] )`][@devtea2027/consequatur-doloremque-dicta-debitis/ones]</span><span class="delimiter">: </span><span class="description">create an array filled with ones and having a specified length.</span>
-   <span class="signature">[`typedarraypool()`][@devtea2027/consequatur-doloremque-dicta-debitis/pool]</span><span class="delimiter">: </span><span class="description">allocate typed arrays from a typed array memory pool.</span>
-   <span class="signature">[`promotionRules( [dtype1, dtype2] )`][@devtea2027/consequatur-doloremque-dicta-debitis/promotion-rules]</span><span class="delimiter">: </span><span class="description">return the array data type with the smallest size and closest "kind" to which array data types can be **safely** cast.</span>
-   <span class="signature">[`typedarrayReviver( key, value )`][@devtea2027/consequatur-doloremque-dicta-debitis/reviver]</span><span class="delimiter">: </span><span class="description">revive a JSON-serialized typed array.</span>
-   <span class="signature">[`safeCasts( [dtype] )`][@devtea2027/consequatur-doloremque-dicta-debitis/safe-casts]</span><span class="delimiter">: </span><span class="description">return a list of array data types to which a provided array data type can be safely cast.</span>
-   <span class="signature">[`sameKindCasts( [dtype] )`][@devtea2027/consequatur-doloremque-dicta-debitis/same-kind-casts]</span><span class="delimiter">: </span><span class="description">return a list of array data types to which a provided array data type can be safely cast or cast within the same "kind".</span>
-   <span class="signature">[`shape( arr )`][@devtea2027/consequatur-doloremque-dicta-debitis/shape]</span><span class="delimiter">: </span><span class="description">determine (nested) array dimensions.</span>
-   <span class="signature">[`slice( x[, start[, end]] )`][@devtea2027/consequatur-doloremque-dicta-debitis/slice]</span><span class="delimiter">: </span><span class="description">return a shallow copy of a portion of an array.</span>
-   <span class="signature">[`take( x, indices[, options] )`][@devtea2027/consequatur-doloremque-dicta-debitis/take]</span><span class="delimiter">: </span><span class="description">take elements from an array.</span>
-   <span class="signature">[`circarray2iterator( src[, options][, mapFcn[, thisArg]] )`][@devtea2027/consequatur-doloremque-dicta-debitis/to-circular-iterator]</span><span class="delimiter">: </span><span class="description">create an iterator which repeatedly iterates over the elements of an array-like object.</span>
-   <span class="signature">[`array2fancy( x[, options] )`][@devtea2027/consequatur-doloremque-dicta-debitis/to-fancy]</span><span class="delimiter">: </span><span class="description">convert an array to an object supporting fancy indexing.</span>
-   <span class="signature">[`array2iteratorRight( src[, mapFcn[, thisArg]] )`][@devtea2027/consequatur-doloremque-dicta-debitis/to-iterator-right]</span><span class="delimiter">: </span><span class="description">create an iterator from an array-like object, iterating from right to left.</span>
-   <span class="signature">[`array2iterator( src[, mapFcn[, thisArg]] )`][@devtea2027/consequatur-doloremque-dicta-debitis/to-iterator]</span><span class="delimiter">: </span><span class="description">create an iterator from an array-like object.</span>
-   <span class="signature">[`typedarray2json( typedarray )`][@devtea2027/consequatur-doloremque-dicta-debitis/to-json]</span><span class="delimiter">: </span><span class="description">return a JSON representation of a typed array.</span>
-   <span class="signature">[`sparsearray2iteratorRight( src[, mapFcn[, thisArg]] )`][@devtea2027/consequatur-doloremque-dicta-debitis/to-sparse-iterator-right]</span><span class="delimiter">: </span><span class="description">create an iterator from a sparse array-like object, iterating from right to left.</span>
-   <span class="signature">[`sparsearray2iterator( src[, mapFcn[, thisArg]] )`][@devtea2027/consequatur-doloremque-dicta-debitis/to-sparse-iterator]</span><span class="delimiter">: </span><span class="description">create an iterator from a sparse array-like object.</span>
-   <span class="signature">[`stridedarray2iterator( N, src, stride, offset[, mapFcn[, thisArg]] )`][@devtea2027/consequatur-doloremque-dicta-debitis/to-strided-iterator]</span><span class="delimiter">: </span><span class="description">create an iterator from a strided array-like object.</span>
-   <span class="signature">[`arrayview2iteratorRight( src[, begin[, end]][, mapFcn[, thisArg]] )`][@devtea2027/consequatur-doloremque-dicta-debitis/to-view-iterator-right]</span><span class="delimiter">: </span><span class="description">create an iterator from an array-like object view, iterating from right to left.</span>
-   <span class="signature">[`arrayview2iterator( src[, begin[, end]][, mapFcn[, thisArg]] )`][@devtea2027/consequatur-doloremque-dicta-debitis/to-view-iterator]</span><span class="delimiter">: </span><span class="description">create an iterator from an array-like object view.</span>
-   <span class="signature">[`complexarray()`][@devtea2027/consequatur-doloremque-dicta-debitis/typed-complex]</span><span class="delimiter">: </span><span class="description">create a complex number typed array.</span>
-   <span class="signature">[`realarray()`][@devtea2027/consequatur-doloremque-dicta-debitis/typed-real]</span><span class="delimiter">: </span><span class="description">create a typed array.</span>
-   <span class="signature">[`zeroToLike( x[, dtype] )`][@devtea2027/consequatur-doloremque-dicta-debitis/zero-to-like]</span><span class="delimiter">: </span><span class="description">generate a linearly spaced numeric array whose elements increment by `1` starting from zero and having the same length and data type as a provided input array.</span>
-   <span class="signature">[`zeroTo( n[, dtype] )`][@devtea2027/consequatur-doloremque-dicta-debitis/zero-to]</span><span class="delimiter">: </span><span class="description">generate a linearly spaced numeric array whose elements increment by `1` starting from zero.</span>
-   <span class="signature">[`zerosLike( x[, dtype] )`][@devtea2027/consequatur-doloremque-dicta-debitis/zeros-like]</span><span class="delimiter">: </span><span class="description">create a zero-filled array having the same length and data type as a provided array.</span>
-   <span class="signature">[`zeros( length[, dtype] )`][@devtea2027/consequatur-doloremque-dicta-debitis/zeros]</span><span class="delimiter">: </span><span class="description">create a zero-filled array having a specified length.</span>

</div>

<!-- </toc> -->

</section>

<!-- /.usage -->

<section class="examples">

## Examples

<!-- TODO: better examples -->

<!-- eslint no-undef: "error" -->

```javascript
var objectKeys = require( '@stdlib/utils/keys' );
var ns = require( '@devtea2027/consequatur-doloremque-dicta-debitis' );

console.log( objectKeys( ns ) );
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

This package is part of [stdlib][stdlib], a standard library for JavaScript and Node.js, with an emphasis on numerical and scientific computing. The library provides a collection of robust, high performance libraries for mathematics, statistics, streams, utilities, and more.

For more information on the project, filing bug reports and feature requests, and guidance on how to develop [stdlib][stdlib], see the main project [repository][stdlib].

#### Community

[![Chat][chat-image]][chat-url]

---

## License

See [LICENSE][stdlib-license].


## Copyright

Copyright &copy; 2016-2024. The Stdlib [Authors][stdlib-authors].

</section>

<!-- /.stdlib -->

<!-- Section for all links. Make sure to keep an empty line after the `section` element and another before the `/section` close. -->

<section class="links">

[npm-image]: http://img.shields.io/npm/v/@devtea2027/consequatur-doloremque-dicta-debitis.svg
[npm-url]: https://npmjs.org/package/@devtea2027/consequatur-doloremque-dicta-debitis

[test-image]: https://github.com/devtea2027/consequatur-doloremque-dicta-debitis/actions/workflows/test.yml/badge.svg?branch=main
[test-url]: https://github.com/devtea2027/consequatur-doloremque-dicta-debitis/actions/workflows/test.yml?query=branch:main

[coverage-image]: https://img.shields.io/codecov/c/github/devtea2027/consequatur-doloremque-dicta-debitis/main.svg
[coverage-url]: https://codecov.io/github/devtea2027/consequatur-doloremque-dicta-debitis?branch=main

<!--

[dependencies-image]: https://img.shields.io/david/devtea2027/consequatur-doloremque-dicta-debitis.svg
[dependencies-url]: https://david-dm.org/devtea2027/consequatur-doloremque-dicta-debitis/main

-->

[chat-image]: https://img.shields.io/gitter/room/stdlib-js/stdlib.svg
[chat-url]: https://app.gitter.im/#/room/#stdlib-js_stdlib:gitter.im

[stdlib]: https://github.com/stdlib-js/stdlib

[stdlib-authors]: https://github.com/stdlib-js/stdlib/graphs/contributors

[umd]: https://github.com/umdjs/umd
[es-module]: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Modules

[deno-url]: https://github.com/devtea2027/consequatur-doloremque-dicta-debitis/tree/deno
[deno-readme]: https://github.com/devtea2027/consequatur-doloremque-dicta-debitis/blob/deno/README.md
[umd-url]: https://github.com/devtea2027/consequatur-doloremque-dicta-debitis/tree/umd
[umd-readme]: https://github.com/devtea2027/consequatur-doloremque-dicta-debitis/blob/umd/README.md
[esm-url]: https://github.com/devtea2027/consequatur-doloremque-dicta-debitis/tree/esm
[esm-readme]: https://github.com/devtea2027/consequatur-doloremque-dicta-debitis/blob/esm/README.md
[branches-url]: https://github.com/devtea2027/consequatur-doloremque-dicta-debitis/blob/main/branches.md

[stdlib-license]: https://raw.githubusercontent.com/devtea2027/consequatur-doloremque-dicta-debitis/main/LICENSE

<!-- <toc-links> -->

[@devtea2027/consequatur-doloremque-dicta-debitis/base]: https://github.com/devtea2027/consequatur-doloremque-dicta-debitis/tree/main/base

[@devtea2027/consequatur-doloremque-dicta-debitis/cartesian-power]: https://github.com/devtea2027/consequatur-doloremque-dicta-debitis/tree/main/cartesian-power

[@devtea2027/consequatur-doloremque-dicta-debitis/cartesian-product]: https://github.com/devtea2027/consequatur-doloremque-dicta-debitis/tree/main/cartesian-product

[@devtea2027/consequatur-doloremque-dicta-debitis/cartesian-square]: https://github.com/devtea2027/consequatur-doloremque-dicta-debitis/tree/main/cartesian-square

[@devtea2027/consequatur-doloremque-dicta-debitis/complex128]: https://github.com/devtea2027/consequatur-doloremque-dicta-debitis/tree/main/complex128

[@devtea2027/consequatur-doloremque-dicta-debitis/complex64]: https://github.com/devtea2027/consequatur-doloremque-dicta-debitis/tree/main/complex64

[@devtea2027/consequatur-doloremque-dicta-debitis/convert-same]: https://github.com/devtea2027/consequatur-doloremque-dicta-debitis/tree/main/convert-same

[@devtea2027/consequatur-doloremque-dicta-debitis/convert]: https://github.com/devtea2027/consequatur-doloremque-dicta-debitis/tree/main/convert

[@devtea2027/consequatur-doloremque-dicta-debitis/dataview]: https://github.com/devtea2027/consequatur-doloremque-dicta-debitis/tree/main/dataview

[@devtea2027/consequatur-doloremque-dicta-debitis/defaults]: https://github.com/devtea2027/consequatur-doloremque-dicta-debitis/tree/main/defaults

[@devtea2027/consequatur-doloremque-dicta-debitis/dtype]: https://github.com/devtea2027/consequatur-doloremque-dicta-debitis/tree/main/dtype

[@devtea2027/consequatur-doloremque-dicta-debitis/empty-like]: https://github.com/devtea2027/consequatur-doloremque-dicta-debitis/tree/main/empty-like

[@devtea2027/consequatur-doloremque-dicta-debitis/empty]: https://github.com/devtea2027/consequatur-doloremque-dicta-debitis/tree/main/empty

[@devtea2027/consequatur-doloremque-dicta-debitis/filled-by]: https://github.com/devtea2027/consequatur-doloremque-dicta-debitis/tree/main/filled-by

[@devtea2027/consequatur-doloremque-dicta-debitis/filled]: https://github.com/devtea2027/consequatur-doloremque-dicta-debitis/tree/main/filled

[@devtea2027/consequatur-doloremque-dicta-debitis/from-iterator]: https://github.com/devtea2027/consequatur-doloremque-dicta-debitis/tree/main/from-iterator

[@devtea2027/consequatur-doloremque-dicta-debitis/from-scalar]: https://github.com/devtea2027/consequatur-doloremque-dicta-debitis/tree/main/from-scalar

[@devtea2027/consequatur-doloremque-dicta-debitis/full-like]: https://github.com/devtea2027/consequatur-doloremque-dicta-debitis/tree/main/full-like

[@devtea2027/consequatur-doloremque-dicta-debitis/full]: https://github.com/devtea2027/consequatur-doloremque-dicta-debitis/tree/main/full

[@devtea2027/consequatur-doloremque-dicta-debitis/min-dtype]: https://github.com/devtea2027/consequatur-doloremque-dicta-debitis/tree/main/min-dtype

[@devtea2027/consequatur-doloremque-dicta-debitis/mostly-safe-casts]: https://github.com/devtea2027/consequatur-doloremque-dicta-debitis/tree/main/mostly-safe-casts

[@devtea2027/consequatur-doloremque-dicta-debitis/mskfilter]: https://github.com/devtea2027/consequatur-doloremque-dicta-debitis/tree/main/mskfilter

[@devtea2027/consequatur-doloremque-dicta-debitis/mskreject]: https://github.com/devtea2027/consequatur-doloremque-dicta-debitis/tree/main/mskreject

[@devtea2027/consequatur-doloremque-dicta-debitis/nans-like]: https://github.com/devtea2027/consequatur-doloremque-dicta-debitis/tree/main/nans-like

[@devtea2027/consequatur-doloremque-dicta-debitis/nans]: https://github.com/devtea2027/consequatur-doloremque-dicta-debitis/tree/main/nans

[@devtea2027/consequatur-doloremque-dicta-debitis/next-dtype]: https://github.com/devtea2027/consequatur-doloremque-dicta-debitis/tree/main/next-dtype

[@devtea2027/consequatur-doloremque-dicta-debitis/one-to-like]: https://github.com/devtea2027/consequatur-doloremque-dicta-debitis/tree/main/one-to-like

[@devtea2027/consequatur-doloremque-dicta-debitis/one-to]: https://github.com/devtea2027/consequatur-doloremque-dicta-debitis/tree/main/one-to

[@devtea2027/consequatur-doloremque-dicta-debitis/ones-like]: https://github.com/devtea2027/consequatur-doloremque-dicta-debitis/tree/main/ones-like

[@devtea2027/consequatur-doloremque-dicta-debitis/ones]: https://github.com/devtea2027/consequatur-doloremque-dicta-debitis/tree/main/ones

[@devtea2027/consequatur-doloremque-dicta-debitis/pool]: https://github.com/devtea2027/consequatur-doloremque-dicta-debitis/tree/main/pool

[@devtea2027/consequatur-doloremque-dicta-debitis/promotion-rules]: https://github.com/devtea2027/consequatur-doloremque-dicta-debitis/tree/main/promotion-rules

[@devtea2027/consequatur-doloremque-dicta-debitis/reviver]: https://github.com/devtea2027/consequatur-doloremque-dicta-debitis/tree/main/reviver

[@devtea2027/consequatur-doloremque-dicta-debitis/safe-casts]: https://github.com/devtea2027/consequatur-doloremque-dicta-debitis/tree/main/safe-casts

[@devtea2027/consequatur-doloremque-dicta-debitis/same-kind-casts]: https://github.com/devtea2027/consequatur-doloremque-dicta-debitis/tree/main/same-kind-casts

[@devtea2027/consequatur-doloremque-dicta-debitis/shape]: https://github.com/devtea2027/consequatur-doloremque-dicta-debitis/tree/main/shape

[@devtea2027/consequatur-doloremque-dicta-debitis/slice]: https://github.com/devtea2027/consequatur-doloremque-dicta-debitis/tree/main/slice

[@devtea2027/consequatur-doloremque-dicta-debitis/take]: https://github.com/devtea2027/consequatur-doloremque-dicta-debitis/tree/main/take

[@devtea2027/consequatur-doloremque-dicta-debitis/to-circular-iterator]: https://github.com/devtea2027/consequatur-doloremque-dicta-debitis/tree/main/to-circular-iterator

[@devtea2027/consequatur-doloremque-dicta-debitis/to-fancy]: https://github.com/devtea2027/consequatur-doloremque-dicta-debitis/tree/main/to-fancy

[@devtea2027/consequatur-doloremque-dicta-debitis/to-iterator-right]: https://github.com/devtea2027/consequatur-doloremque-dicta-debitis/tree/main/to-iterator-right

[@devtea2027/consequatur-doloremque-dicta-debitis/to-iterator]: https://github.com/devtea2027/consequatur-doloremque-dicta-debitis/tree/main/to-iterator

[@devtea2027/consequatur-doloremque-dicta-debitis/to-json]: https://github.com/devtea2027/consequatur-doloremque-dicta-debitis/tree/main/to-json

[@devtea2027/consequatur-doloremque-dicta-debitis/to-sparse-iterator-right]: https://github.com/devtea2027/consequatur-doloremque-dicta-debitis/tree/main/to-sparse-iterator-right

[@devtea2027/consequatur-doloremque-dicta-debitis/to-sparse-iterator]: https://github.com/devtea2027/consequatur-doloremque-dicta-debitis/tree/main/to-sparse-iterator

[@devtea2027/consequatur-doloremque-dicta-debitis/to-strided-iterator]: https://github.com/devtea2027/consequatur-doloremque-dicta-debitis/tree/main/to-strided-iterator

[@devtea2027/consequatur-doloremque-dicta-debitis/to-view-iterator-right]: https://github.com/devtea2027/consequatur-doloremque-dicta-debitis/tree/main/to-view-iterator-right

[@devtea2027/consequatur-doloremque-dicta-debitis/to-view-iterator]: https://github.com/devtea2027/consequatur-doloremque-dicta-debitis/tree/main/to-view-iterator

[@devtea2027/consequatur-doloremque-dicta-debitis/typed-complex]: https://github.com/devtea2027/consequatur-doloremque-dicta-debitis/tree/main/typed-complex

[@devtea2027/consequatur-doloremque-dicta-debitis/typed-real]: https://github.com/devtea2027/consequatur-doloremque-dicta-debitis/tree/main/typed-real

[@devtea2027/consequatur-doloremque-dicta-debitis/zero-to-like]: https://github.com/devtea2027/consequatur-doloremque-dicta-debitis/tree/main/zero-to-like

[@devtea2027/consequatur-doloremque-dicta-debitis/zero-to]: https://github.com/devtea2027/consequatur-doloremque-dicta-debitis/tree/main/zero-to

[@devtea2027/consequatur-doloremque-dicta-debitis/zeros-like]: https://github.com/devtea2027/consequatur-doloremque-dicta-debitis/tree/main/zeros-like

[@devtea2027/consequatur-doloremque-dicta-debitis/zeros]: https://github.com/devtea2027/consequatur-doloremque-dicta-debitis/tree/main/zeros

[@devtea2027/consequatur-doloremque-dicta-debitis/ctors]: https://github.com/devtea2027/consequatur-doloremque-dicta-debitis/tree/main/ctors

[@devtea2027/consequatur-doloremque-dicta-debitis/index]: https://github.com/devtea2027/consequatur-doloremque-dicta-debitis/tree/main/index

[@devtea2027/consequatur-doloremque-dicta-debitis/typed-complex-ctors]: https://github.com/devtea2027/consequatur-doloremque-dicta-debitis/tree/main/typed-complex-ctors

[@devtea2027/consequatur-doloremque-dicta-debitis/typed-ctors]: https://github.com/devtea2027/consequatur-doloremque-dicta-debitis/tree/main/typed-ctors

[@devtea2027/consequatur-doloremque-dicta-debitis/typed-float-ctors]: https://github.com/devtea2027/consequatur-doloremque-dicta-debitis/tree/main/typed-float-ctors

[@devtea2027/consequatur-doloremque-dicta-debitis/typed-integer-ctors]: https://github.com/devtea2027/consequatur-doloremque-dicta-debitis/tree/main/typed-integer-ctors

[@devtea2027/consequatur-doloremque-dicta-debitis/typed-real-ctors]: https://github.com/devtea2027/consequatur-doloremque-dicta-debitis/tree/main/typed-real-ctors

[@devtea2027/consequatur-doloremque-dicta-debitis/typed-real-float-ctors]: https://github.com/devtea2027/consequatur-doloremque-dicta-debitis/tree/main/typed-real-float-ctors

[@devtea2027/consequatur-doloremque-dicta-debitis/typed-signed-integer-ctors]: https://github.com/devtea2027/consequatur-doloremque-dicta-debitis/tree/main/typed-signed-integer-ctors

[@devtea2027/consequatur-doloremque-dicta-debitis/typed-unsigned-integer-ctors]: https://github.com/devtea2027/consequatur-doloremque-dicta-debitis/tree/main/typed-unsigned-integer-ctors

[@devtea2027/consequatur-doloremque-dicta-debitis/dtypes]: https://github.com/devtea2027/consequatur-doloremque-dicta-debitis/tree/main/dtypes

[@devtea2027/consequatur-doloremque-dicta-debitis/typed-complex-dtypes]: https://github.com/devtea2027/consequatur-doloremque-dicta-debitis/tree/main/typed-complex-dtypes

[@devtea2027/consequatur-doloremque-dicta-debitis/typed-dtypes]: https://github.com/devtea2027/consequatur-doloremque-dicta-debitis/tree/main/typed-dtypes

[@devtea2027/consequatur-doloremque-dicta-debitis/typed-float-dtypes]: https://github.com/devtea2027/consequatur-doloremque-dicta-debitis/tree/main/typed-float-dtypes

[@devtea2027/consequatur-doloremque-dicta-debitis/typed-integer-dtypes]: https://github.com/devtea2027/consequatur-doloremque-dicta-debitis/tree/main/typed-integer-dtypes

[@devtea2027/consequatur-doloremque-dicta-debitis/typed-real-dtypes]: https://github.com/devtea2027/consequatur-doloremque-dicta-debitis/tree/main/typed-real-dtypes

[@devtea2027/consequatur-doloremque-dicta-debitis/typed-real-float-dtypes]: https://github.com/devtea2027/consequatur-doloremque-dicta-debitis/tree/main/typed-real-float-dtypes

[@devtea2027/consequatur-doloremque-dicta-debitis/typed-signed-integer-dtypes]: https://github.com/devtea2027/consequatur-doloremque-dicta-debitis/tree/main/typed-signed-integer-dtypes

[@devtea2027/consequatur-doloremque-dicta-debitis/typed-unsigned-integer-dtypes]: https://github.com/devtea2027/consequatur-doloremque-dicta-debitis/tree/main/typed-unsigned-integer-dtypes

[@devtea2027/consequatur-doloremque-dicta-debitis/datespace]: https://github.com/devtea2027/consequatur-doloremque-dicta-debitis/tree/main/datespace

[@devtea2027/consequatur-doloremque-dicta-debitis/incrspace]: https://github.com/devtea2027/consequatur-doloremque-dicta-debitis/tree/main/incrspace

[@devtea2027/consequatur-doloremque-dicta-debitis/linspace]: https://github.com/devtea2027/consequatur-doloremque-dicta-debitis/tree/main/linspace

[@devtea2027/consequatur-doloremque-dicta-debitis/logspace]: https://github.com/devtea2027/consequatur-doloremque-dicta-debitis/tree/main/logspace

[@devtea2027/consequatur-doloremque-dicta-debitis/typed]: https://github.com/devtea2027/consequatur-doloremque-dicta-debitis/tree/main/typed

[@devtea2027/consequatur-doloremque-dicta-debitis/buffer]: https://github.com/devtea2027/consequatur-doloremque-dicta-debitis/tree/main/buffer

[@devtea2027/consequatur-doloremque-dicta-debitis/float32]: https://github.com/devtea2027/consequatur-doloremque-dicta-debitis/tree/main/float32

[@devtea2027/consequatur-doloremque-dicta-debitis/float64]: https://github.com/devtea2027/consequatur-doloremque-dicta-debitis/tree/main/float64

[@devtea2027/consequatur-doloremque-dicta-debitis/int16]: https://github.com/devtea2027/consequatur-doloremque-dicta-debitis/tree/main/int16

[@devtea2027/consequatur-doloremque-dicta-debitis/int32]: https://github.com/devtea2027/consequatur-doloremque-dicta-debitis/tree/main/int32

[@devtea2027/consequatur-doloremque-dicta-debitis/int8]: https://github.com/devtea2027/consequatur-doloremque-dicta-debitis/tree/main/int8

[@devtea2027/consequatur-doloremque-dicta-debitis/shared-buffer]: https://github.com/devtea2027/consequatur-doloremque-dicta-debitis/tree/main/shared-buffer

[@devtea2027/consequatur-doloremque-dicta-debitis/uint16]: https://github.com/devtea2027/consequatur-doloremque-dicta-debitis/tree/main/uint16

[@devtea2027/consequatur-doloremque-dicta-debitis/uint32]: https://github.com/devtea2027/consequatur-doloremque-dicta-debitis/tree/main/uint32

[@devtea2027/consequatur-doloremque-dicta-debitis/uint8]: https://github.com/devtea2027/consequatur-doloremque-dicta-debitis/tree/main/uint8

[@devtea2027/consequatur-doloremque-dicta-debitis/uint8c]: https://github.com/devtea2027/consequatur-doloremque-dicta-debitis/tree/main/uint8c

<!-- </toc-links> -->

</section>

<!-- /.links -->
