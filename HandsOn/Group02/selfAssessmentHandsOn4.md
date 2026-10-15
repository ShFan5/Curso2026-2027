# Hands-on assignment 4 – Self assessment

## Checklist

**Every RDF file:**

- [x] Uses the `.nt` extension.
- [x] Is serialized in the N-Triples format.
- [x] Follows the resource naming strategy.
- [x] Uses class and property URIs that are the same as those used in the ontology.

**Every URI in the RDF files:**

- [x] Is readable and has a meaningful resource type and identifier, such as `park-50265055`.
- [x] Is represented as an RDF URI, not as a string literal.
- [x] Does not contain an accidental double slash in its resource path.

**Every individual in the RDF files:**

- [x] Has an `rdfs:label` containing the name of the individual.
- [x] Has an `rdf:type` statement.

**Every value in the RDF files:**

- [x] Is trimmed.
- [x] Uses an explicit datatype when it is a literal.
- [x] Uses `xsd:string` for text, `xsd:integer` for accessibility, `xsd:decimal` for coordinates and `xsd:anyURI` for the source URL.
- [x] Uses RDF URIs, rather than string literals, for object-property values.

## Comments on the self-assessment

