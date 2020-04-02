# TheCompendium
A collection of definitions, theorems, lemmas, corollaries and their proofs for Math 311, taught by Professor Swindle at Washington and Lee University

## Introduction
	During a 1985 Lecture, Paul Erdos stated, "You don't have to believe in God, but you should believe in *The Book*." Many colleagues of this brilliant and uncouth
mathematician mention his murmuring of *The Book*: God's collection of the most efficient, and thus beautiful, proofs for each mathematical theorem.

Though, the mathematical community has not gone to the extent of compiling the proofs for every known theorem, there have been attempts. *Proofs from THE BOOK*, the 1998
book by Martin Aigner and Gunter Ziegler, is a collection of the most elegant proofs from the fields of number theory, geometry, analysis, combinatorics, and graph theory.
Recently, Evan Chen---a retired math Olympian and current math PhD at MIT---has created an exposition titled *The Napkin*. *The* (infinite) *Napkin* is his attempt to
compile the most essential statements one needs to understand the beauty and importance of mathematics. It features overviews of a myriad of different subjects studied by most
undergraduate mathematicians. *The Napkin* provides the curious a non-trivial foundation of their subject interest; succeeding in honing their mathematical abilities and 
providing them a gateway to more profound investigations.

Additionally, over the past decade, communities of open-source programmers have created multiple chrestomathy websites such as Rosetta Code and the Algorithm Archive that
aggregate elegant computer programs for different algorithms in a variety of languages. Given the Curry-Howard correspondence---a relationship between mathematical proofs
and computer programs---I thought that this would be worth mentioning.

All in all, *that* is what this document tries to be (though, with a far more restricted scope and much less precision). I hope to compile every theorem, lemma, corollary, and
definition covered over the course of MATH-311. There will be a table of contents which indexes the statements as they appear in **From Calculus to Analysis**. Definitions, in 
their totality, will be enumerated first and will be subsequently followed by the theorems that we have proved or covered thus far. Any additional propositions that would 
otherwise be in *The Compendium* will be added at the appropriate time and made not of. Feel free to edit and comment by footnote. This document serves as a palimpsest of our
study of real analysis this term.

Finally, this document is meant to be pedagogical. So I will attempt to provide commentary and references to helpful, auxiliary resources when I can. Have fun!

## Versioning

The most critical part of this project is its capacity as an open source document. Given the assumption that most of my peers are not acquainted with GitHub, a more rudimentary
 version control system must be developed in order to maintain current and alternative versions of *The Compendium*. Because of the nature of this project, future versions of
 *The Compendium* will not see great structural changes. Most changes to the document will entail the addition or editing of mathematical statements. Because new definitions
 are anticipated to be added through the rest of the winter term of 2020, we will avoid a unary versioning system as employed by the TeX typesetting system.

### Version Schema
 I propose the following schema: A major version change will entail a change in structure of the document. A minor version change will entail the correction of a previously
invalid proof or definition. Patch version changes will entail the correction of spelling errors and the addition of new definitions and theorems. If the number of patches 
explodes in the near future, I will implement a modulo on the patch version and record the multiplicity of patches in an appended digit to the version number.

### Submitting Changes
Each individual who intends to edit their copy of *The Compendium* shall make edits to the tex document and resubmit the tex file to me via email. In the email, make
note of:
1. The mathematical statements (theorems, proofs, definitions, etc...) changed  
2. The line numbers at which the changes took place if possible
3. A brief description (need not to be elaborate at all) of the changes.  

Given that I beleive the changes are appropriate, I will then alter the version of *The Compendium* and its state. I will then release the newest version on *Overleaf*,  
 and GitHub, for all to access. All version changes will be recorded after the section titled **Theorems, Lemmas, Corollaries, and Proofs*. Though, do note, no one is stopping you from hosting your own version! Request collaboration from me, and I will create a new branch for you to work on. Or, if you wish to work on *Overleaf*, reset the version of
your own document to 0.0.0, list me as a co-author and yourself as the author, and then tex away!
