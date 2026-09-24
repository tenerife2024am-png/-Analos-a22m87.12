# Analos (ANL)

Analos is an original Layer-1 blockchain prototype for a public testnet.

## Parameters
- Name: Analos
- Symbol: ANL
- Initial supply: 1,000,000,000 ANL
- Consensus: Proof of Stake
- Chain ID: analos-testnet-1
- Base denomination: uanalos
- Display denomination: ANL
- Conversion: 1 ANL = 1,000,000 uanalos

## Important
This repository is a deployment scaffold, not a production-ready blockchain. Before mainnet:
- perform an independent security audit;
- generate validator keys securely;
- replace development credentials;
- establish genesis governance and token allocations;
- configure persistent storage and backups;
- use TLS/authentication for public RPC endpoints;
- review legal, tax, and token-distribution requirements.

## Local testnet

Requirements: Docker and Docker Compose.

```bash
docker compose -f docker-compose.yml up --build
```

The included services are intentionally minimal and are suitable for development scaffolding only.
