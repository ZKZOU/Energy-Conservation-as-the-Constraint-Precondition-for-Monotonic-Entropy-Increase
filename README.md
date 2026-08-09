# Energy Conservation as the Constraint Precondition for Monotonic Entropy Increase: The Intrinsic Mathematical Structure Between the First and Second Laws of Thermodynamics

**Zou, Zhi Kai** (邹志凯)  
Independent Researcher  
Email: zhiyan.zou@foxmail.com  
Wuhan, China  
https://orcid.org/0009-0000-4279-1064  
Funding Declaration: No funding was received

---

## Abstract

Building upon the gradient-driven multiplicative entropy framework proposed by Zou (2025) [3], this paper reveals the intrinsic mathematical constraint structure between the first and second laws of thermodynamics. In this framework, the entropy of a system is defined as \( S = \prod_i m_i \), where \( m_i \) denotes the quantized energy value carried by each discrete node, subject to the strict conservation of total energy \( E = \sum_i m_i \). Energy transfer follows a rigorous gradient-driven rule: energy flows exclusively from higher-valued nodes to lower-valued nodes \( (m_i > m_j + 1) \). This paper demonstrates that, under this multiplicative entropy formulation, the first law is not merely an independent postulate standing alongside the second law, but rather serves as the constraint precondition for the monotonic increase of entropy—energy conservation, via the arithmetic-geometric mean inequality, directly yields the upper bound of entropy \( S \leq (E/N)^N \), while the gradient-driven rule ensures that every step of energy transfer strictly increases the multiplicative entropy. In this manner, the two laws of thermodynamics are unified into a single dynamical process—namely, gradient-driven evolution under a conservation constraint—wherein entropy increase no longer depends on probabilistic or statistical assumptions, but is a necessary consequence jointly determined by energy conservation and the existence of energy gradients.

**Keywords**: multiplicative entropy; gradient-driven; energy conservation; first law of thermodynamics; second law of thermodynamics; non-probabilistic entropy; constraint-dynamics relation

---

## 1. Introduction

The first law of thermodynamics (energy conservation) and the second law (entropy increase) are two of the most fundamental and universal laws in physics. Since the establishment of thermodynamics in the nineteenth century, these two laws have been regarded as mutually independent, basic postulates: the first law asserts that energy can neither be created nor destroyed, while the second law asserts that the entropy of an isolated system never decreases. Although both laws operate simultaneously in physical processes, classical thermodynamics does not provide a precise mathematical constraint relation between them.

In traditional statistical mechanics, entropy is defined as \( S = k_B \ln \Omega \), where \( \Omega \) is the number of microstates of the system. This definition has achieved great success in macroscopic thermodynamics, yet it also brings a fundamental epistemological problem: the value of \( \Omega \) depends on how the observer defines the boundary between "micro" and "macro", depends on the choice of coarse-graining scale, and depends on which degrees of freedom are considered "relevant" and which are "negligible". In other words, the value of statistical entropy depends in part on the observer's level of description, rather than being entirely determined by the physical state of the system itself. This leads to a profound question: does statistical entropy measure the physical state of the system itself, or the observer's missing information?

More importantly, the definition of statistical entropy does not contain the concept of "energy gradient". It tells us that a uniform distribution is the maximum entropy state, but it does not tell us how the system approaches uniformity step by step, what the path of each energy transfer is, or what the magnitude of the gradient is at each step. These questions cannot be directly answered by statistical entropy, because its definition does not contain the physical quantity of "gradient".

However, all real dynamical processes in nature—heat conduction, diffusion, chemical reactions, and electric currents—are driven by a unified physical quantity: the energy gradient. Heat flows from high temperature to low temperature; matter flows from high concentration to low concentration; charge flows from high potential to low potential; mechanical systems move from high potential energy to low potential energy. In all known natural processes, the flow of energy from higher to lower is the sole source of irreversibility.

This paper, based on the gradient-driven multiplicative entropy framework proposed by Zou (2025), aims to answer the following core question: Is there a precise mathematical constraint relation between the first and second laws of thermodynamics? If so, what is the specific structure of this relation?

