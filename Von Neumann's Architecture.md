---
tags:
  - paralleslism
  - autumn2023
  - uni
  - def
---
#todo: Define the architecture and add visual

As good as it can be, like all things there's limits to this [[Architectures|Architecture]]

- The first problem that most of those face is **heating up**
- The second problem would be the separation of the CPU and the memory. The data needs to travel to the CPU and this is almost 10 times more expensive in energy that a floating point operation. If the distance is too great this can even go to 1000 times the energy.
> This is called the **memory wall** or the **Von Neumann's Bottleneck**

This limit is illustrated by what we call **"roof-line mode"**.
- The goal is to link the calculation power **R** [flop/s] with the arithmetic intensity **I** [flop/s] and also with the bandwidth **$\mathbf{\beta}$ [byte/s] 

#todo: add roofline graph