# Decentralized-Identity-Management-for-IoT-Devices-Using-IOTA-Blockchain-Technology

## Overview
This repository contains the source code and implementation details for the paper **"Decentralized Identity Management for IoT Devices Using IOTA Blockchain Technology"**. The project explores a scalable, secure, and privacy-preserving identity management framework for IoT devices, leveraging the IOTA Tangle, decentralized identifiers (DIDs), verifiable credentials (VCs), and IOTA-specific technologies such as **IOTA Identity**, **IOTA Streams**, and **IOTA Stronghold**.

### Abstract
The rapid growth of IoT requires robust identity management solutions. This project proposes a decentralized identity management model using IOTA’s Tangle technology to overcome the limitations of centralized systems, such as single points of failure, scalability, and limited user control over data. The solution incorporates:
- **Self-Sovereign Identity (SSI)** principles for decentralized data sovereignty.
- **Proof-of-Concept implementation** on resource-constrained IoT devices.
- Enhanced security, scalability, and transaction efficiency for IoT ecosystems.

## Features
- **IOTA Identity Framework**: Implements DIDs and VCs for decentralized device identification and authentication.
- **IOTA Streams**: Provides secure, encrypted, and private data exchange.
- **IOTA Stronghold**: Ensures robust key management and cryptographic security.
- **Lightweight IoT Deployment**: Tested on resource-constrained devices (e.g., Raspberry Pi).

## Repository Contents
- **`src/`**: Source code implementing DIDs, VCs, and the IOTA Tangle integration.
- **`docs/`**: Documentation, including an in-depth explanation of the implementation and experimental results.
- **`tests/`**: Unit and integration tests for the identity management framework.
- **`examples/`**: Sample applications demonstrating secure identity verification and data exchange.

## Getting Started

### Prerequisites
- **Hardware**: Raspberry Pi 4 or similar resource-constrained IoT devices.
- **Software**:
  - IOTA Identity
  - IOTA Streams
  - IOTA Stronghold
  - Python or Node.js runtime (for running scripts)

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/decentralized-iot-identity
   cd decentralized-iot-identity
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt  # If using Python
   ```

3. Set up the IOTA Identity node:
   - Follow [IOTA Node Setup Guide](https://docs.iota.org/).
   - Run the node locally or connect to a public IOTA network.

### Running the Proof-of-Concept
1. Generate a Decentralized Identifier (DID):
   ```bash
   python src/generate_did.py
   ```
2. Issue a Verifiable Credential (VC):
   ```bash
   python src/issue_vc.py --subject did:iota:example123
   ```
3. Verify credentials:
   ```bash
   python src/verify_vc.py --vc-file path/to/vc.json
   ```

## Results
The proof-of-concept validates:
- **Real-time credential verification** for IoT devices.
- **Secure data channels** using IOTA Streams for encrypted communication.
- **Key management security** with IOTA Stronghold.

For details, see the `results/` directory.

## Challenges and Future Work
- High computational overhead during cryptographic operations on resource-limited IoT devices.
- Need for seamless integration of DIDComm protocols for improved interoperability.

## Contributing
We welcome contributions to improve and extend this project. Please follow these steps:
1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Submit a pull request detailing the changes.

## License
This project is licensed under the Creative Commons Attribution (CC BY) license. See `LICENSE` for more details.

## Citation
If you use this repository, please cite:
```
Ramírez, T.; Maciá-Lillo, A.; Pujol, F.A.; Garcia-D’Hurso, N.; Azorin-Lopez, J.; Mora, H. 
"Decentralized Identity Management for IoT Devices Using IOTA Blockchain Technology". 
Future Internet 2024. DOI: https://doi.org/xxxxxx
```

## Contact
For questions or collaborations, contact:
- **Tamai Ramírez** - [tamai.ramirez@ua.es](mailto:tamai.ramirez@ua.es)

