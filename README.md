# Introduction

## What is Capx Cloud?

Capx Cloud is a decentralized infrastructure network, designed to support the deployment and scaling of tokenized AI Agent Applications. Leveraging Symbiotic's robust operator framework, Capx Cloud provides scalable, cost-effective, and secure compute solutions for AI workloads while ensuring crypto-economic security through operator staking and decentralized governance.

![Overview of Capx AI Infrastructure](Capx-Ai-Infrastructure.png)

## Why Capx Cloud?

As AI applications proliferate, their compute and hosting demands continue to grow, often concentrating power in large, centralized cloud providers. This raises concerns around trust, data sovereignty, cost, and resilience. Blockchain and decentralized finance (DeFi) have demonstrated how trust and incentives can be algorithmically distributed. The emerging frontier is to merge AI workloads with decentralized infrastructure—ensuring that these AI products are not only scalable and high-performance, but also trust-minimized, community-governed, and economically aligned with stakeholders.

### The Need for Trust-Minimized Infrastructure
AI applications vary widely in their computational requirements. While some advanced machine learning tasks (such as training large models or running complex vision or generative pipelines) may benefit from GPU-accelerated computations, many popular applications rely on external LLM APIs (e.g., ChatGPT or Gemini) and thus need only moderate CPU and memory resources. By supporting a diverse range of hardware capabilities, Capx Cloud ensures that decentralized operators can serve a broad spectrum of AI products—from lightweight inference layers that just need CPU cycles and memory to GPU-intensive processing pipelines. This flexibility allows developers to choose the right operator for their application’s unique performance and cost profile, all within a trust-minimized, on-chain governed ecosystem.

Capx Cloud offers a compelling alternative to traditional, centralized cloud providers for AI workloads. By integrating with the Symbiotic protocol, Capx Cloud enables operators to restake collateral, ensuring strong economic incentives for honesty, high uptime, and reliable performance. Developers benefit from a streamlined deployment pipeline that abstracts away complex resource provisioning, while cryptographic proofs and on-chain governance mechanisms ensure transparency, security, and continuous improvement.

# Capx Cloud

Capx Cloud forms the core of the decentralized compute layer, enabling the deployment and execution of AI agents in a secure, efficient, and scalable manner. Capx Cloud merges the power of decentralized infrastructure with the growing demands of AI workloads to create a trust-minimized, globally accessible platform for running intelligent applications.

## **Capx Cloud Architecture**

![Capx Cloud Architecture](Capx-Cloud-Arch.png)

The architecture of Capx Cloud is designed to facilitate the seamless deployment, execution, and management of AI agents. Here's a breakdown:

1. **Agent Deployment:** Developers deploy AI agents to the Capx Cloud network through the Capx SuperApp or directly via smart contracts on the Capx Chain.
2. **Resource Allocation:** The Capx Cloud protocol matches AI agent resource requirements with available operator resources.
3. **Operator Execution:** Operators execute AI agent workloads on their infrastructure, providing attestations of their work.
4. **Attestation and Aggregation:** Attestations are aggregated and validated to ensure operator performance and availability.
5. **Reward Distribution:** Operators receive rewards in $CAPX tokens based on their contributions and performance.
6. **Restaking Integration:** Symbiotic manages the staking and slashing of operator collateral, ensuring network security.
7. **Governance:** $CAPX token holders participate in the governance of the Capx Cloud protocol, influencing its development and operation.

## Vision and Goals

Capx Cloud seeks to provide:
*   **Decentralized Infrastructure at Scale:** Combining cloud-grade performance with trust-minimized provisioning.
*   **Developer-Friendly Experience:** Seamless deployments using familiar languages and frameworks, abstracting away complexity.
*   **Tokenized Ownership and Governance:** AI products become on-chain assets governed by stakeholders, aligning incentives and distributing rewards.
*   **Incentive-Backed Reliability:** Operators are economically motivated to maintain uptime and honesty, enforced by staking and slashing contracts onchain.

## Foundational Concepts

