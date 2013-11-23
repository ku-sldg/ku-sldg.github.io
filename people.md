---
layout: frontpage
title: People
---

# Faculty

-----

{% for person in site.data.people %}

{% if person.role == faculty %}
* {{ person.name }} - {{ person.description }}
{% else %}
* nothing
{% endif %}

{% endfor %}

# Students

-----

* **Evan Austin** - Verifying Haskell in Haskell using HaskHOL
* **Brigid Halling** - TPM formal specification and verification
* **Kayla Sale** - Static analusis of species niche models

-----

# Alumni

-----

SLDG (University of Kansas) and KBSE (University of
Cincinnati) students who have graduated under my supervision. 

## PhD Graduates

-----

* Dr. Phillip Baraona - VSPEC Formal Semantics - The syntax and
  semantics of the VSPEC specification language are described. A
  transformation from single and multi-component specifications to
  Larch Shared Language specifications is defined to provide language
  syntax. Component specifications are defined using the canonical
  axiomatic style extended to represent component
  activation. Interconnected components are modeled using CSP to model
  control.
  
* Dr. John Penix - Formal Component Retrieval and Architecture
  Representation - A technique for efficient, correct retrieval of
  components and a theory of architectures is presented. The component
  retrieval system combines faceted retrieval and specification
  matching. Facets are formally defined and extracted from component
  specifications using forward inference. Retrieval based on facets
  culls the solution space making specification matching
  feasible. Architecture theories are used to compose and adapt
  specifications.
  
* Dr. Murali Rangarajan - VSPEC formal analysis using automatically
  generated proof obligations - Defined and implemented a methodology
  for automatically generating a discharging proof obligations from
  VSPEC specifications. The semantics of VSPEC were encoded in PVS and
  proof obligations to test several classes of interface errors
  generated. Automatic proof scripts are generated with the
  obligations to attempt automated verification.
  
* Dr. Cindy Kong - Formal Semantics for Model-Based Specification -
  Defined a formal semantics for model-based specification and a
  denotation for the Rosetta specification language to that
  formalism. The system is based on using hidden algebras to represent
  abstract state allowing refinement in specification domains.
  
* Dr. Garrin Kimmel - System Synthesis from a Monadic Functional
  Language - Defined a methodology for synthesizing globally
  asynchronous, locally synchronous (GALS) implementations in VHDL and
  C++ from a common, monadic specification. The specification
  language, called Oread, uses monadic constructs to represent various
  computational features.
  
* Dr. Nick Frisby - Languages for embedded system design and
  synthesis; monadic and comonadic interpreters.
	
* Dr. Mark Snyder - Type system formalization; type checking; and
  dependent type systems.
	
* Dr. Jennifer Streb - Abstract interpretation; monadic, composable
  interpreters; and simulation.
  
## MS Graduates

-----

* Mark Snyder - Modular Type Checking for Rosetta - Defined and
  developed a type checking system for a subset of Rosetta
  specifications. Using InterpreterLib, the type checker is
  implemented as a collection of modular type checking components that
  are implemented independently.
  
* Philip Weaver - Reflective Metaprogramming in Rosetta - Defined and
  developed a staged interpreter for the reflective subset of the
  Rosetta specification language. Established the two-stage nature of
  Rosetta reflection and augmented the existing expression interpreter
  to handle quote and unquote terms in expressions.
  
* Kalpesh Zinjuwadia - GENISYS Component Inversion System -
  Developed the GENISYS prototype for tracing inputs and outputs for
  system components back to system inputs and outputs. Generates
  hierarchies of components and inverts component function to
  determine desired system input for generating specific component inputs. 

* Brandon Morel - SPARTACAS Component Retrieval and Adaptation -
  Developed the SPARTACAS component retrieval and adaptation building
  upon feature-based retrieval techniques. Implemented adaptation
  architectures for automatically performing black box adaptation on
  partially matching specifications. 

* Krishna Ranganathan - Test Vector Generation from Rosetta -
  Developed a system for representing test requirements in Rosetta and
  automatically generating test vectors for VHDL systems.
  
