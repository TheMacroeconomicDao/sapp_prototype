# sapp_prototype
Technical Specification: P2P Web Messenger in Java (Backend Emphasis)

Overview

Project Name: P2P Web Messenger

Technologies: Java, Redis, IPFS, MetaMask

Architecture: P2P with a server-side component for connection facilitation and data exchange.

Objective

Design and develop a secure, robust P2P messenger leveraging encryption technologies and the capabilities of the IPFS network.

Backend Functionalities in Java

a. Authentication:

User verification and authentication through MetaMask keys.
Endpoints for user sign-up and login.
b. Connection Management:

Facilitation of P2P connections among users.
Websocket orchestration for real-time communication.
c. Message Handling:

Message receipt, encryption, and forwarding.
Message storage in IPFS and generation of relevant links.
Hot data storage in Redis with migration to IPFS post 20-hour retention.
d. Key Management:

End-to-end encryption through the exchange of public MetaMask keys.
Functions for encryption and decryption using MetaMask keys.
e. Integration with IPFS & Redis:

Interface for IPFS interactions: data addition, retrieval.
Dedicated service for Redis operations: CRUD operations, data migration.
Security Measures

Advanced encryption techniques for data security.
Rigorous validation and verification methods for incoming requests.
Protection mechanisms against a diverse range of cyber threats.
Deployment and Scalability

Support for horizontal scalability.
Containerized deployment using technologies like Docker for enhanced scalability and orchestration.
API & Documentation

Provision of a well-documented REST API for frontend interactions.
Comprehensive API documentation inclusive of example requests and expected responses.
Testing Paradigms

Unit testing of all pivotal backend components.
Integration testing to validate module interplay and cohesiveness.
Epilogue:

This technical specification offers a panoramic view of the Java-based messenger's backend functionalities. Progressive architectural choices, combined with meticulous design considerations, ensure the robustness and efficiency of the platform. Subsequent iterations may delve into implementation specifics, architectural diagrams, and code samples.
