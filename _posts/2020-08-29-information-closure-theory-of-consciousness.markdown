---
layout: post
title:  "Information Closure Theory of Consciousness"
disqus_id: 2020-08-29-Chang2020
date:   2020-08-29
tags: Theory
comments: true
type: Review
paperauthors: "Chang AYC, Biehl M, Yen Y, Kanai R"
articlelink: https://doi.org/10.3389/fpsyg.2020.01504
year: 2020
journalinfo: "Frontiers in Psychology, 11, 1504"
---

### Summary

Consciousness runs at a particular macro spatio-temporal scale. This fact is often underappreciated as a characteristic of our phenomenology that requires a principled explanation. Here, however, it is the starting point for a newly conceived theory of consciousness, the “information closure theory” (ICT) proposed by Chang et al. 2020. 

ICT is reminiscent of several existing theories of consciousness, including IIT, but the underlying quantity to be evaluated is different from previous proposals. According to ICT, a system is conscious if it forms a C-process (p.4,  Definition 2). The level of consciousness then corresponds to the degree of non-trivial information closure (NTIC) of the system (Bertschinger et al., 2006), the system's state corresponds to its conscious content.

### Why discuss this paper?

ICT shares a number of characteristics with IIT: it is based on information, but is non-functional in its hypothesis; it is aimed at identifying conscious systems at particular spatio-temporal grains; to some degree it even takes an intrinsic perspective with respect to the information available to the system itself at a particular scale.

However, ICT also explicitly rejects some of IIT’s postulates, such as causal exclusion. ICT thus presents an interesting case study in what goes awry once certain essential aspects of IIT are omitted. My expectation is that in trying to improve upon this initial version of ICT, the theory will gradually move closer towards IIT in its formulation and in its predictions. 

##### [Moreover, and most crucially, ICT does not take phenomenology as its starting point, but here I will focus on the theory's technical aspects.]

### Commentary
A system is informationally closed when the flow of information from the environment to the system is zero. This is trivial if the system is independent of the environment, but rather tricky if it is not. Non-trivial information closure may be achieved by two types of systems: ones that model their environment, but also systems that are completely driven by their environment ("passive adaptation"). 

##### [What makes things complicated is that the NTIC measure as defined in eq. 6 + 7 does not in itself imply zero information flow from the environment to the system (see also [Bertschinger et al., 2006](https://www.mis.mpg.de/fileadmin/olbrich/bertschinger_information.pdf)). NTIC > 0 is thus not sufficient for being a conscious entity, or a "C-process" (as called in this paper). In addition, a "C-process" must be a coarse-graining (see Definition 1) that is informationally closed with respect to the underlying microscopic process, which also implies full information closure with respect to the system's environment.]

Full information closure, however, can only be achieved by a modelling system if it *perfectly* predicts any non-random influences from the environment onto itself. *How could this possibly be true for our own neural substrate of consciousness?* I can obviously perceive and experience an unexpected sequence of images, or a tiger jumping out of the woods seemingly from nowhere. It thus seems to me that the definition of a "C-process" must either be weakened in some way, or the measure must at least become state-dependent. Note that the former would likely require a notion of exclusion to avoid a proliferation of C-processes across elements and spatio-temporal scales, while the latter would still imply that I only become conscious of an unexpected stimulus once my brain has settled into a state from which it predicts the tiger to be there.

##### [The definition of NTIC is based on mutual information, which is state-independent. This feature is problematic for a measure that aims to quantify the level of consciousness of a system. Moreover, to be computed, a joint probability distribution of the environment and the current and next system state is required. There are multiple possibilities here, from the observed distribution over a given period of time, to the stationary observed distribution, to an interventional distribution. Which of these should be used is not explicitly specified in the paper, but all three will typically give different results.]

On the other hand, any feedforward system that receives inputs from a deterministic environmental process can achieve informational closure. What is more, for an n-layer feedforward network that is a C-process, any combination of its layers would also count as a separate C-process (see *Integration and Exclusion* below). While the authors argue that such passive adaptation is not advantageous for any real system, the fact that it is possible in principle is sufficient to show that informational closure is not a good candidate to solve the problem of individuality (i.e., identifying (conscious) individuals).

#### What else is missing? Composition, Integration, Exclusion

As it stands, the content of consciousness in ICT simply corresponds to the current state of the C-process. However, a pattern of activity in itself cannot account for the rich structure of phenomenology (Compositon). For that, it is crucial to characterize the system's components and their relations (see, e.g., [Haun and Tononi, 2019](https://www.mdpi.com/1099-4300/21/12/1160) and also [Northoff et al. (2019)](https://www.mdpi.com/1099-4300/21/12/1234/htm).

On p.9 the authors explicitly distance themselves from IIT’s exclusion principle. If there are multiple C-processes at various coarse-grainings over the same micro-substrate, all of them should form separate conscious entities (see their Fig. 4). However, without a proper notion of irreducibility (as in IIT’s integration postulate), all supersets of C-processes would thus form their own C-processes in turn. Any group of conscious individuals would thus have to have a separate conscious experience of its own (The authors recognize this as an issue, see Section 7. Limitations and Future Work).

Nevertheless, the exclusion postulate in IIT also serves to identify the borders of a system within a particular level. By constrast, ICT does allow for the possibility of overlapping or nested conscious entities. While it is true that we ultimately cannot exclude the possibility of other consciousnesses overlapping with our own from within our experience, a conscious system requires definite borders. As argued above, I do not think that information closure by itself can avoid the boundary detection problem.

### Conclusion
Take ICT, replace the mutual information measure with a state-dependent causal measure (as recoginzed in [Bertschinger et al. (2008)](https://www.sciencedirect.com/science/article/abs/pii/S0303264707001037?via%3Dihub) for their measure of autonomy), add compositon, integration, and probably also exclusion, and we might get closer to a theory that is able to account for conscious experience.
