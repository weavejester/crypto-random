# crypto-random

A small Clojure library for generating cryptographically secure random
bytes and strings.

## Installation

Add the following dependency to your `project.clj` file:

    [crypto-random "1.2.0"]

## Functions

### `(crypto.random/bytes size)`

Returns a random byte array of the specified size.

### `(crypto.random/base64 size)`

Return a random base64 string of the specified size in bytes.

### `(crypto.random/base32 size)`

Return a random base32 string of the specified size in bytes.

### `(crypto.random/hex size)`

Return a random hex string of the specified size in bytes.

### `(crypto.random/url-part size)`

Return a random string suitable for being inserted into URLs. The size
denotes the number of bytes to generate.

## License

Copyright © 2014 James Reeves

Distributed under the Eclipse Public License, the same as Clojure.
