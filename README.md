# custom-blockchain

starting the Proof-of-Work demo:

```
git clone git@github.com:danielsmithdevelopment/custom-blockchain.git
cd custom-blockchain
npm install
npm run dev-test
```

starting a 3-node cluster:

```
npm run dev
HTTP_PORT=3002 P2P_PORT=5002 PEERS=ws://localhost:5001 npm run dev
HTTP_PORT=3003 P2P_PORT=5003 PEERS=ws://localhost:5001,ws://localhost:5002 npm run dev
```