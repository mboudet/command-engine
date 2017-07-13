# Parsec Autobuilder

Given that the original scripts which spawned parsec are now used across a
number of different places ([parsec](https://github.com/galaxy-iuc/parsec),
[arrow](https://github.com/galaxy-genome-annotation/python-apollo/),
[chakin](https://github.com/galaxy-genome-annotation/python-chado), and
[tripaille](https://github.com/galaxy-genome-annotation/python-tripal)), this tooling was extracted
to make keeping those in-sync an easier process.


## Running

Currently when this script is used, it is cloned into a subdirectory and we run something like

```
python scripts/autobuilder.py --galaxy
python scripts/commands_to_rst.py
```

But this will be fixed eventually.
