# WASI overview

![WASI](WASI.png)

**Warning: this repo is now deprecated and read-only.**
**The contents of this repo has now been moved into [wasi.dev] crate.**
**If you have an issue, you'd like to raise, please submit it there.**

[wasi.dev]: https://github.com/CraneStation/wasi.dev

Welcome to WASI!

For a quick intro to WASI, including getting started using it, see [the intro document](https://github.com/CraneStation/wasmtime/blob/master/docs/WASI-intro.md).

For more documentation, see [the documents guide](https://github.com/CraneStation/wasmtime/blob/master/docs/WASI-documents.md).

Here's a quick guide to the repositories where things live:

[wasi-sdk](https://github.com/CraneStation/wasi-sdk) - “WASI SDK” packages for C/C++. If you want to try out compiling C/C++, this is a good place to start. "It's just clang."

WASI-enabled Rust - Rust stable (since 1.36) has built-in WASI support. To get started using Rust for targeting WASI:

```
rustup target add wasm32-wasi
cargo build --target wasm32-wasi
```

[wasi-libc](https://github.com/CraneStation/wasi-libc/) - WASI libc sources.

[wasmtime](https://github.com/CraneStation/wasmtime/) - Wasmtime WebAssembly runtime, with WASI support, as well as the WASI documentation.

[Lucet](https://github.com/fastly/lucet/) - Fastly's WebAssembly runtime with WASI support.

Everything here is a work in progress prototype, and not yet stable.
