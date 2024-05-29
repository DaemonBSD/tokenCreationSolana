# Install Rust and Cargo

Rust and Cargo are required for installing the SPL Token CLI.

### Step 1: Install Rust

#### Linux / macOS:

Run the following command to install Rust:

```bash
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
```

#### Windows

Download the installer from the [Rust website](https://www.rust-lang.org/tools/install).

Follow the on-screen instructions to complete the installation.

### Step 2: Configure Your Environment

After installation, configure your current shell:

```bash
source $HOME/.cargo/env
```

### Step 3: Verify Installation

To verify that Rust and Cargo are installed correctly, run:

```bash
rustc --version
cargo --version
```

You should see the version numbers for both Rust and Cargo.

[Back to last page](../README.md)

_Created by [DaemonBSD](https://x.com/DaemonB2D)_
