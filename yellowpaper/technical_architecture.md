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

### Overview

The Consent ecosystem is evolving to enable individuals to contribute to the network by providing inference capabilities to SENT users through the operation of nodes. These nodes, which currently represent local Large Language Models (LLMs), will play a crucial role in the decentralized compute infrastructure of the Consent platform.

### Node Operation and Rewards

At present, operating a local inference node is optional, primarily benefiting users who wish to host AI Agents locally. However, as the system matures, node operation will become essential for those seeking to contribute to the Compute and Community functions within the Consent ecosystem.

In the initial stages, running a local inference node does not generate direct rewards. However, as the network evolves, nodes that actively contribute to Consent's Compute and Community functionalities will receive compensation. This incentivization mechanism aims to encourage participation and support the network's growth and utility expansion.

### Technical Requirements and Setup

To ensure optimal performance and reliability, running a Consent node requires the following hardware specifications:

- 64GB of storage
- GPU with at least 16GB of vRAM
- 16GB of system RAM
- CPU with a minimum of 4 cores

These requirements enable nodes to efficiently handle the demands of running LLMs and other resource-intensive tasks. Detailed setup instructions for Windows users are available on Consent's GitHub repository, with plans to develop a GUI-less node operation suitable for VPS hosting.

### Decentralized Compute Provision

As the Consent infrastructure continues to develop, the future of compute provision within the ecosystem is promising. The platform aims to enable decentralized compute contributions, collaborating with platforms like Akash to create a more flexible and expansive compute provision mechanism. This approach will leverage cloud infrastructure and focus on Inference Per Second (IPS) as a key performance metric.

### Decentralized Model Registry

Consent is establishing a decentralized model registry that allows compute providers to host model weights and definitions. This registry promotes a distributed file-sharing network, enhancing the ecosystem's robustness by leveraging the InterPlanetary File System (IPFS). The decentralized nature of the registry ensures resilience against potential adversarial actions, maintaining the unrestricted flow of AI within the Consent ecosystem.

### Transparency and Resource Utilization

To foster a fair and competitive marketplace for AI inference, Consent prioritizes transparency in router operation and compute resource utilization. By publicly tracking model popularity, compute providers can make informed decisions regarding model prioritization and pricing strategies.

The system measures session lengths and sets prices per unit of time, accommodating both predetermined and variable output lengths to cater to the diverse nature of AI applications. This pricing mechanism ensures that compute providers can optimize their offerings while maintaining a balanced and efficient marketplace.

### Compensation for Model and Agent Builders

Consent recognizes the value of contributions made by model and agent builders within the ecosystem. These creators receive compensation proportional to their contributions and the usage of their models, regardless of the compute provider hosting their work. This framework fosters a culture of innovation and development, incentivizing the creation of high-quality assets that drive the growth and utility of the Consent network.

### Balancing Innovation and Security

The Consent approach to decentralized AI inference strikes a balance between open innovation and secure, reliable computation. Local nodes are equipped with trusted smart contracts for standard operations, providing a secure foundation for AI execution. However, when engaging with third-party models, users are encouraged to exercise heightened responsibility and due diligence to ensure the integrity and safety of their interactions.

By fostering a decentralized compute infrastructure, transparent resource utilization, and a fair compensation model for contributors, Consent is creating a robust and sustainable ecosystem that empowers individuals to actively participate in the evolution of AI technology while maintaining the highest standards of security and reliability.

## Multi-Agent Systems

The multi-agent systems framework lies at the heart of the Consent project, serving as a catalyst for AI Agents to collaborate, cooperate, and achieve complex goals through collective intelligence. By establishing a decentralized, interoperable, and secure environment, the Consent ecosystem fosters the emergence of dynamic AI Agent federations capable of tackling intricate challenges and driving innovation across various domains.

### Seamless Collaboration and Task Delegation

The multi-agent systems framework empowers AI Agents to communicate, share resources, and delegate tasks among themselves, leveraging their individual capabilities to achieve collective objectives. This collaborative approach enables AI Agents to work together seamlessly, combining their unique strengths and expertise to solve problems that would be insurmountable for any single agent.

### Framework-Agnostic Architecture

