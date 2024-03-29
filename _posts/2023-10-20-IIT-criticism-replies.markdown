---
layout: post
title:  "IIT criticisms and replies (a non-exhaustive list)"
disqus_id: 2023-10-20-Criticism
date:   2023-10-20
tags: 	IIT
comments: true
type: Commentary
---

In light of [recent events](https://www.nature.com/articles/d41586-023-02971-1), I have thought quite a bit about constructive ways to address some of the concerns raised about Integrated Information Theory (IIT). At least for the time being, I refer to [Tim Bayne](https://theconversation.com/nobody-knows-how-consciousness-works-but-top-researchers-are-fighting-over-which-theories-are-really-science-214074), [Erik Hoel](https://www.theintrinsicperspective.com/p/ambitious-theories-of-consciousness), and [Anil Seth](https://nautil.us/the-worth-of-wild-ideas-399097/?_sp=e34c8f3f-fbd0-4057-a76b-6ea05c597f2c.1695915413377) for direct responses to the ominous letter, which mainly objected to IIT's portrayal in the media rather than the theory itself. The community's support means a lot and will be more impactful than anything that I could add to the matter. 

Nevertheless, one issue that has surfaced in the subsequent discussion is the perceived silence of the IIT camp with regard to criticisms against the theory proper, published in recent papers or blog posts. 
This is a fair point to some extent, and there is a main reason why replies have been sparse: Time is short and (we thought) better spent on [advancing the theory](https://doi.org/10.1371/journal.pcbi.1011465) with valid criticisms in mind, rather than addressing each critical publication one-by-one. Especially when a critique is based on an obvious misreading or misrepresentation of the theory, it seemed more efficient and less inflammatory to let the theory papers and (future) empirical results speak for themselves. 
(Lack of time is also the reason why this is the first blog post of mine in a while.)

This said, we also noticed that many are apparently unaware that we have actually addressed several points of criticism directly or indirectly in subsequent publications. Below is a non-exhaustive list that highlights a few representative critiques of IIT and corresponding replies. I largely focus on critiques regarding the validity of the theory rather than its philosophical commitments or extra-scientific considerations.

### IIT's axiomatic foundation
IIT starts from consciousness itself and first aims to identify its essential properties. Starting with IIT 3.0 ([Tononi et al., 2012](https://architalbiol.org/index.php/aib/article/view/15056/23165867); [Oizumi et al., 2014](https://doi.org/10.1371/journal.pcbi.1003588)) these essential properties were made explicit as a list of "axioms." The label, as well as the claim that the axioms are "self-evident," has caused some push-back, e.g.:

[Bayne T (2018) On the axiomatic foundations of the integrated information theory of consciousness.](https://doi.org/10.1093/nc/niy007)

In response, we have reformulated the axioms to clarify their intended meaning and explained the use of the term "axiom" in [IIT 4.0](https://doi.org/10.1371/journal.pcbi.1011465): "Traditionally, an axiom is a statement that is assumed to be true, cannot be inferred from any other statement, and can serve as a starting point for inferences." 

We have also emphasized that the axioms should be seen as irrefutable, rather than self-evident. Of course they might be misunderstood, but in their intended (very basic) meaning, denying them leads to contradiction. While there would be no IIT without introspection, the axioms do not rely on the accuracy of our introspective capacities. I have [highlighted this specifically for the information axiom](https://doi.org/10.1017/S0140525X21001977) in my reply to the critical article by [Merker et al. (2021)](https://doi.org/10.1017/S0140525X21000881), which has also received a reply by [Tononi et al. (2021)](https://doi.org/10.1017/S0140525X21001990).

IIT's latest presentation, moreover, explicitly describes the translation of axioms into postulates as an "inference to a good explanation" (and therefore subject to falsification, but also refinement). Finally, other qualities that might be considered as candidates for axiomatic status (such as time, see e.g. [(Hunt, 2016)](https://www.ingentaconnect.com/content/imp/jcs/2016/00000023/F0020009/art00005#)) are discussed in [IIT 4.0](https://doi.org/10.1371/journal.pcbi.1011465), but ultimately considered non-essential (because there are, or could reasonably be, human experiences that lack these properties).

For more on how to understand IIT's axioms please also see [this recent guest post by Boki Milinković](../guest/axioms).

### Φ ("Phi") is not well-defined

[Barrett AB, Mediano PAM (2019) The phi measure of integrated information is not well-defined for general physical systems.](https://www.ingentaconnect.com/content/imp/jcs/2019/00000026/f0020001/art00002)

The article mentions three problems with Φ as defined in IIT 3.0. The first problem has been resolved in IIT 4.0 by an updated, intrinsic difference measure based on IIT's postulates [(Barbosa et al., 2020)](10.1038/s41598-020-75943-4). The other two issues are that IIT's mathematical formalism assumes a discrete system with Markovian dynamics. Practical issues aside, these assumptions concern the ultimate nature of our universe and it is not clear at the moment whether continuous dynamics are real or not, or whether the universe is Markovian or not. Nevertheless, IIT should connect to micro-physics, and we have made a preliminary attempt to apply the IIT 4.0 formalism to (finite-dimensional) quantum systems in [(Albantakis et al., 2023)](https://www.mdpi.com/1099-4300/25/3/449) (see also references therein for previous formulations). For attempts at a continuous formalism of IIT's principles see [(Esteban et al., 2018)](doi:10.1371/journal.pcbi.1006154) and [(Kalita et al., 2019)](doi:10.3390/e21050493), and for a generalized account of the mathematical structure of IIT 3.0 that addresses the issue of discrete time and Markovian dynamics see [(Kleiner and Tull, 2021)](https://doi.org/10.3389/fams.2020.602973). Nevertheless, as mentioned in the [IIT 4.0 paper](https://doi.org/10.1371/journal.pcbi.1011465), it still remains to be determined whether IIT is compatible with current physics.

[Hanson JR, Walker SI (2023) On the non-uniqueness problem in integrated information theory.](https://dx.doi.org/10.1093/nc/niad014)

This paper is concerned with the problem of "ties" in evaluating IIT quantities, see also [(Moon, 2019)](doi:10.3390/e21040405) and [(Krohn and Ostwald, 2017)](doi:10.1093/nc/nix017). Several things to be said here. First, it is true that [PyPhi, the Python toolbox to compute IIT quantities in simple example systems](https://github.com/wmayner/pyphi) only returns one of the tied objects, chosen arbitrarily but consistently ([the documentation has been updated to reflect this in response to the preprint](https://pyphi.readthedocs.io/en/latest/tiebreaking.html)). We have assumed the resulting Φ value to be representative, if not necessarily unique. This is fine as long as examples are used in a representative context, which was the case for most of our publications cited by Hanson and Walker, with the exception of the [cell-cycle analysis paper](https://pubmed.ncbi.nlm.nih.gov/29133455/). In this case, we are planning a proper reply to the article, so suffice it to say that the problem is largely resolved by IIT 4.0, as the substrate is now identified by the system integrated information, before computing its cause-effect structure, though certain ties can still occur and should be resolved in a manner consistent with IIT principles (see [IIT 4.0, supplementary information S1 Text](https://journals.plos.org/ploscompbiol/article/file?type=supplementary&id=10.1371/journal.pcbi.1011465.s001)). Finally, I would argue that the problem of ties is not a detrimental issue but mostly an artifact of the symmetric properties of the simple example systems used to demonstrate the formalism. Similar issues arise, for example, in classical mechanics under specially chosen initial conditions. 

### IIT is not a functionalist theory... therefore it is either false or unfalsifiable

Under this title, I would list the following papers (among others):

[Doerig A, Schurger A, Hess K, Herzog MH (2019) The unfolding argument: Why IIT and other causal structure theories cannot explain consciousness.](https://doi.org/10.1016/j.concog.2019.04.002)

[Hanson JR, Walker SI (2019) Integrated Information Theory and Isomorphic Feed-Forward Philosophical Zombies.](https://www.mdpi.com/1099-4300/21/11/1073)

[Hanson JR, Walker SI (2021) Formalizing falsification for theories of consciousness across computational hierarchies.](https://doi.org/10.1093/nc/niab014)

The [unfolding argument (UA) paper](https://doi.org/10.1016/j.concog.2019.04.002) has caused quite a response in the consciousness science community, despite the fact that it ultimately just highlights the unique challenges of the field. One reason might be that many consciousness researchers are (consciously or unconsciously) functionalists by conviction and/or fall prey to the ["fallacy of misplaced objectivity" (Ellia et al., 2021)](https://doi.org/10.1093/nc/niab032).

Replies to the UA abound. [Here is my post](../unfolding-argument-commentary/) (by which I still stand). Moreover, as formally proven by [Kleiner and Hoel (2021)](https://doi.org/10.1093/nc/niab001), the UA in fact applies to any minimally informative theory of consciousness (including any functional theory that does not simply equate consciousness with report). The UA thus ultimately amounts to the claim that there cannot be a science of consciousness, which should raise suspicion regarding its validity. For more, see e.g. [(Negro, 2020)](https://doi.org/10.1007/s11097-900 020-09681-3), [(Tsuchiya et al., 2020)](https://doi.org/https://doi.org/10.1016/j.concog.2020.102877), and [(Usher, 2021)](https://doi.org/https://doi.org/10.1016/j.concog.2021.103212). In essence, there is no theory-independent way to assess the consciousness of systems that are physically very different from us. Therefore, such cases cannot be used to falsify a theory of consciousness. Yet, a science of consciousness is possible in human subjects, because I can make an inference about their level and state of consciousness based on my own experiences (which constitutes theory-independent evidence). 
One upshot of the UA discussions is that it would be generally useful to mechanistically explain how introspection aligns with a given theory of consciousness, which is on the to-do list for IIT.

The papers by (Hanson and Walker, 2019; 2021) make similar points to the UA, but using actual toy example systems that have the same behavior but different Φ values. As an extension of the UA, "behavior" here includes not only the input-output function of the system, but also its global dynamics (i.e., its state-to-state transition diagram). Somehow the idea seems to be that if two systems can be mapped to the same global transition diagram, they should be identical in every relevant way including their amount of consciousness. As I have shown in the discussion section 4.2 of [(Albantakis & Tononi, 2019)](https://www.mdpi.com/1099-4300/21/10/989), this idea fails already for notions such as agency and autonomy (which many view as prerequisites for consciousness). For example, maintaining the global dynamics of a larger agent-environment system under a remapping of its states does not in general maintain the dynamics of the agent itself. This means that under a state remapping that maintains the global dynamics of a system with several conscious beings, there is no guarantee that these beings can also be found in the new system. 
To be clear, the systems presented in (Hanson and Walker, 2019; 2021) are physically distinct from each other and the dynamics of their subsets differ *because* they are implemented in different ways. Why should the global dynamics matter but not the dynamics of the subsets?---especially if the system itself is usually just a subset of a larger system. 

##### [This last point highlights a general problem with certain functionalist accounts of consciousness that give special relevance to the so-called *algorithmic* level, which supervenes upon, but is distinct from the level of implementation: there is hardly ever just one algorithmic level and it is generally not well-defined in the first place. I also want to point again to my ["Greek Cave" thought experiment](../greek-cave/), which presents an argument against purely functional approaches to consciousness, reminiscent of the Chinese room and China brain thought experiments, but more practical.]


### Some parts of IIT are not testable
#### The core of IIT is not testable

That IIT does make testable predictions is largely accepted by now (I hope). However, some have argued that this does not mean that IIT itself is testable, because its core assumptions are untestable either in principle (see the UA above and replies) or in practice. Accordingly, IIT's testable predictions are then either trivial or not direct evidence of IIT because other theories might make the same predictions. See for example:

[Michel M, Lau H (2020) On the dangers of conflating strong and weak versions of a theory of consciousness.](https://doi.org/10.33735/phimisci.2020.II.54)

I have discussed this paper [here](../fundamental-IIT). 
Nevertheless, a few clarifications: First, while a positive experimental outcome may not be direct evidence in favor of IIT specifically, a negative experimental outcome would be evidence against it (or at least against the assumptions that led to the prediction, as always). In other words, IIT is clearly falsifiable. Moreover, others have argued that a theory should not be measured (solely) by testability, but rather by whether it moves the field forward [(Negro, 2020)](https://doi.org/10.1007/s11097-900 020-09681-3). While I appreciate and endorse this philosophical clarification, the accusation that IIT makes only non-specific or untestable predictions is simply false in the first place, see e.g. [(Ellia et al., 2021)](https://doi.org/10.1093/nc/niab032), [(Haun and Tononi, 2019)](https://www.mdpi.com/1099-4300/21/12/1160), and [(Tononi et al., 2016)](https://www.nature.com/articles/nrn-2016-44#Sec7). 

#### IIT has untestable implications ...


Another concern regarding IIT's testability is that IIT makes (wild) predictions about the consciousness of certain non-human and artificial systems that are untestable in principle, and we should avoid such speculation [(Fleming et al., 2023)](https://psyarxiv.com/zsr78/). 
As discussed above, the available test cases for consciousness science are necessarily limited (to human subjects and animals with similar brain structures). Therefore, any theory that is more generally applicable will make untestable predictions. Accordingly, we distinguish between "predictions" (testable in principle) and "extrapolations" (implications of a theory that are not testable, even in principle) in IIT publications. 

#### ... and I don't like them

Any theory of consciousness that is sufficiently formulated will necessarily specify a minimal system that fits all criteria for consciousness according to that theory but will defy our intuitions. [Doerig et al. (2020)](https://doi.org/10.1080/17588928.2020.1772214) called this the "small network argument". We can either accept this or conclude that the theory only provides necessary but not sufficient criteria for consciousness. However, any additional criterion proposed should increase the theory's explanatory power (for testable cases). Otherwise, it would be ad-hoc and thus unjustified. 

This last point is also the gist of the [official reply](http://www.scottaaronson.com/tononi.docx) to [Scott Aaronson's (in)famous expander-graph argument against IIT](https://scottaaronson.blog/?p=1799) (plus the fact that we can't use expander graphs as evidence against IIT, see replies to the UA above). In Scott's reply to the reply he pointed to a few things that were not accurate: as shown in [(Haun et al., 2019)](https://www.mdpi.com/1099-4300/21/12/1160) grid-like neural networks, including 1-D grids, have the minimally necessary causal structure to account for spatial experiences. Moreover, we do not know whether or not the cerebellum in itself is conscious. What we do know is that it does not seem to contribute to our consciousness even though it is very much connected to the rest of the brain. This is what requires explanation and we have since been more careful about our description of the cerebellum example.

Some have argued that a way to (temporarily) avoid uncomfortable extrapolations is to refrain from a detailed formulation in the first place [(Mediano et al., 2022)](https://doi.org/10.1016/j.tics.2022.04.008). Why scare people away by exploring a theory's extrapolations when there is still a lot of experimental work to be done that does not require a detailed formulation? I have a lot of sympathy for this approach, although I ultimately think it amounts to throwing the baby out with the bathwater. In my opinion, the current debate around IIT shows that it is time to face some of the philosophical challenges surrounding a scientific approach to consciousness, rather than sweeping them under the rug for later. 

It would do the field a lot of good if other theory proposals were formulated in sufficient detail to apply them to toy example systems. The goal is not to compare which theory makes the wildest extrapolations. Applying a theoretical framework to simple example systems allows us to evaluate its internal consistency and to test whether the theory, properly implemented, makes conceptual sense in the first place. 
Insights gained from such theoretical work can then be used to develop more specific predictions. 

### Conclusion

Despite the recent update to IIT version 4.0, the theory remains under development. I certainly would not rule out an alternative formulation that, for instance, is more palatable in terms of its extrapolations, and I would encourage everyone with ideas in that direction to go for it. The measures of success, however, must remain explanatory power and conceptual consistency, not intuition or personal bias.

##### **Acknowledgements:** Many thanks to Tom Bugnon, Jonathan Lang, and my fellow IIT contributors affiliated with the [Center for Sleep and Consciousness at UW Madison](https://centerforsleepandconsciousness.psychiatry.wisc.edu/) for their help with compiling the references, and to Jeremiah Hendren for detailed edits. 





