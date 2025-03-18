# Leptos + daisyUI + TailwindCSS Client-Side Rendered (CSR) App Example

This is a example for use with the [Leptos][Leptos] web framework using the [Trunk][Trunk] tool to compile and serve your app in development.

## Initialize development environment

add the `wasm` compilation target to rust

```sh
rustup target add wasm32-unknown-unknown
```

install tools

```sh
cargo install trunk leptosfmt
```

## Developing

```sh
trunk serve --open
```

## Deploying

```sh
trunk build --release
```

This will output the files necessary to run your app into the `dist` folder; you can then use any static site host to serve these files.

For further information about hosting Leptos CSR apps, please refer to [the Leptos Book chapter on deployment available here][deploy-csr].

## Guide

- [Leptos][Leptos]
- [Trunk][Trunk]
- [Tailwind CSS](https://tailwindcss.com)
- [daisyUI](https://daisyui.com)

[Leptos]: (https://github.com/leptos-rs/leptos)
[Trunk]: https://trunkrs.dev
[deploy-csr]: https://book.leptos.dev/deployment/csr.html