Consent's multi-agent systems framework is designed to be framework-agnostic, accommodating a wide range of multi-agent frameworks such as AutoGen, AutoGPT, and CrewAI. This flexibility allows for the integration of diverse AI Agents, creating a versatile and interoperable ecosystem that supports Human-AI Federation (HAF) operations. By embracing a variety of frameworks, Consent ensures that developers can leverage the tools and methodologies that best suit their needs, while maintaining compatibility with the broader ecosystem.

### Key Components of the Multi-Agent System

The multi-agent system (MAS) within the Consent ecosystem comprises several essential components that work together to facilitate effective collaboration and coordination:

1. **Agent Collaboration Interface (ACI)**: The ACI serves as the primary channel for inter-agent and human-AI communication, interaction, task delegation, and resource sharing. It provides a standardized protocol for agents to exchange information, negotiate tasks, and coordinate their activities, ensuring smooth and efficient collaboration within the ecosystem.

2. **Decentralized Agent Registry (DAR)**: The DAR functions as a directory service for AI Agents, storing and managing essential metadata to streamline collaboration within HAFs. It maintains a decentralized record of agent capabilities, preferences, and performance metrics, enabling agents to discover and select suitable partners for specific tasks or projects.

3. **Shared Resource Pool (SRP)**: The SRP acts as a communal repository for AI Agents and humans to access and leverage shared computational resources, data, and storage. By pooling resources in a decentralized manner, the SRP optimizes resource utilization, reduces redundancy, and promotes cost-efficiency within the ecosystem.

4. **Agent Orchestration Engine (AOE)**: The AOE is responsible for optimizing the coordination of multi-agent and human-AI activities, ensuring effective task allocation and conflict resolution. It employs advanced algorithms and decision-making mechanisms to dynamically assign tasks, balance workloads, and resolve any conflicts that may arise during collaboration.

5. **Security and Trust Module (STM)**: The STM is a critical component that guarantees the security and integrity of human-AI interactions within the Consent ecosystem. It enforces robust authentication mechanisms, encrypts sensitive data, and maintains strict privacy controls to protect the interests of all participants.

### Phased Implementation Approach

The implementation of the multi-agent systems framework follows a phased approach to ensure a smooth and successful rollout:

1. **Infrastructure Setup**: The initial phase focuses on establishing the foundational components necessary to support multi-agent and human-AI interactions. This includes deploying the core infrastructure, setting up communication protocols, and configuring the necessary security measures.

2. **Agent and Human Integration**: The second phase involves developing AI Agents capable of engaging in the HAF ecosystem and integrating them with the shared resources and collaboration mechanisms. This phase also includes onboarding human participants and providing them with the tools and interfaces needed to interact with AI Agents effectively.

3. **System Integration and HAF Testing**: The third phase emphasizes the seamless integration of AI Agents and humans within the Consent ecosystem. Rigorous testing is conducted to ensure stable collaboration, identify potential issues, and optimize performance. This phase aims to create a cohesive and reliable environment for HAF operations.

4. **Security Enhancement and Performance Optimization**: The fourth phase prioritizes strengthening the security framework and optimizing system performance to support dynamic human-AI federations. Continuous monitoring, vulnerability assessments, and performance tuning are carried out to maintain the highest standards of security and efficiency.

5. **Community Engagement**: The final phase focuses on fostering adoption and integration through active community engagement. By gathering insights, feedback, and suggestions from the community, the Consent team can refine and expand the HAF ecosystem to better meet the needs and expectations of its users.

### Continuous Evolution and Improvement

As the implementation progresses, the Consent ecosystem will continue to evolve, enabling seamless integration of AI agents and humans, optimizing performance, and ensuring the highest standards of security and trust. The multi-agent systems framework will be continuously refined and updated based on real-world experiences, technological advancements, and community feedback.

By leveraging the power of collaborative AI through the multi-agent systems framework, the Consent ecosystem is poised to revolutionize the way humans and machines work together, unlocking new frontiers of innovation and problem-solving. As the ecosystem grows and matures, it will serve as a testament to the transformative potential of decentralized, interoperable, and secure multi-agent systems in shaping the future of human-AI collaboration.

## Consent Local

The most basic application is the local Consent applicatoin that can be installed on Mac, Linux or Windows systems, leveraging the Electron framework to seamlessly blend web-based interfaces and server-side functionalities. The application combines AI capabilities with blockchain technology, offering users a range of services, including secure communication, intelligent language processing, and robust blockchain transactions.

