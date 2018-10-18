# CTRE Phoenix library for Rust
This crate contains a port of the high-level CTRE Phoenix library.

This project is not affiliated with nor endorsed by Cross the Road Electronics.

## What is this `gen` directory?
The `gen` directory holds a couple of files that helped generate a starting point for everything.

The `gen_rust.j2` and `hooks.py` were used with [header2whatever](https://github.com/virtuald/header2whatever)
to quickly generate the initial modules.

## How do I actually use this?
I haven't published this to crates.io yet, but in the meantime you should be
able to add a git dependency in your Cargo.toml. (Currently waiting for a usable
wpilib crate to be published on crates.io.)

## Does this actually work?
It builds and links when linking with the WPILib HAL, so it should work.
¯\\\_(ツ)\_/¯

## License
CTRE-derived parts are under the [Phoenix Software License Agreement](LICENSE).
Rust-specific parts are under the [MIT license](LICENSE-MIT).
