# StaticBit Wallet Seed Generator

This page allows users to deterministically generate an XRPL wallet from text input
and optional salt using SHA-256 or PBKDF2 methods.

👉 Use it here: https://staticbit-io.github.io/staticbit-text-to-wallet

⚠ All computations are client-side. No data is sent anywhere.

## Features
- SHA-256 and PBKDF2 (100k iterations)
- Ed25519 or secp256k1 algorithms
- Supports Unicode input (any language)
- X-address (mainnet / testnet)
- Fully deterministic
- Can be used for recovery verification

## Offline Usage
Download `index.html` and open locally.
(or run: `python -m http.server`, `dotnet serve`, etc.)