### Tokenized AI Agents and On-Chain Compute Coordination
The core idea behind Capx Cloud is to represent **AI applications as tokenized, on-chain entities.** By treating each AI agent as a set of tradeable tokens, developers and users can collectively own and govern the application’s fate. This tokenization enables fractional ownership, allowing a broad community—ranging from early adopters and investors to end-users and developers—to share in the risks and rewards of a particular AI service onchain. Moreover, it sets the stage for **decentralized decision-making, as token holders can propose changes, vote on key parameters, and directly influence the application’s evolution.**

Under the hood, **AI agents rely on a decentralized marketplace of operators.** Rather than anchoring all workloads to a single cloud provider, Capx Cloud introduces competition and redundancy. Operators bid for the right to host AI workloads, and their performance is continuously measured and verified. Over time, this **competitive environment drives higher quality of service, better uptime, and more cost-efficient deployment,** all orchestrated by smart contracts that ensure fairness and transparency.

*   **Fractional Ownership:** Multiple stakeholders can own tokens representing shares in the AI application, distributing both financial exposure and potential profit.
*   **Collective Governance:** Token holders collectively shape the application’s direction, feature set, and deployment configurations.
*   **Decentralized Marketplace of Operators:** Instead of relying on one trusted party, the system enables many operators to compete, improving resilience and driving down costs.
*   **On-Chain Coordination:** Smart contracts manage deployment assignments, track operator reputation, and enforce governance decisions, removing reliance on centralized intermediaries.

### Restaking and Shared Security
One of the key innovations in this architecture is the concept of restaking. In traditional models, each new network or use case requires fresh collateral from participants. Restaking changes this dynamic. By allowing already-staked assets to serve multiple purposes, **operators and stakers can amplify their economic footprint,** ultimately bringing more security to the ecosystem without linearly increasing costs.

Restaking aligns incentives more directly than ever before. With collateral on the line, operators must maintain high standards of reliability, honesty, and performance. **Any misbehavior—such as prolonged downtime, tampering with deployed applications, or failing to produce proofs of correct execution—risks losing staked assets.** This direct financial stake in the outcome ensures that operators remain motivated to provide optimal service.

*   **Capital Efficiency:** Restaking enables stakers and operators to deploy their economic capital more effectively, supporting multiple networks (including Capx Cloud) without sourcing new funds for each.
*   **Incentive Alignment:** Operators, by having “skin in the game,” are financially incentivized to maintain optimal performance. Poor service or malicious actions lead to immediate, on-chain penalties (slashing).
*   **Robust Security Model:** With multiple networks sharing security from a common pool of staked collateral, the overall ecosystem becomes more resilient. As more participants join, the collective security strengthens, reducing vulnerability to attacks or collusion.

## **Symbiotic Protocol**

To support the economic backbone of this decentralized ecosystem, **Capx Cloud integrates with Symbiotic—a shared security protocol designed to provide flexible (re)staking infrastructure.** Symbiotic simplifies the sourcing of economic security for networks like Capx Cloud by offering a framework where operators and stakers can commit collateral to multiple networks at once, thereby increasing overall capital efficiency.

At its core, Symbiotic streamlines the process of operator registration, stake management, and slashing adjudication. Instead of custom solutions for each network, **Symbiotic presents a universal, permissionless layer where participants can freely allocate capital, register as operators, and interact with multiple networks in parallel.**

*   **(Re)Staking Infrastructure:** Symbiotic supports repurposing of staked assets (e.g., from Ethereum validators) for additional use cases, like providing security to Capx Cloud.
*   **Vaults and Operator Registries:** Operators register once in Symbiotic’s OperatorRegistry and can then serve multiple networks. Vaults serve as stake pools, holding collateral and enforcing withdrawal and epoch rules.
*   **Resolvers for Dispute Resolution:** Should conflicts arise over slashing incidents, resolvers—neutral arbitration entities—step in to ensure fairness, reducing the likelihood of arbitrary or malicious penalties.

## Capx Cloud System 

This section delves deeper into the Capx Cloud system architecture, outlining the crucial actors and their interactions within the infrastructure.

![Capx Cloud System](Capx-Cloud-System.png)

**Key Actors**

1. **Users:**
    *   **Agent Users:** These users interact with AI agents through the Capx SuperApp. They are the primary consumers of the AI services provided on the platform.
    *   **Token Holders:** These users hold and utilize $CAPX tokens, participating in the economic and governance aspects of the Capx ecosystem.
