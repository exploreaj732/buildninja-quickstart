# Rust Cargo Build

BuildNinja configuration for ripgrep - the blazingly fast grep replacement.

## Source Repository

| Property | Value |
|----------|-------|
| **URL** | https://github.com/BurntSushi/ripgrep |
| **Branch** | master |
| **Author** | [Andrew Gallant](https://github.com/BurntSushi) |
| **Stars** | 59,000+ |
| **License** | MIT/Unlicense |

## About ripgrep

ripgrep is a line-oriented search tool that recursively searches the current directory for a regex pattern while respecting your gitignore. It's one of the most popular Rust projects on GitHub.

**Key Features:**
- Faster than grep, ag, git grep, ucg, pt, and sift
- Respects .gitignore by default
- Skips hidden files and binary files automatically
- Full Unicode support
- Supports compressed file searching (gzip, bzip2, xz, lzma, lz4, Brotli, Zstd)
- PCRE2 regex support

**Performance:** On a 13GB file, ripgrep completes searches in ~0.6 seconds compared to ~9.5 seconds for GNU grep.

## What This Demonstrates

- Rust/Cargo build system
- Release builds with optimizations (`--release`)
- Cargo test execution
- Building large-scale, performance-critical Rust projects

## Agent Requirements

- Rust 1.85+ (stable)
- Cargo

## Build Steps

| Step | Command | Description |
|------|---------|-------------|
| 1 | `cargo build --release` | Build optimized binary |
| 2 | `cargo test` | Run test suite |

## Artifacts

- `target/release/` - Compiled release binary (`rg`)
