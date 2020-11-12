# TaxoNERD

Looking for taxon mentions in text? Ask TaxoNERD

* [Features](#features)
* [Installation](#installation)
* [Usage](#usage)

## Features

* Based on the en_ner_bionlp13cg_md model from [scispaCy](https://allenai.github.io/scispacy/), fine-tuned on ecological and biomedical datasets
* Find scientific names, common names and user-defined abbreviations
* Lightning-fast on CPU, can use GPU to speed-up the recognition process
* Available as a command-line tool and a python library

## Installation

    $ pip install .


## Usage

To use it:

    $ taxonerd --help
