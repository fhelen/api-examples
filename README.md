# Agrimetrics API Examples

This repository contains some examples of how to call Agrimetrics' APIs.

Pre-requisites: 
* Python 3.6+ 
* a valid Field Explorer subscription key must be obtained and set in your environment as `API_KEY`. 

To obtain your subscription key:
* Sign-up to Agrimetrics via either the [Developer Portal](https://developer.agrimetrics.co.uk) or the [Field Explorer Demo](https://app.agrimetrics.co.uk).
* Subscribe to Field Explorer by pressing 'Subscribe' in the [Field Explorer Product page](https://developer.agrimetrics.co.uk/products/field-explorer)

To setup your python environment, install the dependencies using the `requirements.txt` file found in each subdirectory:

```bash
$ pip install -r requirements.txt
```

Alternatively, you can use `pipenv`:

```bash
$ pipenv install
```

# Example directories

This repository has three main directories of examples and tutorials.

## Field Explorer Examples

[Examples](./field-explorer-examples/README.md) of how to use Python to access Agrimetrics' REST APIs. These
provide weather, crop and soil information attributed to individual
fields.

## GraphQL Examples

[Examples and tutorials](./graphql-examples/README.md) of how to use Agrimetrics' GraphQL API. This 
API provides access to all of our queryable data, including premium
data such as field boundaries and satellite observations of fields
(*Verde* data -- see below).

## Verde Examples

Examples and tutorials of how to use Agrimetrics' GraphQL API to
access [Verde](https://app.agrimetrics.co.uk/#/catalog/data-sets/fdebcd1d-9324-401d-b229-fbd21483e584) data. This is our premium data set containing crop measurements derived from satellite observations of the UK.

# Further Reading

* [Agrimetrics Developer Portal](https://developer.agrimetrics.co.uk/docs/services/) - full API documentation
* [GeoJSON](https://geojson.org/) - GeoJSON specification
* [JSON-LD](https://json-ld.org/) - JSON-LD specification
* [Pandas](https://pandas.pydata.org/) - Python Data Analysis Library used by these examples
* [matplotlib](https://matplotlib.org/gallery/index.html) - Python 2D plotting library used by these examples
* [GraphQL](https://graphql.org/) - GraphQL is a query language for APIs and a runtime for fulfilling those queries with your existing data.
* [pipenv](https://pipenv-fork.readthedocs.io/en/latest/) - Pipenv is a dependency manager for Python projects. If you’re familiar with Node.js’ `npm` or Ruby’s `bundler`, it is similar in spirit to those tools.
