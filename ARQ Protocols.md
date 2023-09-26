---
tags:
  - autumn2023
  - uni
  - def
  - networks
source: chatGPT
---
### Definition of ARQ Protocols

ARQ (Automatic Repeat reQuest) Protocols are [[Protocols|communication protocols]] used in telecommunications and computer networks to ensure reliable data transmission between sender and receiver. These protocols employ error-detection and retransmission mechanisms to automatically resend data [[Packets|packets]] that are either lost or received with errors.

### How ARQ Protocols Work

The basic workflow of ARQ Protocols involves the following steps:

1. The sender transmits a data packet along with some form of error-checking code.
2. The receiver examines the received packet and its error-checking code. 
3. If the packet is error-free, the receiver sends an acknowledgment (ACK) back to the sender.
4. If the packet has errors or is lost, the receiver either does nothing or sends a negative acknowledgment (NAK).
5. Upon receiving a NAK or not receiving an ACK within a specific time frame, the sender retransmits the packet.

> [!info] Commonly used types of ARQ Protocols:
> 1. **[[Stop-and-Wait ARQ]]**
> 2. **[[Go-Back-N ARQ]]**
> 3. **[[Selective-Repeat ARQ]]**
#### Examples

- **File Transfer**: When transferring a large file over a network, ARQ protocols ensure that each segment of the file is successfully received before the next segment is sent.
  
- **Streaming Services**: In video streaming, ARQ protocols can be used to ensure that each chunk of data is received correctly for smooth playback.

- **Wireless Networks**: In mobile and wireless networks, where data loss and errors are common, ARQ protocols are crucial for maintaining data integrity.

By utilizing ARQ protocols, networks aim to achieve reliable data transmission even in environments where errors or packet losses are likely to occur.