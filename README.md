# Kola Saami Christian Text Corpus (KSCTC)

Current version: Alpha (not released yet)


## Authors and credits

The originator of the dataset and administrator of this project is [Michael Rießler](https://uefconnect.uef.fi/michael.riesler/). The second main author is [Ilia Egorov](https://www.finnougristik.uni-muenchen.de/personen/wiss_ma/ilia-egorov/).

The paper [Rießler 2024](https://aclanthology.org/2024.iwclul-1.18) includes a more complete description. If you use the data, please cite this paper (below a bibtex code snippet).

```

@incollection{riesler2024a,
	address = {Helsinki},
	author = {Rie{\ss}ler, Michael},
	booktitle = {Proceedings of the 9th International Workshop on Computational Linguistics for Uralic Languages},
	editor = {H{\"a}m{\"a}l{\"a}inen, Mika and Pirinen, Flammie and Macias, Melany and Avila, Mario Crespo},
	pages = {138-144},
	publisher = {ACL},
	title = {Kola Saami Christian Text Corpus},
	url = {https://aclanthology.org/2024.iwclul-1.18},
	year = {2024}}
```


## Data format
The data is modelled in XLM using the corpus tool [ELAN](https://archive.mpi.nl/tla/elan]).

Tiers included are
- "ref" - project-internal ID for each single chunk
- "ref(orig)" - if applicable: verse number (Gospel of Matthew and Lord's Prayer) as location for parallelization
- "orth(orig)" - original text in original script
- "orth" - normalized orthography
- "ft-rus" - if applicable: free Russian translation
- "ft-rus(orig)" - if applicable: original Russian text on which the translation is based


## Data access
Only parts of the corpus are openly available. Other parts – under bound licenses – are found in [KSCTC-bound](https://github.com/langdoc/KSCTC-bound/), which is a private repository and visible only to project collaborators. 

If you are interested in collaboration, contact [Michael Rießler](mailto:michael.riessler@uef.fi).


### Code of conduct
Collaborators must acknowledge the terms of use by signing the [Code of Conduct](CoC.md) (in the works).


## Metadata
Currently, only basic metadata is available. 

Session metadata can be extracted from the overview below. Bibliographic metadata about the text sources is found in [Bibliography](bibliography.bib). Anonymized personal metadata about the text originators is included in the tier names in each individual session (e.g. "PAP1821m" is a male person born 1821, "AAA1932f" is a female person born 1932).

More detailed metadata is planned to be published (in CMDI format) later.


## Simple corpus statistics
The following table provides an overview of the included data and the state of their completion.

| Session                                       | Description      | Tokens | Status   | Use   |
| --------------------------------------------- | ---------------- | ------ | -------- | ----- |
| rus19920000_arapovic1992a-02Annunciation      | Jesus            |        |          | bound |
| rus19920000_arapovic1992a-04Birth             | Jesus            |        |          | bound |
| rus19920000_arapovic1992a-06Shepherds         | Jesus            |        |          | bound |
| rus19920000_arapovic1992a-08Adoration         | Jesus            |        |          | bound |
| rus19920000_arapovic1992a-10Exile             | Jesus            |        |          | bound |
| rus19920000_arapovic1992a-12Disciplines       | Jesus            |        |          | bound |
| rus19920000_arapovic1992a-14Samaritan         | Jesus            |        |          | bound |
| rus19920000_arapovic1992a-16Sermon-Beatitudes | Jesus            |        |          | bound |
| rus19920000_arapovic1992a-19LordsPrayer       | Jesus            |        |          | bound |
| rus19920000_arapovic1992a-20Sower             | Jesus            |        |          | bound |
| sia18760800_bibleMATTHEW1878a-24              | Matthew 24       |        |   | free  |
| sia18760800_bibleMATTHEW1878a-25              | Matthew 25       |        |   | free  |
| sia18760800_bibleMATTHEW1878a-26              | Matthew 26       |        |   | free  |
| sia18760800_bibleMATTHEW1878a-27              | Matthew 27       |        |   | free  |
| sia18760800_bibleMATTHEW1878a-28              | Matthew 28       |        |   | free  |
| sjd18280000_sjogren1828a-LordsPrayer          | Lord's Prayer    | 59     | finished | free  |
| sjd18760800_bibleMATTHEW1878a-00Title         | Imprint          | 2      | finished | free  |
| sjd18760800_bibleMATTHEW1878a-00Titlepage     | Imprint          | 19     | finished | free  |
| sjd18760800_bibleMATTHEW1878a-01              | Matthew 1        |        |   | free  |
| sjd18760800_bibleMATTHEW1878a-05              | Matthew 5        | 822    | finished | free  |
| sjd18760800_bibleMATTHEW1878a-06              | Matthew 6        | 664    | finished | free  |
| sjd18760800_bibleMATTHEW1878a-07              | Matthew 6        | 497    | finished | free  |
| sjd18760800_bibleMATTHEW1878a-16              | Matthew 16       | 517    | finished | free  |
| sjd18760800_genetz1879a-01                    | Matthew 1        | 328    | finished | free  | 
| sjd18760800_genetz1879a-05                    | Matthew 5        | 825    | finished | free  | 
| sjd18760800_genetz1879a-07                    | Matthew 7        | 498    | finished | free  | 
| sjd18760800_genetz1879b-01                    | Matthew 1        | 328    | finished | free  | 
| sjd18760800_genetz1879b-05                    | Matthew 5        | 825    | finished | free  | 
| sjd18760800_genetz1879b-07                    | Matthew 7        | 498    | finished | free  | 
| sjd18760800_genetz1891a-kilb05                | Matthew 5        | 824    | finished | free  |
| sjd18760800_genetz1891a-kilb06                | Matthew 6        | 633    | finished | free  |
| sjd18760800_genetz1891a-kilb07                | Matthew 7        | 497    | finished | free  |
| sjd19960000_arapovic1996a-00Content           | Imprint          | 152    | finished | free  | 
| sjd19960000_arapovic1996a-00Front             | Imprint          | 3      | finished | free  | 
| sjd19960000_arapovic1996a-00Imprint           | Imprint          | 80     | finished | free  | 
| sjd19960000_arapovic1996a-00Title             | Imprint          | 13     | finished | free  |
| sjd19960000_arapovic1996a-02Annunciation      | Jesus            | 260    | finished | acad  |
| sjd19960000_arapovic1996a-04Birth             | Jesus            | 191    | finished | acad  |
| sjd19960000_arapovic1996a-06Shepherds         | Jesus            | 240    | finished | acad  |
| sjd19960000_arapovic1996a-08Adoration         | Jesus            | 251    | finished | acad  |
| sjd19960000_arapovic1996a-10Exile             | Jesus            | 275    | finished | acad  |
| sjd19960000_arapovic1996a-12Disciplines       | Jesus            | 253    | finished | acad  |
| sjd19960000_arapovic1996a-14Samaritan         | Jesus            | 289    | finished | acad  |
| sjd19960000_arapovic1996a-16Sermon-Beatitudes | Jesus            | 259    | finished | acad  |
| sjd19960000_arapovic1996a-19LordsPrayer       | Jesus            | 63     | finished | acad  |
| sjd19960000_arapovic1996a-20Sower             | Jesus            | 214    | finished | acad  |
| sjd19960000_bibleLORDMATTHEW1996a             | Lord's Prayer    | 63     | finished | fair  | 
| sjd20050300_saam2005-03Prayer                 | Prayer           | 70     | finished | fair  |
| sjd20080000_ermolaeva2010a-00Title            | Imprint          | 5      | finished | free  |
| sjd20080000_ermolaeva2010a-01                 | Matthew 1        | 322    | finished | fair  | 
| sjd20141008_bibleLORDMATTH2022b               | Lord's Prayer    | 58     | finished | fair  |
| sjd20220300_bibleAPOSTLES2022a                | Apostles' Creed  | 71     | finished | fair  |
| sjd20220300_bibleLORDMATTH2022a               | Lord's Prayer    | 60     | finished | fair  |
| sjd20220300_bibleMATTHEW2022a-00Imprint       | Imprint          | 56     | finished | free  | 
| sjd20220300_bibleMATTHEW2022a-00Title         | Imprint          | 10     | finished | free  | 
| sjd20220300_bibleMATTHEW2022a-01              | Matthew 1        | 315    | finished | bound |
| sjd20220300_bibleMATTHEW2022a-02              | Matthew 2        |        |   | bound |
| sjd20220300_bibleMATTHEW2022a-03              | Matthew 3        |        |   | bound |
| sjd20220300_bibleMATTHEW2022a-04              | Matthew 4        |        |   | bound |
| sjd20220300_bibleMATTHEW2022a-05              | Matthew 5        |        |   | bound |
| sjd20220300_bibleMATTHEW2022a-06              | Matthew 6        |        |   | bound |
| sjd20220300_bibleMATTHEW2022a-07              | Matthew 7        |        |   | bound |
| sjd20220300_bibleMATTHEW2022a-08              | Matthew 8        |        |   | bound |
| sjd20220300_bibleMATTHEW2022a-09              | Matthew 9        |        |   | bound |
| sjd20220300_bibleMATTHEW2022a-10              | Matthew 10       |        |   | bound |
| sjd20220300_bibleMATTHEW2022a-11              | Matthew 11       |        |   | bound |
| sjd20220300_bibleMATTHEW2022a-12              | Matthew 12       |        |   | bound |
| sjd20220300_bibleMATTHEW2022a-13              | Matthew 13       |        |   | bound |
| sjd20220300_bibleMATTHEW2022a-14              | Matthew 14       |        |   | bound |
| sjd20220300_bibleMATTHEW2022a-15              | Matthew 15       |        |   | bound |
| sjd20220300_bibleMATTHEW2022a-16              | Matthew 16       | 464    | finished | bound |
| sjd20220300_bibleMATTHEW2022a-16L2            | Matthew 16:22-28 | 127    | finished | fair  |
| sjd20220300_bibleMATTHEW2022a-17              | Matthew 17       |     |  | bound |
| sjd20220300_bibleMATTHEW2022a-18              | Matthew 18       |     |  | bound |
| sjd20220300_bibleMATTHEW2022a-19              | Matthew 19       |     |  | bound |
| sjd20220300_bibleMATTHEW2022a-20              | Matthew 20       |     |  | bound |
| sjd20220300_bibleMATTHEW2022a-21              | Matthew 21       |     |  | bound |
| sjd20220300_bibleMATTHEW2022a-22              | Matthew 22       |     |  | bound |
| sjd20220300_bibleMATTHEW2022a-23              | Matthew 23       |     |  | bound |
| sjd20220300_bibleMATTHEW2022a-24              | Matthew 24       |     |  | bound |
| sjd20220300_bibleMATTHEW2022a-25              | Matthew 25       |     |  | bound |
| sjd20220300_bibleMATTHEW2022a-26              | Matthew 26       |     |  | bound |
| sjd20220300_bibleMATTHEW2022a-27              | Matthew 27       |     |  | bound |
| sjd20220300_bibleMATTHEW2022a-28              | Matthew 28       |     |  | bound |
| sjd20220300_scheller2022a                     | Preface          | 559    | finished | bound |

Session
- Points to the file name
	- The language is indicated (as ISO) in the first three letters of the file name.
 	- The second section of the file name indicates the (known or estimated) date of origin, at least the year. 
 	- The third section (after underscore) includes a pointer to the [Bibliography](bibliography.bib), where the original text sources are listed.
  	- The fourth section (if applicable, after hyphen) indicates sub-sets. 	 

Description
- See more metadata in the respective CMDI files (work in progress).

Tokens
- Simple token count

Status
- Data marked as "finished" includes data in the minimal tier set (ref, [ref(orig)], orth(orig), word(orig)); read the paper for more detail

Use
- Data marked as "bound" must not be re-published or shared in any way outside this project because copyright applies. These data can, however, be analysed and processed by project collaborators.
- Data marked as "acad" are under copyright but can be used under an academic license via the Language Bank of Finland.
- Data marked as "fair" are technically also under copyright. But the nature of these texts (especially Lord's Prayer), their earlier distribution, or other reasons allows their use as open corpus data in research, in our opinion.
- Data marked as "free" are either in the Open Domain (old publications) or do not meet the threshold of originality (book imprints, title pages, etc.).


## TODO
Planned improvements
- Website
- submodule
- validation scripts
- dynamic corpus statistics
- metadata links to Wikidata
