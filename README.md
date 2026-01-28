# 📊 NFT Market Subgraph

本项目是基于 **The Graph Protocol** 的 Subgraph，用于索引和查询 **NFT Marketplace** 链上数据，  
支持高效获取 **NFT 列表、交易记录、用户行为** 等信息，替代前端频繁 RPC 调用。

---

## ✨ Features

- 📦 索引 NFT Mint / List / Buy 事件
- 🧾 查询 NFT 市场列表
- 👤 查询用户交易记录
- ⚡ 高性能 GraphQL 查询
- 🔗 支持 EVM 兼容链（Ethereum / Sepolia / Polygon 等）

---

## 🏗️ Tech Stack

- **The Graph**
- **Graph CLI**
- **AssemblyScript**
- **GraphQL**
- **Solidity Events**
- **IPFS**

---

## 📁 Project Structure

```text
subgraph/
├── abis/                   # 合约 ABI
│   ├── NFT.json
│   └── NFTMarket.json
├── schema.graphql          # GraphQL Schema
├── subgraph.yaml           # Subgraph 配置文件
├── src/
│   ├── nft.ts              # NFT 相关事件处理
│   ├── market.ts           # 市场事件处理
│   └── helpers.ts
├── generated/              # 自动生成代码
├── package.json
└── README.md
