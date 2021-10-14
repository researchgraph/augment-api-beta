# Welcome to the Augment API Documentation

## Join our Beta Testing!

!!! tip

    We are pleased to announce that we are opening the registration for a Closed Beta Testing of
    the Augment API. You can register your interest in the API using the following EOI form:
    [https://forms.gle/jv5xPh5zN8PQfsu78](https://forms.gle/jv5xPh5zN8PQfsu78)

## Getting started

1. Make sure you have a valid Augment API `API_KEY` by joining the Beta Testing program.
2. Put the `API_KEY` into a `.env` file in the `Notebooks` folder. The file should include the line `API_KEY=YOURVALIDAPIKEY`, where your API has replaced the string `YOURVALIDAPIKEY`.
3. Install all Python dependencies by running `pip install -r requirements.txt` from the command line within your `notebooks` folder.
4. Start the notebooks by running `jupyter lab` from the command line within your `notebooks` folder.

## What is Augment API?

The Research Graph Augment API transforms disconnected research information to a connected graph, and augment this graph with the data from the global network of scholarly works. Augment API leverages the Research Graph distributed network and persistent identifiers to establish connections between publications, researchers, research datasets and grants across global infrastructures such as DataCite and open access initiatives such as Scholix.

![](images/augment-api-figure.gif)

The Augment API provides cloud hosted functions to enable three transformations.

- Build Graph: Transform disconnected bibliographic records to a connected graph
- Augment: Transform the graph with data from Research Graph clusters and the global research data infrastructures.
- Create Open Graphs: Transform the augmented graph to interoperable formats such as VIVO RDF, GraphML and JSON.
