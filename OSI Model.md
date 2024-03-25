---
tags:
  - def
  - networks
  - autumn2023
  - uni
source: chatGPT
---
## Definition
The OSI (Open Systems Interconnection) Model is a **conceptual framework** that standardizes the functions of a telecommunication or computing system into **seven distinct layers**. This standardization makes it easier to understand, design, and troubleshoot networks by breaking down the complex processes into smaller, manageable layers.

## Layers
1. **Physical Layer (Layer 1)**
    - **Responsibility**: Deals with the physical medium and transmission of raw binary data.
    - **Examples**: Ethernet cables, fiber optics, hubs.
2. **Data Link Layer (Layer 2)**
    - **Responsibility**: Responsible for creating a reliable link between two directly connected nodes. It also manages MAC addressing and error detection.
    - **Examples**: Ethernet frames, switches, MAC addresses.
3. **Network Layer (Layer 3)**
    - **Responsibility**: Handles the routing of data packets between different networks. It deals with IP addressing and routing.
    - **Examples**: Routers, IP addresses, ICMP.
4. **Transport Layer (Layer 4)**
    - **Responsibility**: Ensures reliable data transfer between two devices on a network. It provides error checking and data segmentation into smaller packets.
    - **Examples**: TCP, UDP, ports.
5. **Session Layer (Layer 5)**
    - **Responsibility**: Manages sessions or connections between applications on different devices.
    - **Examples**: NetBIOS, RPC.
6. **Presentation Layer (Layer 6)**
    - **Responsibility**: Translates the data format between the application and transport layers. It can involve encryption, data compression, and translation services.
    - **Examples**: JPEG, GIF, MPEG, SSL/TLS.
7. **Application Layer (Layer 7)**
    - **Responsibility**: Provides networking services to end-user applications. This layer interacts directly with software applications.
    - **Examples**: HTTP, FTP, SMTP, DNS.


![[OSI Model.canvas|OSI Model]]