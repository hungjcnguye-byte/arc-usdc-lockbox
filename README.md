# arc-usdc-lockbox

Time-locked USDC savings on Arc testnet.

- Chain ID: `5042002`
- RPC: `https://rpc.testnet.arc.network`
- USDC: `0x3600000000000000000000000000000000000000`
- Explorer: https://testnet.arcscan.app

## Contract

`src/LockBox.sol` records USDC payments and emits accounting events.

## Build

```bash
forge build
```

## Deployment

- Contract: `0xf71e0d4D2158c27F77E2246FAd9bD8Fcb2206f45`
- Tx: `inferred-from-nonce`
- Explorer: https://testnet.arcscan.app/address/0xf71e0d4D2158c27F77E2246FAd9bD8Fcb2206f45
