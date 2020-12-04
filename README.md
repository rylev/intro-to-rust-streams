# Intro to Rust

This is the code for the my series of "Introduction to Rust" streams. You can find the streams on my [YouTube channel](https://www.youtube.com/channel/UCpeX4D-ArTrsqvhLapAHprQ).

## Who are these streams for?

These introductory streams assume no previous knowledge of [the Rust programming language](https://www.rust-lang.org), but they do assume previous experience with programming. If you are new to programming or have not programmed in a long time, this stream may be too advanced for you. 

## Getting Started

To follow along with these streams you'll need only a few pre-requisites:

#### The Rust compiler toolchain and core tooling

To install the toolchain, first go to [rustup.rs](https://rustup.rs), and follow the instructions. This should install the compiler, Cargo (Rust's build tool), and other things like documentation.

You can check that this all worked by:
* opening your terminal (PowerShell, cmd.exe, bash, etc. should all work)
* entering `cargo new hello-world`
* changing into the newly created `hello-world` directory
* running `cargo run`
* if you see "Hello, world!" printed to your screen, then everything should be good to go!

**Note**: If you are on Windows you will need to install the [Visual C++ build tools](https://visualstudio.microsoft.com/downloads/#build-tools-for-visual-studio-2019) which includes the MSVC linker which Rust uses.

#### An Editor

You can write Rust in an editor of your choice, but for this stream we're using VS Code along with the [rust-analyzer](https://marketplace.visualstudio.com/items?itemName=matklad.rust-analyzer) extension. If you're using VS Code, we recommend using this extension over the soon-to-be-deprecated RLS extension.

## Asking Questions

Feel free to leave questions about the contents of the stream as [issues in this repository](https://github.com/rylev/intro-to-rust-streams/issues/new) or as comments on the YouTube videos. I will do my best to answer them.

## Additional Resources

* [The Book](https://doc.rust-lang.org/book/): _The_ resource for learning Rust
* [Rust by Example](https://doc.rust-lang.org/rust-by-example/): Learning Rust by going through examples
* [Rustlings](https://github.com/rust-lang/rustlings): Learn Rust interactively in your terminal