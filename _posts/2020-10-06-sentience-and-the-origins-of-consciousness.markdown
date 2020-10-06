---
layout: post
title:  "Sentience and the Origins of Consciousness: From Cartesian Duality to Markovian Monism"
disqus_id: "2020-10-06-Friston2020"
date:   2020-10-06
tags: FEP
comments: true
type: Review
paperauthors: "Friston KJ, Wiese W, Hobson JA"
articlelink: https://www.mdpi.com/1099-4300/22/5/516
year: 2020
journalinfo: "Entropy 22(5):516"
---

### Summary

By conditioning on a system's "Markov blanket", which corresponds to the border between its internal and external states, the dynamics of a temporally sustained system can be interpreted in two different ways: as probabilistic “beliefs” about the external environment of the system and as the temporal evolution of the system’s internal states. These interpretations give rise to a duality of information geometries: an extrinsic information geometry which specifies "beliefs" of the system about the external world, and an intrinsic information geometry corresponding to information about the system's own future states.
On this basis, the authors propose that the extrinsic information geometry could account for “mental” properties assigned to the system, or even “qualia”. However, because the two interpretations are mutually reductive, the proposed metaphysical interpretation is termed “markovian monism” and categorized as a form of reductive materialism. Nevertheless, the existence of an extrinsic information geometry is not in itself deemed sufficient for consciousness.


