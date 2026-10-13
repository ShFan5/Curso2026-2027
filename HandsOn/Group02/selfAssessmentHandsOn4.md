# Hands-on assignment 4 – Self-assessment

## Deliverables

- [x] An RML mapping is provided in `mappings/parks.rml`.
- [x] The mapping uses the cleaned CSV from Hands-on 3 as its logical source.
- [x] The mapping generates parks, addresses, districts and neighborhoods with the resource naming strategy defined in Hands-on 2.
- [x] The transformed data is provided as Turtle in `rdf/parks-generated.ttl`.
- [x] SPARQL validation queries are provided in `rdf/queries.sparql`.

## Mapping and transformation

- [x] The CSV `PK` is used to create stable park URIs.
- [x] Datatype properties are mapped with the datatypes defined in the ontology.
- [x] Object properties generate links to address, district and neighborhood resources.
- [x] The generated RDF contains one `parks:Park` resource for each of the 208 CSV records.
