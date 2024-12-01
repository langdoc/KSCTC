# Kola Saami Christian Text Corpus (KSCTC)

The main author of the dataset and administrator of this project is Michael Rießler.

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

## Code of conduct
…to be added in the file [Code of Conduct](CoC.md)…


## Metadata
Currently, only basic metadata is included; see the overview below. More detailed metadata is planned to be published (in CMDI format) later.


## Simple corpus statistics
The following table provides an overview of the included data and the state of their completion. Basic metadata can also be extracted.

| Session                                 | Description     | Tokens | Status   | Use  |
| --------------------------------------- | --------------- | -----: | -------- | ---- |
| sjd19960000_arapovic1996a-00Content     | Imprint         | 152    | finished | open | 
| sjd19960000_arapovic1996a-00Front       | Imprint         | 3      | finished | open | 
| sjd19960000_arapovic1996a-00Imprint     | Imprint         | 80     | finished | open | 
| sjd19960000_arapovic1996a-00Title       | Imprint         | 13     | finished | open |
| sjd20080000_ermolaeva2010a-00Title      | Imprint         | 5      | finished | open |
| sjd20080000_ermolaeva2010a-01           | Matthew 1       | 322    | finished | fair | 
| sjd20220300_bibleAPOSTLES2022a          | Apostles' Creed | 71     | finished | fair |
| sjd20220300_bibleLORDMATTH2022a         | Lord's Prayer   | 60     | finished | fair |
| sjd20220300_bibleMATTHEW2022a-00Imprint | Imprint         | 56     | finished | open | 
| sjd20220300_bibleMATTHEW2022a-00Title   | Imprint         | 10     | finished | open | 
| sjd20220300_scheller2022a               | Preface         | 559    | finished | clos |
|                                         |                 |        | planned  | acad |
|                                         | Matthew 1       |        |          | clos |
|                                         | Matthew 1       |        |          | open |
|                                         | Matthew 1       |        |          | open |

### Session
- Points to the file name
	- The language is indicated (as ISO) in the first three letters of the file name.
 	- The second section of the file name indicates the data of origin, at least the year. 
 	- The third section (after underscore) includes a pointer to the [Bibliography](bibliography.bib), where the original text sources are listed.
  	- The fourth section (if applicable, after hyphen) is for sub sets. 	 

### Description
- See more metadata in the respective CMDI files (work in progress).

### Tokens
- Simple token count

### Status
- Data marked as "finished" includes data in the minimal tier set (ref, [ref(orig)], orth(orig), word(orig)); read the paper for more detail

### Use
- Data marked as "closed" must not be re-published or shared in any way outside this project because copyright applies. These data can, however, be analysed and processed by project collaborators.
- Data marked as "acad" are under copyright but can be used under an academic license via the Language Bank of Finland.
- Data marked as "fair" are technically also under copyright. But the nature of these texts (especially Lord's Prayer) or the fact that they have already been widely distributed in print makes allows their use as open corpus data, in our opinion.
- Data marked as "open" are either in the Open Domain (old publications) or do not meet the threshold of originality (title pages, etc.).


## TODO
Planned improvements
- Website
- submodule
- validation scripts
- dynamic corpus statistics
- metadata links to Wikidata
