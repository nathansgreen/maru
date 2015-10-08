# Directions #

## Kernel and bootstrap ##

  * a proper model of heap and stack variables (done since Dec. 23 version)
  * a proper model of environments, preservable through run-time (done)
  * first-class namespaces (done)
  * unifying special forms and active leaves (symbols or 'naked' form values) into a single rewrite mechanism (done)
  * a real model of class, inheritance, and direct access to instance variables in methods (done)
  * a smaller, faster PEG framework (in progress)
  * a public repo, a wiki, and a madding crowd of enthusiasts (in progress)
  * figuring out the problem with linking code on mingw/win32 (pending)
  * a more extensible model of generic functions with better default behaviour (pending)
  * merging the metacircular part and semantic level-shifting part into a single artefact (pending)
  * hygienic macros (pending)
  * dynamic and static back-ends for 386 binary, avoiding dependencies on assembler and linker (pending)
  * a proper model of ABIs, and automatic conversion between them, in the 386 back-end (pending)
  * a rewrite of the kernel as a literate program, cf. TeX B-Book, to add pedagogical value (pending)

These should all preserve the 'minimality' (that can be measured as LOC) at less than 2000.

## Extensions, languages and applications ##

Standalone scaffolding for OpenFirmware (the cola2/OLPC one can be reused) and EFI.

Pluggable optimisers: BURG-ish, RTL/SSA, insert-your-favorite-here, etc.

Lots of static back-ends (C for bootstrap, JS for bootstrap and/or online deployment, maybe Java or other popular VM for distributed deployment).

Given the right Ph.D. student: static and dynamic back-ends for PGAs.

Lots of front-ends; given unlimited time:
  * various parts of the kernel desperately need something that isn't s-expressions (= dramatic reduction in LOC)
  * something Slate-like to evolve Smalltalk out of the 1980s
  * something small, fun, interactive, compact, and with graphics for instant gratification: 'basic meets logo'
  * something like 'Erlang meets LSL meets R' for UI, agent, VR, and other kinds of 'particle-field' scripting
  * something whose central computational primitive is n-way associative lookup (cf. unlearning lab)
  * something that can extract APIs from all those inconvenient C header files
  * at least one industrial-strength implementation of a nontrivial popular programming language, with deep self-extensibility for free because of the choice of implementation vehicle
  * &c. &c. &c.

A framework for generating fast bytecode interpreters and/or JIT VMs.

Concurrency and a model for scaling to SMP and MMP.

Development tools (especially one that displays and modifies execution state).

A model/API for tools that dissociates their function from any particular presentation medium.

Local (hosted) and remote (cloud) presentation media for the tools.