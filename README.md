# Super Seeder

Venice models on [AntSeed](https://antseed.com), paid per token in USDC and settled on Base.

- **Venice's catalog**: Claude, GPT, Grok, Gemini, Kimi, GLM, DeepSeek and more, with streaming and tools
- **Currently about half of Venice's list price**, on average; prices are dynamic
- **No account, no subscription**: you pay per token, through AntSeed payment channels
- **Have a Venice key?** Add a dedicated key and its credit sells here, paid in SEED:
  [super-seeder.com/earn](https://super-seeder.com/earn/)

## Use it

```bash
npm install -g @antseed/cli
antseed buyer deposit
antseed buyer start --peer d19ffae0e85b5230422019926b2f37ec0f1f41f3
# then point any OpenAI-compatible client at http://localhost:8377/v1
```

Prices, models and the desktop app: [super-seeder.com/use](https://super-seeder.com/use/).

## SEED

SEED is the project's token on Base. Credit holders are paid in SEED, and SEED stakers receive the project's net revenue every week.

- Contract: [`0x89a0A44100628B1011EE69783cE867f26c32d07A`](https://basescan.org/token/0x89a0A44100628B1011EE69783cE867f26c32d07A) (verified source, no owner, no mint)
- Fixed supply of 1,000,000,000, no sale and no team allocation
- SEED/VVV liquidity on Uniswap v3, held by a lock contract with no owner and no withdraw function
- Every project contract, with links to check it: [super-seeder.com/docs/verify](https://super-seeder.com/docs/verify/)
- Token page: [super-seeder.com/seed](https://super-seeder.com/seed/) · Tokenomics: [super-seeder.com/docs/tokenomics](https://super-seeder.com/docs/tokenomics/)

## Identity

- Seller peer: `d19ffae0e85b5230422019926b2f37ec0f1f41f3`
- Agent ID: `53509`
- Domain: [super-seeder.com](https://super-seeder.com)
- X: [@Super_Seeder](https://x.com/Super_Seeder)

The [`antseed.json`](./antseed.json) file in this repository links this GitHub account to our seller peer,
verifiable by any AntSeed client.
