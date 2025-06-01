# ETHGlobalPrague 2025 – Decycler Project

Welcome to the collection of repositories created during the **ETHGlobalPrague 2025** hackathon by the **Decycler** team.  
Each repository corresponds to a component of our full-stack solution for smart waste detection, classification, and on-chain tracking.

---

### 🔗 Repositories

- 🗑️ [trash-warriors](https://github.com/ETHGlobalPrague2025/trash-warriors)  
  Central coordination repo – project overview, pitch, architecture, and deployment info.

- 🤖 [garbage-detector](https://github.com/ETHGlobalPrague2025/garbage-detector)  
  YOLO-based object detection for real-time waste classification on edge devices.

- 🔁 [decycler](https://github.com/ETHGlobalPrague2025/decycler)  
  Servo motor control system that sorts detected waste into categories via mechanical arms.

- 🌐 [node](https://github.com/ETHGlobalPrague2025/node)  
  Local Jetson Nano node logic that processes sensor input and handles inference control.

- 🧠 [facial-recognition](https://github.com/ETHGlobalPrague2025/facial-recognition)  
  Face-based user profiling system for bin interaction statistics and behavior analysis.

- 🎮 [vlayer](https://github.com/ETHGlobalPrague2025/vlayer)  
  Visualization and UI layer for dashboards, bin states, waste categories, and logs.

- 📜 [contracts](https://github.com/ETHGlobalPrague2025/contracts)  
  Solidity smart contracts for on-chain proof of disposal, rewards, and user actions.

---

Each part of the system is modular and open-source — feel free to explore, fork, and contribute!  
Let’s build a smarter, cleaner future together. ♻️

— **Decycler @ ETHGlobalPrague 2025**

## 🛠️ Tech Stack & Architecture

We are building the smart trash can using a combination of AI, embedded systems, and blockchain technologies.

### 🎛️ Hardware
- **NVIDIA Jetson Nano** – Handles image processing for both facial recognition and waste classification.
- **Microcontrollers** – Control the motors responsible for sorting and moving waste.

### 🔐 Blockchain & Account Abstraction
- **VLayer** – Enables zero-knowledge proof–based account abstraction, including face- or email-based identity.
- **Flow** – Hosts the main smart contract for managing user accounts, ownership, and payments.
- **LayerZero** – Facilitates cross-chain communication to interact with other blockchains.
- **BlockScout** – Used to visualize and monitor blockchain data.

### 💻 Software
- **Next.js** – Frontend web application for user interaction and admin control.
- **Python** – Powers all backend components, including AI models, hardware interfacing, and system logic.

---

This architecture allows users to interact with the smart trash can seamlessly, without needing a phone, while enabling collectors, stakeholders, and admins to benefit from transparent and automated blockchain-based incentives.

