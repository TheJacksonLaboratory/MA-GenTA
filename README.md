# Targeted Probe Design Pipeline

## Setup:
Prior to running this pipeline, analyses will need to create:
* genome bin fasta files for each cluster
* Prokka annotation prediction files (.ffn)

* Modify the [toml](https://docs.python.org/3.6/library/sqlite3.html) configuration file (probe_design.config.toml) to use on your system.
* Install all required applications and modules.


### Application requirements:
* catch/design.py - "A package for designing compact and comprehensive capture probe sets."
  * https://github.com/broadinstitute/catch/
* usearch (used v8.0.1517_i86linux64)
  * http://drive5.com/usearch/
* ncbi-blast+ for makeblastdb, blastn (used 2.8.1+)
  * ftp://ftp.ncbi.nlm.nih.gov/blast/executables/blast+/

### Python3:
* [Python](https://www.python.org) &gt;= 3.6
## License
This app is licensed under the terms of the [MIT license](./LICENSE).
