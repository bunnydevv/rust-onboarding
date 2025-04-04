
# 🦀 Rust Learning Roadmap

## ✅ Week 1: Foundations of Rust (Basics)
**Goal**: Understand the core syntax and Rust mindset.

### 📚 Topics
- [ ] Rust setup: `rustup`, `cargo`, `crates.io`
- [ ] Basic syntax: `fn`, `let`, `mut`, `const`
- [ ] Primitive types: `i32`, `f64`, `bool`, `char`, `&str`
- [ ] Ownership & Borrowing
- [ ] Lifetimes (intro)
- [ ] Functions & Control Flow (`if`, `match`, `loop`)
- [ ] Basic error handling: `Result`, `Option`

### 📘 Resources
- [The Rust Book – Chapters 1–6](https://doc.rust-lang.org/book/)
- [Rustlings Exercises 1–4](https://github.com/rust-lang/rustlings)

### 🛠 Practice Projects
- [ ] Simple calculator
- [ ] Fahrenheit ⇄ Celsius converter
- [ ] Guessing game

---

## ✅ Week 2: Intermediate Concepts
**Goal**: Dive deeper into Rust’s unique features.

### 📚 Topics
- [ ] Structs & Enums
- [ ] Pattern Matching
- [ ] Modules, Packages, `mod`, `use`, `pub`
- [ ] Collections: `Vec`, `HashMap`, `HashSet`
- [ ] Traits & Generics
- [ ] Ownership in complex structures

### 📘 Resources
- [The Rust Book – Chapters 7–10](https://doc.rust-lang.org/book/)
- [Rust by Example](https://doc.rust-lang.org/rust-by-example/)
- [Rustlings Exercises 5–8](https://github.com/rust-lang/rustlings)

### 🛠 Practice Projects
- [ ] CLI Todo App
- [ ] File reader/writer using `std::fs`
- [ ] Struct + Trait practice

---

## ✅ Week 3: Project Building & Rust Ecosystem
**Goal**: Build real tools using common crates.

### 📚 Topics
- [ ] Error handling with `anyhow` / `thiserror`
- [ ] JSON & CSV handling (`serde_json`, `csv`)
- [ ] File & HTTP I/O (`reqwest`, `tokio`)
- [ ] Testing: `#[test]`, `cargo test`
- [ ] Logging: `log`, `env_logger`
- [ ] CLI tools: `clap`, `chrono`, `rayon`

### 🛠 Practice Projects
- [ ] REST API client using `reqwest`
- [ ] CSV analyzer
- [ ] Logger + CLI integration

---

## ✅ Week 4: Async, Concurrency & Systems Programming
**Goal**: Learn async and low-level Rust.

### 📚 Topics
- [ ] Async basics: `async`, `await`, `tokio`
- [ ] Concurrency: `Mutex`, `Arc`, `thread`
- [ ] Channels and thread communication
- [ ] Systems-level memory handling

### 📘 Resources
- [The Rust Book – Chapters 11–16](https://doc.rust-lang.org/book/)
- [Tokio Tutorial](https://tokio.rs/tokio/tutorial)

### 🛠 Practice Projects
- [ ] Async file downloader
- [ ] Multithreaded task runner
- [ ] Basic chat client using `tokio`

---

## ✅ Week 5–6: Advanced Concepts & Final Projects
**Goal**: Master advanced topics and build a capstone project.

### 📚 Topics
- [ ] Macros (declarative & procedural)
- [ ] Unsafe Rust (intro)
- [ ] FFI (optional)
- [ ] Web APIs: `axum` / `actix-web`
- [ ] WebAssembly + Rust (optional)
- [ ] Crate publishing (`cargo publish`)

### 🛠 Capstone Project Ideas
- [ ] Command-line note manager
- [ ] Mini web service (with REST API)
- [ ] Parallel file searcher (`ripgrep` clone)
- [ ] WASM-powered browser game
- [ ] Discord bot in Rust

---

## 🎯 Daily Learning Plan (Suggested)
- ✅ **1–1.5 hrs** theory/reading
- ✅ **1–1.5 hrs** hands-on coding