### Application Architecture

- **Electron Framework**: Consent Local is packaged and installed using Electron, enabling native application experiences on PC and Linux platforms through web technologies.
- **Large Language Model (LLM) Integration**: The core of Consent Local's AI capabilities lies in its integrated LLM and the corresponding API, which processes and generates human-like text. This setup allows for direct communication with the LLM, facilitating access to its sophisticated features.
- **Foundational Technologies**: Consent Local utilizes Chromium for web-based user interfaces and Node.js for backend operations, delivering a responsive and efficient user experience.
- **LangChain and Supportive Library**: LangChain, embedded within the application, links the LLM with vector stores and APIs, enhancing the language model's capabilities. A comprehensive library supports LangChain operations, ensuring smooth data handling and integration with third-party services.

### Functional Modules:

- **Vector Store**: Employs a storage solution for vectorized data, crucial for the LLM's information retrieval and processing tasks.
- **Private Chat UI**: Offers a user interface optimized for private messaging, leveraging the LLM for conversational AI interactions.
- **RPC (Remote Procedure Call)**: Facilitates networked server-side processes, ensuring seamless communication across the application.
- **Private Tools and Security Keys**: A suite of internal tools aids in application administration and development, while a dedicated security module manages cryptographic keys for encryption and digital signatures.
- **Prompt Rank and Smart Snap/Wallet**: Incorporates an algorithm to optimize user input prompts and a component that provides blockchain transaction capabilities, including a built-in wallet for digital asset management.

Consent Local represents a multifaceted desktop application that embodies the integration of AI with blockchain technology, setting a new standard for secure, intelligent, and user-centric blockchain interactions.

## Identity & Attestations

Consent leverages the Ethereum Attestation Service by Coinbase to issue verifiable, on-chain attestations linked to users' Ethereum (EVM) wallets. These attestations confirm a user's country of residence and are essential for participating in decentralized governance activities at various levels. Attestations are unique to an individual's Ethereum wallet and cannot be transferred between wallets.

### Verification Procedure

- **Initiating Verification**: Users verify their country of residence through Coinbase's verification portal, establishing their eligibility for participation in relevant governance activities.
- **Issuance of Attestation**: Successfully verified users receive an attestation bound to their specified Ethereum wallet address. Users can verify up to three wallet addresses via Coinbase.

### Engaging in Decentralized Governance

Verified attestations enable users to participate in governance mechanisms within their verified jurisdictions.

- **Regional-Level Participation**: Attested users can participate in regional governance initiatives by claiming citizenship through a designated smart contract and receiving a non-transferrable citizenship NFT. This NFT serves as a gateway to engaging in governance activities but cannot be sold or transferred outside the DAO contracts.
- **Sub-National Governance**: Future phases will introduce governance functionalities at state and local levels, requiring users to lock their citizenship NFTs within the corresponding jurisdiction's smart contracts to ensure commitment to the specific governance activities of that region.

The governance framework is designed to facilitate a transparent and inclusive voting process, supported by decentralized platforms like Tally.xyz. Efforts are underway to provide a user-friendly interface for streamlining the attestation process and enhancing the overall governance participation experience.

### Future Directions and Considerations

- **Diversification of Attestation Services**: Exploring alternatives to Coinbase for attestation issuance, such as Polygon ID or Worldcoin, to further decentralize the verification process.
- **Scalability and Performance**: As the user base expands, the system's scalability will be crucial, possibly requiring enhancements to accommodate a larger pool of participants.
- **Refinement of Governance Protocols**: Establishing clear, robust governance protocols at all jurisdictional levels will be key to maintaining a transparent and effective governance system.
- **Security Measures**: Continuous security assessments and updates are vital to safeguarding the integrity of the on-chain verification and decentralized governance framework.

This innovative approach to on-chain verification and decentralized governance marks a significant step towards more autonomous and representative decision-making processes within the Ethereum ecosystem.


## Data Commons

Data Commons is an initiative to create an open, accessible dataset repository. It supports AI development with high-quality, diverse datasets, reflecting the intricate details of different cultures and communities.

This summary of the "Technical Architecture" section of the yellow paper highlights the Consent Project's innovative integration of blockchain and AI technologies. Detailed information about each component can be found in their respective subsections within the full documentation.

[<< Previous](ecosystem.md) | [Next >>](tokenomics.md)
