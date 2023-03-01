# Potential of natural language processing for metadata extraction from environmental scientific publications

[![DOI](https://zenodo.org/badge/452244190.svg)](https://zenodo.org/badge/latestdoi/452244190)


This repository is part of the [EJP SOIL CLIMASOMA project](https://ejpsoil.eu/soil-research/climasoma/).

This work aims to explore the potential of natural language processing (NLP) for metadata extraction from scientific publications. In this repository two corpus (set of documents) can be found:
- `Meta corpus`: all primary studies from the [review of meta-analyses](https://github.com/climasoma/review-of-meta-analyses)
- `OTIM corpus`: all studies from the [OTIM-DB](https://github.com/climasoma/otim-db)

Three different NLP techniques are explored:
- topic modelling ([notebooks/nlp-meta-analyses.ipynb](notebooks/nlp-meta-analyses.ipynb))
- extraction of metadata with regular expressions ([notebooks/nlp-meta-analyses.ipynb](notebooks/nlp-otim-db.ipynb))
- relationships extraction and classification from abstracts ([notebooks/nlp-meta-analyses.ipynb](notebooks/nlp-meta-analyses.ipynb))

Note that the full-text version of the publications is needed to run the NLP notebooks. For copyrights reasons, these are not provided in this repository.

In addition two others notebooks propose to walk you through the use of regular expression:
- [notebooks/nlp-workshop.iypnb](notebooks/nlp-workshop.ipynb): you can run it online on mybinder: [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/climasoma/nlp/HEAD?labpath=notebooks%2Fnlp-workshop.ipynb)
- [notebooks/pdf2meta.iypnb](notebooks/pdf2meta.ipynb): can retrieve metada from multiple pdfs [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/climasoma/nlp/HEAD?labpath=notebooks%2Fpdf2meta.ipynb)

## Citation
Refer to this citation if you make use of the database:
```
CLIMASOMA authors. 2022. "Potential of natural language processing for metadata extraction from environmental scientific publications" CLIMASOMA report.
