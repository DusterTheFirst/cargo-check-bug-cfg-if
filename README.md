# `cargo-check-bug-cfg-if`
A minimum example for a cargo check bug

## Steps
- Install the `thumbv7em-none-eabihf` toolchain
- Compile the program with `cargo build --release` (should work)
- Check the program with `cargo check --release` (Should not work)
- Check the program with `cargo check --release --target your-platform` where `your-platform` is replaced by the target triple of your platform (should work)