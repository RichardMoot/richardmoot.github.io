# Richard Moot's personal homepage


I'm a [CNRS](http://www.cnrs.fr) research scientist in computer science, working at [LIRMM](http://www.lirmm.fr) ([Montpellier](https://www.montpellier.fr)) as a member of the [Texte](https://www.lirmm.fr/recherche/equipes/texte) team in computational linguistics.

## Research interests

* logic, proof theory, proof nets
* proof theoretic aspects of categorial grammars and type-logical grammars
* parsing/theorem proving for categorial grammars and type-logical grammars
* computational linguistics

## Current research

* [TLGbank](https://richardmoot.github.io/TLGbank/), a type-logical treebank  for French,
* Wide-coverage syntax and semantics for French,
* The Grail family of theorem provers/parsers for type-logical grammars.
* Proof-theoretic aspects of type-logical grammars

### The Grail theorem provers

A succinct summary of the different theorem proves I have developed can be found in the table below (see Moot 2017 and the individual linked prover pages for further details). 

| Prover       | Logic           | Code | ND  | SR | Interactive |
|---------|----------|-----|-----|-----| -----|
| [Grail0](https://github.com/RichardMoot/Grail0) | MMCG | SWI Prolog |yes | yes | no |
| [Grail2](https://github.com/RichardMoot/Grail2) | MMCG | SICStus Prolog/Tcl|  yes | yes | yes |
| [Grail3](https://github.com/RichardMoot/Grail) | MMCG | SWI Prolog/XPCE | no | yes | yes |
| [Grail Light](https://github.com/RichardMoot/GrailLight) | MMCG | SWI Prolog/Tcl/Python | yes | no | no |
| [Linear One](https://github.com/RichardMoot/LinearOne) | MLL1, D, HTLG | SWI Prolog | yes | NA | no |

* `ND`: prover has natural deduction output (true for all provers except Grail 3)
* `SR`: prover has user-defined set of structural rules 
* `MMCG`: [multimodal categorial grammars](https://academic.oup.com/jigpal/article/3/2-3/371/732861), 
* `MLL1`: [first-order linear logic](https://hal.archives-ouvertes.fr/hal-00826416)
* `D`: [Displacement calculus](https://link.springer.com/article/10.1007/s10849-010-9129-2)
* `HTLG`: [hybrid type-logical grammars](https://www.researchgate.net/publication/268982205_Hybrid_Type-Logical_Categorial_Grammar)


### Wide-coverage parsing

 [Grail Light](https://github.com/RichardMoot/GrailLight) is a specialised, wide-coverage chart parser. It is designed to work together with a supertagger - essentially a probabilistic assignment of formulas to words - such as [DeepGrail](https://richardmoot.github.io/DeepGrail/).

GrailLight also includes a semantic lexicon assigning a logical semantics in the style of [Discourse Representation Theory](https://en.wikipedia.org/wiki/Discourse_representation_theory) to parsed sentences, making it a tool for wide-coverage semantics for French. 

## Slides and presentations

[Slides](https://richardmoot.github.io/Slides/) for some selected presentations, some old, some new.

## Selected publications

[full publication list](https://scholar.google.fr/citations?user=l8_rzAoAAAAJ&hl=nl) (contact me for author's copies of pdf files)

* Moot, R. and Retoré, C. (2019), _Natural language semantics and computability_, Journal of
Logic, Language and Information **28(2)**, 287-307 ([HAL](https://hal.archives-ouvertes.fr/lirmm-01471644v1)).

* Moot, R. and Stevens-Guile, S.J.  (2019),  _Proof-Theoretic Aspects of Hybrid Type-Logical Grammars_, International Conference on Formal Grammar, 84-100 ([HAL](https://hal.archives-ouvertes.fr/lirmm-02268104v1)).

* Kogkalidis, K., Moortgat, M., Moot, R., and Tziafas, G. (2019), _Deductive parsing with an unbounded type lexicon_, Proceedings SEMSPACE2019, Riga, Latvia ([HAL](https://hal.archives-ouvertes.fr/lirmm-02313572v1)). 

* Moot, R. (2018), _Combining logical and distributional methods in type-logical grammars_, Journal of Language Modelling **6(2)**, 287-317 ([HAL](https://hal.archives-ouvertes.fr/lirmm-01651508v1)).

* Moot, R. (2018), _Chart Parsing Multimodal Grammars_, ([Github](http://richardmoot.github.io/GrailLight/), [HAL](https://hal.archives-ouvertes.fr/hal-02101396/)).

* Moot, R. (2017), _The Grail theorem prover: Type theory for syntax and semantics_, Modern Perspectives in Type-Theoretic Semantics, 247-277 ([HAL](https://hal.archives-ouvertes.fr/lirmm-01471644v1)).

* Lafourcade, M., Mery, B. Mirzapour, M., Moot, R., and Retoré, C. (2017), _Collecting crowd-Sourced lexical coercions for compositional semantic analysis_, Proceedings LENLS 2017: Logic and Engineering of Natural Language Semantics, Tokyo ([HAL](https://hal.archives-ouvertes.fr/lirmm-01916195v1)).

* Moot, R. (2015), _A Type-Logical Treebank for French_, Journal of
Language Modelling **3(1)**, pp. 229-265 ([Github](https://richardmoot.github.io/TLGbank/), [HAL](https://hal.archives-ouvertes.fr/hal-02102867v1)).

* Moot, R. and Retoré, C. (2012), _The Logic of Categorial Grammars: A Deductive account of Natural Language Syntac and Semantics_, Springer.

