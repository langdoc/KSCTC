# Kola Saami Christian Text Corpus (KSCTC)

Current version: Alpha (not released yet)


## Authors and credits

The main author of the dataset and administrator of this project is [Michael Rießler](https://uefconnect.uef.fi/michael.riesler/).

The following paper includes a more complete description.

```
@incollection{riesler2024a,
	address = {Helsinki},
	author = {Rie{\ss}ler, Michael},
	booktitle = {Proceedings of the 9th International Workshop on Computational Linguistics for Uralic Languages},
	pages = {138-144},
	publisher = {ACL},
	title = {Kola Saami Christian Text Corpus},
	year = {2024}}
```

If you use the data, please cite my paper.


## Data format
The corpus data is modelled in XLM using the tool [ELAN](https://archive.mpi.nl/tla/elan]).


## Data access
Only parts of the corpus are openly available. Other parts – under bound licenses – are found in [KSCTC-bound](https://github.com/langdoc/KSCTC-bound/), which is a private repository and visible only to project collaborators. 

If you are interested in collaboration, contact [Michael Rießler](mailto:michael.riessler@uef.fi).

### Code of conduct
Collaborators must acknowledge the terms of use by signing the [Code of Conduct](CoC.md).


## Metadata
Currently, only basic metadata is available. 

Session metadata can be extracted from the overview below. 

Bibliographic metadata about the text sources is found in [Bibliography](bibliography.bib). 

Anonymized personal metadata about the text originators is included in the tier names in each individual session (e.g. "PAP1821m" is a male person born 1821, "AAA1932f" is a female person born 1932).

More detailed metadata is planned to be published (in CMDI format) later.


## Simple corpus statistics
The following table provides an overview of the included data and the state of their completion.

| Session                                   | Description     | Tokens | Status   | Use   |
| ----------------------------------------- | --------------- | -----: | -------- | ----- |
| sia1876                                   | Matthew 24      |        | planned  | free  |
| sia1876                                   | Matthew 25      |        | planned  | free  |
| sia1876                                   | Matthew 26      |        | planned  | free  |
| sia1876                                   | Matthew 27      |        | planned  | free  |
| sia1876                                   | Matthew 28      |        | planned  | free  |
| sjd18760800_bibleMATTHEW1878a-00Title     | Imprint         | 2      | finished | free  |
| sjd18760800_bibleMATTHEW1878a-00Titlepage | Imprint         | 19     | finished | free  |
| sjd18760800_bibleMATTHEW1878a-05          | Matthew 5       | 822    | finished | free  |
| sjd18760800_bibleMATTHEW1878a-06          | Matthew 6       | 664    | finished | free  |
| sjd18760800_bibleMATTHEW1878a-07          | Matthew 6       | 497    | finished | free  |
| sjd18760800_bibleMATTHEW1878a-16          | Matthew 16      | 517    | finished | free  |
| sjd18760800_genetz1879a-01                | Matthew 1       | 328    | finished | free  | 
| sjd18760800_genetz1879a-05                | Matthew 5       | 825    | finished | free  | 
| sjd18760800_genetz1879b-01                | Matthew 1       | 328    | finished | free  | 
| sjd18760800_genetz1879b-05                | Matthew 5       | 825    | finished | free  | 
| sjd18760800_genetz1879b-07                | Matthew 7       | 498    | finished | free  | 
| sjd18760800_genetz1891a-kilb05            | Matthew 5       | 824    | finished | free  |
| sjd18760800_genetz1891a-kilb06            | Matthew 6       | 633    | finished | free  |
| sjd18760800_genetz1891a-kilb07            | Matthew 7       | 497    | finished | free  |
| sjd19960000_arapovic1996a-00Content       | Imprint         | 152    | finished | free  | 
| sjd19960000_arapovic1996a-00Front         | Imprint         | 3      | finished | free  | 
| sjd19960000_arapovic1996a-00Imprint       | Imprint         | 80     | finished | free  | 
| sjd19960000_arapovic1996a-00Title         | Imprint         | 13     | finished | free  |
| sjd19960000_arapovic1996a-02Annunciation  | Jesus           | 260    | finished | acad  |
| sjd19960000_arapovic1996a-04Birth         | Jesus           | 191    | finished | acad  |
| sjd19960000_arapovic1996a-10Exile         | Jesus           | 275    | finished | acad  |
| sjd20080000_ermolaeva2010a-00Title        | Imprint         | 5      | finished | free  |
| sjd20080000_ermolaeva2010a-01             | Matthew 1       | 322    | finished | fair  | 
| sjd20220300_bibleAPOSTLES2022a            | Apostles' Creed | 71     | finished | fair  |
| sjd20220300_bibleLORDMATTH2022a           | Lord's Prayer   | 60     | finished | fair  |
| sjd20220300_bibleMATTHEW2022a-00Imprint   | Imprint         | 56     | finished | free  | 
| sjd20220300_bibleMATTHEW2022a-00Title     | Imprint         | 10     | finished | free  | 
| sjd20220300_bibleMATTHEW2022a-01          | Matthew 1       | 315    | finished | bound |
| sjd20220300_scheller2022a                 | Preface         | 559    | finished | bound |
| sjd18760800_bibleMATTHEW1878a-01          | Matthew 1       |        | planned  | free  |
| sjd20220300_bibleMATTHEW2022a-02          | Matthew 2       |        | planned  | bound |

Session
- Points to the file name
	- The language is indicated (as ISO) in the first three letters of the file name.
 	- The second section of the file name indicates the data of origin, at least the year. 
 	- The third section (after underscore) includes a pointer to the [Bibliography](bibliography.bib), where the original text sources are listed.
  	- The fourth section (if applicable, after hyphen) is for sub sets. 	 

Description
- See more metadata in the respective CMDI files (work in progress).

Tokens
- Simple token count

Status
- Data marked as "finished" includes data in the minimal tier set (ref, [ref(orig)], orth(orig), word(orig)); read the paper for more detail

Use
- Data marked as "bound" must not be re-published or shared in any way outside this project because copyright applies. These data can, however, be analysed and processed by project collaborators.
- Data marked as "acad" are under copyright but can be used under an academic license via the Language Bank of Finland.
- Data marked as "fair" are technically also under copyright. But the nature of these texts (especially Lord's Prayer) or the fact that they have already been widely distributed in print makes allows their use as open corpus data, in our opinion.
- Data marked as "free" are either in the Open Domain (old publications) or do not meet the threshold of originality (book imprints, title pages, etc.).


## TODO
Planned improvements
- Website
- submodule
- validation scripts
- dynamic corpus statistics
- metadata links to Wikidata
