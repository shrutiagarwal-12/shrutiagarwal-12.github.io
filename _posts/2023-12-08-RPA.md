---
title: "Random Phase Approximation"
date: 2023-12-08
author: Shruti
---

RPA^ is one of the ways to get an effective theory for a system where it is assumed that the ground state is known and the excitations are calculated for the many-body state. The validity of RPA results relies upon the idea that the excitation energies would be smaller compared to the ground state energy. For a weak coupling case, the ground state would hardly change at the fundamental level. On the other hand, if a strong coupling leads to a phase transition and the ground state modifies significantly, RPA starts to break down. This also means that a divergence in susceptibility calculated via RPA would indicate the breaking down of RPA, implying invalidity of the assumed ground state and thus can be a good indication of phase transition.
An example of RPA (that we have seen in the class of advanced solid state physics) is where the Jelium model of electron gas responds to the applied (weak) electric field. As the name suggests, the ground state is assumed to be uniform electron gas, and the response to the applied field is calculated. The response of the electrons results in further modification of the electric field "seen" by the system, and the response is again modified. This feedback loop continues, and one extracts the effective susceptibility of the system for the electric field. The convergence of the loop, and hence finite susceptibility means the assumed ground state remains as the parent state in the system even with the presence of an electric field, whereas the divergence would imply that the perturbation to the system done by the field is drastic and the ground state is now changing as well, and hence a phase transition.

<mark style="background: #BBFABBA6;">In the energy regime adequate to be described by RPA, it is plausible to separate the role of the external probe, which excites the system, from its response. Each probe, photon, electron, neutrino, hadron, electric and magnetic field, sound wave, etc., is described by a specific set of operators depending on the type of interaction with the system. The response of the system depends only on the interactions between its fundamental components. For this reason, the many-body response is universal, independent of the specific probe that induces it. RPA evaluates this universal response.</mark>^^

Susceptibility is one of the major results computed using RPA. In the referred review article, the author delves deeper into RPA and provides RPA equations using three different approaches, and discusses certain characteristics of RPA via each method, which would otherwise be overlooked, making more extensive comments on the approximations, usefulness, and limitations at the same time.
I am concluding this article here and am ready to re-open it in the future. Shall I get more curious about it or see something related to this somewhere in my study that I poorly understand

^ Funny enough that in the framework of RPA, there is hardly any approximation of/using random phase. The author of the referred article has though provided brief comments on the origin of such a name.

Some open questions are left for now due to the lack of sufficient interest.
^^*Are they saying that the susceptibility is independent of the value of the external field or are they saying that susceptibility for each kind of probe would be universal? - Still a question
What is the relation between excitation and susceptibility?

Ref: arXiv:2303.05801v1 [nucl-th] 10 Mar 2023
