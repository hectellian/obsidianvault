---
tags:
  - autumn2023
  - uni
  - def
  - networks
---
##### Definition
Stop-and-Wait ARQ is a basic form of [[ARQ Protocols|ARQ protocol]] where the sender transmits a single data [[Packets|packet]] and then waits for an acknowledgment (ACK) from the receiver before sending the next packet.

##### How It Works
1. **Sender**: Transmits a data packet and starts a timer.
2. **Receiver**: Upon receiving the packet, checks for errors and sends an ACK if the packet is error-free.
3. **Sender**: Waits for the ACK. If received before the timer expires, sends the next packet.

##### Pros and Cons
- **Pros**: Simple to implement.
- **Cons**: Inefficient use of bandwidth as the sender remains idle while waiting for ACKs.

#### Example
In a file transfer scenario, each chunk of the file would be sent individually, with the sender waiting for a confirmation before proceeding to the next chunk.