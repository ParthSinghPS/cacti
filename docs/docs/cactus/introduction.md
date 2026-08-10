Welcome to Hyperledger Cacti documentation!
=========================================================================================================================

Hyperledger Cacti provides decentralized, secure, and adaptable integration between blockchain networks. It is a pluggable, enterprise-grade framework designed to transact across multiple distributed ledgers without introducing yet another competing blockchain.

**What is Cacti?**

Cacti is a unified interoperability framework that allows different distributed ledger technology (DLT) networks to interact with each other through atomic transactions and state commits. This eliminates information silos, increases network value, and abstracts the application layer from DLT protocol fragmentation.

The framework is composed of active subsystems designed to serve distinct operational roles:
*   **SATP Hermes:** Cross-chain asset transfer protocol implementation.
*   **Ledger Connectors:** Standardized interfaces for networks like Besu, Fabric, and Stellar.
*   **COPM:** Cross-chain operations and lifecycle management.
*   **Weaver:** Advanced interoperability framework and relay architecture.
*   **API Server:** Centralized orchestration for Cacti plugins.
*   **Core Libraries:** Foundational utilities and SDK components (common, core, core-api).

**Why use Cacti?**

*   **Future-Proof Integration:** Maximize flexibility through a highly modular, plug-in based architecture.
*   **Security by Default:** Enforce security policies seamlessly; vaults and credential management are built directly into the SDK.
*   **Credential Protection:** Ensure keys and sensitive credentials are never stored in source code, configuration files, or environment variables.
*   **Scalability:** Preserve native ledger features while enabling horizontal scalability across interconnected networks.
