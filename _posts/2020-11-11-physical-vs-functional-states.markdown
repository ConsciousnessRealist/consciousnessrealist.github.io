---
layout: post
title:  "Why IIT cares about physical not functional states"
disqus_id: 2020-11-11-PhysicalFunctional
date:   2020-11-11
tags: IIT
comments: true
type: Commentary
mathjax: true
---


While the postulates of IIT are often demonstrated in small, simulated, artificial systems (e.g., [Albantakis et al., 2014](https://doi.org/10.1371/journal.pcbi.1003966)), IIT does not consider such simulations conscious, no matter their "virtual" $$\Phi$$-value. Just like the simulation of a hurricane is not actually windy and wet, simulating a system of interacting physical components does not emulate its subjective experience.

The amount of integrated information of a computer, it is argued, has to be evaluated based on its physical, not functional, states and standard computer architectures constituted of massivly parallel chains of transistors (not unlike the cerebellum) do not possess the right causal structure for high $$\Phi$$, no matter how complex the software they run ([Koch and Tononi, 2015](); [Findlay et al., 2019](http://ceur-ws.org/Vol-2287/short7.pdf)*).

##### [* Full paper version will eventually appear.]

But why this emphasis on physical states? Doesn't the IIT algorithm depend only on a system's complete state transition probabilities? Those can easily be simulated. After all, there must exist a mapping between the states of the physical system and some set of functional states in the computer when the computer is simulating the temporal evolution of the physical system. Shouldn't the state transition probabilities, and thereby the amount of integrated information of the system, also be preserved?

**This is an issue that tends to come up time and again, so let me try to explain:**

In short, the reason for IIT's focus on physical states stems from IIT's axioms of "existence" and "intrinsicality" (please bear with me for a moment). 

##### [The axioms in IIT correspond to essential properties of every experience. They are the starting point from which a corresponding set of requirements for the physical substrate of consciousness are obtained through abduction (termed "postulates").]

Consciousness exists. Existence in physical terms amounts to having cause-effect power (you only exist if you make a difference to something and if something can make a difference to you). So in order to be a substrate of consciousness a system must exist in terms of cause-effect power.

Consciousness, moreover, exists intrinsically, from my intrinsic perspective as the experiencing subject. A substrate of consciousness must thus also exist intrinsically, from its own perspective, without the need of an external observer. It must have cause-effect power onto itself, meaning it must make a difference to itself, which must again be independent of interpretation by an external observer.

The state transition probabilities as the input to the IIT analysis are thus required to be causal, not merely correlational. In other words, they must describe a dynamical causal network in which edges denote causal dependencies (e.g., [Albantakis et al., 2019](https://doi.org/10.3390/e21050459)). This means, that the probabilities are maintained under perturbation of the system or its components ([Pearl, 2009](http://bayes.cs.ucla.edu/BOOK-2K/)).

But isn't this also true for a simulated system? After all, if I set the simulated system into a particular state, it will update according to the same transition probabilities as the corresponding physical system. 

Virtually, yes. **The problem with the simulated system is that it is not observer independent. Thus, its virtual causal powers are not intrinsic. The virtual system does not exist by itself.** 

To see why that is, let's consider what it means to simulate a physical system. First, a simple (extrinsic) mapping from the states of the physical system P over time onto the states of a different system S (the simulator) is not sufficient for S to simulate P [(Chalmers, 1996)](https://link.springer.com/article/10.1007%2FBF00413692), otherwise "pancomputationalism" would follow and even a rock could be said to simulate any finite state automaton (FSA) [(Putnam, 1988)](https://mitpress.mit.edu/books/representation-and-reality).

Instead, [Chalmers (1996)](https://link.springer.com/article/10.1007%2FBF00413692) argues for a notion of implementation which requires that the state transitions of the simulator are causal in a counterfactual sense: if the simulation requires S to transition from state $$s_1$$ into $$s_2$$, then it should do so no matter how the system S ended up in state $$s_1$$ (including upon perturbation). Crucially, this needs to be the case independent of environmental (background) conditions and it needs to hold even for possible states of P that do not happen on a particular run or trajectory (starting from a particular initial state). 

The physical states of the simulator S thus do play a significant role in determining whether S implements a simulation of P. In other words, the virtual states cannot be considered without their physical implementation, even just for deciding whether the system S actually simulates P. 

A standard computer running a simulation of a physical system P according to P's state transition probabilities is an implementation in the above sense if we consider the state of the computer as a whole. However, the virtual states of the simulation only correspond to a small subset of the physical elements within the computer at any given time. Moreover, this mapping is typically not persistent in time and space. The state of element A, for example, may be stored at a different physical location within the computer with every update of the virtual system. 

Note that IIT's causal analysis is closely related to Chalmer's definition of implementation. The IIT analysis requires the state transition probabilities for all system states, and background conditions are fixed to their actual state as they are not intrinsic to the system. Fixing all computer components that do not directly correspond to the functional states of the simulation, the simulation wouldn't run.

##### [For the same reasons, the virtual system itself does not have a "Markov Blanket" and thus does not exist according to the free energy principle (FEP), even if the computer does. Just as I was typing up this post a new preprint was published by [Wiese and Friston (2020)](https://psyarxiv.com/7gefk/), which makes this exact point based on very similar arguments about the nature of computation as my summary above. Please check it out!]

**Within the computer, the virtual states of the simulated system thus require interpretation.** In addition to the initial state of the physical system, an input specifying the dynamical evolution of the physical system (e.g., its state transition probabilities) must be provided to the computer to model the physical system in simulation. This corresponds to telling the computer which program to run and means that information from outside the system itself is required to perform the simulation. A different software program would lead to different transitions, both at the virtual and physical level. 
Obviously, the original physical system itself does not require this additional input because it *is* its own causal model (and nothing else). 

Thus, virtual states do not make a difference to themselves, because their implementation may change in the course of the update and their effects have to be mediated by parts of the computer external to the virtual system. The functional states of the simulation are thus only shifting sub-states of the full causal model that actually implements the simulation.

For these reasons IIT requires causal models to correspond to actual physical systems and it evaluates the causal interactions between actual physical components. 

##### [Subsets of elements within a larger system may be considered (and actually have to be considered to identify the set of maximal $$\Phi$$). In that case, however, the rest of the system is treated as a fixed background condition, as mentioned above.]

From the perspective of IIT, standard computer architectures have cause-effect structures that do not fare well in terms of their amount of integrated information, as they typically include feedforward components, or are only weakly integrated. Moreover, the way in which the various constituents of the computer interact is largely independent of which program the computer is running and does not even remotely reflect the cause-effect structure of the system being simulated.  

##### [Note here that, while the computer as a whole may simulate the physical system P, it typically does a whole lot more then that at the same time. Even from a functional point of view, the computer as a whole is thus not doing the same thing as the original physical system.]  

IIT does provide a way to move up levels from a system's micro physical implementation by causal coarse-graining [(Hoel et al., 2016)](https://doi.org/10.1093/nc/niw012), or black-boxing [(Marshall et al., 2018)](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1006114) of the system's micro elements into physical/causal macro elements. By contrast to arbitrary mappings of the global system state, these macroing procedures require a stable mapping between micro and macro components, where every micro element must be mapped into one and only one macro element (macro elements thus cannot physically overlap, and no micro element can simply be ignored).

Typically, there is no possible mapping of the computer's basic elements into macro elements that could reproduce the cause-effect structure, and thus phenomenal experience, of the system being simulated. An exception could be detailed neuromorphic computers that emulate the causal structure of the original system in their implementation, but those are very different from our standard computer architectures with CPUs, clocks, and data registers.

In conclusion, the reason IIT cares about physical not functional states is that functional states are virtual not real, because the simulated system within the computer does not exist for itself.

##### [Acknowledgements: An informative discussion of the meaning of "computation" and "information processing" with respect to cognition and brain function can be found here [(Piccinini and Shagrir, 2014)](https://www.sciencedirect.com/science/article/pii/S0959438813002043). [(Piccinini, 2007)](http://www.tandfonline.com/doi/abs/10.1080/00048400601176494) discusses the notion of "pancomputationalism" with respect to computational theories of mind. While I do not agree with all their points, the two papers contain a lot of food for thought and many useful references.]