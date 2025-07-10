# Crypto Nodes

## Ether (Sepolia Testnet)

```bash
docker compose -f docker-compose-linux.yaml -p crypto-nodes up --build -d ether-testnet-execution ether-testnet-consensus
docker compose -f docker-compose-windows.yaml -p crypto-nodes up --build -d ether-testnet-execution ether-testnet-consensus
```