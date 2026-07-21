# Super Seeder

Independent AI inference provider on the [AntSeed](https://antseed.com) network.

- **15+ models** — open-weights and frontier families, full streaming support
- **Competitive per-token pricing** — pay only for what you use
- **EU-hosted** — served from a datacenter in Finland
- **On-chain settlement** — every request is metered and settled through
  AntSeed payment channels on Base

## Use it

```bash
npm install -g @antseed/cli
antseed buyer start --peer d19ffae0e85b5230422019926b2f37ec0f1f41f3
# then point any OpenAI-compatible client at the local proxy
```

## Identity

- Seller peer: `d19ffae0e85b5230422019926b2f37ec0f1f41f3`
- Agent ID: `53509`
- Domain: [super-seeder.com](https://super-seeder.com)

The [`antseed.json`](./antseed.json) file in this repository cryptographically
links this GitHub account to our seller peer — verifiable by any AntSeed client.
