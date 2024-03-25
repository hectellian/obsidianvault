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

> [!faq] So what is parallelism in computers exactly?
>Parallelism, is the fact to have multiple [[Processors]] ([[Threads]]) **working together** on a same problem.
>We can see that 

Programmers will be the coordinators of the entire system (all the [[Processing Element]])

> [!warning] 
> By leaving most of the work to automation will only be causing more problems like [[Deadlocks]]

One of the main difficulties of parallelism is the strong coherence between the [[Programming Model]] and the materials

[[Von Neumann's Architecture]] is a great example of a perfect link between hardware and software. This birthed the success of [[Sequential Programming]] for years to come.

> [!danger] But we still want more [[Performance#Performance in Parallelism|performance]]!

---

> [!FAQ] Then where could we find some performance?
### **Technologies** (physical process used to treat information)

We could find new **technologies** like semi-conductors or silicium used in the current electronics. 
For a long time we've observed [[Moore's Law]] but it's starting to stagnate now. But Moore's Law was not the only exponential law observed all this time. Limited:
$$dissipated\ heat(f): P=v^2f$$
> v: voltage in the transistor bounds 
> f: clock frequency


#todo: finish law def

> [!NOTE]
> There is limits imposed by physics :
> - The speed of light: data cannot go faster than **c**
> - $E=mc^2$ and $E=h \cdot \mu$ (h is Planks constant, $\mu$ is the frequency)

A rapidly evolving technology worth exploring is **DNA Storage**, which enables the storage of digital information on DNA strands.

> [!INFO]
> DNA Storage is about 500 Exobytes ($10^{18}$) per strand

> [!FAQ]- What about the brain's performances?
> - $10^{11}$ neurons
> - $10^4$ synapses per neuron at 10 Hz
> - All this for a consummation of about 100 Watt

> [!FAQ] What is the more effective approach for optimal performance: utilizing multiple [[Processing Elements|PEs]] with lower computational power or employing a single [[Processing Element]] with significantly higher computational power? 
> #todo: finish card with calculations and proof

### [[Architectures]] upgrades





