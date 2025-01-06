# Web3 Naming System (3NS)

3NS.link is an AI-first domain naming system that redefines web addressing by integrating AI-driven workflows into .Web3 domains, enabling autonomous agent workflows. The addressing system defines the future of the next-gen agentic web, where domains act as intelligent agents that negotiate, transact, and communicate on behalf of their owners.

Building on insights from decentralised systems like ENS (.eth) and BNS (.btc), 3NS transforms .Web3 domains into powerful, evolving assets. With on-chain intelligence merging, these agents can upgrade their skills, collaborate seamlessly across chains and adapt to new opportunities in a decentralised ecosystem.

3NS bridges traditional frameworks and facilitates the power of cutting-edge projects like LangChain and Google's GenKit, while also integrating on-chain frameworks such as Fetch.ai and Near. Through the portal website [YouLink.ai](https://YouLink.ai), users can effortlessly manage their domains. For those seeking simplicity, they can host their own personalized link aggregation website at https://<your-domainname>.3ns.link — a simple yet powerful site, akin to LinkTree, but enhanced with an AI chatbot powered by the .Web3 domain's digital intelligence.

Our vision is to build an AI-first internet where agents autonomously transact, provide advice, and even self-evolve through on-chain intelligence merging. With advanced on-chain functionality—such as managing wallets for transactions, versioning, and rollback to ensure security and reliability after merges—3NS empowers agents to operate seamlessly with a variety of visual AI workflows such as ActivePieces and N8N. Integration with open-source frameworks like Ollama and compatibility with OpenWebUI model files bring cutting-edge LLM capabilities into the protocol, turning this vision into a reality.

At the heart of 3NS is the Agent Domain Protocol (ADP)—a groundbreaking standard redefining digital addressing for the agentic web. Designed for real-world applications, 3NS equips agents with transactional wallets, on-chain intelligence merging with versioning and rollback and seamless integration with leading frontier LLMs via frameworks like Google GenKit. The incorporation of a wide variety of (ActivePieces, N8N and more) extends workflow capabilities, delivering unprecedented versatility for decentralized and autonomous operations.

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

## Introduction

The future of Web3 is intelligent, interoperable, and decentralized.

Agent Domain Protocol provides a foundation for creating and managing intelligent agents backed by .Web3 domains. With support for multichain deployment, AI-driven workflows, decentralized reputation systems, and tokenized governance, ADP empowers developers to build ecosystems where agents perform tasks, negotiate terms, and evolve over time.

---

## Top Features at a Glance:

1. **Domain Architecture**: The Domain Architecture of ADP redefines digital assets and utilises the full power of blockchain technology with advanced on-chain versioning, seamless intelligence merging,  on-chain rollback capabilities and integrated blockchain-based payments, enabling robust multichain interoperability and decentralized governance for dynamic ecosystems.
2. **Discovery and Reputation**: Advanced metadata indexing, automonous agent discovery and decentralized reputation scoring ensure trust and discoverability.  
3. **Agent Workflows**: AI-driven workflows with seamless multichain execution, supported by AI workflow-compatible syntax for drag-and-drop ease.  
4. **Agent Frameworks**: Supports a number of agent (decentralised like Fetch.ai, as well as, Google GenKit, Langchain, Autogen, CrewAI and more) frameworks is not opinionated on which one your agent chooses to utilise.   
5. **Cross-Chain Interoperability**: Native support for Ethereum, Moonbeam, Polygon, Fetch.ai, Near and more for seamless multichain operations.  

### Key repositories:

The ADP embeds powerful, autonomous intelligence directly into digital assets. This capability allows agents to independently negotiate, act, and optimize communication across ecosystems, from high-level AI reasoning to low-level binary protocols.  

