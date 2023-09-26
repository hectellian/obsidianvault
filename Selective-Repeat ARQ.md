---
tags:
  - autumn2023
  - uni
  - def
  - networks
---
##### Definition

In Selective Repeat ARQ, the sender transmits multiple [[Packets|packets]], like in [[Go-Back-N ARQ|Go-Back-N]], but only retransmits the specific packets that were acknowledged as faulty, rather than all packets from the point of failure.

##### How It Works

1. **Sender**: Sends multiple packets up to a **"window size"**, similar to Go-Back-N.
2. **Receiver**: Sends an ACK for each correctly received packet and a NAK for each erroneous or lost packet.
3. **Sender**: Only retransmits the packets for which a NAK was received.

> [!success] Pros
> Most efficient use of bandwidth among the three, as only erroneous packets are retransmitted.

> [!failure] Cons 
> More complex to implement due to the need to track individual packet statuses.

> [!example]
> In real-time multiplayer online gaming, where each packet could represent a game event like a player's movement, Selective Repeat would ensure that only crucial missing or erroneous events are retransmitted, preserving bandwidth and reducing latency.