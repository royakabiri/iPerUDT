# Informal Persian Universal Dependency Treebank (iPerUDT)
**Informal Persian Universal Dependency Treebank**, consisting of 3000 sentences and 54,904 tokens, is an open source collection of colloquial informal texts from Persian blogs. The corpus is annotated in CoNLL-U format within the Universal Dependencies scheme (Nivre et al., 2020).

If you use **iPerUDT** in your work, please cite this paper:

**Kabiri, Roya, Simin Karimi, and Mihai Surdeanu. (2022). [Informal Persian universal dependency treebank](http://www.lrec-conf.org/proceedings/lrec2022/pdf/2022.lrec-1.768.pdf). In Proceedings of the 5th International Conference on Language Resources and Evaluation (LREC), 7096-7105. Marseille, France.**

This treebank was developed as a building block of the following PhD dissertation:

**Kabiri, Roya. (2022). Neural Dependency Parsing of Informal Persian. PhD Dissertation. University of Arizona, Tucson, Arizona, USA.** 



### Summary of Annotation Schema
The following Course-grained Universal Dependencies parts of speech tags (UPOS), and fine-grained language-specific parts of speech tags (XPOS) are used in this treebank. 


| UPOS  | XPOS | Description |
| ------------- | ------------- | ------------- |
| ADJ  | ADJ  | Adjective  |
| ADJ  | ADJ_CMPR  | Comparative adjective  |
| ADJ  | ADJ_SUP  | Superlative adjective  |
| ADV  | ADV  | Adverb  |
| ADV  | ADV_I  | Adverb of interrogation  |
| ADV  | ADV_LOC  | Adverb of location  |
| ADV | ADV_NEG  | Adverb of Negation  |
| ADV  | ADV_TIME  | Adverb of time  |
| ADP  | P  | Preposition  |
| AUX  | V_AUX  | Auxiliary/copula verb  |
| CCONJ  | CON  | Coordinating conjunction  |
| DET  | DET  | Determiner  |
| INTJ  | INTJ  | Interjection  |
| NOUN  | N_PL  | Plural noun  |
| NOUN  | N_SING  | Singular noun  |
| NUM  | NUM  | Numeral  |
| PART  | PART  | Differential object marker, focus marker, negative particle, question particle |
| PRON  | PRO  | Pronoun  |
| PROPN  | PROPN  | Proper nouns (persons,locations, months, organizations, geopolitical entities)  |
| PUNCT  | DELM  | Punctuation/delimiter  |
| SCONJ  | CON  | Subordinating conjunction  |
| VERB  | V_IMP  | Imperative verb  |
| VERB  | V_PA  | Past tense verb  |
| VERB  | V_PP  | Past participle  |
| VERB  | V_PRS | Present tense verb  |
| VERB  | V_SUB  | subjunctive verb  |
| X  | FW  | Foreign word  |

We used the Universal Dependencies annotation scheme which produces syntactic analyses of sentences in terms of the dependency structures of dependency grammar, determined by the relation between a head and its dependents. The syntactic annotation consists of 42 dependency relations, including 32 universal and 10 language-specific relations (marked by *). 

| Dependency relation  | Description |
| ------------- | ------------- |
| acl  | Clausal modifier of noun  |
| acl:relcl<sup>*</sup>  | relative clause modifier  |
| advcl  | Adverbial clause modifier  |
| advmod  | Adverbial modifier  |
| amod  | Adjectival modifier  |
| appos  | Appositional modifier |
| aux  | Auxiliary  |
| aux:pass  | Passive auxiliary  |
| case  | Accusative marker/case marking  |
| cc  | Coordination  |
| cc:preconj<sup>*</sup>  | Preconjunction  |
| ccomp  | Clausal complement  |
| compound  | Compound  |
|  compound:lvc<sup>*</sup> | Nominal/adjectival NVE in complex predicates  |
| compound:prt<sup>*</sup>  | Particle NVE in complex predicates  |
| compound:redup<sup>*</sup>  | Reduplicative words |
| compound:svc<sup>*</sup>  | Serial verb constructions  |
| conj  | Conjunct  |
| Cop  | Copula  |
| det  | Determiner  |
| det:predet<sup>*</sup>  | Predeterminer  |
| discourse  | Discourse element |
| discourse:top/foc<sup>*</sup>  | Topic/focus marker  |
| dislocated | Dislocated elements  |
| fixed  | Fixed multiword expressions  |
| flat  | Flat multiword expressions   |
| goeswith  | Goes with for poorly-edited words  |
| nmod  | Nominal modifier  |
| nmod:poss<sup>*</sup>  | Possessive/genitive modifier  |
| nsubj  | Nominal subject  |
| nsubj:pass  | Passive nominal subject  |
| nummod  | Numeric modifier  |
| mark  | Complementizer/marker  |
| obj  | Object |
| obl  | Oblique  |
| obl:arg<sup>*</sup>  | Oblique core argument  |
| orphan  | Ellipsis constructions  |
| parataxis  | Parataxis  |
| punct  | Punctuation  |
| root  | Root |
| vocative  | Vocative  |
| xcomp  | Open clausal complement  |


### Feedback and Bug Reports

Feel free to contact royakabiri@arizona.edu for feedback and bug reports. 


### Acknoledgments 
We would like to thank [Roshan Cultural Heritage Institute](https://roshan-institute.org/) and [Dr. Malakeh Taleghani Graduate Fellowship in Iranian Studies](https://linguistics.arizona.edu/node/545) for their support and financial contribution. We are also grateful to Farzaneh Bakhtiary for her help with the annotation.

### References 

Nivre, Joakim, Marie-Catherine de Marneffe, Filip Ginter, Jan Hajič, Christopher D. Manning, Sampo Pyysalo, Sebastian Schuster, Francis M. Tyers, and Dan Zeman. (2020). Universal dependencies v2: An evergrowing multilingual treebank collection. In Proceedings of the 12th Conference on Language Resources and Evaluation (LREC), 4027–4036.













