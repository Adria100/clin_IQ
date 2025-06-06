Spacy Models for Biomedical Text.

| Feature | Description |
| --- | --- |
| **Name** | `en_ner_bc5cdr_md` |
| **Version** | `0.5.4` |
| **spaCy** | `>=3.7.4,<3.8.0` |
| **Default Pipeline** | `tok2vec`, `tagger`, `attribute_ruler`, `lemmatizer`, `parser`, `ner` |
| **Components** | `tok2vec`, `tagger`, `attribute_ruler`, `lemmatizer`, `parser`, `ner` |
| **Vectors** | 4087446 keys, 50000 unique vectors (200 dimensions) |
| **Sources** | BC5CDR<br>OntoNotes 5<br>Common Crawl<br>GENIA 1.0 |
| **License** | `CC BY-SA 3.0` |
| **Author** | [Allen Institute for Artificial Intelligence](https://allenai.github.io/SciSpaCy/) |

### Label Scheme

<details>

<summary>View label scheme (99 labels for 3 components)</summary>

| Component | Labels |
| --- | --- |
| **`tagger`** | `$`, `''`, `,`, `-LRB-`, `-RRB-`, `.`, `:`, `ADD`, `AFX`, `CC`, `CD`, `DT`, `EX`, `FW`, `HYPH`, `IN`, `JJ`, `JJR`, `JJS`, `LS`, `MD`, `NFP`, `NN`, `NNP`, `NNPS`, `NNS`, `PDT`, `POS`, `PRP`, `PRP$`, `RB`, `RBR`, `RBS`, `RP`, `SYM`, `TO`, `UH`, `VB`, `VBD`, `VBG`, `VBN`, `VBP`, `VBZ`, `WDT`, `WP`, `WP$`, `WRB`, `XX`, ```` |
| **`parser`** | `ROOT`, `acl`, `acl:relcl`, `acomp`, `advcl`, `advmod`, `amod`, `amod@nmod`, `appos`, `attr`, `aux`, `auxpass`, `case`, `cc`, `cc:preconj`, `ccomp`, `compound`, `compound:prt`, `conj`, `cop`, `csubj`, `dative`, `dep`, `det`, `det:predet`, `dobj`, `expl`, `intj`, `mark`, `meta`, `mwe`, `neg`, `nmod`, `nmod:npmod`, `nmod:poss`, `nmod:tmod`, `nsubj`, `nsubjpass`, `nummod`, `parataxis`, `pcomp`, `pobj`, `preconj`, `predet`, `prep`, `punct`, `quantmod`, `xcomp` |
| **`ner`** | `CHEMICAL`, `DISEASE` |

</details>

### Accuracy

| Type | Score |
| --- | --- |
| `TAG_ACC` | 0.00 |
| `LEMMA_ACC` | 0.00 |
| `DEP_UAS` | 0.00 |
| `DEP_LAS` | 0.00 |
| `DEP_LAS_PER_TYPE` | 0.00 |
| `SENTS_P` | 0.00 |
| `SENTS_R` | 0.00 |
| `SENTS_F` | 0.00 |
| `ENTS_F` | 85.31 |
| `ENTS_P` | 86.79 |
| `ENTS_R` | 83.88 |
| `NER_LOSS` | 199870.22 |