---
layout: post
slug: functional-redundancy
title:  Functional equivalence and functional redundancy
disqus_id: 2022-06-17-Fefr
date:   2022-06-17
tags: 	Theory
comments: true
type: Commentary
author: "Jonathan P Lang"
editor: "Larissa Albantakis"
---

The concept of *functional equivalence* plays an important role in Functionalism and the thought experiments that are often used to motivate it. Here I show how this bedrock concept entails that Functionalism is forced to multiply conscious systems (as well as tokens of individual conscious states) beyond necessity when faced with conscious systems that are *functionally redundant*.

### The equivalence principle

Although different functionalist theories of mind may differ in their commitments, the following Equivalence Principle (EP) is common to all of them: 

*If two numerically non-identical systems C and C' are functionally equivalent (in terms of both having some privileged functional profile F)and C is conscious, then so too is C'.*

The EP presupposes the core claim of Functionalism while being agnostic about how one should go about characterizing *F*.
EP is not only a consequence of a functionalist theory of mind, but it has often been used to motivate the theory: Thought experiments concerning the possibility of consciousness in aliens, artificial systems, and other biological systems with radically different anatomies mobilize EP as a premise. The principle is also intimately tied to the notion of multiple realizability.

EP also seems to have some practical utility in that it can, in principle, help us to identify further conscious systems in the world so long as (1) we have at least one system that we know to be conscious, (2) we have a method for identifying the proper functional profile of that system and (3) we have a method of identifying the functional profile of other systems in the world so that we can compare them to the conscious system. 

Critics of functionalism have sometimes argued that conditions (2) and (3) cannot be satisfied. I want to argue an even stronger claim though: Even if (1)-(3) can be satisfied, Functionalism will still face intractable problems concerning its ability to properly individuate conscious systems. 
### Matryoshka systems and functional redundancy

Consider a conscious system C1 (i.e., a core system) that is embedded in a series of concentric shells, much like a nested doll. Every shell receives inputs from and sends outputs to its nearest neighbors , with each shell performing some transform on those inputs/outputs. Let the function that each shell performs on its inputs/outputs be the inverse function of any shell directly adjacent to it; i.e., odd-numbered shells will perform some function *f*, while even-numbered shells will perform the function *f<sup>--1</sup>*. 

As shells are added to a system, successive supersystems are created. For instance, C1 and Shell 1 comprise a supersystem C2, C2 and Shell 2 comprise another supersystem C3, and so on (see Figure 1). Let us call any system displaying such a nested architecture of inverting shells a *Matryoshka system*. 

![Matryoshka system](../images/JLang/Fig1.jpg){:style="float: none; margin-left: auto; margin-right: auto;" width="50%"}

##### **Figure 1. Matryoshka systems.** From top to bottom, successive nestings of systems within shells implementing inverse transforms. Supersystems C2, C3 and C4 count as Matryoshka systems, as they contain nested architecture which embeds a core system in a progressive series of larger shells that invert input and outputs that are passed to them.

C1 will then be behaviorally and functionally equivalent to its Matryoshka supersystem C3 (and the same for C2 and C4, and so on).
Any Matryoshka system possessing an odd/even number of shells will be *functionally redundant*:

*A system S with functional profile F is functionally redundant iff there is some proper subsystem of S that contributes functions to F such that its removal from S would result in a new system S' with the same F.*

A conjunction of this definition with EP entails the following: *Any functionally redundant system will be functionally equivalent to one of its proper subsystems.*

### The issue: Multiplying conscious systems and states beyond necessity

We now arrive at a problem. There are systems that satisfy the definition of functional redundancy (i.e., Matryoshka systems). These systems have a proper subsystem (or proper subsystems) to which they are functionally equivalent. But by EP, this means that if we find just one system among those subsystems is conscious, *then all of those systems must also be conscious.* 

This flies in the face of powerful intuitions concerning how we should individuate conscious systems in these cases. Why would iteration of a 'canceling' transform over my behavioral outputs/sensory inputs result in novel consciousnesses? For instance, imagine I was embedded in a defective Iron Man suit that inverted all incoming stimuli and inverted all my speech/motor outputs. It turns out that the glitchy system cannot be fixed, and so to remedy the issue I (while still wearing the defective suit) am embedded in yet another such defective Iron Man suit, causing the inversions to cancel. Why would anyone ever think that there are now two conscious entities that exist here instead of one?

In addition to this problem being one of overcounting conscious systems, it can also be seen as a problem of overcounting token occurrences of particular qualitative states. Any input into that functionally equivalent Matryoshka system will be an input also into its functionally equivalent core system. Both systems will thus end up occupying the same internal states. Moreover, a Matryoshka system and its functionally equivalent subsystems will always be embedded within the same environment and stand in the same relation to it.

### Are core systems and their behaviorally equivalent Matryoshka systems really functionally equivalent? 

Showing that two systems have the same output for every input is only sufficient to establish *behavioral* equivalence. To show that the two systems are *functionally* equivalent we would have to compare, not just the global input-output mappings of each system, but also the *internal states* of those systems. Unfortunately for the functionalist though, the equivalence can be shown (Figure 2).

![Proper subsystems](../images/JLang/Fig2.jpg){:style="float: none; margin-left: auto; margin-right: auto;" width="75%"}

