# ODP-Book
This project is an introductory guide to Embedded Programming under the Open Device Partnership (ODP) framework.

## About this material

For an overview of the Open Device Partnership, visit the [ODP Website](https://opendevicepartnership.github.io/).

For some existing code examples and documentation, see [ODP repositories](https://github.com/OpenDevicePartnership)

ODP features the **Rust** programming language as its foundation.  If you're new to Rust or unfamiliar with using it in embedded contexts, we recommend starting with these resources:

- [The Rust Programming Language Book](https://doc.rust-lang.org/stable/book/title-page.html)
- [Rustup (Rust toolchain installer)](https://rustup.rs/)
- [Visual Studio Code](https://code.visualstudio.com/) with Rust extensions (free and well-supported)

Because this project deals with Embedded Controllers, you’ll also need some familiarity with cross-compiling and running Rust in either emulated or hardware environments. A great place to start:

- [The Embedded Rust Book](https://docs.rust-embedded.org/book/)

This guide and its examples use the **STM32F3 Discovery Board**—a widely available, affordable microcontroller used in Rust tutorials. While not itself an Embedded Controller, it's perfect for learning key principles with real hardware.

## Building the Book

To build and view this book locally, install [`mdbook`](https://rust-lang.github.io/mdBook/):

```sh
cargo install mdbook
```

Then run:
```
mdbook serve --open
```
This will start a local development server and open the book in your browser.

