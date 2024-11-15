# `lca-monetized`

Import monetized environmental impacts as LCIA methods into Brightway2. These are technically weightings of characterization methods, but are still implemented as LCIA methods (characterization) methods to enable use in other software (e.g. pathways).

## Environmental impact categories

The following impact categories are covered:

- acidification
- climate change
- ecotoxicity
- eutrophication
- fossil resources
- human toxicity
- ionizing radiation
- land use
- metal/mineral resources
- ozone depletion
- particulate matter formation
- photochemical oxidant formation
- water use

The underlying LCIA methods which quantify environmental impacts vary, depending on the monetization factor.

## Monetization factors

The collection of monetization factors is based on the review by [Amadei et al, 2021](https://doi.org/10.1016/j.jclepro.2021.129668).

## Limitation

Now works with ``bw2io 0.8.7`` and ``bw2io 0.8.8``. 


## Usage

In an open Brightway2 project:
```python
from premise_gwp import add_premise_gwp
add_premise_gwp()
```

## Installation

`pip install premise_gwp`

or

`conda install -c romainsacchi premise_gwp`

