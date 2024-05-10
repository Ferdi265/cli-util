# cli-util - Utility functions and macros for command line applications

This project aims to provide useful functions and macros to create command line
applications. It uses the Cargo crate
[argparse](https://crates.io/crates/argparse) for the argument parsing macro.

Note: The argparse crate is not required to compile this crate. It is, however,
needed if you use the argument parsing macro in another crate and for running
the tests.

## Maintenance Note

This project is unmaintained. I built this in 2016, and didn't touch it since,
except for making it build cleanly with a modern Rust edition in 2024.

## Building

This project is inteded to be build with Cargo, the Rust package manager.

This project compiles with stable Rust 1.78.0.

## Documentation

Documentation is managed via rustdoc, and specifically, Cargo's implementation
of it, `cargo doc`.

## Contributing

Contributions are welcome, although I might not accept all pull requests,
simply as a matter of taste. Don't be afraid to create a fork.

## License

This project is licensed under the GNU GPLv3 and later licenses. The GNU GPLv3 is
provided in the LICENSE file.
