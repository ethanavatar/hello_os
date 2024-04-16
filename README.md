# Hello OS

A super simple x86_64 OS Kernel that says hello in VGA text mode.

This is based on the first 2 chapters of [Writing an OS in Rust](https://os.phil-opp.com/).

## Building

Requires:
- `rust nightly` - I'm using the one from roughly 2024-03-28
- `qemu`

Install prerequisite components with rustup:
```bash
$ rustup component add rust-src llvm-tools-preview --toolchain YOUR_NIGHTLY_TOOLCHAIN
```

Build and run with (will launch qemu):
```bash
$ cargo run --release
```
