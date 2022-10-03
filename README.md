## Run Length Encoding

Run length encoding (RLE) is a simple compression algorithm for lossless compression.


### Worked example

Given the image data representing Red (r), Green (g) and Blue (b) pixels

> rrrbbggggggbrrrrrr

Te sequences of repeated characters can be represented by a single character and a count so that this data becomes

> 3r2b6g1b5r

18 pieces of information has become 10. This is a compression ratio of 9:5, or 1.8.

### Compression ratio

The [compression ratio](https://en.wikipedia.org/wiki/Data_compression_ratio) of a compression algorithm is `uncompressed size / compressed size`

A higher compression ratio is better. values below 1 mean that the compression has made the data larger instead of smaller.
