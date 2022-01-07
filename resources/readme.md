
# Databases and Versions

### Reasoning:
This reposistory is part of wider effort to create and maintain detailed and consistent functional annotation across several genome projects. To help maintain consistency and improve effciency a database versions are frozen. They can be updated as needed in your own versions, or at some later date for this version. The effciency saving step is that meta-data associated with a genomic hit is saved  between runs of the pipeline in pickle format, allowing for memoization leading to decreased look-up time the more times the pipeline is run. 

-----------------------------------------

## UniRef50 version 2021_02
### About
released 07-Apr-2021 see additional information [here](https://ftp.uniprot.org/pub/databases/uniprot/previous_releases/release-2021_02/relnotes.txt) and tarball available [release_2021_02/uniref](https://ftp.uniprot.org/pub/databases/uniprot/previous_releases/release-2021_02/uniref/). It is a respectable size (152GB) even when compressed. 

## Select Uniprot Accesions
### About:
I have selected 36 uniprot accession that span green plants ([link](https://github.com/NDHall/CirrostratusGFA/blob/main/resources/uniprot_table.tsv)) the version numbers for each set of meta-data can be found in [uniprot_versions.txt](https://github.com/NDHall/CirrostratusGFA/blob/main/resources/uniprot_versions.txt)

#InterProScan (iprscan5)
### About: 
We are using iprscan/5.47.82.0.Py3 and database v82.




