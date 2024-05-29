# Change Token Settings

You might want to update your token settings, such as freezing an account or setting a new authority.

### Freeze an Account

Freezing an account prevents any future transactions involving this account:

```bash
spl-token freeze <TOKEN_ACCOUNT> <TOKEN_ADDRESS>
```

Replace `<TOKEN_ACCOUNT>` and `<TOKEN_ADDRESS>` with the respective addresses.

### Set a New Authority

To set a new authority (e.g., mint authority or freeze authority), use the following command:

```bash
spl-token authorize <TOKEN_ADDRESS> <AUTHORITY_TYPE> <NEW_AUTHORITY>
```

Replace `<TOKEN_ADDRESS>`, `<AUTHORITY_TYPE>`, and `<NEW_AUTHORITY>` with the token address, the type of authority (mint, freeze, etc.), and the new authority address.

### Verify Changes

To verify the changes, you can check the token account details:

```bash
spl-token account-info <TOKEN_ACCOUNT>
```

[Back to last page](../README.md)

_Created by [DaemonBSD](https://x.com/DaemonB2D)_
