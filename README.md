# classification-gold-standard
Gold standard for the evaluation of machine classification of patent data

The data for the gold standards can be found in the data/ directory, as TSV files. The columns are:

 * Class - whether the example is positive or negative
 * DocDB Family ID - the ID for the family from the DOCDB system, to aid grouping into families
 * Serial no. - the serial number of the publication, to allow identification of the publication, in the EPO [country-code][number][kind-code] format.
 * Title - the title as published, to aid cross-checking
 * Publication date - date the patent was published by the PO

Alongside the classification data are the scope notes, in a .txt file with the same base name.