2. **Developers:**
    *   **Agent Developers:** These developers are responsible for creating and deploying the AI agents that power the Capx Cloud.
    *   **Application Developers:** They build applications that leverage the Capx SuperApp and integrate with the deployed AI agents.
3. **Operators:**
    *   **Compute Provider:** Operators contribute essential computing resources, such as CPU, memory, and GPU, to the network. They are responsible for executing the AI agent workloads.
    *   **Restaker:** Operators also function as restakers, staking collateral through the Symbiotic protocol to ensure the security and trustworthiness of the network.
4. **Capx SuperApp:** The SuperApp acts as the central interface for users to interact with AI Agents as well as trade & own the tokenized AI Agents & Apps.
5. **Capx Chain:** This is the foundational blockchain infrastructure that enables secure and transparent transactions within the Capx ecosystem. It handles key operations like AI agent tokenisation, resource allocation, and reward distribution.
6. **Symbiotic:** Symbiotic is the restaking protocol integrated into Capx Cloud. It plays a critical role in maintaining network security by managing the (re)staking and potential slashing of operator collateral.

**Interactions**

*   **User-SuperApp Interaction:** Users interact with the Capx SuperApp to access and utilize AI agents.
*   **Developer-SuperApp/Capx Cloud Interaction:** Developers use the SuperApp or interact directly with the Capx Cloud to deploy their AI agents.
*   **Operator-Network Interaction:** Operators provide compute resources to the network and execute AI agent workloads.
*   **Operator-Symbiotic Interaction:** Operators engage with Symbiotic for restaking purposes, contributing to network security.
*   **SuperApp-Chain Interaction:** The Capx SuperApp interacts with the Capx Chain to facilitate AI agent tokenisation and onchain ownership-trading transactions.
*   **Chain-Ecosystem Interaction:** The Capx Chain serves as the backbone for all on-chain transactions and interactions within the Capx ecosystem.


# Roles & Responsibilities within the Capx Cloud Ecosystem

Capx Cloud is designed as an interconnected ecosystem where each role—Performer Nodes, Attestor Nodes, Operators, Delegators, and Resolvers—collaborates to provide reliable, secure, and efficient decentralized services. These roles are interdependent, with each participant contributing unique expertise to maintain network integrity and scalability.

## **Performer Node**

Performer Nodes are the engine of the Capx Cloud network, responsible for executing the core AI computations and tasks submitted by users. These nodes form the foundation of the decentralized infrastructure, ensuring tasks are processed efficiently, reliably, and at scale. Their role is vital for supporting AI-driven applications and other AI-based operations.

When a user submits a task—such as running an AI model, processing data, or performing complex calculations—the Performer Node undertakes the execution.

**Key Responsibilities:**

*   **Task Execution:** Upon receiving a task, the Performer Node utilizes its computational resources to process and complete the task efficiently.
*   **Proof of Task Generation:** After completing the task, the node generates a cryptographic proof, known as the Proof of Task, which serves as verifiable evidence of the task's execution.
*   **Result Dissemination:** The Performer Node then broadcasts the task results and the Proof of Task to the network, ensuring transparency and enabling subsequent validation.

**Importance in the Network:**

The efficiency and reliability of Performer Nodes are crucial, as they directly impact the network's ability to handle complex computations and deliver timely results to users. Performer Nodes regularly communicate with other components in the Capx Cloud, particularly Attestor Nodes, to ensure the integrity of their output. This continuous verification cycle establishes trust and minimizes the risk of fraudulent or incorrect task execution.

## **Attestor Node**

Attestor Nodes serve as the Capx Cloud’s quality assurance mechanism, validating tasks executed by Performer Nodes. Their primary objective is to ensure that all computations meet the network’s predefined standards for accuracy and reliability. This process strengthens trust and prevents tampering or dishonesty within the network.

**Key Responsibilities:**

*   **Validation Process:** Upon receiving the Proof of Task and associated results from a Performer Node, Attestor Nodes independently verify the accuracy and legitimacy of the execution.
*   **Consensus Mechanism:** Attestor Nodes participate in a consensus protocol, where they cast votes on the validity of each task. A task is approved if a supermajority (typically two-thirds) of Attestor Nodes confirm its validity.
*   **Enforcement of Penalties:** If a significant portion of Attestor Nodes (e.g., more than one-third) deems a task invalid, the network enforces penalties, such as slashing, against the responsible Performer Node to uphold network integrity.

