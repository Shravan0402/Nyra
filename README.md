Nyra: Private Perpetual Market on Horizen 

Nyra is a private perpetual market built on the Horizen, designed to provide leveraged trading with robust privacy guarantees and minimal gas fees. By combining smart contracts with Trusted Execution Environments (TEEs), Nyra enables institutions and individuals to trade perpetual futures, options, and indices without exposing sensitive strategies, balances, or transaction details.

🚀 Vision

Nyra aims to create a privacy-first perpetual market where:

Traders can open leveraged positions on multiple assets with strong privacy.

Liquidity Providers (LPs) supply collateral and earn interest or fees.

Automated Liquidators maintain market health by closing undercollateralized positions securely and privately.

This design ensures a secure, private, and efficient perpetual trading system.

>> Problem Statement

Most decentralized perpetual markets today:

1) Operate on public blockchains, revealing transaction data and strategies.
2) Lacks institutional-grade privacy and scalability.
3) Struggle with advanced instruments like options due to computational overhead.

Nyra solves this by leveraging Horizen with TEEs to keep trading encrypted, private, and scalable.

🛠 Product Features
1. Private Perpetual Futures

Open leveraged long/short positions privately.
Interest rate model for borrowed capital (variable or fixed).
Funding rate ensures market balance between longs and shorts.
Automated liquidation keeps markets solvent.

2. Private Leveraged Indices

Create indices of multiple assets.
Trade indices with private leverage.
Private rebalancing without revealing composition.

3. Private Options Market

Perpetual call and put options with privacy guarantees.
Hedging strategies remain fully confidential.
Private liquidations if collateral falls short.

📐 Technical Architecture

Nyra combines Horizen smart contracts and Trusted Execution Environments (TEEs) for private trading.

Workflow (as per diagram):


<img width="1280" height="610" alt="image" src="https://github.com/user-attachments/assets/b6a28bc2-50c8-4869-adbc-a884e56d34da" />



1) Asset Locking: Users lock assets in a Horizen smart contract.

2)TEE Event Listening: The TEE listens to smart contract events and maintains a balance Merkle tree.

3) TEE Public Key Fetching: Users fetch the TEE public key for encrypting trade details.

4) Users send encrypted trade data to the Horizen smart contract.

5) Private Execution: Trade details are decrypted and executed inside the TEE, ensuring confidentiality.

This architecture guarantees that no sensitive data is visible on-chain while preserving trust via TEE attestation.

📊 Market Opportunity

Decentralized Derivatives Market Size (2025 projection): ~$30B+ TVL
Perpetual Futures Volume (2024): $2–3T annually in DeFi
Options Market Growth: Early but expanding rapidly, especially for institutional DeFi.

Nyra differentiates itself by combining privacy + perpetuals + scalability, addressing a gap in both retail and institutional DeFi.

🔑 Go-to-Market Strategy

Target crypto-native traders and institutions valuing privacy.
Leverage the Horizen ecosystem for initial liquidity and community support.
Create educational content on private derivatives.

Form strategic partnerships with liquidity providers and DeFi protocols.

📌 Roadmap

Phase 1: Smart contract deployment on Horizen testnet.

Phase 2: Integrate TEE-based encrypted trading.

Phase 3: Launch perpetual futures.

Phase 4: Add leveraged indices and perpetual options.

Phase 5: Mainnet launch with institutional onboarding.

🛡 Security & Privacy

TEE Attestation: Verifiable computation inside hardware enclaves.
Encrypted Trades: No strategy, position, or collateral data exposed on-chain.
Private Liquidations: Protects traders while ensuring system solvency.
