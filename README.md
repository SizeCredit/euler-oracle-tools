# Uniswap Oracle Attack Simulator
The tool calculates the cost to move a token's Uniswap v3 TWAP to x price, given its liquidity profile by binary searching trades on Uniswap QuoterV2 lens.
Check out [this article](https://medium.com/eulerfinance/uniswap-oracle-attack-simulator-42d18adf65af) for details.

## Setup

    npm i

Create `.env` file in the root folder with your provider URL

```bash
REACT_APP_ETHEREUM_NETWORK_HTTP=
```

Optional prameters:

```
REACT_APP_NETWORK=base
REACT_APP_USE_CUSTOM_TOKENLIST=true
```

## Run dev server

    npm start

## Run production build

    npm run build