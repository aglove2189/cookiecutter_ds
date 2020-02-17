Cookiecutter Data Science
====================

A boilerplate for reproducible and transparent science with close resemblances to the philosophy of [Cookiecutter Data Science](https://github.com/drivendata/cookiecutter-data-science): *A logical, reasonably standardized, but flexible project structure for doing and sharing data science work.*

Requirements
------------

`pip install cookiecutter`

or

`conda install -c conda-forge cookiecutter`

Usage
-----

To start a new science project:

`cookiecutter https://github.com/aglove2189/cookiecutter_ds`

Project Structure
-----------------

```
.
├── README.md
├── bin                <- Your compiled model code can be stored here (not tracked by git)
├── config             <- Configuration files, e.g., for doxygen or for your model if needed
├── data
│   ├── interim        <- Intermediate data that has been transformed.
│   ├── processed      <- The final, canonical data sets for modeling.
│   └── raw            <- The original, immutable data dump.
├── docs               <- Documentation or scientific papers (not tracked by git)
├── nbs                <- Ipython or R notebooks
└── src                <- Source code for this project
    ├── data           <- Scripts and programs to process data
    ├── models         <- Source code for your own model
```