**Importance in the Network:**

By validating tasks, Attestor Nodes ensure that only accurate and trustworthy computations are accepted, preventing fraudulent or erroneous outputs. Their role is essential for maintaining the network's credibility and ensuring that users can trust the results produced by the Capx Cloud.

## **Operator**

Operators are the custodians of the Capx Cloud network, managing the infrastructure that keeps everything running smoothly Their responsibilities extend across multiple layers of the network, ensuring the stability, scalability, and security of decentralized services. Operators play a crucial role in maintaining node uptime, managing upgrades, and safeguarding the infrastructure against threats.

**Operators who have opted-in into the Capx Cloud Network**

*   P2P
*   Luganodes
*   Kiln
*   PierTwo
*   Alchemy
*   Node Monster
*   Certik
*   Block & Bones
*   and many more..

**Key Responsibilities:**

*   **Infrastructure Management:** Operators oversee the setup, configuration, and maintenance of nodes, ensuring optimal performance and minimal downtime.
*   **Security Enforcement:** They implement security protocols to protect nodes from threats and ensure data integrity.
*   **Governance Participation:** Operators engage in the network's governance processes, contributing to decision-making on protocol upgrades, policy changes, and other critical matters.

Through the Symbiotic protocol, operators can accept stakes from diverse partners via unified vaults. This system enables operators to run a single infrastructure for multiple stakeholders without the complexity of separate setups. By doing so, operators improve resource efficiency while broadening access to network services for stakers and users alike.

## **Delegator**

Delegators are crucial contributors to the Capx Cloud’s security and stability. Rather than directly operating nodes, they delegate their staked assets to trusted operators, thereby supporting network infrastructure while earning rewards for their participation. Delegators play a vital role in decentralizing the network by distributing stake among various operators.

**Key Responsibilities:**

*   **Operator Selection:** Delegators carefully choose reputable Operators based on performance metrics, reliability, and trustworthiness.
*   **Stake Delegation:** They allocate their assets to selected Operators, thereby enhancing the Operators' capacity to manage more tasks and secure the network.
*   **Governance Participation:** Delegators engage in voting processes, influencing decisions on network policies, upgrades, and other governance matters.

**Importance in the Network:**

Delegation lowers the barrier to entry for those who wish to support decentralized infrastructure without managing technical operations. Through their contributions, Delegators enhance the network’s economic security, allowing it to scale while maintaining decentralization and resilience.

## **Resolvers**

Resolvers are specialized entities responsible for resolving disputes within the Capx Cloud network. They serve as arbiters, handling disputes and overseeing slashing incidents—penalties imposed for malicious or faulty behavior when a Performer Node fails to meet task execution standards. Resolvers provide an impartial mechanism for reviewing these incidents to ensure that penalties are applied fairly and in accordance with network policies.

**Key Responsibilities:**

*   **Dispute Resolution:** Resolvers review conflicts arising from task executions, validations, or other network activities, providing impartial judgments.
*   **Slashing Oversight:** They assess slashing incidents to confirm that penalties are warranted and executed fairly.
*   **Policy Enforcement:** Resolvers ensure that all actions taken within the network adhere to established rules and guidelines, maintaining fairness and transparency.

Resolvers operate under predefined agreements between networks and vaults. Depending on the network’s risk tolerance, multiple resolvers may collaborate to reach a consensus before approving or vetoing a slashing event. This arrangement provides additional security guarantees for stakeholders, as decisions are made transparently and through a decentralized process.

**Importance in the Network:**

By providing a structured mechanism for dispute resolution and penalty enforcement, Resolvers uphold the network. Allowing for flexible, scalable governance structures tailored to the needs of different protocols within the Capx Cloud ecosystem.


# Getting Started

As of today, AI agent deployment on Capx Cloud is still under Mainnet-Beta, and therefore permissioned. With around 15 AI Agent Apps LIVE on Capx Cloud, if you wish to leverage Capx Cloud to test and deploy your AI Agent on our infrastructure kindly get in touch with the team by filling the following form. 

[Google Form](https://forms.gle/KM28h9jkQ6xoiWAFA)
