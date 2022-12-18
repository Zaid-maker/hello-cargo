# RUST

Today i started learning rust and this repo contains the beginner guide.

## How much i have learned 🤔

I have learned how to install rust on my system and create new rust project accordingly.

1) We can create a new rust project by running: `cargo new`.
2) We can then build that project by running: `cargo build`.
3) We can then run that project by running: `cargo run`.
4) We can then check for errors by running: `cargo check`.

**An additional advantage of using Cargo is that the commands are the same no matter which operating system you’re working on. So, at this point, we’ll no longer provide specific instructions for Linux and macOS versus Windows.**

## Building for release

When your project is finally ready for release, you can use `cargo build --release` to compile it with optimizations. This command will create an executable in target/release instead of target/debug. The optimizations make your Rust code run faster, but turning them on lengthens the time it takes for your program to compile. This is why there are two different profiles: one for development, when you want to rebuild quickly and often, and another for building the final program you’ll give to a user that won’t be rebuilt repeatedly and that will run as fast as possible. If you’re benchmarking your code’s running time, be sure to run `cargo build --release` and benchmark with the executable in target/release.
