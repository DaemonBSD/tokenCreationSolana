# Install Solana CLI

The Solana Command Line Interface (CLI) is necessary for interacting with the Solana blockchain.

### Step 1: Download and Install

Open your terminal and run the following command:

```bash
sh -c "$(curl -sSfL https://release.solana.com/stable/install)"
```

### Step 2: Update Your Path

After installation, you need to update your PATH environment variable to include the Solana CLI. Add the following line to your .bashrc, .zshrc, or equivalent file:

```bash
export PATH="/home/yourusername/.local/share/solana/install/active_release/bin:$PATH"
```

Then, reload your shell configuration:

```bash
source ~/.bashrc
# or
source ~/.zshrc
```

### Step 3: Verify Installation

To verify that the Solana CLI is installed correctly, run:

```bash
solana --version
```

You should see the version number of the Solana CLI.

[Back to last page](../README.md)

_Created by [DaemonBSD](https://x.com/DaemonB2D)_
