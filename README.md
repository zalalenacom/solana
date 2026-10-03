# Solana Reward Counter

Minimal Anchor program for creating a per-wallet counter and incrementing it on-chain.

## Stack

- Solana
- Anchor
- TypeScript + Mocha

## Quick start

Install the Solana CLI, Anchor, Rust, Node.js, and Yarn. Then run:

```bash
yarn install
anchor build
anchor test
```

## Program instructions

- `initialize` creates a PDA-backed `Counter` for the signer.
- `increment` increases the stored count by one.

The PDA uses the seed `counter` plus the owner's public key.

## License

MIT
