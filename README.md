# pleme-inner-derive

Newtype accessors: pub fn inner(&self) -> &Inner + pub fn into_inner(self) -> Inner. Borrow + owned access to the wrapped value.

[![Build](https://github.com/pleme-io/pleme-inner-derive/actions/workflows/auto-release.yml/badge.svg)](#)
[![crates.io](https://img.shields.io/crates/v/pleme-inner-derive.svg)](https://crates.io/crates/pleme-inner-derive)

## Install

```toml
[dependencies]
pleme-inner-derive = "*"
```

## Generation

This crate is mechanically emitted by [`tatara-rust-ast`](https://github.com/pleme-io/tatara-rust-ast). The author surface is a typed `(defmacro …)` Spec — the proc-macro implementation, tests, Nix flake, caixa wrapper, and CI workflow are all generated. See the catalog at `catalog.json` in the parent registry.
