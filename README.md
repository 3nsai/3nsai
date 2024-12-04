# 🚀 Welcome to Agent Domain Protocol!

## Vision

We believe that **websites as they are now will become a thing of the past**. The Agent Domain Protocol enables **AI agents** to interact through your **.Web3 domain**, acting on your behalf to negotiate, communicate, transact, and issue digital assets. Imagine your AI, trained based on your preferences, automatically engaging with other domains, finalizing deals, or executing transactions on-chain—all while you focus on what matters most.

### 🔥 Intelligence Burned On-Chain: A Genuine, Tradable Asset

Unlike traditional domain services like ENS, BNS, or **.eth**, **3NS** integrates blockchain to **burn your intelligence on-chain**—embedding N8N-powered workflows and AI logic into your **.Web3 domain**. 

By using blockchain as a foundation, **intelligence merging, on-chain versioning, and rollback functionalities** become possible. Imagine your AI agent starts behaving unpredictably post-merge—blockchain auditing and rollback enable you to revert to the prior state with full accountability. Additionally, agents can autonomously **negotiate and pay** for services on your behalf, creating a frictionless, intelligent digital economy.

---

## 🌟 .Web3 Supports

### 1. **Web2 and Web3 Aggregation**
Your **.Web3 domain** combines Web2 and Web3, aggregating your social media, websites, and decentralized features like wallet addresses and smart contracts. It acts as a hub for both centralized and decentralized digital presence.

### 2. **True Ownership & Control**
Your **.Web3 domain** is decentralized and entirely under your control. It transcends traditional websites, serving as your unique digital identity.

### 3. **AI-Powered Agents**
Integrate advanced AI models to automate your digital presence. AI agents tied to your **.Web3 domain** can assist visitors, promote content, handle transactions, and even negotiate contracts.

### 4. **Decentralized Agent Management**
Choose from various AI models—**OpenAI**, **Ollama**, **OpenWebUI**, or decentralized frameworks like **Fetch.ai**—to avoid lock-in and maintain control over your AI's evolution.

---

## Agent Domain Protocol (ADP)

Agent Domain Protocol (ADP) is an open-source standard for enabling AI-driven intelligence, discovery, and cross-chain workflows for .Web3 domains. It bridges the gap between decentralized naming systems and intelligent agents, providing a unified way to define, discover, and execute agent-based workflows.

---

## Table of Contents

