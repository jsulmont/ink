# ink! code examples

This folder contains a set of example contracts for ink!.

Have a look at the different examples to better understand how to use ink! to build your own Substrate smart contracts.

## Preparation

For building the example smart contracts found in this folder you will need to have `cargo-contract` installed.

```
cargo install --force --git https://github.com/paritytech/ink cargo-contract
```

We use the `--force` to update to the most recent `cargo-contract` version.

## Build example contract and generate the contracts metadata

To build a single example and generate the contracts Wasm file, navigate to the root of the smart contract and run the following command:

`cargo contract build`

To generate the contract metadata (a.k.a. the contract ABI), run the following command:

`cargo contract generate-metadata`

You should now have an optimized `<contract-name>.wasm` file and an `metadata.json` file in the `target` folder of your contract.

## License

The entire code within this repository is licensed under the [GPLv3](LICENSE). Please [contact us](https://www.parity.io/contact/) if you have questions about the licensing of our products.
