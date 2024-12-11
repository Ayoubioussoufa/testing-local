# Use the official Geth image from Docker Hub
FROM ethereum/client-go:latest

# Expose the Geth RPC port
EXPOSE 8545

# Start Geth in dev mode (this is ideal for testing)
CMD ["geth", "--dev", "--http", "--http.api", "web3,eth,net,personal,miner"]
