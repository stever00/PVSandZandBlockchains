# PVS and Blockchains
Modelling blockchains in PVS---from the absurdly abstract to the more-or-less real

(Notes below from a talk I gave at Data61 in Setpember 2018)


Introduction
------------

􏰀 What general properties should blockchains have?

􏰀 Initially independently from any particular “version”

􏰀 Express properties first

􏰀 Then build models and try to show those properties hold

􏰀 There is other work in the last two years or so (using for example Coq and Isabelle) has been looking at existing contracts or the EVM

􏰀 I am starting at the “other end”

􏰀 More abstract, sometimes trivial, models

􏰀 Seeing what properties are expressible at high, and then
decreasing, levels of abstraction

􏰀 Maybe with refinement between the levels, but certainly
preservation of properties


Using PVS
---------

􏰀 Long pedigree

􏰀 Personal experience

􏰀 Functional programming with dependent types, and a proof theory—and all the support that goes with those

􏰀 This allows (as do Coq, Isabelle etc. of course)...

􏰀 Good models: they are simpler than the thing being modelled

􏰀 Impose as little rigidity as possible

􏰀 Formal models open up the possibilities...

􏰀 particularly property-driven development


A plan
------

A model of a trivial blockchain in PVS

􏰀 Some proofs of simple properties—which guide the model in a
modelling/validation cycle 􏰀 A plan for what’s next

􏰀 The simplified Etherlite in PVS (Nikoli ́c et al.)

􏰀 Full Etherlite in PVS (Luu et al.)

􏰀 (Keep an eye on Data61 work in Isabelle/HOL...)


Conclusions
-----------

Things we find valuable:

􏰀 Simplicity

􏰀 Generality

􏰀 Statement and proofs of required properties

􏰀 Gradually increasing complexity/specificity

􏰀 Property-driven development
