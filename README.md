# barbut_sui_move

*Rearranging the [satoshi flip coin game](https://github.com/MystenLabs/satoshi-coin-flip) to understand move language and converting it to a dice game.

* To install Sui: https://docs.sui.io/guides/developer/getting-started/sui-install

* The devnet contract address can be found below.

[package]
name = "barbut"
version = "0.0.1"

[dependencies]
Sui = { git = "https://github.com/MystenLabs/sui.git", subdir = "crates/sui-framework/packages/sui-framework", rev = "framework/devnet" }

[addresses]
barbut = "0x0"
