# Getting Started

Welcome! If you're new to the Open Device Partnership (ODP), you're in the right place.

If you're also new to the world of Embedded Controllers and the software that drives them—don't worry. You're still in the right place.

The Open Device Partnership introduces game-changing concepts for **reuse** and **interchangeability** of Embedded Controller components—especially in modern laptops. Just as importantly, it promotes a *revolutionary focus on security and code safety from the ground up*.

ODP is designed with **Rust** as the implementation language. If you're coming from a C or assembly background, you may feel some initial resistance to learning a new language and unfamiliar patterns. That’s completely understandable.

But let’s face it: while it’s *certainly possible* to write memory-safe, secure code in C, it’s also very easy to make mistakes. With Rust, you’d have to work hard to write unsafe code that even compiles.

As new standards—and potentially even regulations—begin to push for memory-safe languages in critical systems, ODP aims to be ahead of the curve by making that future available *now*.

If you haven’t already, refer to the `README.md` file in this repository for links and guidance on getting started with Rust and embedded programming. If you’re new to embedded systems, we strongly recommend following the Rust Embedded Book and getting a **STM32F3 Discovery board** (~$25) for hands-on experience.

Once you're ready, begin with the [Concepts](./Concepts.md) section, which explains how the pieces of ODP fit together.

From there, the [Tutorials](./Tutorials.md) section will put these concepts into action—starting with the STM32F3 hardware, and gradually moving into real Embedded Controller examples, including considerations specific to Windows devices.

Later, we’ll also explore boot firmware and ODP’s role in this domain with practical examples.

This book is a guided tour for developers at all levels. Feel free to skip ahead, jump back, or explore in the order that makes sense for you. By the end, you’ll be equipped to design **safe**, **modular**, and **interchangeable** embedded component code—ready to power the heart of a new machine.