
My research investigates fundamental problems in **quantum many-body physics** and **quantum error correction**, with a particular focus on topological phases, symmetries, and quantum anomalies. Especially in recent years, I have been using **symmetry** as a unifying viewpoint to systematically understand the universal structure and dynamics of strongly correlated quantum systems and error-correcting codes.

Below I briefly summarize my past and current research by themes.

---

{{< details "1. Symmetry of Quantum Error-Correcting Codes and Logical Gates" >}}

In quantum error correction, it is crucial not only to build codes robust against noise, but also to understand **how to implement logical computation (logical gates) on encoded qubits**. A central theme of my work is that generalized symmetries in quantum matter are deeply tied to the structure of logical gates in stabilizer codes.

For example, I showed that finite-group gauge theories—including the Z2 toric code—**universally exhibit higher-group symmetries**. These generalized symmetries can be interpreted as logical operations, and their algebraic structure leads to the **Clifford hierarchy**, thereby revealing symmetry principles that enable **non-Clifford logical gates** essential for universal fault-tolerant quantum computation.  
([arXiv:2208.07367](https://arxiv.org/abs/2208.07367), [arXiv:2211.11764](https://arxiv.org/abs/2211.11764))

Building on this, I discovered a new emergent **Z8 symmetry** in the 3D Z2 toric code and demonstrated that it gives rise to transversal non-Clifford gates such as **CCZ / CS / T**.  
([arXiv:2311.05674](https://arxiv.org/abs/2311.05674))

More recently, I constructed the **first example of a self-correcting quantum memory with non-Abelian excitations**, which is also the first instance of a thermally stable non-Abelian topological order. The model supports a transversal **non-Clifford CCZ** gate, and I showed that it achieves a code-distance scaling that surpasses that of known color codes.  
([arXiv:2405.11719](https://arxiv.org/abs/2405.11719))

I further discovered a broad family of **Clifford-hierarchy stabilizer codes**, which support transversal non-Clifford gates at level d+1 in spatial dimension $d$. These codes break the well-known **Bravyi–König bound** for Pauli stabilizer codes, demonstrating that transversal gate constraints can be fundamentally circumvented in broader code families.  
([arXiv:2511.02900](https://arxiv.org/abs/2511.02900))

**Keywords:** generalized symmetries, topological codes, transversal gates, magic states, classification of logical gates

{{< /details >}}

{{< details "2. Invariants and Response Theories in Quantum Many-Body Systems" >}}


Topological phases exhibit striking boundary phenomena. For instance, in (2+1) dimensions, a nonzero **thermal Hall conductivity** implies **gapless edge modes**. However, there are also situations where the thermal Hall response vanishes (c- = 0) and yet gapless boundaries are unavoidable. Motivated by this, recent developments have identified the **higher central charge** as a key invariant controlling whether a topologically ordered phase can admit a gapped boundary.

I developed a way to physically characterize and compute the **higher central charge** directly from a ground-state wavefunction by applying a **partial rotation** operator and evaluating its expectation value. This provides an observable definition of the invariant, accessible both in numerical simulations and (in principle) measurement protocols on quantum computing platforms. Using this method, I showed that for **Abelian topological orders**, the higher central charge completely determines whether gapped boundaries can exist, based on a single wavefunction.  
([arXiv:2303.04822](https://arxiv.org/abs/2303.04822))

Extending this line of work, I proposed a new invariant—the **higher Hall conductivity**—which generalizes both the electric and thermal Hall responses in U(1)-symmetric systems. I showed that even if the conventional Hall conductivities vanish, a nontrivial higher Hall conductivity can still enforce **protected gapless edge states under U(1) symmetry**.  
([arXiv:2203.08156](https://arxiv.org/abs/2203.08156), [arXiv:2404.10814](https://arxiv.org/abs/2404.10814))

I have also proposed frameworks to extract invariants in topological phases enriched by **crystalline symmetries**, including fractional Chern insulators. In particular, I found that the standard Chern insulator becomes a nontrivial crystalline topological phase when **mirror reflection is combined with time-reversal symmetry (RT symmetry)**, and I identified a corresponding new crystalline invariant characterizing this phase.  
([arXiv:2303.16919](https://arxiv.org/abs/2303.16919), [arXiv:2403.18887](https://arxiv.org/abs/2403.18887), [arXiv:2405.17431](https://arxiv.org/abs/2405.17431))

**Keywords:** topological invariants, edge physics, crystalline symmetries, numerical diagnostics

{{< /details >}}

{{< details "3. Higher-Form Symmetry and Microscopic Diagnostics of Quantum Anomalies" >}}


Another central theme of my recent research is to develop **microscopic (lattice-level) diagnostics** of quantum anomalies based on generalized symmetries. I proposed a universal framework to compute topological invariants in lattice models with internal or generalized symmetries by evaluating expectation values of composite symmetry operators directly in the many-body wavefunction.  
([arXiv:2412.01886](https://arxiv.org/abs/2412.01886))

These invariants provide microscopic manifestations of quantum anomalies and impose stringent constraints on low-energy behavior. In particular, if such an invariant is nonzero, the state **cannot be a trivial symmetric gapped phase**, strongly narrowing down what is possible in the infrared.

Higher-form symmetries play a particularly important role in describing quantum spin liquids, gauge theories, and topologically ordered phases. I proved that anomalies associated with higher-form symmetries enforce a **strong form of long-range entanglement**: the fidelity between the system’s state and any short-range-entangled state decays exponentially with system size. In other words, anomalous higher-form symmetries prohibit any approximation by short-range-entangled states.  
([arXiv:2504.10569](https://arxiv.org/abs/2504.10569))

I also investigated how higher-form symmetries can be defined and realized on microscopic lattice models, establishing a general lattice formulation of **higher-form symmetry anomalies**, and I clarified precise criteria for when a higher-form symmetry can be realized as an **onsite** symmetry.  
([arXiv:2509.12304](https://arxiv.org/abs/2509.12304), [arXiv:2510.23701](https://arxiv.org/abs/2510.23701))

**Keywords:** higher-form symmetry, quantum anomalies, lattice diagnostics, long-range entanglement, open quantum systems

{{< /details >}}

{{< details "4. Non-Invertible Symmetries and Their Physical Consequences" >}}


Traditionally, symmetries have been formulated as invertible operations forming a group. Recently, it has become clear that symmetry can be generalized further: **non-invertible operators** can also generate symmetries (non-invertible symmetries).

I showed that in quantum many-body systems with non-invertible symmetries, one can obtain **Hall-type responses** and **symmetry fractionalization** phenomena analogous to those in fractional quantum Hall states.  
([arXiv:2405.20401](https://arxiv.org/abs/2405.20401))

I also studied situations where an ordinary (invertible) symmetry becomes effectively non-invertible through coupling to a partially dynamical gauge field—so-called **coset symmetries**. I analyzed their responses and anomalies systematically and showed that for certain discrete coset symmetries, a **symmetric gapped phase is forbidden**.  
([arXiv:2503.00105](https://arxiv.org/abs/2503.00105))

Furthermore, for discrete non-invertible symmetries, I showed that even when the symmetry is completely spontaneously broken, distinct gapped phases can still be meaningfully classified. I constructed explicit lattice models realizing such phases and demonstrated that nontrivial **interface modes** appear at boundaries between different symmetry-broken phases.  
([arXiv:2501.03314](https://arxiv.org/abs/2501.03314), [arXiv:2507.12515](https://arxiv.org/abs/2507.12515))

**Keywords:** non-invertible symmetry, coset symmetry, Hall responses, phase classification, interfaces

{{< /details >}}

{{< details "5. Symmetry, Quantum Anomalies, and Boundaries of Topological Phases (SPT/SET)" >}}


Among gapped quantum phases, **symmetry-protected topological (SPT) phases** are those that do not spontaneously break global symmetries and do not have ground-state degeneracy. A hallmark of SPT phases is the presence of nontrivial boundary phenomena; topological insulators and topological superconductors are well-known examples.

The nontriviality of SPT boundaries is naturally explained by **(’t Hooft) quantum anomalies** in the corresponding field theories. Because anomalies are invariant under renormalization group flow, the low-energy theory must retain degrees of freedom that reproduce the anomaly. This prohibits a boundary from becoming a trivial symmetric insulator.

I studied qualitative relationships between anomalies and energy gaps in both bosonic and fermionic systems. While perturbative anomalies typically force gapless boundary modes, more general (non-perturbative) anomalies can be saturated by a **symmetry-preserving topological order**, i.e., a **symmetry-enriched topological (SET) phase**. A key question is therefore: which SPT boundaries can be realized as symmetry-preserving gapped SET phases?

I showed that broad classes of fermionic SPT phases with finite-group symmetries, as well as SPT phases beyond group cohomology, admit boundaries realized by SET phases. I provided explicit constructions that define the corresponding SET effective theories locally, demonstrating that anomalies can be saturated by gapped topological degrees of freedom rather than gapless excitations.  
([arXiv:1905.05391](https://arxiv.org/abs/1905.05391), [arXiv:1905.05902](https://arxiv.org/abs/1905.05902))

In addition, I analyzed symmetry actions on (2+1)-dimensional bosonic/fermionic SET phases and derived explicit formulas that determine anomalies from algebraic data characterizing the topological order. This allows concrete computations of, for example, time-reversal anomalies in fermionic SET phases and U(1) anomalies relevant to surfaces of topological insulators/superconductors.  
([arXiv:2104.14567](https://arxiv.org/abs/2104.14567), [arXiv:2111.14827](https://arxiv.org/abs/2111.14827))

These results also lead to mathematical consequences: by constructing local (3+1)D path integrals from (2+1)D SET data, one obtains new combinatorial topological invariants for 4-manifolds. In particular, [arXiv:2104.14567](https://arxiv.org/abs/2104.14567) provides a first example of a **combinatorial invariant that distinguishes exotic smooth structures** such as RP4 and a “fake” RP4.

Finally, I pointed out that topological orders can possess symmetries that act nontrivially **without** anyon permutation or symmetry fractionalization—an effect that goes beyond the standard textbook pictures of symmetry actions in topologically ordered phases.  
([arXiv:2501.03314](https://arxiv.org/abs/2501.03314))

**Keywords:** SPT/SET, quantum anomalies, boundary theories, path integrals, topological order

{{< /details >}}

---

### For prospective students

The themes above connect abstract theory (**symmetry, anomalies, and field theory**) with concrete realizations (**lattice models, quantum error-correcting codes, and quantum computation**). My research directions may evolve over time, but if you find any of these topics exciting or feel that they resonate with your interests, I would be happy if you reach out.
