# Juno Smart Contracts Workspace

Build smart contracts on the cloud powered by [gitpod](https://www.gitpod.io/).

[![Open in Gitpod](https://gitpod.io/button/open-in-gitpod.svg)](https://github.com/giansalex/juno-wasm-workspace)

## Steps
After your workspace is ready, follow next steps.

:point_right: Create your smartcontract project.
```bash
cargo generate --git https://github.com/CosmWasm/cosmwasm-template.git --name PROJECT_NAME
cd PROJECT_NAME
```
This create a basic counter smartcontract, but you can make changes for your custom smartcontract. 

:point_right: Build your smartcontract
```bash
rustup default stable
cargo wasm
```
This produce `project.wasm` in `target/wasm32-unknown-unknown/release` directory, that you can download from editor.

Finally you can upload to [juno chain](https://docs.junochain.com/smart-contracts/uploading-and-interacting#go-cli). :rocket:
