# [WIP] halo2 ZK-WASM

## Description

This is a WIP (Work-In-Progress) repository. It is a modified version of the original **halo2** ZK-based Proving system in order to be compiled to WASM (WebAssembly).

### Changelog (Wed 31st May 2022)

* updated older dependencies to newer versions
* added **wasm-bindgen** dependency
* updated the **crate-type** to **lib**
* added the **build-wasm.sh** script

# halo2 [![Crates.io](https://img.shields.io/crates/v/halo2.svg)](https://crates.io/crates/halo2) #

## [Documentation](https://docs.rs/halo2)

## Minimum Supported Rust Version

Requires Rust **1.56.1** or higher.

Minimum supported Rust version can be changed in the future, but it will be done with a
minor version bump.

## Controlling parallelism

`halo2` currently uses [rayon](https://github.com/rayon-rs/rayon) for parallel computation.
The `RAYON_NUM_THREADS` environment variable can be used to set the number of threads.

## License

Licensed under either of

 * Apache License, Version 2.0, ([LICENSE-APACHE](LICENSE-APACHE) or
   http://www.apache.org/licenses/LICENSE-2.0)
 * MIT license ([LICENSE-MIT](LICENSE-MIT) or http://opensource.org/licenses/MIT)

at your option.

### Contribution

Unless you explicitly state otherwise, any contribution intentionally
submitted for inclusion in the work by you, as defined in the Apache-2.0
license, shall be dual licensed as above, without any additional terms or
conditions.
