
# 5G Network Slicing Simulation

Welcome to the **5G Network Slicing Simulation Project**! This repository contains a simulation framework designed to explore the concept of 5G network slicing, where multiple logical networks are created over a common physical infrastructure. The project leverages cutting-edge techniques to simulate the dynamic allocation of resources across different network slices, optimizing for various performance metrics.

## 📚 Project Overview

**5G Network Slicing** is a critical feature of next-generation wireless communication systems, enabling the partitioning of a physical network into multiple logical slices that cater to specific applications and performance requirements. This project simulates the deployment and management of network slices, evaluating performance under different configurations.

The key objectives include:

- **Slice Creation & Management**: Dynamically generate and manage network slices with distinct characteristics.
- **Resource Allocation**: Optimize resource distribution across slices for maximum efficiency.
- **Performance Metrics**: Evaluate latency, throughput, and reliability for each slice.

### Key Features

- 🛠 **Modular Architecture**: Built with Python and highly modular, allowing easy customization.
- 📡 **5G Base Station Simulation**: Simulates 5G base stations interacting with clients and network slices.
- ⚙️ **Dynamic Resource Allocation**: Adaptive allocation of bandwidth, frequency, and computational resources.
- 📊 **Comprehensive Analytics**: Detailed performance metrics using real-time data from each slice.

## 🚀 Getting Started

To get started, you can clone the repository and set up your local environment. Ensure you have Python 3.8+ installed.

### Prerequisites

- Python 3.8 or higher
- Dependencies listed in `requirements.txt` (install with `pip install -r requirements.txt`)

### Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/rohan-chandrashekar/5g-network-slicing.git
    cd 5g-network-slicing
    ```

2. Install the necessary dependencies:

    ```bash
    pip install -r requirements.txt
    ```

3. Run the main simulation script:

    ```bash
    python __main__.py
    ```

## 🧑‍💻 Project Structure

Here's a breakdown of the main files and their roles:

- **`BaseStation.py`**: Manages the simulation of 5G base stations and their interactions with clients.
- **`Client.py`**: Defines the behavior of clients requesting services from the network slices.
- **`Container.py`**: Manages containerized applications running within network slices.
- **`Coverage.py`**: Handles the simulation of coverage areas and signal strength.
- **`Distributor.py`**: Manages the distribution of resources across slices.
- **`Graph.py`**: Generates visual representations of network performance.
- **`Slice.py`**: Implements the core functionality of network slices, including creation and management.
- **`Stats.py`**: Collects and analyzes performance data.
- **`utils.py`**: Utility functions used across the project.

## 🌐 Network Slicing

In 5G, **network slicing** allows the creation of isolated virtual networks tailored for different use cases like:

- **eMBB (Enhanced Mobile Broadband)**: High-speed internet for applications like VR/AR.
- **mMTC (Massive Machine-Type Communications)**: Supports IoT with low power and high device density.
- **URLLC (Ultra-Reliable Low Latency Communications)**: For mission-critical applications like remote surgery.

This simulation models each of these slices, providing an environment to explore how resources are allocated to meet the requirements of each slice.

## 📊 Performance Metrics

The simulation focuses on several key performance indicators:

- **Latency**: Measures delay in data transmission.
- **Throughput**: Tracks the rate of successful message delivery over the network.
- **Resource Utilization**: Assesses how efficiently the network resources are allocated to different slices.

## 🛠 Future Work

Some potential areas of improvement and further exploration include:

- 🧠 **AI-Driven Resource Allocation**: Use AI to optimize resource distribution.
- 🌐 **Multi-Access Edge Computing (MEC)**: Explore edge computing to reduce latency further.
- 🚀 **Scalability**: Enhance the scalability to simulate larger and more complex network environments.

## 🤝 Contributing

Contributions are welcome! If you're interested in improving this project, feel free to fork the repository, make changes, and submit a pull request. For major changes, please open an issue first to discuss what you'd like to change.

### Steps to Contribute:

1. Fork the project.
2. Create your feature branch (`git checkout -b feature/awesome-feature`).
3. Commit your changes (`git commit -m 'Add awesome feature'`).
4. Push to the branch (`git push origin feature/awesome-feature`).
5. Open a pull request.
