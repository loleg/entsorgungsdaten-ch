A [Data Package](https://frictionlessdata.io/data-packages/) describing locations of waste collection and recycling stations in Switzerland.

# Data

We initially are using a dataset from the cities of Basel and Zürich for this example.

The CSV file for Basel was obtained from https://opendata.swiss/en/dataset/entsorgungsstellen/ and is also directly downloadable using the CKAN API. See attached example R program.

The CSV file for Zürich is available from https://data.stadt-zuerich.ch/dataset/geo_sammelstelle and can be downloaded through the geo-viewer ordering process [at this link](https://www.stadt-zuerich.ch/geodaten/download/Sammelstelle?format=10008). (Note that you need to provide an e-mail address, but the link appears in a few minutes in the browser after the request is made.)

# Preparation

No transformation needed, except to rename the file and place it in the `data` folder.

We used the [Data Package Creator](https://create.frictionlessdata.io/) tool to extract schema details from the data resources.

# License

### Basel

<img src="https://opendata.swiss/content/themes/wp-ogdch-theme/assets/images/terms/terms_by.svg" width=150>

[Open use. Must provide the source.](https://opendata.swiss/en/terms-of-use/#terms_by)

- You may use this dataset for non-commercial purposes.
- You may use this dataset for commercial purposes.
- You must provide the source (author, title and link to the dataset).

### Zürich

Creative Commons Zero (CC-0)

Quelle: Stadt Zürich

### Data Package

This Data Package itself is made available by its maintainers under the [Public Domain Dedication and License v1.0](http://www.opendatacommons.org/licenses/pddl/1.0/), a copy of the full text of which is in [LICENSE.md](LICENSE.md).
