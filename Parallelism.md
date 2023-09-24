---
tags:
  - parallelism
  - autumn2023
  - uni
  - "#course"
---
From the beginning of time, works was always split to many different people for important tasks. It's hard to imagine the pyramids or China's Great Wall construction without sharing the work to a massive number of people. That way by **sharing the workload** people could achieve a huge display of power. Of course there's many others examples of this in human history:

- Astronomy Calculation in the XIX century
- Meteorologic Calculation in the years 1920
- ENIAC (one of the first computers):
	- Multiple Calculation units activated at the same time
	- Didn't work well because of the coordination problems as well as the materials reliability

So what is parallelism in computers exactly?
Parallelism, is the fact to have multiple [[Processors]] ([[Threads]]) **working together** on a same problem.
We can see that 

Programmers will be the coordinators of the entire system (all the [[Processing Element]]), By leaving most of the work to automation will only be causing more problems like [[Deadlocks]]

One of the main difficulties of parallelism is the strong coherence between the [[Programming Model]] and the materials

[[Von Neumann's Architecture]] is a great example of a perfect link between hardware and software. This birthed the success of [[Sequential Programming]] for years to come.

> But we still want more [[Performance#Performance in Parallelism|performance]]!

---

Then where could we find some performance?
#### **Technologies** (physical process used to treat information)

We could find new **technologies** like semi-conductors or silicium used in the current electronics. 
For a long time we've observed [[Moore's Law]] but it's starting to stagnate now. But Moore's Law was not the only exponential law observed all this time. Limited:
$$dissipated\ heat(f): P=v^2f$$
> v: voltage in the transistor bounds 
> f: clock frequency


#todo: finish law def

