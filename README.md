# MetaGeneAnnotator
[MetaGeneAnnotator](http://metagene.nig.ac.jp/) is a gene-finding program for prokaryote and phage.
Anonymous and fragmented genomic sequences (longer than 60 bp) can be accepted.

This project encapsulated MetaGeneAnnotator into a docker container.

## Usage
```usage
docker run \
    -v data_dir_path:/data \
    yookuda/mga \
    mga \
        /data/input_file \
        <-m/-s> \
        > output_file
```
