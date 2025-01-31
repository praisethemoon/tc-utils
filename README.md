TC-Toolkit
===

A Type-C utility library, heavily inspired by [es-toolkit](https://github.com/toss/es-toolkit).

```tc
let arr = new Array<f32>([0.0f, 1.0f, 2.0f, 3.0f, 4.0f])
let arr2 = tctoolkit.at(arr, [1, 1, 2, 0, 4])
// [1.0f, 1.0f, 2.0f, 0.0f, 4.0f]

let value = new Array<u32>([1, 2, 3, 4, 5, 6, 7, 8, 9, 10])
let value2 = tctoolkit.chunk(value, 3)
// [[1, 2, 3], [4, 5, 6], [7, 8, 9], [10]]
```