# WASI overview

![WASI](WASI.png)

Welcome to WASI!

For a quick intro to WASI, including getting started using it, see [the intro document](https://github.com/CraneStation/wasmtime/blob/master/docs/WASI-intro.md).

For more documentation, see [the documents guide](https://github.com/CraneStation/wasmtime/blob/master/docs/WASI-documents.md).

Here's a quick guide to the repositories where things live:

[wasi-sdk](https://github.com/CraneStation/wasi-sdk) - “WASI SDK” packages for C/C++. If you want to try out compiling C/C++, this is a good place to start. "It's just clang."

[WASI-enabled Rust](https://github.com/alexcrichton/rust/tree/wasi) - Rust toolchain with support for wasm32-unknown-wasi. Rust Nightly builds will have built-in WASI support starting in early April.
To get started using Rust for targeting WASI, see the [release page](https://github.com/alexcrichton/rust/releases/tag/wasi3).

[wasi-sysroot](https://github.com/CraneStation/wasi-sysroot/) - WASI libc sources.

[wasmtime](https://github.com/CraneStation/wasmtime/) - Wasmtime WebAssembly runtime, with WASI support, as well as the WASI documentation.

Everything here is a work in progress prototype, and not yet stable.
