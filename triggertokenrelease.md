# How to manually trigger a token release

Each token deployed via MintME.com contains a ````release()```` function that can be called by anyone to release tokens to the pre-configured token release address. It turns out that anyone can call this function, not just the token creator or MintME.com. This means that if the MintME.com exchanges goes offline permanently, token creators who have configured a custom release address can continue to trigger token releases as they wish.

[JSON/ABI Interface for the release function](https://github.com/EUBIToken/LLToken/blob/main/release.json)