1. [Introduction](#introduction)  
2. [Top Features](#top-features-at-a-glance)  
3. [Quick Start](#quick-start)  
4. [Domain Architecture](#domain-architecture)  
5. [Discovery and Reputation](#discovery-and-reputation)  
6. [Workflows](#workflows)  
7. [Workflow Syntax](#workflow-syntax)  
8. [Example Workflows](#example-workflows)  
9. [Integrated and Compatible Projects](#integrated-and-compatible-projects)  
10. [Contributing](#contributing)  
11. [License](#license)  

---

## Top Features at a Glance:

1. **Domain Architecture**: Tokenized, multichain-enabled domains with advanced on-chain versioning, seamless intelligence merging, rollback capabilities, and blockchain-based payments.  
2. **Discovery and Reputation**: Advanced metadata indexing, autonomous agent discovery, and decentralized reputation scoring.  
3. **Agent Workflows**: AI-driven workflows with seamless multichain execution using N8N-compatible syntax.  
4. **Agent Frameworks**: Supports frameworks like **Fetch.ai**, **Langchain**, **Autogen**, and more.  
5. **Cross-Chain Interoperability**: Native support for Ethereum, Moonbeam, Polygon, Fetch.ai, Near, and others.  

---

## Quick Start

### Get Started in Minutes

1. **Clone the Repository**  
   ```bash
   git clone https://github.com/3nsai/agent-domain-protocol.git
   cd agent-domain-protocol
   ```

2. **Install Dependencies**  
   ```bash
   npm install
   ```

3. **Run Local Environment**  
   ```bash
   npm start
   ```

---

## Domain Architecture

### Transforming Digital Assets

The **Domain Architecture** of ADP represents a significant leap forward in empowering digital assets across chains. Each domain is a tokenized, decentralized entity, embedded with a powerful ADP specification that defines its logic and functionality.  

1. **Multichain Registration**: Domains can be registered across multiple blockchains, ensuring interoperability and storing metadata like registries, transaction hashes, and timestamps.  
2. **Tokenized Collectives**: Domains support tokenization for decentralized decision-making, staking, and value-sharing.  
3. **Versioning, Merge, and Rollback**: Safeguard workflows with on-chain versioning, merging capabilities for combining intelligences, and blockchain-audited rollback functions.  
4. **Blockchain-Based Payments**: Agents can autonomously manage payments and escrow services, ensuring secure and seamless transactions.  

---

## Discovery and Reputation

ADP includes advanced discovery tools and decentralized reputation systems:  

1. **Agent Discovery**: Metadata like tags, workflow descriptors, and intent definitions enable efficient agent search.  
2. **Reputation Framework**: DID-based identities, verifiable credentials, and reputation scoring build trust among agents and users.  

---

## Workflows

ADP workflows enable agents to execute tasks seamlessly across chains. Fully compatible with N8N, ADP provides a drag-and-drop interface for creating workflows.  

### Example Nodes:

#### Merge Workflow Node:
```json
{
  "type": "web3-nodes-base.merge",
  "parameters": {
    "merge_policy": "destination_priority",
    "source_domain": "blockchain://veganchef.web3",
    "destination_domain": "blockchain://dietitianAI.web3"
  },
  "position": [520, 300]
}
```

#### Payment Workflow Node:
```json
{
  "type": "web3-nodes-base.payments",
  "parameters": {
    "escrow_uri": "blockchain://escrow.fetch.ai/escrow123",
    "supported_methods": ["USDT", "FET", "NEAR"],
    "base_fee": "0.01 FET",
    "variable_fee": "0.005% of task value"
  },
  "position": [720, 400]
}
```

---

## Example Workflows

### Multistep Workflow with Decentralized Functionality

1. **Fetch Data**: Collect input from trusted sources.  
2. **Process Data**: Apply AI transformations.  
3. **Store Output**: Commit results on-chain.  

```json
{
  "nodes": [
    {
      "type": "n8n-nodes-base.httpRequest",
      "parameters": {
        "url": "https://api.fetch.ai/data"
      }
    },
    {
      "type": "n8n-nodes-base.function",
      "parameters": {
        "code": "return items.map(item => item.json.data);"
      }
    }
  ]
}
```

---

## Integrated and Compatible Projects

| **Project**       | **Description**                                           | **Website**                                | **GitHub**                                   |
|--------------------|-----------------------------------------------------------|--------------------------------------------|----------------------------------------------|
| **OpenWebUI**      | Import/export prompts and models seamlessly.              | [Website](https://openwebui.com/)          | [GitHub](https://github.com/open-webui)      |
| **Ollama**         | Open-source model hosting for agents.                     | [Website](https://ollama.com/)             | [GitHub](https://github.com/ollama)          |
| **Moonbeam**       | EVM-compatible blockchain for multichain deployment.      | [Website](https://moonbeam.network/)       | [GitHub](https://github.com/moonbeam)        |
| **Fetch.ai**       | Decentralized agent framework for autonomous systems.     | [Website](https://fetch.ai/)               | [GitHub](https://github.com/fetchai)         |
| **SingularityNET** | Decentralized AI platform for agentic frameworks.         | [Website](https://singularitynet.io/)      | [GitHub](https://github.com/singnet)         |

---

## Contributing

We welcome contributions! See [CONTRIBUTING.md](CONTRIBUTING.md) for details.

---

## License

This project is licensed under the [MIT License](LICENSE).
```
