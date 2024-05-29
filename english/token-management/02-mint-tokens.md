# Mint Tokens

Once your token is created, the next step is to mint some tokens.

### Step 1: Create a Token Account

First, create a token account where your tokens will be stored:

```bash
spl-token create-account <TOKEN_ADDRESS>
```

Replace `<TOKEN_ADDRESS>` with the address of the token you created.

### Step 2: Mint Tokens

Now, you can mint tokens to the created token account:

```bash
spl-token mint <TOKEN_ADDRESS> <AMOUNT> <RECIPIENT_TOKEN_ACCOUNT>
```

Replace `<TOKEN_ADDRESS>`, `<AMOUNT>`, and `<RECIPIENT_TOKEN_ACCOUNT>` with your token address, the number of

tokens you wish to mint, and the token account you created, respectively.

### Step 3: Verify Minting

To verify that the tokens have been minted, you can check the balance of the recipient token account:

```bash
spl-token balance <RECIPIENT_TOKEN_ACCOUNT>
```

[Back to last page](../README.md)

_Created by [DaemonBSD](https://x.com/DaemonB2D)_
