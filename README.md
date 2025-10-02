# ⚡️ Rust File Hashing & Comparison Tool

## 🛡️ Project Overview

This is a high-performance command-line utility built in Rust for **efficiently identifying duplicate files** within a specified directory structure.

It works by recursively scanning a target directory and using the **SHA-256 cryptographic hash** to ensure file integrity and contents are truly identical, regardless of file name or timestamp.

**This project demonstrates:**
* **Systems Programming & Performance:** Efficient file I/O and handling of large data streams.
* **Rust Fundamentals:** Robust error handling (`Result`), dependency management (`Cargo`), and the use of external crates (like `clap` and `sha2`).
* **Professional Tooling:** Usage of the Agile/Kanban methodology (tracked via Jira/GitHub Projects) and Git for version control.

## 🚀 Getting Started

### Prerequisites

You must have the Rust toolchain installed. If not, install it using `rustup`:

```bash
curl --proto '=https' --tlsv1.2 -sSf [https://sh.rustup.rs](https://sh.rustup.rs) | sh
