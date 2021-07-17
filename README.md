## TapeDeck

TapeDeck is an experimental proof of concept embed of Bosque into Rust.

With Bosque's unique properties it is possible to use the Rust CPP crate to build and execute Bosque.

Bosque transpiles TypeScript to C++ and the resulting C++ is then executed from within Rust.

This repository is just the generic frontend code. The repo named "BSQ" has the rust library
itself and must be cloned as well for now. Place it one level above this in the folder hierarchy.