We will demonstrate that, under the definition of multiplicative entropy, the first law (energy conservation) is not merely a prerequisite for the second law (entropy increase), but directly yields the mathematical upper bound of entropy via the arithmetic-geometric mean inequality, thereby providing a non-probabilistic, necessary mathematical foundation for the monotonic increase of the second law.

---

## 2. Definition of Multiplicative Entropy and the Gradient-Driven Rule

### 2.1 Basic Setting of the Discrete Node System

Consider a closed system consisting of \( N \) nodes. Each node carries a certain amount of energy, with energy quantized in units of Planck's constant \( h \):

\[
m_i \in \mathbb{N}^+
\]

where \( m_i \) is the energy value carried by the \( i \)-th node (in units of \( h \)).

The total energy of the system is strictly conserved:

\[
E = \sum_i m_i = \text{constant}
\]

Energy transfer between nodes is allowed only between adjacent nodes, one unit at a time, and only when an energy gradient exists:

**Transfer condition**:

\[
m_i > m_j + 1
\]

**Transfer rule**:

\[
m_i \rightarrow m_i - 1, \quad m_j \rightarrow m_j + 1
\]

Here "1" represents one unit of Planck's constant \( h \). These rules constitute the complete dynamical rules of the system—no probability, no ensembles, no randomness, no external driving, and no artificially chosen coarse-graining scale. The evolutionary direction of the system at each step is entirely determined by the current energy gradient distribution.

### 2.2 Definition of Multiplicative Entropy

Define the entropy of the system as the product of all node energy values:

\[
S = \prod_i m_i
\]

This definition has the following characteristics:

- Does not depend on probability distributions;
- Does not depend on ensemble assumptions;
- Does not depend on coarse-graining operations;
- Does not depend on logarithmic approximation;
- Is uniquely determined by the current energy distribution;
- Is a positive integer.

More importantly, it directly reflects the outcome of gradient-driven evolution.

### 2.3 Calculation of Entropy Change

Before and after each energy transfer, the change in entropy can be precisely calculated. Let the energies of the two participating nodes before transfer be \( a \) and \( b \) (with \( a > b + 1 \)), and after transfer become \( a - 1 \) and \( b + 1 \). The ratio of entropy values is:

