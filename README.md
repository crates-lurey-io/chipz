# chipz

CHIP-8 Virtual Machine.

[![Rust](https://github.com/crates-lurey-io/chipz/actions/workflows/test.yml/badge.svg)](https://github.com/crates-lurey-io/chipz/actions/workflows/test.yml)
[![Crates.io Version](https://img.shields.io/crates/v/chipz)](https://crates.io/crates/chipz)
[![codecov](https://codecov.io/gh/crates-lurey-io/chipz/graph/badge.svg?token=Z3VUWA3WYY)](https://codecov.io/gh/crates-lurey-io/chipz)

## Contributing

This project uses [`just`][] to run commands the same way as the CI:

- `cargo just init` to install dependencies needed by the rest of the commands.
- `cargo just check` to check formatting and lints.
- `cargo just test` to run tests.
- `cargo just doc` to generate and preview docs.
- `cargo just coverage` to generate and preview code coverage.

[`just`]: https://crates.io/crates/just

For a full list of commands, see the [`Justfile`](./Justfile).
