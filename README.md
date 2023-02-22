<div align="center">

# bevy-template

</div>

This is a minimal [bevy](https://bevyengine.org/) template for [cargo generate](https://github.com/cargo-generate/cargo-generate), intended to be run on Linux.

It contains just the setup recommended in [Bevy The Book](https://bevyengine.org/learn/book/getting-started/setup/), with enabled fast compiles, mold linker and nightly rust compiler for the best performance.

## Usage

You'll need to have installed `clang` and `mold` packages.

To create the project simply run:
```bash
cargo generate https://github.com/alpinus4/bevy-template.git
```
For more info go to [cargo generate guide](https://cargo-generate.github.io/cargo-generate/index.html).

## Motivation

While there exist other templates, such as:

[https://github.com/Teg64/basic-bevy-template](https://github.com/Teg64/basic-bevy-template)

[https://github.com/taurr/bevy-template-rs](https://github.com/taurr/bevy-template-rs)

they include many more things than I would like from a template.
This repo contains as clean plate as you can get, no bloat.
