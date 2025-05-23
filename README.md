# Kola Saami Christian Text Corpus (KSCTC)
Current version: Alpha (not released yet)


## Authors and credits
The originator of the dataset and administrator of this project is [Michael Rießler](https://uefconnect.uef.fi/michael.riesler/). The second main author is [Ilia Egorov](https://www.finnougristik.uni-muenchen.de/personen/wiss_ma/ilia-egorov/).

The paper [Rießler 2024](https://aclanthology.org/2024.iwclul-1.18) includes a more complete description. If you use the data, please cite this paper (see the bibtex code snippet below).

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


## License, data reuse, and collaboration
The corpus data in this repository are free and open and licensed under CC-BY, see [LICENSE](LICENSE). Other parts of the corpus – under bound licenses – are found in [KSCTC-bound](https://github.com/langdoc/KSCTC-bound/), which is a private repository and visible only to project collaborators. 

If you are interested in collaboration, contact [Michael Rießler](mailto:michael.riessler@uef.fi). Collaborators must acknowledge the terms of use by signing the [Code of Conduct](CoC.md) (in the works).


## Data format
The data is modelled in XLM using the corpus tool [ELAN](https://archive.mpi.nl/tla/elan]).

Tiers included are
- "ref" - project-internal ID for each single chunk
- "ref(orig)" - if applicable: verse number (Gospel of Matthew and Lord's Prayer) as location for parallelization
- "orth(orig_<SOURCE>)" - original text in original script (<SOURCE> refers to an ID in the [Bibliography](bibliography.bib)); there can be more than one original texts included, e.g. in case of reprints of the same texts or different transcripts/transliterations of the same texts
- "orth" - normalized orthography
- "ft-rus(orig_<SOURCE>)" - if applicable: original Russian text on which the translation is based (<SOURCE> refers to an ID in the [Bibliography](bibliography.bib))


## Metadata
Basic metadata can be extracted from the overview below. Bibliographic metadata about the text sources is found in [Bibliography](bibliography.bib). Personal metadata about the text originators is included in the tier names in each individual session (e.g. "PAP1821m" is a male person born 1821, "AAA1932f" is a female person born 1932).


## Corpus statistics
Focus of our work so far has been on the Kildin Saami (sjd) subset in contemporary orthography. Genetz's original texts are not fully complete yet. Akkala Saami (sia) and Skolt Saami (sms) data are not included yet.

The following table provides an overview of the included data and the state of their completion. Below are more explanations of this table.

| Session                                       | Description      | Tokens | Status   | Use   |
| --------------------------------------------- | ---------------- | ------ | -------- | ----- |
| sia18760800_bibleMATTHEW1878a-23              | Matthew 23       |        |   | free  |
| sia18760800_bibleMATTHEW1878a-24              | Matthew 24       |        |   | free  |
| sia18760800_bibleMATTHEW1878a-25              | Matthew 25       |        |   | free  |
| sia18760800_bibleMATTHEW1878a-26              | Matthew 26       |        |   | free  |
| sia18760800_bibleMATTHEW1878a-27              | Matthew 27       |        |   | free  |
| sia18760800_bibleMATTHEW1878a-28              | Matthew 28       |        |   | free  |
| sia18760800_genetz1879a-23                    | Matthew 23       |        |   | free  |
| sia18760800_genetz1879a-24                    | Matthew 24       |        |   | free  |
| sia18760800_genetz1879a-25                    | Matthew 25       |        |   | free  |
| sia18760800_genetz1879a-26                    | Matthew 26       |        |   | free  |
| sia18760800_genetz1879a-27                    | Matthew 27       |        |   | free  |
| sia18760800_genetz1879a-28                    | Matthew 28       |        |   | free  |
| sjd18280000_sjogren1828a-LordsPrayer          | Lord's Prayer    | 59     | finished | free  |
| sjd18760800_bibleMATTHEW1878a-00Title         | Imprint          | 2      | finished | free  |
| sjd18760800_bibleMATTHEW1878a-00Titlepage     | Imprint          | 19     | finished | free  |
| sjd18760800_bibleMATTHEW1878a-01              | Matthew 1        | 323    | finished | free  |
| sjd18760800_bibleMATTHEW1878a-02              | Matthew 2        | 444    | finished | free  |
| sjd18760800_bibleMATTHEW1878a-03              | Matthew 3        | 281    | finished | free  |
| sjd18760800_bibleMATTHEW1878a-04              | Matthew 4        | 404    | finished | free  |
| sjd18760800_bibleMATTHEW1878a-05              | Matthew 5        | 822    | finished | free  |
| sjd18760800_bibleMATTHEW1878a-06              | Matthew 6        | 664    | finished | free  |
| sjd18760800_bibleMATTHEW1878a-07              | Matthew 7        | 497    | finished | free  |
| sjd18760800_bibleMATTHEW1878a-08              | Matthew 8        | 546    | finished | free  |
| sjd18760800_bibleMATTHEW1878a-09              | Matthew 9        | 639    | finished | free  |
| sjd18760800_bibleMATTHEW1878a-10              | Matthew 10       | 679    | finished | free  |
| sjd18760800_bibleMATTHEW1878a-11              | Matthew 11       | 517    | finished | free  |
| sjd18760800_bibleMATTHEW1878a-12              | Matthew 12       | 847    | finished | free  |
| sjd18760800_bibleMATTHEW1878a-13              | Matthew 13       | 1002   | finished | free  |
| sjd18760800_bibleMATTHEW1878a-14              | Matthew 14       | 528    | finished | free  |
| sjd18760800_bibleMATTHEW1878a-15              | Matthew 15       | 583    | finished | free  |
| sjd18760800_bibleMATTHEW1878a-16              | Matthew 16       | 517    | finished | free  |
| sjd18760800_bibleMATTHEW1878a-17              | Matthew 17       | 483    | finished | free  |
| sjd18760800_bibleMATTHEW1878a-18              | Matthew 18       | 639    | finished | free  |
| sjd18760800_bibleMATTHEW1878a-19              | Matthew 19       | 556    | finished | free  |
| sjd18760800_bibleMATTHEW1878a-20              | Matthew 20       | 579    | finished | free  |
| sjd18760800_bibleMATTHEW1878a-21              | Matthew 21       | 822    | finished | free  |
| sjd18760800_bibleMATTHEW1878a-22              | Matthew 22       | 625    | finished | free  |
| sjd18760800_genetz1879a-01                    | Matthew 1        | 328    | finished | free  | 
| sjd18760800_genetz1879a-05                    | Matthew 5        | 825    | finished | free  | 
| sjd18760800_genetz1879a-07                    | Matthew 7        | 498    | finished | free  | 
| sjd18760800_genetz1879b-01                    | Matthew 1        | 328    | finished | free  | 
| sjd18760800_genetz1879b-02                    | Matthew 2        | 450    | finished | free  | 
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
| sjd19960000_arapovic1996a-18Sermon-Love       | Jesus            | 407    | finished | acad  |
| sjd19960000_arapovic1996a-19LordsPrayer       | Jesus            | 63     | finished | acad  |
| sjd19960000_arapovic1996a-20Sower             | Jesus            | 214    | finished | acad  |
| sjd19960000_arapovic1996a-22Storm             | Jesus            | 132    | finished | acad  |
| sjd19960000_arapovic1996a-24Raising           | Jesus            | 282    | finished | acad  |
| sjd19960000_arapovic1996a-24Raising-Fn        | Jesus            | 10     | finished | acad  |
| sjd19960000_arapovic1996a-26Feeding           | Jesus            | 196    | finished | acad  |
| sjd19960000_arapovic1996a-28GoodSamaritan     | Jesus            | 227    | finished | acad  |
| sjd19960000_arapovic1996a-28GoodSamaritan-Fn  | Jesus            | 6      | finished | acad  |
| sjd19960000_arapovic1996a-30GoodShepherd      | Jesus            | 287    | finished | acad  | 
| sjd19960000_arapovic1996a-32LostSheep         | Jesus            | 144    | finished | acad  | 
| sjd19960000_arapovic1996a-34Prodigal          | Jesus            | 150    | finished | acad  | 
| sjd19960000_arapovic1996a-36Return            | Jesus            | 234    | finished | acad  | 
| sjd19960000_arapovic1996a-38Blesses           | Jesus            | 122    | finished | acad  | 
| sjd19960000_arapovic1996a-40Blind             | Jesus            | 165    | finished | acad  | 
| sjd19960000_arapovic1996a-42Zacchaeus         | Jesus            | 197    | finished | acad  | 
| sjd19960000_arapovic1996a-44Commandment       | Jesus            | 114    | finished | acad  | 
| sjd19960000_arapovic1996a-46Supper            | Jesus            | 164    | finished | acad  | 
| sjd19960000_arapovic1996a-48Gethsemane        | Jesus            | 245    | finished | acad  | 
| sjd19960000_arapovic1996a-50Arrest            | Jesus            | 208    | finished | acad  | 
| sjd19960000_arapovic1996a-52Pilatus           | Jesus            | 310    | finished | acad  | 
| sjd19960000_arapovic1996a-54Crucifixion       | Jesus            | 351    | finished | acad  | 
| sjd19960000_arapovic1996a-56Burial            | Jesus            | 266    | finished | acad  |
| sjd19960000_arapovic1996a-56Burial-Fn         | Jesus            | 14     | finished | acad  | 
| sjd19960000_arapovic1996a-58Risen             | Jesus            | 218    | finished | acad  | 
| sjd19960000_arapovic1996a-60Ascent            | Jesus            | 195    | finished | acad  | 
| sjd19960000_arapovic1996a-62Way               | Jesus            | 344    | finished | acad  | 
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
| sjd20220300_bibleMATTHEW2022a-02              | Matthew 2        | 392    | finished | bound |
| sjd20220300_bibleMATTHEW2022a-03              | Matthew 3        | 269    | finished | bound |
| sjd20220300_bibleMATTHEW2022a-04              | Matthew 4        | 385    | finished | bound |
| sjd20220300_bibleMATTHEW2022a-05              | Matthew 5        | 771    | finished | bound |
| sjd20220300_bibleMATTHEW2022a-06              | Matthew 6        | 619    | finished | bound |
| sjd20220300_bibleMATTHEW2022a-07              | Matthew 7        | 466    | finished | bound |
| sjd20220300_bibleMATTHEW2022a-08              | Matthew 8        | 521    | finished | bound |
| sjd20220300_bibleMATTHEW2022a-09              | Matthew 9        | 612    | finished | bound |
| sjd20220300_bibleMATTHEW2022a-10              | Matthew 10       | 643    | finished | bound |
| sjd20220300_bibleMATTHEW2022a-11              | Matthew 11       | 465    | finished | bound |
| sjd20220300_bibleMATTHEW2022a-12              | Matthew 12       | 795    | finished | bound |
| sjd20220300_bibleMATTHEW2022a-13              | Matthew 13       | 938    | finished | bound |
| sjd20220300_bibleMATTHEW2022a-14              | Matthew 14       | 486    | finished | bound |
| sjd20220300_bibleMATTHEW2022a-15              | Matthew 15       | 534    | finished | bound |
| sjd20220300_bibleMATTHEW2022a-16              | Matthew 16       | 464    | finished | bound |
| sjd20220300_bibleMATTHEW2022a-16L2            | Matthew 16:22-28 | 127    | finished | fair  |
| sjd20220300_bibleMATTHEW2022a-17              | Matthew 17       | 438    | finished | bound |
| sjd20220300_bibleMATTHEW2022a-18              | Matthew 18       | 622    | finished | bound |
| sjd20220300_bibleMATTHEW2022a-19              | Matthew 19       | 536    | finished | bound |
| sjd20220300_bibleMATTHEW2022a-20              | Matthew 20       | 536    | finished | bound |
| sjd20220300_bibleMATTHEW2022a-21              | Matthew 21       | 779    | finished | bound |
| sjd20220300_bibleMATTHEW2022a-22              | Matthew 22       | 594    | finished | bound |
| sjd20220300_bibleMATTHEW2022a-23              | Matthew 23       | 643    | finished | bound |
| sjd20220300_bibleMATTHEW2022a-24              | Matthew 24       | 736    | finished | bound |
| sjd20220300_bibleMATTHEW2022a-25              | Matthew 25       | 700    | finished | bound |
| sjd20220300_bibleMATTHEW2022a-26              | Matthew 26       | 1106   | finished | bound |
| sjd20220300_bibleMATTHEW2022a-27              | Matthew 27       | 1228   | finished | bound |
| sjd20220300_bibleMATTHEW2022a-28              | Matthew 28       | 309    | finished | bound |
| sjd20220300_scheller2022a                     | Preface          | 559    | finished | bound |

Session
- Points to the file name
	- The language is indicated (as ISO) in the first three letters of the file name.
	- The second section of the file name indicates the (known or estimated) date of origin, at least the year. 
	- The third section (after underscore) includes a pointer to the [Bibliography](bibliography.bib), where the original text sources are listed.
	- The fourth section (if applicable, after hyphen) indicates sub-sets (e.g. for footnotes or Matthew 16:22-28).

Description
- See more metadata in the respective CMDI files (work in progress).

Tokens
- Word token count

Status
- Data marked as "finished" includes data in the minimal tier set (ref, [ref(orig)], orth(orig), [ft-rus(orig)]; read the paper for more detail).

Use
- Data marked as "bound" must not be re-published or shared in any way outside this project because copyright applies. These data can, however, be analysed and processed by project collaborators.
- Data marked as "acad" are under copyright and not made freely available via the present repository . But they can be used under an academic license, which is handled by the [Language Bank of Finland](https://www.kielipankki.fi/language-bank/). 
- Data marked as "fair" are technically also under copyright. But the nature of these texts (especially Lord's Prayer), their earlier distribution, or other reasons allow their use as open corpus data in research, in our opinion. 
- Data marked as "free" are either in the Open Domain or do not meet the threshold of originality (book imprints, title pages, etc.).


## TODO
Planned improvements in the data
- finnish the Kildin Saami data
- check the parallel data
- last round of proofreading

Planned improvements at the platform level
- Website
- Pipeline: sjd-fair --> KSCTC
- validation scripts
- dynamic corpus statistics
- metadata links to Wikidata

## Open questions
- what to do with letter η in Cyrillic (Genetz), using Greek or Latin?