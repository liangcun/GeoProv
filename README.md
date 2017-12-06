GeoProv
========
*Abstract:* This repository provides a mapping from ISO lineage terms [1] to the W3C PROV-O [2]. [Examples](examples) and [queries](queries) are given to demonstrate the mapping. The mapping ontology allows domain experts to use W3C PROV syntax to query and consume geospatial data provenance information encoded with the ISO lineage model, improving interoperability between ISO lineage and PROV applications.

*Keywords:* geospatial data provenance; lineage model; ISO 19115; W3C PROV

Members & contributors:
- xxx

Contents
----------------------
- [`examples/`](examples): Usage exmaples of geospatial data provenance in RDF.
- [`queries/`](queries): SPARQL queries run over example provenance triples.
- [`vocabularies/`](vocabularies): OWL ontologies about ISO 19115 lineage model and its mapping to W3C PROV.
- [`lineage.rules`](lineage.rules): mapping rules in Jena Rule syntax.
- [`prefixes.txt`](prefixes.txt): prefixes used in uses cases.

Status
---------
The example provenance data are also availabe at a ([SPARQL server](http://geos.whu.edu.cn:8099/fuseki/)). SPARQL queries can be executed in the corresponding endpoints.


References
----------
- [1] ISO/TC 211, 2014. ISO 19115-1:2014 Geographic information-Metadata-Part 1: Fundamentals. Geneva, Switzerland.
- [2] Lebo, T., Sahoo, S., and McGuinness, D., 2013. PROV-O: The PROV Ontology [online]. W3C recommendation. Available from: https://www.w3.org/TR/2013/REC-prov-o-20130430/ [Accessed 17 Feb 2017].

