# Jake

Jake is an idea for a Julia-based enterprise application platform that applies data-centric architecture principles.

In this architecture, all applications share a common, extensible data model and (usually) common storage of the data encoded in the same way as the data model.

Jake will use RDF triples as a storage medium, including configuration.

The data model itself is defined using RDF, of course, but using the OWL 2 RL ontology definition language.

Humans typicvally build ontologies using a tool such as [Protegé https://protege.stanford.edu/].
Jake will need to enable prgrammatic construction of ontologies, probably using a purpose-built DSL.

Jake applications use SPARQL queries - also dynamically generated - to manipulate concepts defined in the data model.

Much of a Jake application is built dynamically from the data model itself, which can be annotated with custom code.

Explore the idea of mapping RDF triples to Julia functions

:predicate(:subject::T, :object::TT) where T,TT

More to come!