\[
\frac{S'}{S} = \frac{(a - 1)(b + 1)}{a \cdot b}
\]

Expanding:

\[
\frac{S'}{S} = 1 + \frac{a - b - 1}{a \cdot b}
\]

Since the transfer condition is \( a > b + 1 \), i.e., \( a - b - 1 > 0 \), and \( a, b > 0 \), we have:

\[
\frac{S'}{S} > 1
\]

That is:

\[
S' > S
\]

Every legitimate energy transfer necessarily leads to a strict increase in multiplicative entropy. The magnitude of the entropy increase is directly related to the energy gradient \( a - b \) before the transfer—the larger the gradient, the greater the entropy increase.

### 2.4 Logarithmic Relation to Classical Entropy

Taking the logarithm of multiplicative entropy:

\[
\ln S = \sum_i \ln m_i
\]

Under conditions where the energy distribution is relatively uniform, \( \ln S \) can be related to the traditional Boltzmann entropy \( S = k_B \ln \Omega \) through Stirling's approximation or other statistical methods. This indicates that multiplicative entropy can recover classical thermodynamic results in the appropriate macroscopic limit, while simultaneously providing a finer description for discrete systems.

---

## 3. The First Law as the Constraint Precondition for the Second Law

### 3.1 The Upper Bound of Multiplicative Entropy: Application of the AM-GM Inequality

This section proves the core proposition: energy conservation directly yields the mathematical upper bound of multiplicative entropy.

For \( N \) positive real numbers \( m_1, m_2, \ldots, m_N \), the arithmetic-geometric mean inequality (AM-GM inequality) gives:

\[
\frac{m_1 + m_2 + \cdots + m_N}{N} \geq (m_1 \cdot m_2 \cdots m_N)^{1/N}
\]

That is:

\[
\frac{E}{N} \geq S^{1/N}
\]

Raising both sides to the \( N \)-th power:

\[
\left(\frac{E}{N}\right)^N \geq \prod_i m_i = S
\]

Therefore:

\[
S \leq \left(\frac{E}{N}\right)^N
\]

The condition for equality (the equality condition of the AM-GM inequality):

\[
m_1 = m_2 = \cdots = m_N = \frac{E}{N}
\]

That is, when the system energy reaches a perfectly uniform distribution, the multiplicative entropy attains its maximum value:

\[
S_{\text{max}} = \left(\frac{E}{N}\right)^N
\]

### 3.2 Structural Analysis of the Constraint Relation

The above derivation reveals the precise mathematical structure between the first and second laws:

| Law | Role in This Framework | Mathematical Expression |
| :--- | :--- | :--- |
| **First Law (Energy Conservation)** | **Constraint Precondition**: Determines the accessible state space | \( E = \sum_i m_i = \text{constant} \) |
| **Second Law (Entropy Increase)** | **Dynamical Output**: Determines the actual evolutionary path | \( S = \prod_i m_i \) increases monotonically |

The first law delineates the "accessible surface" in state space—all possible energy distributions must satisfy the constraint that the total energy is \( E \). On this surface, the multiplicative entropy \( S = \prod_i m_i \) has a definite upper bound \( (E/N)^N \), which is uniquely determined by the first law through the AM-GM inequality.

The second law specifies the direction of actual motion on the accessible surface—the gradient-driven rule ensures that every step evolves toward increasing entropy, ultimately approaching the maximum entropy state given by the AM-GM inequality.

**Key insight**: The first law not only specifies "which states are accessible", but also directly gives, through the AM-GM inequality, "what is the maximum value of entropy among the accessible states". The monotonic increase of the second law is then the necessary dynamical consequence of the gradient-driven rule under the constraint of energy conservation.

### 3.3 Relation to Classical Thermodynamics

In the traditional statistical entropy formulation, there is no explicit mathematical derivational relation between the first and second laws. The maximum entropy state \( S_{\text{max}} = k_B \ln \Omega_{\text{max}} \) is usually obtained through statistical methods (such as the equal a priori probability assumption), rather than derived directly from energy conservation.

In this framework, the maximum entropy value \( S_{\text{max}} = (E/N)^N \) is derived directly from energy conservation, requiring no probabilistic assumptions whatsoever. This represents a fundamental epistemological difference between the two formulations of entropy:

| Dimension | Traditional Statistical Entropy | Multiplicative Entropy |
| :--- | :--- | :--- |
| Origin of entropy maximum | Statistical assumptions (equal a priori probability) | Energy conservation (AM-GM inequality) |
| Necessity of entropy increase | Probabilistic ("most likely") | Necessary (guaranteed by gradient-driven rule) |
| Role of the first law | Independent postulate alongside the second law | Constraint precondition for the second law |
| Foundation of the second law | Statistical ensemble assumptions | Gradient-driven rule + energy conservation |

### 3.4 Numerical Example

Consider a system with \( N = 4 \) nodes and total energy \( E = 12 \). The upper bound of multiplicative entropy is:

\[
S_{\text{max}} = \left(\frac{12}{4}\right)^4 = 3^4 = 81
\]

When the system is in a non-uniform state \([3, 1, 5, 3]\):

\[
S = 3 \times 1 \times 5 \times 3 = 45
\]

Under the gradient-driven rule, through successive energy transfers, the system may evolve to the uniform state \([3, 3, 3, 3]\):

\[
S = 3 \times 3 \times 3 \times 3 = 81 = S_{\text{max}}
\]

The entropy values at each step are:

| State | Energy Distribution | Multiplicative Entropy | Increase from Previous |
| :--- | :--- | :--- | :--- |
| Initial | [3, 1, 5, 3] | 45 | — |
| Intermediate | [3, 2, 4, 3] | 72 | +27 |
| Final | [3, 3, 3, 3] | 81 | +9 |

Entropy strictly increases at every step until reaching the maximum value bounded by the AM-GM inequality.

It is worth noting that, since energy is transferred in integer quanta, not all systems can reach a perfectly uniform distribution. For example, when the total energy \( E \) is not divisible by \( N \), the maximum entropy state is the distribution in which all node energies are as close as possible (i.e., some nodes carry \( \lfloor E/N \rfloor \) and others carry \( \lceil E/N \rceil \)). The multiplicative entropy still satisfies the upper bound \( S \leq (E/N)^N \).

---

## 4. The Necessity of Gradient-Driven Evolution: Eliminating Probabilistic Interpretation

### 4.1 Equivalence of the "Maximum Entropy Path" and the "Maximum Gradient Path"

In this framework, each step of energy transfer follows the direction of the maximum energy gradient. The ratio of entropy before transfer \( S \) to entropy after transfer \( S' \) is:

\[
\frac{S'}{S} = 1 + \frac{a - b - 1}{a \cdot b}
\]

This expression directly shows: the larger the energy gradient, the greater the entropy increase. Therefore, in this framework, the "maximum entropy path" and the "maximum gradient path" are equivalent—the system evolves along the direction of maximum entropy increase, which is precisely the direction of maximum energy gradient.

This equivalence transforms the second law of thermodynamics from a statistical statement about "probability" into a dynamical statement about "gradient".

### 4.2 Necessity vs. Probability of Entropy Increase

In traditional statistical mechanics, the formulation of the second law relies on probabilistic language:

> "The entropy of an isolated system tends to increase."  
> "High-entropy states are more probable than low-entropy states."  
> "The system tends toward the most probable macroscopic state."

These statements are mathematically valid, but leave an open question at the conceptual level: what does "tend" mean? If the system is only "more likely" to move toward a high-entropy state, is entropy increase a physical necessity or a statistical contingency?

In this framework, this question is completely eliminated:

> As long as an energy gradient exists, energy will flow along the gradient; each step of flow increases the entropy value; this process has no exceptions and does not depend on any statistical assumptions.

The second law is no longer:

> "An isolated system will most likely move toward a high-entropy state."

But rather:

> "An isolated system with an energy gradient will necessarily redistribute its energy distribution along the gradient direction; this redistribution process is precisely the process of entropy increase."

### 4.3 Epistemological Differences Between the Two Formulations

| Dimension | Traditional Statistical Formulation | Formulation in This Framework |
| :--- | :--- | :--- |
| Nature of entropy increase | "Probable" | "Necessary" |
| Definition of entropy | Logarithm of "number of microstates" | "Product of energy distribution" |
| Basis of the second law | Depends on ensemble assumptions | Directly derived from gradient-driven rules |
| Prerequisite | Probability is a prerequisite | Probability is not a prerequisite; gradient is |
| Coarse-graining | Coarse-graining is necessary | Coarse-graining is not necessary |

This difference directly affects our understanding of "irreversibility". In this framework, irreversibility is written directly into the dynamical rules—energy flow along a gradient is irreversible, because reverse flow would require energy to move from low to high, which violates the precondition of gradient driving. Irreversibility is not a statistical byproduct, but a direct product of gradient driving.

---

## 5. Compatibility with Classical Thermodynamics

### 5.1 Recovery in the Macroscopic Limit

Although this framework is based on a discrete node network, in the appropriate macroscopic limit (number of nodes \( N \to \infty \), energy quantum \( h \to 0 \)), multiplicative entropy can recover the results of classical thermodynamics.

Taking the logarithm of multiplicative entropy:

\[
\ln S = \sum_i \ln m_i
\]

Under conditions where the energy distribution is relatively smooth, the standard methods of statistical mechanics can establish a correspondence between \( \ln S \) and the Boltzmann entropy \( S_{\text{Boltzmann}} = k_B \ln \Omega \). The monotonic increase of multiplicative entropy is preserved under logarithmic transformation, and is therefore consistent with the classical principle of entropy increase.

### 5.2 Reinterpretation of Classical Thermodynamic Concepts

| Classical Concept | Interpretation in This Framework |
| :--- | :--- |
| Thermal equilibrium | State in which all node energies are equal (or differ by no more than one quantum unit), where multiplicative entropy attains its maximum |
| Irreversible process | Unidirectional transfer of energy along the gradient direction |
| Entropy production | Increase in multiplicative entropy at each step of energy transfer |
| Second law of thermodynamics | Mathematical necessity jointly guaranteed by the gradient-driven rule and the AM-GM inequality |
| Role of the first law | Determines the upper bound of entropy, rather than merely serving as an independent statement of energy conservation |

### 5.3 Conditions of Applicability

A system can adopt a multiplicative entropy description if it satisfies the following conditions:

1. The number of units carrying numerical values remains constant;
2. Each unit is associated with a quantifiable value (e.g., energy, resource amount, or population size);
3. The total sum of all unit values is conserved;
4. The dynamical evolution follows a flow or exchange rule wherein quantities transfer from units with higher values to those with lower values;
5. The numerical value carried by each unit can be unitized, i.e., expressed as an integer multiple of the basic unit.

The fifth condition is not a necessary requirement for the definition of multiplicative entropy itself. However, satisfying this condition ensures that the computed entropy value is an integer, which is particularly convenient for computer simulations and numerical implementations.

---

## 6. Conclusion

This paper, based on the gradient-driven multiplicative entropy framework proposed by Zou (2025), has demonstrated the existence of a precise mathematical constraint structure between the first and second laws of thermodynamics:

The first law (energy conservation) \( E = \sum_i m_i = \text{constant} \), as the constraint precondition, directly yields the mathematical upper bound of multiplicative entropy \( S = \prod_i m_i \) via the arithmetic-geometric mean inequality: \( S \leq (E/N)^N \). The second law (entropy increase) is then the necessary dynamical output of the gradient-driven rule under this constraint—every legitimate step of energy transfer strictly increases the multiplicative entropy until reaching the maximum value bounded by the AM-GM inequality.

The core contributions of this framework are:

1. **It reveals the mathematical constraint relation between the first and second laws**: they are no longer independent postulates standing side by side, but rather complement each other as "constraint" and "drive";
2. **It eliminates the probabilistic interpretation of entropy increase**: entropy increase is no longer a statistical "possibility", but a necessary consequence jointly determined by energy conservation and the existence of gradients;
3. **It provides a non-probabilistic definition of entropy**: multiplicative entropy does not depend on the observer's choice of coarse-graining, and is entirely determined by the system's own energy distribution;
4. **It establishes the equivalence between the maximum entropy path and the maximum gradient path**: the direction of maximum entropy increase is precisely the direction of maximum energy gradient, providing an intuitive dynamical foundation for the second law.

From an epistemological perspective, this framework reduces the two laws of thermodynamics from a "statistical formulation" to a "geometric-dynamical formulation"—entropy increase is no longer a vague proposition dependent on probabilistic language, but an irreversible evolutionary process directly driven by energy gradients and trackable step by step. In this framework, the underlying principles of thermodynamics are visible, understandable, and countable. It no longer answers "what we do not know." It answers: "what is happening, and how it is happening."

---

## References

[1]Max Planck. (1901). Ueber das Gesetz der Energieverteilung im Normalspectrum. Annalen der Physik. https://doi.org/10.1002/andp.19013090310 

[2]Annila A(2025), Comprehensible dynamics of quanta: from the quantum of action to the 2nd law of thermodynamics. Eur. Phys. J. Plus 140, 28 2025. https://doi.org/10.1140/epjp/s13360-025-05970 

[3]Zou,  Z. K. (2025). The Thermodynamic Arrow of Time in a Double-Layer Topology-Invariant Chiral Space with Geometric (GR) and Gauge (QFT) Degrees of Freedom :Time-Entropy Mapping; Mass-Gravity Duality; Metric-Frequency Mirroring. Preprints. https://doi.org/10.20944/preprints202505.0270.v12 
