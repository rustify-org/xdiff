# README

## Install

```shell
cargo add clap --features derive
cargo add serde_yaml
cargo add tokio --features full
cargo add anyhow
cargo add reqwest --features rustls --no-default-features
cargo add similar #https://github.com/mitsuhiko/similar
cargo add console
cargo build
```

## test similar

```shell
cargo run --example similar
cargo add similar --features bytes
```