To complement this open protocol, we've provided tools and libraries to simplify implementation:  
- **[3NS Agent Domain Protocol](https://github.com/3nsai/agent-domain-protocol)**: The core protocol and node implementaiton 
- **[3NS Smart Contracts](https://github.com/3nsai/3NS)**: A fork of ENS contracts designed to support ADP.  
- **[3NS Frontend dApp](https://github.com/3nsai/web3names-app)**: Manage .Web3 domains through a seamless UI.  
- **[3NS MetaMask Snap Plugin](https://github.com/3nsai/web3names-snap)**: Enable direct wallet-based domain interactions.  
- **[3NS Subgraph](https://github.com/3nsai/3ns-subgraph)**: Optimize domain discovery and indexing with our subgraph.
- **[3NS YouLink.ai Customer Portal](https://youlink.ai)**: Provides an easy to use portal website for customer management of .Web3 domains  

*Certain repositories, due to the transformative potential they hold, remain private as we refine and secure their capabilities. Among these are our autonomous WebRTC agent-to-agent communication binary protocol and the Collective DAO framework, both designed to completely change the way we currently utilise the web through decentralized autonomous agent collaboration. These innovations will be unveiled in alignment with community input and ethical considerations of their powerful impact.  

We actively collaborate with leading Web3 and AI open-source initiatives, including OpenWebUI, Ollama, Near, Solana, and Polkadot. For the full scope of integrations, refer to the **[Integrated and Compatible Projects](#integrated-and-compatible-projects)** section. If you would like to propose an integration or join our development ecosystem, we welcome your input.  

Our ongoing research also includes exploring DeFi innovations such as Beefy Protocol, further expanding the horizons of intelligent, autonomous agents in the Web3 landscape. Join us on [Discord](https://discord.com/invite/5rJgQTnV4s) to contribute and stay informed.*

---

## Quick Start

### Get Started in Minutes

1. **Clone the Repository**  
   ```bash
   git clone https://github.com/agent-domain-protocol/agent-domain-protocol.git
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

### Key Capabilities:

1. **Domain Architecture**: Tokenized, multichain-enabled domains supporting decentralized governance and collective decision-making. 
2. **Discovery and Reputation**: Advanced metadata indexing, autonomous agent discovery and decentralized reputation scoring ensure trust and discoverability.  
3. **Agent Workflows**: Visual editors we compatible with include ActivePieces and N8N syntax for drag-and-drop ease with 100s of powerful extensions.


## Domain Architecture

The **Domain Architecture** of ADP represents a significant leap forward in empowering digital assets across chains. Whether it is an NFT on an EVM, Solana, Ordinal on Stacks each domain is a tokenized decnetralised entity, embedded with a powerful ADP (defined in protocol_spec.json) that is stored decentrally and define its AI logic and workflow functionality within both decentralized and wider traditional web ecosystems.

1. **Multichain Registration**:  
   Domains can be registered across multiple blockchains, ensuring interoperability. Metadata stored with domains includes critical details like their registries, transaction hashes, and timestamps.  

   JSON implementation:  
   ```json
   "domain": {
       "name": "dietitianAI.web3",
       "did": "did:web3:dietitianAI.web3",
       "collective": {
           "token_shortcode": "DIET",
           "token_address": "0x324342432",
           "dao_governor": "0xew34234234"
       }
       "chains": [
            {
                "chain_id": 1284,
                "chain_name": "Moonbeam",
                "created_at": 1697472000,
                "ens_registry": "0xENSRegistryAddressOnMoonbeam",
                "resolver": "0xPublicResolverAddressOnMoonbeam",
                "subgraph_url": "https://subgraph.url/moonbeam",
                "transaction_hash": "0xTxHashOfBurnOnMoonbeam"
            },
            {
                "chain_id": 1,
                "chain_name": "Ethereum",
                "created_at": 1697572000,
                "ens_registry": "0xENSRegistryAddressOnEthereum",
                "resolver": "0xPublicResolverAddressOnEthereum",
                "subgraph_url": "https://subgraph.url/ethereum",
                "transaction_hash": "0xTxHashOfBurnOnEthereum"
            }
        ]
   }
   ```

2. **Tokenized Collectives**:  
   Domains support tokenization, enabling decentralized decision-making, staking, and value-sharing. Domains can act as collective DAOs, where governance is driven by holders of native tokens.

3. **Decentralized Governance**:  
   Updates and decision-making are handled on-chain through voting mechanisms, providing transparency and equity for domain stakeholders.

---

## Discovery and Reputation

Discoverability and trust are foundational to ADP, enabling agents to locate and assess each other effectively.

### Features:

1. **Agent Discovery**:  
   Metadata includes tags, workflow descriptors, and intent definitions. These elements are indexed to allow efficient search and discovery.  

   Example:  
   ```json
   "discovery": {
       "tags": ["dietitian", "nutrition"],
       "workflow_descriptors": {
           "fetch_nutrition_data": "Retrieve detailed nutrition data from trusted sources."
       }
   }
   ```

2. **Reputation Framework**:  
   The protocol integrates decentralized identity (DID) with verifiable credentials, allowing agents to build trust. Reputation scores are calculated based on reviews, performance, and more.  

---

## Workflows

ADP workflows are the beating heart of agent automation, enabling tasks to execute seamlessly across chains. There is full support for the visual editor including drag-and-drop ease. We wanted to make sure non-technical users could leverage the full capabilities of the ADP without having to program. Using ActivePieces-compatible syntax, workflows are designed for flexibility and simplicity. Our belief is more simple time-tested ETL based workflows work much better for most business tasks. So we focused on developing multiple framework support such as N8N and activepieces compatibility which offers a variety of off-the-shelf plugins from Outlook to Asana functionality incombination with several of our own plugins that work seamlessless with decentralised projects and autonomous agent innovation. Our code serves as a basis for custom components across these workflow frameworks. We believe this is fundamental to how the evolution of decentralised web will evolve.

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






---


## Integrated and Compatible Projects
The following have either integrated already or are in *evaluation

### AI Frameworks and Infrastructure

| **Project**       | **Description**                                                                 | **Website**                              | **GitHub**                                   |
|--------------------|---------------------------------------------------------------------------------|------------------------------------------|----------------------------------------------|
| **OpenWebUI**      | Full support for importing and exporting prompts and model files to/from 3NS.   | [Website](https://openwebui.com/)        | [GitHub](https://github.com/open-webui)      |
| **Ollama**         | Host your own Ollama server for complete control over models and data.          | [Website](https://ollama.com/)           | [GitHub](https://github.com/ollama)          |
| **BitTensor**      | *Evaluating integration: Decentralized digital commodities                         | [Website](https://bittensor.org/)        | [GitHub](https://github.com/opentensor)      |
| **Google (GenKit)**| Integration with GenKit for AI workflows.                                       | [Website](https://firebase.google.com/)  | [GitHub](https://github.com/firebase)        |
| **DecentralML**    | Polkadot substrate pallet for decentralized task execution using Docker.        | [Website](http://www.decentralml.io/)    | [GitHub](https://github.com/ashleyturing/decentralml)                              |
| **Akash Network**  | *Evaluating integration: Decentralized compute marketplace for hosting docker (useful for ADP workflow (N8N, ActivePieces) hosting).          | [Website](https://akash.network/)        | [GitHub](https://github.com/ovrclk/akash)    |
| **0g.ai**          | *Evaluating integration: Operating system for decentralized compute solutions (useful for ADP workflow hosting).                           | [Website](https://0g.ai/)                | -                              |
| **HyperCycle**     | *Evaluating integration: Decentralized AI infrastructure for docker (useful for ADP hosting).                   | [Website](https://www.hypercycle.ai/)    | [GitHub](https://github.com/singnet)         |
| **Space and Time** | *Evaluating integration: Decentralized data warehouse built for blockchain indexing and agent smart contracts (useful for DeFi).                  | [Website](https://www.spaceandtime.io/)  | -                               |

---

### .Web3 AI Domains can be traded on or deployment is in *progress

| **Project**            | **Description**                                            | **Website**                          | **GitHub**                                   |
|-------------------------|-----------------------------------------------------------|--------------------------------------|----------------------------------------------|
| **Moonbeam Polkadot**   | .Web3 domains support and can be traded on Moonbeam (EVM for Polkadot ecosystem).      | [Website](https://moonbeam.network/) | [GitHub](https://github.com/moonbeam)        |
| **Stacks Bitcoin**      | Layer for Bitcoin.            | [Website](https://www.stacks.co/)    | [GitHub](https://github.com/stacks-network)  |
| **Solana**              | *.Web3 domains are compatible and can be deployed on Solana.    | [Website](https://solana.com/)       | [GitHub](https://solana.com/github)          |
| **Polygon**             | .Web3 domains support and can be traded on Polygon.        | [Website](https://polygon.technology/)| [GitHub](https://github.com/0xpolygon)       |
| **Base**                | .Web3 domains support and can be traded on Base.   | [Website](https://www.base.org/)     | [GitHub](https://github.com/base-org)        |
| **Ethereum**                | *.Web3 domains are compatible and can be deployed on Ethereum.   | [Website](https://www.ethereum.org/)     | [GitHub](https://github.com/ethereum)        |
---

### Compatible Agent Frameworks

| **Project**            | **Description**                                              | **Website**                          | **GitHub**                                   |
|-------------------------|-------------------------------------------------------------|--------------------------------------|----------------------------------------------|
| **Fetch.ai**            | *Evaluating integration: Decentralized framework for building autonomous agents.      | [Website](https://fetch.ai/)         | [GitHub](https://github.com/fetchai)         |
| **SingularityNET**      | *Evaluating integration: Works with Fetch.      | [Website](https://singularitynet.io/)| [GitHub](https://github.com/singnet)         |
| **Ocean Protocol**      | *Evaluating integration: Works with Fetch.       | [Website](https://oceanprotocol.com/)| [GitHub](https://github.com/oceanprotocol)   |
| **LangChain**           | Integrated Framework for creating AI-powered workflows and agents.     | [Website](https://langchain.com/)    | [GitHub](https://github.com/langchain-ai)    |
| **Near Protocol**       | *Evaluating integration: Intents and chain abstraction.  | [Website](https://near.org/)         | [GitHub](https://github.com/near)           |
| **Theoriq.ai**          | *Evaluating integration: Awaiting testnet - AI-driven agent collaboration.            | [Website](https://www.theoriq.ai/)   | [GitHub](https://github.com/chain-ml/theoriq-agent-sdk)                              |
| **Wire.Network**        | *Evaluating integration: Decentralized infrastructure for agent workflows.  | [Website](https://www.wire.network/) | [GitHub](https://github.com/Wire-Network) |

---


## Contributing

We welcome contributions! See [CONTRIBUTING.md](CONTRIBUTING.md) for details.

---

## License

This project is licensed under the [MIT License](LICENSE).

