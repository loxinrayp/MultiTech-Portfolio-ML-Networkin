# MultiTech-Portfolio-ML-Networkin
A collection of Machine Learning (Google Colab) and Advanced Enterprise Networking (Cisco Packet Tracer) projects.

# Professional Tech Portfolio: Machine Learning & Advanced Networking

This repository contains two core projects demonstrating my expertise in Deep Learning model development and enterprise-grade network infrastructure design.

---

## Project 1: Image Classification Model (Cat vs Dog)
An automated image classification system utilizing Deep Learning approaches to accurately detect and differentiate between cats and dogs.

* **Tech Stack & Tools:** Python, TensorFlow, Keras, Google Colab, Matplotlib.
* **Key Features:**
  * Implemented a *Convolutional Neural Network* (CNN) architecture featuring multiple convolution and max-pooling layers.
  * Applied pixel normalization techniques to optimize data processing and accelerate model training convergence.
  * Evaluated model performance metrics utilizing sparse categorical cross-entropy loss functions.
* **Project File:** `Machine_Learning_CatDog_Classifier.ipynb`

---

## Project 2: Multi-Client Enterprise Network Architecture
Design and simulation of a secure, core-distribution enterprise network infrastructure utilizing advanced traffic isolation for multi-client environments.

* **Tech Stack & Tools:** Cisco Packet Tracer, Cisco IOS CLI, RIPv2 Dynamic Routing, Inter-VLAN Routing (Router-on-a-Stick).
* **Topology & Hardware Specs:**
  * **Core Distribution Router:** Cisco 2911 ISR
  * **Client Edge Routers:** Cisco 1941 ISR (3 Units)
  * **Core Managed Switch:** Cisco Catalyst 2960-24TT
* **Key Features:**
  * **VLAN Segmentation:** Isolated network broadcast domains for 3 distinct clients using VLAN 10, VLAN 20, and VLAN 30 mapped over IEEE 802.1Q trunk lines.
  * **Dynamic & Static IP Allocation:** Deployed automated DHCP Server pooling for Client 1, alongside strict manual Static IP addressing policies for Client 2 and Client 3.
  * **Dynamic Routing Integration:** Configured **RIP Version 2** across all routing nodes to enable automated, real-time routing table updates across cross-segment traffic.
* **Project File:** `MultiClient_VLAN_Enterprise_Network.pkt`

---

### How to Run the Projects
1. **For Machine Learning:** Download the `.ipynb` file, open it inside Google Colab or Jupyter Notebook, and run all code blocks sequentially.
2. **For Cisco Networking:** Ensure you have **Cisco Packet Tracer** installed. Open the `.pkt` file, enter the Desktop environment on any PC, and use the Command Prompt to perform end-to-end network `ping` testing.
