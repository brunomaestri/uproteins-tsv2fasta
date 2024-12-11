# tsv2fasta
![Python](https://img.shields.io/badge/Python3-blue.svg)

Simple script to convert tsv result files generated by μProteInS \
(https://github.com/Eduardo-vsouza/uproteins) into fasta files.

## Installation
To start running tsv2fasta, follow these steps:
1. Install Python3
2. `git clone` this repository to your desired directory
3. Run `pip install -r requirements.txt`

## Usage
tsv2fasta [-h] [-o OUTPUT] [-d DIR] input

positional arguments:
  input                 input file, should be a results file from μProteInS

options:
  -h, --help            show this help message and exit
  -o OUTPUT, --output OUTPUT
                        output file name, default is the input file name with fasta extension
  -d DIR, --dir DIR     output directory, default is .\results

The input file will not be validated by the script. Make sure it is a valid \
μProteInS result file, or the program may crash or fail silently.