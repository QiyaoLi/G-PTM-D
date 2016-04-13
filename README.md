# G-PTM-D is a global peptide/protein modification discovery strategy.

# xml_trimming.pl
The xml_trimming.pl is for deleting unnecessary information contained in the xml database downloaded from UniProt (named "uniprot.xml") and thus speeding up the database search. A simplified database named “uniprot_trimmed.xml” will be created.

# xml_AddOpenSearchResult.pl
The xml_AddOpenSearchResult.pl is for adding potential modification information (identities and sites) discovered from the first-round wide tolerance search to the original database. The modified database is to be used in a second-round database search. 
