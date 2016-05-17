# cli-util - Utility functions and macros for command line applications

This project aims to provide useful functions and macros to create command line
applications. It uses the Cargo crate
[argparse](https://crates.io/crates/argparse) for the argument parsing macro.

Note: The argparse crate is not required to compile this crate. It is, however,
needed if you use the argument parsing macro in another crate and for running
the tests.

## Building

This project is inteded to be build with Cargo, the Rust package manager.

This project specifically requires (as of 2016.05.08) a nightly build of rustc
to compile, as it uses some macro code (`parse_args!` from
[cli-util](https://github.com/Ferdi265/cli-util) inexplicably doesn't work on
release rustc) that doesn't work with release rustc.

## Documentation

Documentation is managed via rustdoc, and specifically, Cargo's implementation
of it, `cargo doc`.

## Contributing

Contributions are welcome, although I might not accept all pull requests,
simply as a matter of taste. Don't be afraid to create a fork.

## License

This project is licensed under the GNU GPLv3 and later licenses. The GNU GPLv3 is
provided in the LICENSE file.
