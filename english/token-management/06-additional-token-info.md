# Additional Token Information

In addition to the basic token creation and management covered in the main guide, you may want to customize your token further by adding additional information such as a name, symbol, logo, and other metadata. This can enhance the visibility and usability of your token in wallets, exchanges, and other platforms. Here's how you can manipulate these additional token details:

### Set Token Name and Symbol

While the SPL Token CLI doesn't have direct commands to set the token name and symbol, you can use the `spl-token set-token-label` command to set a label for your token, which can serve as its name. Run the following command:

```bash
spl-token set-token-label <TOKEN_ADDRESS> "MyToken"
```

Replace `<TOKEN_ADDRESS>` with the address of your token and "MyToken" with the desired name for your token.

### Set Token Logo

To set a logo for your token, you'll typically need to use a platform or service that supports token metadata, such as the Solana Token Registry. Follow the documentation or guidelines provided by the platform to upload or associate a logo with your token.

### Add Other Metadata

You can add various metadata to your token to provide more context and information. Here are some additional options:

#### Description:

Add a description to provide more details about your token.

```bash
spl-token set-token-description <TOKEN_ADDRESS> "Description of MyToken"
```

Replace `<TOKEN_ADDRESS>` with the address of your token and "Description of MyToken" with the desired description.

#### Website URL:

Include a website URL to direct users to more information about your token.

```bash
spl-token set-token-website <TOKEN_ADDRESS> "https://mytokenwebsite.com"
```

Replace `<TOKEN_ADDRESS>` with the address of your token and `"https://mytokenwebsite.com"` with the URL of your token's website.

#### Decimal Points:

Adjust the number of decimal points for your token.

```bash
spl-token set-token-decimals <TOKEN_ADDRESS> 6
```

Replace `<TOKEN_ADDRESS>` with the address of your token and `6` with the desired number of decimal points.

#### Supply:

Set the total supply of your token.

```bash
spl-token set-token-supply <TOKEN_ADDRESS> <TOTAL_SUPPLY>
```

Replace `<TOKEN_ADDRESS>` with the address of your token and `<TOTAL_SUPPLY>` with the desired total supply of your token.

### Verify Changes

After making any changes to your token's information, you can verify the updates by checking the token details:

```bash
spl-token token-info <TOKEN_ADDRESS>
```

This command will display the current information and metadata associated with your token.

[Back to last page](../README.md)

_Created by [DaemonBSD](https://x.com/DaemonB2D)_
