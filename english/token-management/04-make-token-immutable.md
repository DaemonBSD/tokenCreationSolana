# Make Tokens Immutable

To ensure the immutability of your tokens, you need to disable the authority. This step is crucial for security and trust.

### Step 1: Disable Mint Authority

```bash
spl-token authorize <TOKEN_ADDRESS> mint --disable
```

### Step 2: Disable Freeze Authority (if applicable)

```bash
spl-token authorize <TOKEN_ADDRESS> freeze --disable
```

After running these commands, no one will be able to mint new tokens or freeze accounts.

### Verify Immutability

To verify that the token is immutable, you can check the token details:

```bash
spl-token token-info <TOKEN_ADDRESS>
```

[Back to last page](../README.md)

_Created by [DaemonBSD](https://x.com/DaemonB2D)_
