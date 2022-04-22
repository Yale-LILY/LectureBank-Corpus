# LILY LectureBank Data

Data for experiments [link](https://github.com/Yale-LILY/LectureBank).



## Meta Data

### Versions
`LectureBank1and2.tsv`: LectureBank 1.0 and 2.0, 1717 files.

`LectureBank3.tsv`: LectureBank 3.0, 5009 files.

Each line identifies a lecture file. Format:

`(ID, Title, URL, Year, Author, Domain, Venue)`


- `ID`: Id of each line.
- `Title`: File tile.
- `URL`: Online URL.
- `Year`: Year of the course.
- `Author`: The author name(s).
- `Domain`: The domain (nlp, ir, dl, ml, ai).
- `Venue`: Name of the university, or `GitHub`.

## Taxonomy

This is the scheme release for our paper [CLICKER: A Computational LInguistics Classification Scheme for Educational Resources](https://arxiv.org/abs/2112.08578).

In the file `taxonomy.csv`, we include the taxonomy with 320 topics in a tree structure. The topic ID for each topic shows the parent node. For example, `233 (Relation Extraction)` has a parent node to be `23 (Part of Speech Tagging)`, and topic `23` has its parent node to be `2 (Language Modeling, Syntax, Parsing)`.


- `Topic ID`: Id of topic.
- `Topic`: topic name.


