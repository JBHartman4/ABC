# ABC - The Annotated Beethoven Corpus

The ABC dataset consists of expert harmonic analyses of all Beethoven string quartets (opp. 18, 59, 74, 95, 127, 130, 131, 132, 135, composed between 1800 and 1826), encoded in a human- and machine-readable format (MuseScore format). Using a modified Roman Numeral notation, the dataset includes the common music-theoretical set of harmonic features such as key, chordal root, chord inversion, chord extensions, suspensions, and others.

The accompanying Data Report has been published by [Frontiers in Digital Humanities](https://www.frontiersin.org/articles/10.3389/fdigh.2018.00016/full).

## Authors
Markus Neuwirth (markus.neuwirth@epfl.ch), Daniel Harasim (daniel.harasim@epfl.ch), Fabian C. Moss (fabian.moss@epfl.ch), Martin Rohrmeier (martin.rohrmeier@epfl.ch)

## Remarks

### Possible annotation errors

While the annotation process (detailed in the Data Report) was conducted very carefully, and all annotated symbols have been automatically checked for syntactic correctness, the authors can not entirely exclude that some typos or misinterpretations remain, due to ambiguities in the score or underspecification in the musical texture. After all, music analysis is not a deterministic process but involves interpretation. If you encounter anything that seems not right to you, please create an issue [here](https://github.com/DCMLab/ABC/issues).

### Missing bars

The original XML file for Op. 132 No. 15, mov. 5 from Project Gutenberg did not contain measures XX-XX. We added these manually.