# Technical Architecture

The Consent Project's technical framework synergizes blockchain's decentralized, immutable nature with the transformative power of artificial intelligence. The architecture supports diverse components including AI Agents (and their NFT representations), decentralized nodes, and AI inference mechanisms, underpinned by a robust tech stack facilitating functionality and interoperability.

## Tech Stack

The system's architecture is built on a curated tech stack designed for robustness, scalability, and user-friendliness:

- **Llama2**: Open-source Large Language Model (LLM) providing core AI capabilities. [Learn More](https://github.com/OpenAI/llama)
- **Ollama**: Tool simplifying Llama2 installation and deployment. [Placeholder for actual link]
- **LangChain**: Bridges LLMs with vector stores/APIs for complex AI functionalities. [Placeholder for actual link]
- **LangSmith Editor**: Low-code platform for building AI Agents on LangChain. [Placeholder for actual link]
- Additional components include SmartContractRank Algorithm, AgentRank Algorithm, PromptRank Algorithm, Filecoin, Akash Network, and Wallet Connect, each integral to the functioning and scalability of the Consent ecosystem.

## AI Agents

AI Agents are versatile, general-purpose artificial intelligences that bridge the gap between human language and Web3 interactions. By leveraging advanced LLM Transformer models, these agents interpret user or group intent and translate it into actionable code for autonomous smart contract execution. They serve as the intermediaries between human desires and on-chain execution, making Web3 activities more accessible and user-friendly.

Advantages of Personal AI Agents
Consent provides the foundational layer for AI Agents to navigate and operate seamlessly across the Web3 landscape. By aggregating and streamlining Web3 activities through user-centric AI Agents, Consent lowers entry barriers and offers a seamless interaction experience for both crypto natives and newcomers alike. This approach democratizes access to Web3 technologies, empowering users to harness the potential of decentralized systems with ease.

Technical Capabilities and Requirements
To effectively serve users within the Consent ecosystem, AI Agents should possess a wide range of capabilities, including:

Crypto knowledge integration
Data retrieval and analysis
Blockchain analysis and contract understanding
Code generation, execution, and debugging
News impact analysis
Agentic behavior and decision-making
Transaction construction and risk management
Open evaluations and performance metrics
These capabilities enable AI Agents to provide comprehensive support and guidance to users, ensuring a seamless and secure Web3 experience.

AI Agent Transaction Flow
The typical transaction flow involving an AI Agent within the Consent ecosystem follows these steps:

User Prompt: The interaction begins with a user inputting a request or query to the AI Agent, which utilizes a Language Learning Model (LLM) to process the input.
Web3 Intent Recognition: The LLM analyzes the user's input to determine if the intent involves Web3 technology and aligns the user's goals accordingly.
Recommendation via Promptrank: The AI Agent consults the Promptrank system to obtain transaction recommendations that align with the user's goals and preferences.
Transaction Construction: Based on the user's intent and the recommendations provided by Promptrank, the AI Agent constructs the appropriate transaction, including an estimate of the gas cost.
Proposal Generation: The AI Agent generates a proposal for the transaction and presents it to the user for review and approval.
Approval and Inquiry Process: User consent is mandatory for the transaction to proceed. If the user has any questions or concerns, the AI Agent engages in an interactive dialogue to address them.
Fund Verification: The AI Agent verifies that the user has sufficient funds to execute the transaction. If funds are insufficient, the user is prompted to increase their balance.
Contract Update and Execution: Once the user has approved the transaction and the necessary funds are available, the AI Agent executes the transaction via the Consent Promptrank contract.
Confirmation and Personalization: The system confirms that the executed transaction aligns with the user's intent and updates the user's personal Promptrank based on the interaction.
Gas Reconciliation: The gas consumed during the transaction is reconciled, ensuring transparency in cost management.
AI Training: Information gathered from the transaction is used to further train the LLM, enabling improved future interactions and recommendations.
User Reporting: Finally, the outcome of the transaction, along with any relevant details, is reported back to the user, completing the transaction flow.
AI Agent SDK: Empowering Decentralized Agent Development
The AI Agent SDK provides a robust foundation for developers to create decentralized AI Agents within the Consent ecosystem. This comprehensive suite of tools and functionalities enhances the ecosystem's capabilities while allowing developers the flexibility to choose their preferred implementations and frameworks.

The SDK is designed to seamlessly transition from a local operational environment to a decentralized architecture, enabling AI Agents to leverage decentralized resources as they become available. This adaptability ensures that AI Agents can evolve alongside the Consent network, harnessing the power of decentralized technologies.

Key components of the AI Agent SDK include:

Wallet Integration: The SDK seamlessly integrates with the user's wallet, serving as a secure gateway for transactions and agent interactions within the Consent network.
Risk Management & UI: The SDK provides robust risk management tools and a user-friendly interface, ensuring a safe and intuitive experience for users interacting with AI Agents.
Registration & Payments: The SDK handles agent registration and manages transaction and payment flows within the ecosystem, interfacing directly with Consent Smart Contracts for secure and decentralized financial operations.
Agent Framework Compatibility: The SDK supports various orchestration frameworks, such as langchain, AutoGPT, and Crew AI, allowing developers to utilize their preferred tools and leverage community-developed resources for agent creation.
Inter-Agent Communication: AI Agents developed using the SDK can operate independently or register with the Consent network to collaborate and provide network services. The SDK architecture facilitates seamless interaction with 3rd party APIs, RPC nodes, and other agents, fostering a cooperative and interconnected agent ecosystem.
Indexing & Model Repositories: The SDK offers structured repositories for Indexes and Models, providing efficient data organization and access, as well as hosting the machine learning algorithms that power AI Agents' intelligent decision-making capabilities.
Foundation for Development: The SDK serves as the bedrock for the entire system, offering essential "Storage" for secure data retention and "Compute" capacity to support the operations of AI Agents. Engineered for scalability, the SDK ensures that storage and compute services can progressively decentralize as the Consent network evolves.
NFT Representations of AI Agents
AI Agents within the Consent ecosystem can be optionally represented as Non-Fungible Tokens (NFTs), providing users with the flexibility to run them locally or mint them as NFTs for a distinct on-chain presence. These NFTs encapsulate the agent's capabilities, provenance, and operational parameters, ensuring interoperability and consistency across the ecosystem.

Minting an AI Agent as an NFT offers several benefits:

Verifiable History: NFT minting provides a tamper-proof record of the AI Agent's history, performance metrics, and usage data, ensuring transparency and accountability.
SmartRank Capability: The SmartRank system leverages Web3 datasets to evaluate and rank the effectiveness of AI Agents, ensuring optimal alignment with user requirements and preferences.
Unique Economic Model: AI Agents represented as NFTs enable a distinctive economic model for purchase, sale, and ownership transfer, reinforced by staking mechanisms that ensure transactional integrity.
Decentralized Ethos: NFT-based AI Agents maintain a decentralized ethos, with transparent code and dependencies, accessible through dedicated marketplaces that foster a vibrant and open ecosystem.
By offering NFT representations of AI Agents, Consent empowers users with greater control, flexibility, and transparency in their interactions with these intelligent entities, while also creating new opportunities for innovation and value creation within the Web3 landscape.

## Nodes & Decentralised AI Inference

The ecosystem leverages decentralized nodes for AI inference, providing computational resources critical for AI operations. This setup ensures the smooth functioning of AI Agents and supports decentralized model registries.

## Multi-Agent Systems

Multi-agent systems allow AI Agents to collaborate, share resources, and delegate tasks, enhancing the ecosystem's capabilities. This framework supports dynamic human-AI federations, promoting cooperative problem-solving and innovation.

## Consent Local

Consent Local is a desktop application that integrates AI capabilities with blockchain technology, offering services like secure communication, intelligent language processing, and blockchain transactions within a user-friendly interface.

## Identity & Attestations

Utilizing attestations, Consent verifies user identities and enables participation in decentralized governance. This system links attestations to Ethereum wallets, confirming user eligibility for governance activities.

## Data Commons

Data Commons is an initiative to create an open, accessible dataset repository. It supports AI development with high-quality, diverse datasets, reflecting the intricate details of different cultures and communities.

This summary of the "Technical Architecture" section of the yellow paper highlights the Consent Project's innovative integration of blockchain and AI technologies. Detailed information about each component can be found in their respective subsections within the full documentation.

[<< Previous](ecosystem.md) | [Next >>](tokenomics.md)
