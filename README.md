# Waves seed generator

This program will generate seeds for [Waves](https://github.com/wavesplatform/waves) which public key (address) is ends with what you want.

### usage

1. `cargo build --release`
2. `./target/release/waves-address-generator {thread_numbers} {word1} {word2}`

For example `./waves-address-generator 2 xxx yyy` will start generator with 2 threads. It will print only those seeds which address ends with "xxx" or "yyy".