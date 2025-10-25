Proposal 0005 — Compatibility Layer Between LLVM Rust and LTSS Rust

## Goal
Provide a transparent ABI bridge between LLVM-based and R3C-based Rust compilers.

## Features
- `r3c_abi` crate for cross-compiler FFI compatibility  
- LTSS ABI table generation for stable binary linkage  
- Long-term guarantee: same crate builds for both pipelines

## Benefit
Allows companies to adopt LTSS Rust incrementally without breaking their LLVM-based CI.


---
