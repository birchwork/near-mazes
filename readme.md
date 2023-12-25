# Mazes

Demo day project

## What's next? How do I make an app with this?

#### **compile of the smart contract** 

```
cargo build --target wasm32-unknown-unknown --release
```

[^INFO]: The above command is setting a flag to create a WebAssembly file.`build` `target` `.wasm`

### contract address

```
mazesexample.testnet
```

### view contract storage

```
near contract view-storage mazesexample.testnet all as-json network-config testnet now
```
