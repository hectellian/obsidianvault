---
tags:
  - autumn2023
  - uni
  - def
  - networks
---
##### Definition

Go-Back-N ARQ allows the sender to transmit multiple [[Packets|packets]] up to a fixed window size without waiting for individual ACKs. However, if an error is detected, all packets starting from the erroneous one are retransmitted.

##### How It Works

1. **Sender**: Sends multiple packets up to a specified **"window size"** without waiting for ACKs.
2. **Receiver**: Sends an ACK for each correctly received packet.
3. **Sender**: If it receives a negative acknowledgment (NAK) or a timeout occurs, retransmits all packets starting from the non-acknowledged one.

##### Pros and Cons

- **Pros**: Better utilization of bandwidth.
- **Cons**: May result in redundant retransmissions.

#### Example

In video streaming, Go-Back-N can be used to send multiple frames ahead, with retransmission occurring only if a frame is detected to be lost or corrupted.