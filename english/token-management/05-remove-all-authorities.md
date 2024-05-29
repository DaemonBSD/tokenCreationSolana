# Remove All Authorities

For maximum security, you may want to remove all authorities from your token. This will make the token completely immutable.

### Step 1: Remove Mint Authority

```bash
spl-token authorize <TOKEN_ADDRESS> mint --disable
```

### Step 2: Remove Freeze Authority

spl-token authorize `<TOKEN_ADDRESS>` freeze --disable

```bash
spl-token authorize <TOKEN_ADDRESS> freeze --disable
```

### Step 3: Remove Owner Authority

```bash
spl-token authorize <TOKEN_ADDRESS> owner --disable
```

### Step 4: Remove Close Authority

```bash
spl-token authorize <TOKEN_ADDRESS> close --disable
```

### Verify Removal of Authorities

To verify the removal of authorities, you can check the token details:

```bash
spl-token token-info <TOKEN_ADDRESS>
```

[Back to last page](../README.md)

_Created by [DaemonBSD](https://x.com/DaemonB2D)_