##### **Figure 2. Functional equivalence of a Matryoshka system and its proper subsystem.** Systems C1 and C3 yield the same outputs for every input, making them behaviorally equivalent. Carving up each system functionally reveals that C1 and C3 can each be described as having (for example) 3 modular subsystems (a, b and c), with the respective states of each systems’ modules, as well as the respective inputs and outputs of each systems’ modules, being identical across both systems. 

In Figure 2, the functions of the two shells of C3 are distributed among the subsystem a and subsystem c. Such a distribution ensures that there exists a one-to-one mapping of subsystems between C1 and C3, thus satisfying our first criterion on functional equivalence.

Note that the functional profile of C1 and C3 entail nothing about the specifics of the systems’ physical architectures and the relative placement of their components. One can, of course, choose to appeal to non-functional properties (such as structural relations) in order to render the two systems functionally inequivalent. But reaching beyond the resources of functionalism is to abandon functionalism in favor of a non-functionalist theory of consciousness. 

Crucially, the same strategy used to prove the functional equivalence of the fully-specified C1 in Figure 2 will work with any functional description of C1 whatsoever. All one must do in cases of more complex functional profiles is to distribute the shell functions of C3 across every initial input subsystem and every ultimate output subsystem within that profile. This means that, with regard to any functionalist theory and any F the theory claims will, if implemented, produce a conscious system, I can construct a functionally redundant Matryoshka system that exhibits F. The problem of functional redundancy is thus fully general.  

### Further replies

At this point, a functionalist might concede that there is but one conscious system in each of my Matryoshka examples. She might also concede that my intuitions about the Iron Man suit are correct. But, she will say, my Matryoshka cases are crucially based on *subsystems* and *supersystems*, and so I'm wrong to claim that in these cases there are actually multiple systems involved: There is clearly only a single system involved in every one of these cases, albeit one with various parts.

However, each successive supersystem of C1 contains more and more token functions, and more and more processes/components that are realizers of those functions. The functionalist cannot merely dismiss appeals to additional processes and components when those components act as realizers of functions. 

The functionalist may then reply that there is a relevant difference between C1 and C3 that I have ignored, namely, that C3 has two extra functions that C1 does not have. This is because, despite canceling each other out, the inverse functions that characterize shell 1 and shell 2 must be counted as two functions that do not occur in C1. 

However, it is still true that *for any functionalist description of C1, we can describe C3 in such a way that it is shown to be fully isomorphic to C1.*

Consider a famous thought experiment involving neural replacement that is often used as an intuition pump for functionalism. In such a scenario, we are asked to imagine that a single neuron in a person’s brain is carefully replaced with an artificial ‘neuron’ of approximately the same size that performs all and only the same functions as a real neuron. In this case, the new brain will be functionally identical to the old one, and we are inclined to believe that the consciousness of the brain will remain unchanged. Then we are asked to imagine that another neuron is replaced, then another, then another until the entire brain is now artificial. Many are inclined to believe that this new, functionally equivalent brain would be just as conscious as the previous versions, and this in turn lends intuitive support to EP and Functionalism in general.  

Notice though that we can also manufacture replacement scenarios involving functional redundancy. Imagine that we take one neuron of your brain and replace it with two artificial units instead of one, each unit about half the size of a neuron, but together functionally equivalent to the neuron.

What are our intuitions in the second replacement scenario? I submit that, whatever they are, they should be the same as our intuitions in the first. But then there is no difference in consciousness between a brain with no artificial neurons and a brain with one or more neurons replaced with the afore described set of artificial units.

Note also that, while a functionally redundant system may implement more functions than one of its own subsystems to which it is functionally equivalent, this does not entail that the system will always take more time than the subsystem to execute those functions, because it is possible to generate similarly problematic embeddings in which the functional redundancy arises from processes running in parallel instead of in series.

### If there is only one consciousness, which is it?

Let us be charitable for a moment and assume that, with regard to systems like Matryoshkas that exhibit functional redundancy, the functionalist can somehow avoid multiplying conscious systems and states beyond necessity. In other words, imagine that for any given Matryoshka system consisting of behaviorally equivalent systems C1, C3, C5, ... Cn (where n is odd), the functionalist can legitimately claim that at any time there is only one conscious systems in one conscious state instead of n conscious systems and n occurrences of the same qualitative state. Still, we'd be left with the following question: Which of the aforementioned systems is *actually the conscious one*? Functionalism just doesn’t seem to have the resources to answer such questions. 

### Conclusion

Systems can be functionally redundant. If any system is functionally redundant, it is functionally equivalent to a proper subsystem to which it is not numerically identical. This means that functionalism faces a problem: For any system that is conscious and functionally redundant, functionalism entails that both its core system and any supersystem to which it is equivalent are conscious entities. This conclusion is extremely counterintuitive and entails a troubling proliferation of conscious subjects. It also entails a troubling proliferation of token qualitative states having the same content, regardless of whether one endorses an internalist or externalist version of functionalism.

##### **Acknowledgements:** I would like to thank Andrew Haun, Larissa Albantakis, and Matteo Grasso for their helpful comments. This work was funded by a grant from the Tiny Blue Dot Foundation.



