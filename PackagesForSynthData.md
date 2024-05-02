Research notes on generating synthetic data.

## Libraries:


### General

- DataSynthesizer
Privacy-protecting data synetheizer
http://demo.dataresponsibly.com/synthesizer
https://github.com/DataResponsibly/DataSynthesizer

- Synthetic Data Vault
Loads as a Python library which hosts multiple methods, including GAN and cumulative distribution functions

- Gretel
Uses Reccurent neural networks (RNN) to produce synthetic text and data structred from a dataset. Has a "data frame" mode for synthetic dataframes.
https://github.com/gretelai/gretel-synthetics/tree/master

- Mesa
Agent-based model to create synthetic interaction data (Eg; simulating diseasespread)

### Specific features:

- TimeseriesGenerator

Produces time series data (and made by Nike)

- Faker
Seems to be focused on generating synthetic people (names, addresses, some text)

- Pydbgen
Creates synethetic "people" information-- addresses, names, phone numbers, emails, SSNs.

- Mimesis
Also creates synthetic people information, but allows for "context-aware" implmentation. (Can customize to a target country, make sure that the outputs are sensible given teh context)

- Zpy
Synthetic image data

## Metrics

- Correlation matrix for variables in the original vs synthetic