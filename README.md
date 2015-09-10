# DURAARK SDAS Queries

This repository holds a set of SPARQL queries showing the retrieval capabilities of the [DURAARK system](https://github.com/DURAARK/duraark-system).

# Format

Each query is living in its own [YAML](https://en.wikipedia.org/wiki/YAML) file. Each file has the three mandatory items

* label,
* description,
* sparql,

where 'sparql' contains the actual SPARQL query for the SDAS. 'label' and 'description' are necessary to display the query in the [WorkbenchUI](https://github.com/DURAARK/workbench-ui).

# SPARQL Playground

Before adding a file to the repository please test the query at

```
http://data.duraark.eu/sparql
```

which provides a SPARQL endpoint to the DURAARK SDAS knowledge graph.



