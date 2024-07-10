# Reproduction for auto-imports not working with typescript-tools when using a yarn pnp monorepo

Steps to reproduce:

1 - Navigate to packages/frontend/src/index.ts
2 - The auto import code action doesn't list an available import
3 - Checkout branch "working-with-bun"
4 - run `bun install`
5 - Auto import is now working
