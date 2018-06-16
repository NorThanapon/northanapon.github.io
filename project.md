---
layout: null
section-type: project
title: project
---

## Project


#### RNNLM and n-gram statistics
This project explores how explicitly stated n-gram distribution can be used as a set of soft constraints to direct the language model behavior during the generation without sacrificing its accuracy in assigning probability to sequences of words. We apply the technique to reduce word-level repetition (a common problematic behavior). It also improves model generalizability by incorporating statistical constraints are n-gram statistics taken from a large corpus.

[ Paper: [AAAI'18](https://www.cs.northwestern.edu/~ddowney/publications/noraset_aaai_2018.pdf) \| Links: [code](https://github.com/northanapon/seqmodel/tree/aaai18)]


#### Definition Modeling

This project aims to build generative models of definitions in dictionaries and encyclopedias. The model learns from pairs of word embedding and definition. The model is then tested on how well it generates definitions for a given set of word embeddings. We are exploring deep learning algorithms and other language models.

[ Paper: [AAAI'17](http://www.aaai.org/ocs/index.php/AAAI/AAAI17/paper/view/14827) or [arXiv](https://arxiv.org/abs/1612.00394) \| Links: [demo](http://thor.cs.northwestern.edu:24603/), [code](https://github.com/Websail-NU/torch-defseq), [preprocessing](https://github.com/NorThanapon/dict-definition) ]

#### Key Phrase Extraction

This is a collaboration between [WebSAIL](http://websail.cs.northwestern.edu/) and [Allen Institute for Artificial Intelligence (AI2)](http://allenai.org/). The project focuses on building a system that extracts key phrases from scholar articles. These key phrases are  facet values to filter search results. [Chandra](http://allenai.org/team/chandrab/) is maintaining the system at AI2. [semanticscholar.org](https://www.semanticscholar.org) is using a version of the system.

[ Links: [SemanticScholar](https://www.semanticscholar.org)]


#### WebSAIL Wikifier and TabEL

WebSAIL Wikifier is an Entity Linking system that identifies and links phrases to a Wikipedia page. The project participated in [TAC 2013](http://www.nist.gov/tac/2013/KBP/EntityLinking/index.html) and [ERD 2014](http://web-ngram.research.microsoft.com/ERD2014/). We also attempted to "wikify" English Wikipedia to increase structured information on Wikipedia. Furthermore, [Chandra](http://allenai.org/team/chandrab/) has extended WebSAIL Wikifier for his TabEL project to extract entities from tables on websites. The algorithm here is an improved version of the original project.

[ Papers:
[3W](https://www.semanticscholar.org/paper/Adding-High-Precision-Links-to-Wikipedia-Noraset-Bhagavatula/0484edee55ee8c456e13b15b9f25f97f40351691),
[TabEL](https://www.semanticscholar.org/paper/TabEL-Entity-Linking-in-Web-Tables-Bhagavatula-Noraset/33b94ba1d8b02f05d42954025798210867a833b7),
[ERD](https://www.semanticscholar.org/paper/WebSAIL-wikifier-at-ERD-2014-Noraset-Bhagavatula/182324155ee1df44202d5f77c203d702d0390a31),
[TAC](https://www.semanticscholar.org/paper/WebSAIL-Wikifier-English-Entity-Linking-at-TAC-Noraset-Bhagavatula/225de99e1f9aa0783467b9b3e739cd692b981f20)
\|
Links:
[3W](http://websail.cs.northwestern.edu/projects/3W/),
[TabEL](http://websail-fe.cs.northwestern.edu/TabEL/) ]

#### TextJoiner and WikiTables
These projects aim to improve user information exploration of data from Wikipedia. TextJoiner is a system that allows users to interactively query and perform joins on facts expressed in Wikipedia using text patterns like `cities such as $x`. The project uses n-gram language models and word embeddings. On the other hand, WikiTables extracts Wikipedia tables and used machine learning to enable table exploration via "search" and "join". WikiTables allows user to find and view columns from different table side by side, and potentially discover an interesting correlation. *(Only involved in discussion and developing UI)*

[ Paper:
[TextJoiner](http://www.akbc.ws/2014/submissions/akbc2014_submission_24.pdf),
[WikiTables](https://www.semanticscholar.org/paper/Methods-for-exploring-and-mining-tables-on-Bhagavatula-Noraset/249e73a10351b9e9d2150762a287df0698d4f830)
 \|
Link:
[TextJoiner](http://websail-fe.cs.northwestern.edu/textjoiner/),
[WikiTables Join](http://downey-n1.cs.northwestern.edu/wikiTables/),
[WikiTables Search](http://downey-n1.cs.northwestern.edu/tableSearch/index.html)
]
