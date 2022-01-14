
# Databases and Versions

### Reasoning:
This reposistory is part of wider effort to create and maintain detailed and consistent functional annotation across several genome projects. To help maintain consistency and improve effciency  database versions are frozen. They can be updated as needed in your own versions, or at some later date for this version. The effciency saving step is that meta-data associated with a genomic hit is saved  between runs of the pipeline in pickle format, allowing for memoization leading to decreased look-up time the more times the pipeline is run. 

-----------------------------------------

## UniRef50 version 2021_02
### About
released 07-Apr-2021 see additional information [here](https://ftp.uniprot.org/pub/databases/uniprot/previous_releases/release-2021_02/relnotes.txt) and tarball available [release_2021_02/uniref](https://ftp.uniprot.org/pub/databases/uniprot/previous_releases/release-2021_02/uniref/). It is a respectable size (152GB) even when compressed. 

## Select Uniprot Accesions
### About:
I have selected 36 uniprot accession that span green plants ([link](https://github.com/NDHall/CirrostratusGFA/blob/main/resources/uniprot_table.tsv)) the version numbers for each set of meta-data can be found in [uniprot_versions.txt](https://github.com/NDHall/CirrostratusGFA/blob/main/resources/uniprot_versions.txt)

## InterProScan (iprscan5)
### About: 
We are using iprscan/5.47.82.0.Py3 and database v82.

## NCBI Accessions
### About
A select set of proteins downloaded from NCBI and curated to include proteins with links to GeneIds. With the exception of _Avena sativa_ which was only available through COGE. Documentation on production of these databases vailable on request.
* [curation notes](https://docs.google.com/spreadsheets/d/1G_QFUXiFlAi772adg_6x7Mjv_xOhdsAK/edit?usp=sharing&ouid=110533873252875230607&rtpof=true&sd=true)
* [seqs](https://drive.google.com/file/d/1Gq7ADthvLnPCAWeRlayrsiC2sdDW6E1F/view?usp=sharing)
* [id pickle](https://drive.google.com/file/d/1GpOFpMyK9zJAvkwsq3BYTrtY8WVt5_hd/view?usp=sharing)
* [description pickle](https://drive.google.com/file/d/1GpRWUG8b6Keg9C-IkDv61zywN7LXqlKj/view?usp=sharing)