* Srinivas Akkipeddi - Advanced Test Vector Generation from Rosetta -
  Developed a system for generating WAVES vectors from abstract test
  vectors. Improved the test vector generation algorithm. Developed
  mechanisms for specifying and generating test vectors from sampled
  waveform inputs.
  
* Cindy Kong - ActiveSPEC-based Active network modeling library -
  Defined and implemented a collection of PVS libraries for active
  network modeling. Developed the ActiveNodeSpec library for
  integrating multiple execution environments into an active
  node. Verified properties of the active network implementation.
  
* Sarjoun Doumit - ActiveSPEC and ANSE usage environment using orbit -
  Developed a combined simulation and formal analysis environment
  based on the orbit/gravity subsystem. Translated a common graphical
  representation of active networks into both ANSE and ActiveSPEC
  representations. 

* Makarand Patil - Specification-Based component retrieval using
  Rosetta - Continued work started by John Penix by implemented a
  specification retrieval capability using PVS. Demonstrated the
  capability by developing and fielding a DSP component retrieval
  library.
  
* Kshama Jambhekhar - Test Vector Generation from VSPEC - Building on
  work in the specification-based software testing area, Implemented a
  specification-based test vector generation tool that transformed
  VSPEC requirements and entities into abstract test vectors and test
  scenarios.
  
* Amit Rajkhowa - VSPEC Constraint Modeling - The semantics of VSPEC
  constraints are defined in the Performance Description Language
  (PDL) and a checker implemented. PDL semantics are defined for
  predefined VSPEC constraints including power consumption, heat
  dissipation, clock speed, area and pin-to-pin timing. A translator
  was written to output PDL specifications from the JVOM intermediate
  form. The translator is integrated into the orbit environment.
  
* Iqbal Mutabanna - Network security modeling - Techniques for
  modeling security in active networks is presented. Traditional
  security models are explored and a proposal for composable security
  components based on the ActiveSPEC system discussed. Theories
  describing an FTP file bounce attack are developed and verified. A
  solution is developed demonstrating that a collection of nodes that
  are not individually secure can be assembled in a secure fashion
  within a network.
  
* Sathiyanarayanan Vijayaraghavan (Sat) - LSL Parsing and PVS
  Translation - A PCCTS based parser and object model is developed to
  provide generic front-end analysis for Larch Shared Language (LSL)
  traits. Semantic checking and symbol table manipulations are
  provided. The object model is then used to develop a translator from
  LSL specifications to PVS theories. Shorthands, induction rules,
  extensionality rules, and other Larch specifics are transformed into
  PVS their equivalents.
  
* Tareq Altakrouri - Formal Move Machine Verification - The DSS
  synthesized design of the Move Machine is formally verified using
  the Boyer-Moore Theorem proving system. The structural and
  behavioral representations are translated into Boyer-Moore logic
  using techniques defined by Hunt. Then, an induction proof is used
  to show that the structural model meets requirements specified by
  the behavioral model.
  
* Raj Sayana - VHDL Partial Evaluation - A partial evaluation system
  is developed for VHDL. Values are specified for a subset of input
  parameters and propagated throughout the VHDL code. Dead code is
  eliminated, loops are unrolled, and wait statements evaluated for
  validity.
  
* Liming Cai - Constraint Modeling - Formal theories for constraint
  modeling are developed using the algebraic specification language
  COLD-K. These theories model constraint propagation throughout VLSI
  designs. The theories are translated into the Refine environment and
  used to evaluate constraints in the COMET co-synthesis environment.
  
* Megan Peck - Rosetta Composition Semantics

## Undergraduates

-----

* Justin Ward - Polytypic Theorem Proving Framwork - The Prufrock
  (literary reference intended) polytypic theorem prover
  famework. Prufrock was developed to perform static anlaysis on
  Haskell and Rosetta source modules. It is a first-order theorem
  prover supporting rewriting and a proof scripting language.
  
