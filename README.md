<div align="center">    
 
# UniteD-SRL: A unified dataset for span- and dependency-based multilingual and cross-lingual Semantic Role Labeling

[![Paper](http://img.shields.io/badge/paper-Link-B31B1B.svg)](https://www.researchgate.net/publication/354550985_UniteD-SRL_A_Unified_Dataset_for_Span-and_Dependency-Based_Multilingual_and_Cross-Lingual_Semantic_Role_Labeling)
[![Conference](http://img.shields.io/badge/conference-EMNLP--2021-4b44ce.svg)](https://2021.emnlp.org/)
[![License: CC BY-NC 4.0](https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc-sa/4.0)

</div>

## Description
This is the repository for the paper [*UniteD-SRL: A unified dataset for span- and dependency-based multilingual and cross-lingual Semantic Role Labeling*](https://www.researchgate.net/publication/354550985_UniteD-SRL_A_Unified_Dataset_for_Span-and_Dependency-Based_Multilingual_and_Cross-Lingual_Semantic_Role_Labeling),
to be presented at EMNLP 2021 by [Rocco Tripodi](https://www.unibo.it/sitoweb/rocco.tripodi), [Simone Conia](https://c-simone.github.io) and [Roberto Navigli](https://www.diag.uniroma1.it/navigli/).


## Abstract
> Multilingual and cross-lingual Semantic Role Labeling (SRL) have recently garnered increasing attention as multilingual text representation techniques have become more effective and widely available. While recent work has attained growing success, results on gold multilingual benchmarks are still not easily comparable across languages, making it difficult to grasp where we stand. For example, in CoNLL-2009, the standard benchmark for multilingual SRL, language-to-language comparisons are affected by the fact that each language has its own dataset which differs from the others in size, domains, sets of labels and annotation guidelines. In this paper, we address this issue and propose UNITED-SRL, a new benchmark for multilingual and cross-lingual, span-and dependency-based SRL. UNITED-SRL provides expert-curated parallel annotations using a common predicate-argument structure inventory, allowing direct comparisons across languages and encouraging studies on cross-lingual transfer in SRL.

## Download
You can download a copy of all the files in this repository by cloning the
[git](https://git-scm.com/) repository:
```sh
git clone https://github.com/SapienzaNLP/unify-srl.git
```
or [download a zip archive](https://github.com/SapienzaNLP/united-srl/archive/main.zip).

### Get the data
The latest version of UniteD-SRL is freely available for research purposes at https://nlp.uniroma1.it/resources (coming soon).

## Cite this work
If you use any part of this work, please cite our reference paper.

Plaintext:
> Rocco Tripodi, Simone Conia and Roberto Navigli, 2021. **UniteD-SRL: Unified Dataset for Span- and Dependency-based Multilingual and Cross-Lingual Semantic Role Labeling.** *In Findings of the Association for Computational Linguistics: EMNLP 2021.* Punta Cana, Dominican Republic. Association for Computational Linguistics.

Bibtex:
```bibtex
@inproceedings{tripodi-etal-2021-united-srl,
    title = {{UniteD-SRL}: {A} Unified Dataset for Span- and Dependency-based Multilingual and Cross-Lingual {S}emantic {R}ole {L}abeling},
    author = "Tripodi, Rocco  and
      Conia, Simone  and
      Navigli, Roberto",
    booktitle = "Findings of the Association for Computational Linguistics: {EMNLP} 2021",
    month = nov,
    year = "2021",
    address = "Punta Cana, Dominican Republic",
    publisher = "Association for Computational Linguistics"
}
```

### Other references
In our experiments, we used the model from [*Bridging the Gap in Multilingual Semantic Role Labeling: a Language-Agnostic Approach*](https://www.aclweb.org/anthology/2020.coling-main.120). 
```bibtex
@inproceedings{conia-navigli-2020-bridging,
    title = "Bridging the Gap in Multilingual Semantic Role Labeling: a Language-Agnostic Approach",
    author = "Conia, Simone  and
      Navigli, Roberto",
    booktitle = "Proceedings of the 28th International Conference on Computational Linguistics (COLING 2020)",
    month = dec,
    year = "2020",
    address = "Barcelona, Spain (Online)",
    publisher = "International Committee on Computational Linguistics",
    url = "https://www.aclweb.org/anthology/2020.coling-main.120",
    pages = "1396--1410"
}
```

Read more about [*VerbAtlas*](https://www.aclweb.org/anthology/D19-1058), the Semantic Role Labeling inventory we used to tag UniteD-SRL.
```bibtex
@inproceedings{di-fabio-etal-2019-verbatlas,
    title = "{V}erb{A}tlas: {A} Novel Large-Scale Verbal Semantic Resource and Its Application to Semantic Role Labeling",
    author = "Di Fabio, Andrea  and
      Conia, Simone  and
      Navigli, Roberto",
    booktitle = "Proceedings of the 2019 Conference on Empirical Methods in Natural Language Processing and the 9th International Joint Conference on Natural Language Processing (EMNLP-IJCNLP)",
    month = nov,
    year = "2019",
    address = "Hong Kong, China",
    publisher = "Association for Computational Linguistics",
    url = "https://www.aclweb.org/anthology/D19-1058",
    doi = "10.18653/v1/D19-1058",
    pages = "627--637"
}
```

## License
UniteD-SRL is licensed under [Creative Commons Attribution-NonCommercial-ShareAlike 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0).
