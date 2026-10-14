# Super Seeder

Venice models on [AntSeed](https://antseed.com), paid per token in USDC and settled on Base.

- **Venice's catalog**: Claude, GPT, Grok, Gemini, Kimi, GLM, DeepSeek and more, with streaming and tools
- **Currently about half of Venice's list price**, on average; prices are dynamic
- **No account, no subscription**: you pay per token, through AntSeed payment channels
- **Have a Venice key?** The credit you don't use can sell here too (beta, by invitation):
  [super-seeder.com/earn](https://super-seeder.com/earn/)

## Use it

```bash
npm install -g @antseed/cli
antseed buyer deposit
antseed buyer start --peer d19ffae0e85b5230422019926b2f37ec0f1f41f3
# then point any OpenAI-compatible client at http://localhost:8377/v1
```

Prices, models and the desktop app: [super-seeder.com/use](https://super-seeder.com/use/).

## Identity

- Seller peer: `d19ffae0e85b5230422019926b2f37ec0f1f41f3`
- Agent ID: `53509`
- Domain: [super-seeder.com](https://super-seeder.com)

The [`antseed.json`](./antseed.json) file in this repository links this GitHub account to our seller peer,
verifiable by any AntSeed client.
