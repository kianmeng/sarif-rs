# sarif-rs

A group of Rust projects for interacting with the
[SARIF](https://sarifweb.azurewebsites.net/) format.

See each subproject for more information:

- `clippy-sarif`: CLI tool to convert `clippy` diagnostics into SARIF. See the
  [Rust documentation](https://psastras.github.io/sarif-rs/clippy_sarif/index.html).
- `hadolint-sarif`: CLI tool to convert `hadolint` diagnostics into SARIF. See
  the
  [Rust documentation](https://psastras.github.io/sarif-rs/hadolint_sarif/index.html).
- `shellcheck-sarif`: CLI tool to convert `shellcheck` diagnostics into SARIF.
  See the
  [Rust documentation](https://psastras.github.io/sarif-rs/shellcheck_sarif/index.html).
- `sarif-fmt`: CLI tool to pretty print SARIF diagnostics. See the
  [Rust documentation](https://psastras.github.io/sarif-rs/sarif_fmt/index.html).
- `serde-sarif`: Typesafe SARIF structures for serializing and deserializing
  SARIF information using [serde](https://serde.rs/). See the
  [Rust documentation](https://psastras.github.io/sarif-rs/serde_sarif/index.html).

License: MIT
