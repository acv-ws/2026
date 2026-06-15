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

... *more are TBA*

## Contributed Presentations:

Each slot is (20-min talk + 10-min discussion), to bridge different backgrounds.

<ul>
  <li>SV-LIB 1.0: A Standard Exchange Format for Software-Verification Tasks, <a href="https://www.sosy-lab.org/people/beyer/">Dirk Beyer</a>, <a href="https://www.sosy-lab.org/people/ernst/">Gidon Ernst</a>, <a href="https://mjonas.net/">Martin Jonáš</a>, <a href="https://www.sosy-lab.org/people/lingsch-rosenfeld/">Marian Lingsch-Rosenfeld</a> (LMU Munich)</li>
  
  <li>Constrained and Robust Policy Synthesis with Satisfiability-Modulo-Probabilistic-Model-Checking, <a href="https://linus.space/">Linus Heck</a> (Radboud University); <a href="https://www.fit.vut.cz/person/imacak/.en">Filip Macák</a>, <a href="https://www.fit.vut.cz/person/ceskam/.en">Milan Češka</a> (Brno University of Technology); <a href="https://sjunges.github.io/">Sebastian Junges</a> (Radboud University)</li>
  
  <li>Why codensity lifting works: A formal perspective, <a href="https://www.cs.ox.ac.uk/people/zev.shirazi/">Zev Shirazi</a> (University of Oxford)</li>
  
  <li>Stochastic Processes: Coinduction in Probabilistic Programming, <a href="https://sjpmath.github.io/">Seo Jin Park</a> (University of Oxford)</li>
  
  <li>Certified Harmonic-Mean Abstraction and Refinement for Continuous-Time Markov Chains, <a href="https://www.researchgate.net/profile/Bingqing-Hu-8">Bingqing Hu</a> (Utah State University); <a href="https://www.thomasnowak.net/">Thomas Nowak</a> (ENS Paris-Saclay); <a href="https://engineering.usu.edu/directory/be/faculty/zhan-jixun">Jixun Zhan</a> (Utah State University); <a href="https://www.colorado.edu/ecee/chris-myers">Chris J. Myers</a> (University of Colorado Boulder); <a href="https://engineering.usu.edu/ece/people/faculty/zhang-zhen">Zhen Zhang</a> (Utah State University)</li>
  
  <li>Semantics and Equational Axiomatisation of Quantum Communication, <a href="https://theo.wang/">Theo Wang</a> (University of Oxford)</li>
  
  <li>Multiobjective Predicate Transformers: Computing the Pareto Front in Probabilistic Programs, <a href="https://www.cs.cornell.edu/people/kevin-stefan-batz">Kevin Batz</a> (Cornell University); <a href="https://moves.rwth-aachen.de/people/hannah-mertens/">Hannah Mertens</a> (RWTH Aachen University); <a href="https://sjunges.github.io/">Sebastian Junges</a> (Radboud University); <a href="https://quave.cs.uni-saarland.de/benjamin-kaminski/">Benjamin Lucien Kaminski</a> (Saarland University and University College London); <a href="https://moves.rwth-aachen.de/people/katoen/">Joost-Pieter Katoen</a> (RWTH Aachen University); <a href="https://quave.cs.uni-saarland.de/members/lena-verscht/">Lena Verscht</a> (Saarland University and RWTH Aachen University)</li>
  
  <li>Coalgebraic Notions of Simulation, Bisimulation and Relators, <a href="https://research.birmingham.ac.uk/en/persons/pouya-partow/">Pouya Partow</a>, <a href="https://sergey-goncharov.org/">Sergey Goncharov</a> (University of Birmingham)</li>
  
  <li>Compositional Verification of Higher-Order Effectful Programs via Interactive Semantics, <a href="https://sciences-techniques.univ-nantes.fr/guilhem-jaber">Guilhème Jaber</a> (Nantes Université)</li>
  
  <li>Verification of Systems with Unbounded Agents By Exploiting Concurrency, <a href="https://tephilla.github.io/">Tephilla Prince</a></li>

  <li>Imprecise Probabilistic Programming, Precisely, <a href="https://jackliellcock.com/">Jack Liell-Cock</a> (University of Oxford)</li>

  <li>Scalable Probabilistic Program Verification by Theory-Extended Decision Diagrams,
<a href="https://github.com/dbasgoeze">Daniel Basgöze</a> (RWTH Aachen University); <a href="https://kevinbatz.github.io/">Kevin Batz</a> (University of Münster); <a href="https://sjunges.github.io/">Sebastian Junges</a> (Radboud University); <a href="https://moves.rwth-aachen.de/people/katoen/">Joost-Pieter Katoen</a> (RWTH Aachen University)
</li>


  <li>Basic Lattice Theory for Basic Model Checking, <a href="https://group-mmm.org/~ichiro/">Ichiro Hasuo</a> (National Institute of Informatics, SOKENDAI and Imiron)</li>


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



