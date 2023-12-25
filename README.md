## Basic Information

**Project Name:** CBIndex

**Github Links:**

- [**Smart Contract**](https://github.com/CypherBabel-Lab/VHorizon-contracts)
- [**Frontend**](https://github.com/CypherBabel-Lab/VHorizon)

**Useful Links:**

- [**Demo Website**](https://viction.cbindex.finance/)
- [**Deck for Hackathon**](https://docsend.com/view/duk56in24qhex4x8)
- [**Whitepaper**](https://cbindex.finance/CBIndex_whitepaper_2023_v1.pdf)
- [**X (Twitter)**](https://twitter.com/CBIndex_Global)
- [**Telegram**](https://t.me/CBIndexGlobalM)

## Important Note

## Planned Tasks for the Hackathon

**Blockchain Side**

[x] Develop the smart contracts for the ACTIVE FUND feature (fund creation, investment, withdrawal, etc.).

[x] Test and deploy the smart contracts on the TomoChain Testnet.

[x] Build an environment for demoing the active funds, including issuing ERC20 tokens, setting up LP pools, mocking Chainlink's V3's price feed, and deploying Uniswap V2.

**Client Side**

[x] Develop the frontend for the ACTIVE FUND feature using NextJS.

[x] Realize wallet connection by integrating Web3Modal V3.

---

## Completed Tasks During the Hackathon (100% completion)

**Blockchain Side**

✅ Develop the smart contracts for the ACTIVE FUND feature (fund creation, investment, withdrawal, etc.).

✅ Test and deploy the smart contracts on the TomoChain Testnet.

✅ Build an environment for demoing the active funds, including issuing ERC20 tokens, setting up LP pools, mocking Chainlink's V3's price feed, and deploying Uniswap V2.

**Client Side**

✅ Develop the frontend for the ACTIVE FUND feature using NextJS.

✅ Realize wallet connection by integrating Web3Modal V3.

---

## Details about the completed tasks for the blockchain side

**1. Completed the smart contracts for the ACTIVE FUND feature.**

**2. Deployed and tested the smart contracts on the TomoChain Testnet.**

- `vaultFactory contract`: [`0x3868BC3557392E92f58463cbb042007Ca7B3aa96`](https://testnet.tomoscan.io/address/0x3868BC3557392E92f58463cbb042007Ca7B3aa96)

- `valueEvaluator contract`: [`0x7F7190fe45be177746CbA90106B3D1e6C91233Aa`](https://testnet.tomoscan.io/address/0x7F7190fe45be177746CbA90106B3D1e6C91233Aa)

- `integrationManager contract`:[`0x3a9d736b6A5A0f2B5741B918bdC778cE4E9A795b`](https://testnet.tomoscan.io/address/0x3a9d736b6A5A0f2B5741B918bdC778cE4E9A795b)

**3. Issued five ERC20 crypto assets on the TomoChain Testnet, the contract addresses are:**

- WBTC: [`0xf283c304b29c94385C01e77ef5E08160419D5760`](https://testnet.tomoscan.io/token/0xf283c304b29c94385C01e77ef5E08160419D5760)
- WETH: [`0xaF4c3cB96c011Bd123a5aeB7C8eaf5E17f5Ca080`](https://testnet.tomoscan.io/token/0xaF4c3cB96c011Bd123a5aeB7C8eaf5E17f5Ca080)
- WSOL: [`0xC0FcE24e33DB355e21d63eb91Fd35D8F65D0A1DE`](https://testnet.tomoscan.io/token/0xC0FcE24e33DB355e21d63eb91Fd35D8F65D0A1DE)
- DAI: [`0xC5A8156f554FCB771e9A6E174eF394487a4d2EdD`](https://testnet.tomoscan.io/token/0xC5A8156f554FCB771e9A6E174eF394487a4d2EdD)

**4. Mocked Chainlink V3's `Price Feed`, the contract addresses are:**

- WBTC/USD: [`0x03e344EB6f3a45e5e4d89Cc03725038C5d0cC939`](https://testnet.tomoscan.io/address/0x03e344EB6f3a45e5e4d89Cc03725038C5d0cC939)
- WETH/USD: [`0xFA0a10A519cC24a00f5dc95ae6666a1aAe54D775`](https://testnet.tomoscan.io/address/0xFA0a10A519cC24a00f5dc95ae6666a1aAe54D775)
- WSOL/USD: [`0x573B6cb7d55057Eb7fb943a73d12a26D4b132452`](https://testnet.tomoscan.io/address/0x573B6cb7d55057Eb7fb943a73d12a26D4b132452)
- DAI/USD: [`0xAF37DF5Eb35A27424D275677D68bc7Ead7D844a7`](https://testnet.tomoscan.io/address/0xAF37DF5Eb35A27424D275677D68bc7Ead7D844a7)

**5. Built a Uniswap V2 on the TomoChain Testnet with the `UniswapV2Factory`([`0x5CA4db2bB728b0d6285A9C83d43F7503Dca12e92`](https://testnet.tomoscan.io/address/0x5CA4db2bB728b0d6285A9C83d43F7503Dca12e92)), `adapterUniswapV2Exchange`([`0xb67A5D68dfB27F672bB1fCE32128dC189eCF9123`](https://testnet.tomoscan.io/address/0xb67A5D68dfB27F672bB1fCE32128dC189eCF9123)), and `adapterUniswapV2LP`([`0xF8AA80A1A2bc406b85AEc34AF5937480F10a9F2E`](https://testnet.tomoscan.io/address/0xF8AA80A1A2bc406b85AEc34AF5937480F10a9F2E)) to create four Liquidity Pools on the XRPL EVM Sidechain containing the five crypto assets, the contract addresses are:**

- WBTC/DAI LP
- WETH/DAI LP
- WSOL/DAI LP

**6. Deployed `Adaptor` for Uniswap V2 to enable swap.**

- UniswapV2Router02 ([`0x46BAFFad74F525f5D3eaCE0e7D94A3A74a224eFa`](https://testnet.tomoscan.io/address/0x46BAFFad74F525f5D3eaCE0e7D94A3A74a224eFa)) is used for swap.

---

# 🚀 How to run the project

## 📦 Prerequisites

- Node.js v18.18.2+
- npm v9.8.1+

## 🗿 Deploy frontend

### Step 1. Clone the repository

Note: the smart contracts and frontend are located in two repositories, please use the correct one.

```bash
git clone [GIT_REPOSITORY_URL]
```

### Step 2. Go to the project directory (frontend)

```bash
cd [Project Name]
```

### Step 3. Install dependencies

```bash
npm i -f
```

### Step 4. Run the project

```bash
npm run dev
```

<div style="color:orange; background-color:#333">
Note:
<br />
- The frontend connects to the smart contracts deployed on the TomoChain Testnet by us instead of yours.
  <br />
- The frontend also connects to our centralized backend for data fetching, e.g. vault chart.
  </div>