### Why discuss this paper?
This is not the first attempt to connect aspects of the free energy formalism to consciousness (see, e.g., [Clark (2013)](https://doi.org/10.1017/S0140525X12000477), [Hohwy (2013)](https://doi.org/10.1093/acprof:oso/9780199682737.001.0001), [Williford et al. (2018)](https://www.frontiersin.org/articles/10.3389/fpsyg.2018.02571/full), and [Karl Friston himself in Aeon](https://aeon.co/essays/consciousness-is-not-a-thing-but-a-process-of-inference)). 
Here, a metaphysical interpretation is proposed at the most basic level of the FEP formalism: "proto-mental" qualities are ascribed to the information that can be derived from the internal states of a system about its external world, a system's "beliefs". I have two major issues with this proposal: (1) the so-called "beliefs" do not correspond to information that is available to the system itself and thus cannot account for subjective experience; (2) the authors want to have their cake and eat it: since the most straightforward interpretation of the system's "beliefs" as qualia would lead to literally every thing being conscious, ad-hoc functional criteria are superimposed to distinguish between conscious and unconscious systems (which is a particular pet peeve of mine). 

The paper is also long and complex: a lot of notions are woven together in the spirit of Markov blankets. Below I will attempt to disentangle the proposed connection between Markov blankets and consciousness.

### Commentary

##### [Disclaimer: I am still---to this date---struggling to understand Karl Friston's mathematical framework around the free energy principle, predictive coding, active inference etc., despite my efforts. So if I get anything wrong below, please feel free to call me out on it in the comments. For those working on or with the FEP: Can we have a simple toy model that shows how everything actually works? Please?]

#### Technical Background:
Let's start with Markov blankets. The Markov blanket of a set of nodes in a causal (directed acyclic) graph simply corresponds to all nodes that can influence that set, which are termed the "parents", all nodes that are influenced by the set, i.e. the "children, and also other nodes that may influence the children. Once the state of all these nodes is accounted for, no other information about nodes outside the system is required to determine the system's dynamics ("conditional independence").

Importantly, *everything* has a Markov blanket. The only exceptions are fully connected systems and isolated system, as those do not have external states. A feedforward system has a Markov blanket, and if a neural network has a Markov blanket the same network plus or minus some neurons also has a Markov blanket. While the Markov blanket makes it possible to separate a system into external and internal nodes/states which are conditionally independent given the state of the Markov blanket, the notion of a Markov blanket alone is of little use for *identifying* the borders of a system if they are not already known.

So which Markov Blankets are interesting? The Free Energy Principle (FEP) formalism imposes a strict (maybe too strict?) condition for something to exist over time by requiring that the dynamics of the system must converge to an attracting set which is assumed not to change throughout the lifetime of the system. For humans that would mean from conception to death, or maybe decomposition. During that interval we are wandering from state to state according to our nonequilibrium steady-state probability density. 

Any system that maintains itself (its attracting set) in the above way possesses the following properties: if we look at its internal and active states ("autonomous states"), it will *seem as if* the system is trying to minimize the surprisal (self-information, or, on average, the entropy) of its "particular states" (the internal plus blanket states).

From the above, it necessarily follows that one can infer information from the blanket states about the system's internal state and the external world (if the blanket state is x, the most likely internal state is y; moreover, the blanket state constrains which environmental states could have caused it.) The blanket state thus connects the conditional probabilities of internal and external states in a one-to-one mapping. Note that this inference is purely extrinsic, in the sense that it is not something the system "does", but something we can do by observing the system, its blanket states and the environment. 

##### [There is an interesting parallel to the role of mechanism states in IIT, where a set of nodes within the system constrains its causes and effects in a similar manner as assumed here for the Markov blanket. The crucial difference is that in IIT these constraints are internal to the system, information the system has by being in a state about its own causes and effects within the system.]

This relationship between internal and external states can be formulated in terms of an information geometry, which is called the "extrinsic" information geometry, because it specifies "beliefs" of the system about its external world. Importantly, a "belief" here is simply a conditional probability distribution, nothing more and nothing less (as the authors themselves state multiple times these "beliefs" are not in any way propositional in nature.) This all simply means that by being what it is, the system specifies some information about its external world. If my fusiform face area neurons fire, there likely was a face presented to my eyes. Again, the neuroscientist can infer this correlation, the system itself cannot.

The system also specifies an information geometry about its own future states, which is termed the "intrinsic" information geometry. The internal states of the system thus give rise to a duality, as the two information geometries are two aspects of the same process. "However, the existence of a dual aspect information geometry does not, in and of itself, give a system mental states and consciousness, but only computational properties (including probabilistic beliefs)" (p. 11). 

#### Metaphysical interpretation:
So far the formalism. The novel (and unfortunately less consistent) part starts in section 9, which discusses the metaphysical implications of the dual aspect information geometries. While it is acknowledged that there might just not be any metaphysical meaning whatsoever to the above observations, the authors' favored metaphysical flavor is one of "Markovian Monism." I cite:

*"Markovian monism consists of two claims: (1) Fundamentally, there is only one type of thing and only one type of irreducible property (this is why it is a Markovian monism). (2) All systems possessing a Markov blanket have properties that are relevant for understanding the mind and consciousness: if such systems have mental properties, then they have them partly by virtue of possessing a Markov blanket (this is why it is a Markovian monism)."*

A proper dualism is excluded because the two information geometries are reducible to each other. Instead, Markovian Monism is likened to "panprotopsychism" and "Neutral Monism." Here is the issue though: everything has a Markov blanket and all that follows is that such systems "seem" like they represent probability distributions about the world and perform computations based on those "beliefs" even without actively doing so. If we take the information geometries per se to be of metaphysical relevance with respect to mental or phenomenological properties, then simple systems like single-cell organisms might end up having a mind and ... the authors don't like that.
 
So how can we distinguish between conscious and unconscious systems? Unfortunately, the only thing presented to address this issue is a list of everyone's favorite contenders: macro variables, sufficient complexity, intentionality, etc. No operational distinction is offered to disambiguate systems that only "seem" to have "beliefs" from those that actually do. Instead consciousness should be thought of as a vague concept, with borderline cases. 

If we take consciousness as phenomenology, then what on earth would be an edge case? Consciousness is not like life in that respect. While we cannot agree on whether a virus is alive or not, the virus couldn't care less. Maybe there are organisms or other systems for which we will never be able to clearly tell whether they are conscious, but from their own perspective either the light is on or it isn't.

The main problem I see is a complete disregard of the intrinsic perspective of the system itself. The FEP formalism is first of all descriptive. If we have a temporally sustained system, a lot of math follows, which can explain why certain things *seem* like they have certain properties to us observers. But do they actually? How do we get a self-sustaining system in the first place? What mechanisms and dynamics are required? This is not provided by the FEP formalism. In fact, the specific system dynamics are irrelevant. Since the FEP can account for everything, it risks accounting for nothing in particular. Likewise, proposing an interpretation of the extrinsic information geometry as proto-mental does not bring us any closer to being able to distinguish conscious from unconscious systems. 

#### IIT comparison

To end, I am briefly going to address the comparison between the FEP and IIT made in this article:
While interpretations of IIT's axioms in terms of the FEP are given, in most cases, the essential property is not actually captured in the FEP formulation. I have already mentioned the lack of intrinsicality: the conditional probabilities in the extrinsic information geometry are not intrinsic in the IIT sense. The system itself cannot have "intrinsic" information about anything outside itself, as it cannot take anything past its Markov blanket into account. Such extrinsic information only exists from the perspective of an observer of the system. "What is this [intrinsic] information about...?" (p. 22) the authors ask. In IIT, the meaning has to come from the internal cause-effect structure: how all pieces of information specified by the system's mechanism are related to each other, without explicit reference to the external world. 

With respect to integration, having a Markov blanket has nothing to do with being an integrated system. We can, for example, describe any pair of cells, or humans, with one joint Markov blanket including joint information geometries etc. While the joint "beliefs" will be represented by probability distributions over the state space of both individuals, they are still (largely) reducible to the beliefs of their parts. 

Lastly, as the authors point out themselves, the notion of hierarchical Markov Blankets does not square with IIT's formulation of the exclusion postulate. Hierarchical generative models supposedly have "beliefs" about "beliefs" and it is postulated in this article and others (see above) that "Markov blankets within Markov blankets" might be necessary for phenomenal consciousness. But what does that mean with respect to the extrinsic information geometries? Do all overlapping Markov blankets have their own? How do I identify which Markov blanket is the one that subsumes all others? Again, I can have one Markov blanket of a pair of humans. Yet, to account for consciousness I must somehow identify the Markov blankets that delimit individuals. Moreover, the notion of "beliefs about beliefs" is extrinsic again. Every Markov blanket itself only has "beliefs" about its outside. How do the beliefs of various Markov blankets come together to form one mind and where are its borders?

