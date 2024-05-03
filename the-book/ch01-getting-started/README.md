# Chapter 1 Notes

## Rust

- Update rust using `rustup update`
- Rust code can be compiled with the compiler using `rustc <filename>`. This will output a compiled binary

## Cargo

- Create a project with `cargo new <project_name>`
- Build a project with `cargo build`. Outputs the binary under `./target/debug`
- Run a project with `cargo run`. This will build and run the compiled binary in one
- Build a project without a binary and check for errors with `cargo check`
- A release binary can be built with `cargo build --release`. This compiles it with optimizations
