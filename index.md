---
layout: home
title: ACV 2026
image: /assets/images/moere.jpeg
---


First Workshop on Abstract and Concrete Techniques in Verification


July 24-25, 2026  
At [FLoC 2026](https://www.floc26.org/), affiliated with [LICS 2026](https://lics.siglog.org/lics26/) and [CAV 2026](https://conferences.i-cav.org/2026/)   
Lisbon, Portugal

## Workshop Scope

Formal verification research stands upon two lines of work. One is on *abstract mathematical semantics* of systems, defining systems’ behaviors based on which formal verification is conducted. The other one is on *concrete algorithms and methods* that enable efficient and scalable verification. 

The two lines have some marked differences in their ecosystems. For example, experimental evaluation is virtually a must for the latter, while it is not for the former. Their different orientations---abstract and concrete---have made them hard to communicate with each other. 

However, a recent scientific trend points to the need, feasibility, and prolificacy of the unification of abstract and concrete. On the abstract side, more works have implementations and experiments, demonstrating right away the practical value of their abstract theory. Conversely, on the concrete side, abstraction, generalization, and unification of various concrete verification methods have been actively sought. 

This way, a new form of unification of abstract and concrete is emerging, centered around the mathematical languages of lattices and categories. This also follows a well-beaten track of the successful collaboration between abstract and concrete in programming language research (such as monads in functional programming). Such unification is much desired, too, now that the hard-to-(logically-)model nature of statistical AI is posing methodological challenges to formal verification.

The goal of this workshop is to promote the unification of abstract and concrete and thus to incubate breakthroughs in formal verification. Specifically,

* we gather a wide audience from the formal verification community,  
* we share results, observations, and experience from both sides of abstract and concrete,  
* we seek a common language, and   
* we seek matchings between abstract theories and concrete techniques,

thereby picturing a new form of formal verification research in the AI era.

## Invited Speakers:

* [Syyeda Zainab Fatmi](https://zainabfatmi.github.io/), U Oxford, UK.   
  **Robust Probabilistic Bisimilarity**. 
  <details>
    <summary>Abstract</summary>
  Labelled Markov chains are commonly used to model systems with random behaviour. To mitigate the state-space explosion problem, behavioural equivalences such as probabilistic bisimilarity can be used to minimise the state space.
  <br/>
  In this talk, I will begin with an introduction to probabilistic bisimilarity and its associated behavioural pseudometric. I will then discuss a key limitation: probabilistic bisimilarity suffers from a lack of robustness under small perturbations of the transition probabilities. This can lead to unexpected changes in behaviour in practical applications where transition probabilities are often approximations derived from experimental data.
  <br/>
  There exist different approaches in the literature to address the sensitivity of probabilistic bisimilarity. I will also present our notion of robust probabilistic bisimilarity, which is designed to be stable under small changes in the model by ensuring the continuity of the associated probabilistic bisimilarity distance function. Finally, I will give an overview of our partition-refinement algorithm for computing robust probabilistic bisimilarity.
  </details>

* [Justin Hsu](https://www.justinhsu.net/), Cornell University, Ithaca, US.    
  **Type Systems for Exchangeability (Joint Keynote with [VeriProP 2026](https://veriprop.github.io/2026/))** 
  <details>
    <summary>Abstract</summary>
    TBA
  </details>
* [Benjamin Kaminski](https://quave.cs.uni-saarland.de/benjamin-kaminski/), Saarland University, Saarbr&uuml;cken, Germany & U College London, UK
* [Mayuko Kori](https://mkori.com/), RIMS, Kyoto U, Japan.    
  **A Lattice-Theoretic Abstraction of PDR via Adjunctions**.
  <details>
    <summary>Abstract</summary>
  Property directed reachability (PDR, also known as IC3) is a model checking algorithm for proving or refuting safety properties of transition systems. Although many variants and extensions have been studied, presentations and implementations of PDR algorithms often rely on concrete representations and solver-based mechanisms. This sometimes makes it difficult to identify the underlying algorithmic principles and to develop natural extensions.
  <br/>
  In this talk, I will present a lattice-theoretic abstraction of PDR, in which PDR can be understood as an interaction between searches for invariants and counterexamples. This abstraction reveals that the interaction is mediated by an adjunction representing forward and backward computations along transitions.
  <br/>
  I will then explain how to handle cases where such an adjunction is not available. The required adjunction can be recovered by the lower-set construction, which is categorically understood as a free cocompletion via Kan extensions. Finally, I will discuss how this framework yields a PDR algorithm solving max reachability problems for Markov decision processes, together with experimental results.
  </details>

* [Cristina Matache](https://homepages.inf.ed.ac.uk/cmatache/), U Birmingham, UK.     
  **An equational axiomatization of dynamic threads**.
  <details>
    <summary>Abstract</summary>
  Algebraic effects are a way to describe and reason about computational effects in a modular way, via the algebraic theories from universal algebra. A current challenge is to extend these ideas to concurrent programming. In this talk, I will present recent work on modelling dynamic thread creation, inspired by POSIX fork, using an algebraic theory. The main result characterizes this algebraic theory in terms of labelled partial orders, leading to a semantics where concurrent programs denote partial orders. The algebraic theory provides sound and complete equational reasoning principles for equality of such partial orders. This is joint work with Ohad Kammar, Jack Liell-Cock, Sam Lindley, and Sam Staton.
  </details>

* [Caterina Urban](https://caterinaurban.github.io/), INRIA, Paris, France.   
  **Termination Resilience Static Analysis**.
    <details>
    <summary>Abstract</summary>
    We present a novel abstract interpretation-based static analysis framework for proving Termination Resilience, the absence of Robust Non-Termination vulnerabilities in software systems. Robust Non-Termination characterizes programs where an untrusted (e.g., externally-controlled) input can force infinite execution, independently of other trusted (e.g., internally-controlled) variables. Our framework is a semantic generalization of Cousot and Cousot’s abstract interpretation-based ranking function derivation, and our sound static analysis extends Urban and Miné’s decision tree abstract domain in a non-trivial way to manage the distinction between untrusted and trusted program variables. The talk concludes with open challenges in dealing with angelic non-determinism, pointer-manipulating programs, and going beyond termination to program properties expressed in Computational Tree Logic (CTL) or Alternating-Time Temporal Logic (ATL).
    </details>
* [Florian Wittbold](https://flo-witt.github.io/), U Duisburg-Essen, Germany.   
  **Approximative Fixpoint Theory and Applications to Reinforcement Learning**.
  <details>
    <summary>Abstract</summary>
  Fixpoints play a central role throughout computer science, and classical fixpoint theory provides fundamental tools for establishing their existence and analyzing the convergence of fixpoint iterations. At the same time, in modern computer science, there has long been a trend to consider classical problems in approximative settings, such as quantitative problems in which the true dynamics of an underlying system cannot be known precisely but may be approximated. Reinforcement learning is a prominent example: optimal policies can be derived from fixpoints of operators whose dynamics are typically unknown and must be learned through interaction with an environment.
  <br/>
  Despite the growing importance of reinforcement learning, the fixpoint-theoretic foundations of such approximative settings remain comparatively underdeveloped. Approximative fixpoint theory seeks to address this gap by studying fixpoint computation when the operator of interest is accessible only through a sequence of approximating functions converging to it. In this framework, standard fixpoint iteration may fail to converge to a fixpoint, even when its classical assumptions are satisfied, necessitating new techniques and proof methods.
  <br/>
  In this talk, I will introduce the basic concepts of approximative fixpoint theory and discuss convergence results of the so-called dampened Mann iteration. As an application, these results yield generalized convergence guarantees for (model-based) reinforcement learning algorithms and provide a step towards a unifying fixpoint-theoretic perspective on quantitative learning in environments with unknown dynamics.
  </details>


## Contributed Presentations:

Each slot is (20-min talk + 10-min discussion), to bridge different backgrounds.

<ul>
  <li>SV-LIB 1.0: A Standard Exchange Format for Software-Verification Tasks, <a href="https://www.sosy-lab.org/people/beyer/">Dirk Beyer</a>, <a href="https://www.sosy-lab.org/people/ernst/">Gidon Ernst</a>, <a href="https://mjonas.net/">Martin Jonáš</a>, <a href="https://www.sosy-lab.org/people/lingsch-rosenfeld/">Marian Lingsch-Rosenfeld</a> (LMU Munich)
<br/>
<details>
    <summary>Abstract</summary>
In the past two decades, significant research and development effort went into the development of verification tools for individual languages, such as C, C++, and Java. Many of the used verification approaches are in fact language-agnostic and it would be beneficial for the technology transfer to allow for using the implementations also for other programming and modeling languages. To address the problem, we propose SV-LIB, an exchange format and intermediate language for software-verification tasks, including programs, specifications, and verification witnesses. SV-LIB is based on well-known concepts from imperative programming languages and uses SMT-LIB to represent expressions and sorts used in the program. This makes it easy to parse and to build into existing infrastructure, since many verification tools are based on SMT solvers already. Furthermore, SV-LIB defines a witness format for both correct and incorrect SV-LIB programs, together with means for specifying witness-validation tasks. This makes it possible both to implement independent witness validators and to reuse some verifiers also as validators for witnesses.
</details>

</li>
  
  <li>Constrained and Robust Policy Synthesis with Satisfiability-Modulo-Probabilistic-Model-Checking, <a href="https://linus.space/">Linus Heck</a> (Radboud University); <a href="https://www.fit.vut.cz/person/imacak/.en">Filip Macák</a>, <a href="https://www.fit.vut.cz/person/ceskam/.en">Milan Češka</a> (Brno University of Technology); <a href="https://sjunges.github.io/">Sebastian Junges</a> (Radboud University)
<br/>
<details>
    <summary>Abstract</summary>
We present an approach that solves a general class of problems that require combinatorial and probabilistic reasoning, for example, synthesizing a policy that satisfies first-order logical constraints in an underlying uncertain environment modeled as a family of MDPs. Our approach is to embed probabilistic model checking as a theory within an SMT solver. This leverages the practical advantages of both tools. We use the resulting tool to find policies that are robust, i.e., they perform well on perturbations of the MDP, and that satisfy additional structural constraints regarding, e.g., their representation or implementation cost. These constraints can be flexibly specified in a first-order theory over a set of MDPs.
</details>

</li>
  
  <li>Why codensity lifting works: A formal perspective, <a href="https://www.cs.ox.ac.uk/people/zev.shirazi/">Zev Shirazi</a> (University of Oxford)
  <br/>
<details>
    <summary>Abstract</summary>
Many verification techniques rely on lifting a system signature from a category of state spaces to a category of predicates, relations, metrics, or other proof objects. Codensity lifting provides a general method for constructing such liftings and has led to applications in fibrational bisimulation, quantitative reasoning, modal logics, and compositional verification. However, the literature often introduces new categorical machinery for each particular instance, making it difficult to identify the general structure that explains why these constructions work. This talk presents work in progress towards a 2-categorical account of codensity lifting. The aim is to separate the formal part of the construction from the application-specific verification data. From this perspective, several existing results on codensity lifting arise as instances of general fibrational and 2-categorical principles.
</details>

</li>
  
  <li>Stochastic Processes: Coinduction in Probabilistic Programming, <a href="https://sjpmath.github.io/">Seo Jin Park</a> (University of Oxford)
  <br/>
<details>
    <summary>Abstract</summary>
Stochastic processes give a mathematical representation of the probabilistic changes of a random system over time. Verification techniques use these representations to reason about quantitative behavioural properties, such as termination probabilities and probabilistic safety guarantees. Under the compositional view of probabilistic modelling in which probability is modelled by a monad, stochastic processes have a natural coalgebraic interpretation as coinductively generated stochastic structures. This allows for a structured and succinct expression of both discrete-time and continuous-time stochastic processes in higher-order probabilistic programming languages admitting lazy structures, such as LazyPPL. In this presentation, I will show that omega Qbs, a mixture of quasi-Borel spaces and complete partial orders, supports these higher order constructions of various stochastic processes, such as i.i.d measures, Markov chains, Brownian motion and stochastic differential equations.
</details>

</li>
  
  <li>Certified Harmonic-Mean Abstraction and Refinement for Continuous-Time Markov Chains, <a href="https://www.researchgate.net/profile/Bingqing-Hu-8">Bingqing Hu</a> (Utah State University); <a href="https://www.thomasnowak.net/">Thomas Nowak</a> (ENS Paris-Saclay); <a href="https://engineering.usu.edu/directory/be/faculty/zhan-jixun">Jixun Zhan</a> (Utah State University); <a href="https://www.colorado.edu/ecee/chris-myers">Chris J. Myers</a> (University of Colorado Boulder); <a href="https://engineering.usu.edu/ece/people/faculty/zhang-zhen">Zhen Zhang</a> (Utah State University)
  <br/>
<details>
    <summary>Abstract</summary>
We report ongoing work on a framework that constructs a compact, formally certified surrogate of a large continuous-time Markov chain (CTMC) for transient reachability analysis: it takes a PRISM model as input and returns a small abstract PRISM model whose induced CTMC approximates the concrete one within a user-specified tolerance.The core idea is to lift predicate abstraction from program verification into the continuous-time stochastic setting, where the new semantic challenge is rate aggregation: choosing a single transition rate for a block of concrete states without losing formal guarantees.The presentation focuses on three ideas: a semantically derived rate aggregation theory; an automated, learning-inspired refinement loop; and an explicit output artifact that is reusable, inspectable, and diagnostic.The corresponding full paper is under review at a leading international conference on automated verification, and its core theorems have been machine-checked in the Lean 4 proof assistant.
</details>


</li>
  
  <li>Semantics and Equational Axiomatisation of Quantum Communication, <a href="https://theo.wang/">Theo Wang</a> (University of Oxford)
  <br/>
<details>
    <summary>Abstract</summary>
We present a parameterised algebraic theory for classically controlled quantum communication, together with two sound models -- a quantum-stream-based operational semantics and a monadic denotational semantics. The two models induce the same notion of program equivalence -- the denotational one is adequate and fully abstract with respect to the operational one. We view this as a first step towards equational verification of quantum communication protocols.
</details>
</li>
  
  <li>Multiobjective Predicate Transformers: Computing the Pareto Front in Probabilistic Programs, <a href="https://www.cs.cornell.edu/people/kevin-stefan-batz">Kevin Batz</a> (Cornell University); <a href="https://moves.rwth-aachen.de/people/hannah-mertens/">Hannah Mertens</a> (RWTH Aachen University); <a href="https://sjunges.github.io/">Sebastian Junges</a> (Radboud University); <a href="https://quave.cs.uni-saarland.de/benjamin-kaminski/">Benjamin Lucien Kaminski</a> (Saarland University and University College London); <a href="https://moves.rwth-aachen.de/people/katoen/">Joost-Pieter Katoen</a> (RWTH Aachen University); <a href="https://quave.cs.uni-saarland.de/members/lena-verscht/">Lena Verscht</a> (Saarland University and RWTH Aachen University)
  <br/>
<details>
    <summary>Abstract</summary>
Many real-world systems require balancing several conflicting quantitative objectives simultaneously. For instance, randomized retry protocols must trade off reliability against latency and communication overhead, while autonomous robotic systems must balance safety, energy consumption, and task completion time. Such systems are naturally modeled as probabilistic programs, where quantitative reasoning about multiple objectives becomes essential. <br/>

We present a predicate transformer approach to multiobjective verification for probabilistic programs. Our work combines ideas from weakest preexpectation calculi and multiobjective model checking to compute Pareto fronts (that is, optimal values for several objectives) directly at the program level.
</details>
</li>
  
  <li>Coalgebraic Notions of Simulation, Bisimulation and Relators, <a href="https://research.birmingham.ac.uk/en/persons/pouya-partow/">Pouya Partow</a>, <a href="https://sergey-goncharov.org/">Sergey Goncharov</a> (University of Birmingham)
  <br/>
<details>
    <summary>Abstract</summary>
Simulation and bisimulation play a central role in coalgebra and in program semantics. Bisimulation is a certain canonical notion of program (or system) equivalence, which can be formulated in different equivalent ways in base cases, while these ways need not remain equivalent under further generalizations. This is acknowledged and investigated in the literature. Contrastingly, simulation is a non-canonical notion of program in-equivalence (or approximation), subject to the same issue, but much less explored. This is a work in progress on exploring it.
</details>
</li>
  
  <li>Compositional Verification of Higher-Order Effectful Programs via Interactive Semantics, <a href="https://sciences-techniques.univ-nantes.fr/guilhem-jaber">Guilhème Jaber</a> (Nantes Université)
  <br/>
<details>
    <summary>Abstract</summary>
We propose a framework for compositional verification of higher-order effectful programs based on operational game semantics. Starting from a monadic evaluator for a programming language, the framework derives interactive models of open program components as monadic transducers indexed by games. Their composition is defined by a bidirectionnal synchronization process based on feedback loops, in the style of Geometry of Interaction, and expressed algebraically through a trace operator induced by monadic iteration. This provides a common structure for approximating both evaluation and composition, opening the way to abstract-interpretation techniques for computing or over-approximating the behaviour of composed components. The approach is illustrated by ongoing implementation work in the CAVOC project for OCaml modules.
</details>
</li>
  
  <li>Verification of Systems with Unbounded Agents By Exploiting Concurrency, <a href="https://tephilla.github.io/">Tephilla Prince</a>

  <br/>
<details>
    <summary>Abstract</summary>
Client server systems are one of the largest programming paradigms. Crypto exchanges with an unbounded number of investors, multiplayer games where the number of players are not known apriori and services with an unbounded customer base are instances of unbounded client server systems. We focus on client server systems with single server and unboundedly many clients, where the number of clients are not known apriori and there can be unbounded concurrent interactions between the clients and server. The  major challenges are to identify the suitable model to abstract the behaviour of the systems,  to identify suitable logics to specify the properties and to identify formal techniques  for verifying the properties on the model. <br/>

In this talk, we discuss the formal modeling, encoding , verification algorithm to exploit concurrency. We also discuss the suite of formal verification tools for client server systems with unbounded clients using classes of nets and various suitable logics to represent their properties.
</details>
</li>

  <li>Imprecise Probabilistic Programming, Precisely, <a href="https://jackliellcock.com/">Jack Liell-Cock</a> (University of Oxford)
  <br/>
<details>
    <summary>Abstract</summary>
Imprecise probability generalizes standard probability theory by replacing a single distribution with a convex set of possible distributions. We show that this generalization requires no change to the standard BDD compilation and weighted model counting pipeline used by discrete probabilistic languages. An imprecise coin flip is simply a BDD variable whose weight is left free rather than fixed. We introduce "Imp", a Haskell embedded DSL for imprecise probabilistic programming. A graded monad, indexed by finite sets of named sources of epistemic uncertainty, restores the commutativity that the standard convex powerset monad lacks, and GHC's type system enforces this at compile time. Weighted model counting is parametric in the semiring, so the same compiled BDD supports exact, differentiable, and interval-bounded inference.
</details>

</li>

  <li>Scalable Probabilistic Program Verification by Theory-Extended Decision Diagrams,
<a href="https://github.com/dbasgoeze">Daniel Basgöze</a> (RWTH Aachen University); <a href="https://kevinbatz.github.io/">Kevin Batz</a> (University of Münster); <a href="https://sjunges.github.io/">Sebastian Junges</a> (Radboud University); <a href="https://moves.rwth-aachen.de/people/katoen/">Joost-Pieter Katoen</a> (RWTH Aachen University)
  <br/>
<details>
    <summary>Abstract</summary>
Weakest pre-expectations are the probabilistic program analogue to weakest preconditions in classical programs. Deductive veri!cation approaches aim to establish bounds on these quantitative expectations. Their automation has been successful in analysing a variety of discrete probabilistic programs. Key routines in that automation require reasoning about (partially unrolled) loops, however, the logical representation of weakest pre-expectations on such unrollings often explodes. <br/>

In this talk, we will present typed extended decision diagrams (TEDDs), inspired by various extensions to binary decision diagrams in classical planning. We demonstrate computing WPs represented as TEDDs, SMT-based pruning to further shrink their representation, and we lift some proof rules for loops to operate on TEDDs. Experimental results demonstrate that TEDDs boost the scalability of deductive probabilistic program veri!cation by orders of magnitudes over the state of the art.
</details>

</li>


  <li>Basic Lattice Theory for Basic Model Checking, <a href="https://group-mmm.org/~ichiro/">Ichiro Hasuo</a> (National Institute of Informatics, SOKENDAI and Imiron)
  <br/>
<details>
    <summary>Abstract</summary>
TBA
</details>

</li>


</ul> 



## Program: TBA

## Call for Presentations

We solicit contributed presentations. Topics of interest include the following, although the list is by no means exclusive.

* Abstract semantical techniques in formal verification, towards concrete methods  
  * Lattice-theoretic modeling  
  * Categorical modeling  
  * Algebras and coalgebras  
  * String diagrams  
  * Implementation techniques for abstract theories  
* Concrete verification algorithms and methods, towards abstraction  
  * Model checking  
  * Theorem proving, automated and interactive  
  * Program verification  
  * Type systems  
  * Probabilistic verification  
  * Cyber-physical systems  
  * Quantum systems  
* Accessible introduction to basics, abstract or concrete  
  * Abstract semantical methods  
  * Concrete verification methods  
* Examples of successful matchings between abstract and concrete, or efforts towards them

### Submission

We call for presentation proposals (typically 1-2 pages) describing ongoing research developments, an overview of past research, or a survey of a broad topic. A presentation of already published results, or those currently under review, is welcome, too. There are no formal proceedings.


Submission deadline: &nbsp; <s>May 6th 2026 AoE</s> &nbsp;  **May 20th 2026 AoE (extended)**  
Submission link: [https://submissions.floc26.org/acv/](https://submissions.floc26.org/acv/)   
Notification: late May 2026 (before the early workshop registration deadline)

## Attending

The workshop takes place on July 24-25, 2026, at [FLoC 2026](https://www.floc26.org/).

## Organizers

[Ichiro Hasuo](https://group-mmm.org/~ichiro/) (National Institute of Informatics, Tokyo, Japan)    
[Bart Jacobs](https://www.cs.ru.nl/B.Jacobs/) (Radboud University, Nijmegen, the Netherlands)  
[Joost-Pieter Katoen](https://moves.rwth-aachen.de/people/katoen/) (RWTH Aachen University, Germany)  
[Sam Staton](https://www.cs.ox.ac.uk/people/samuel.staton/main.html) (University of Oxford, UK)

## Acknowledgments

Many thanks are due to the FLoC 2026 organization team. The workshop is partially supported by JST ASPIRE Grant No. JPMJAP2301.



