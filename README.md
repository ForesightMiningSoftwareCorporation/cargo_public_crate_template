# cargo_crate_template
[![CI](https://github.com/ForesightMiningSoftwareCorporation/cargo_crate_template/actions/workflows/release.yml/badge.svg?branch=main)](https://github.com/ForesightMiningSoftwareCorporation/cargo_crate_template/actions/workflows/release.yml/badge.svg)

## Repository Quick Start
In order to get started, you can clone this repository and run the following commands:
```bash
find ./ -type f -exec sed -i 's/cargo_crate_template/YOUR_CRATE_NAME/g' {} \;
```

## Quick Start

Add this to your `Cargo.toml`:

```toml
[dependencies]
cargo_crate_template = { version = "0.1.0", registry = "foresight-mining-software-corporation" }
```