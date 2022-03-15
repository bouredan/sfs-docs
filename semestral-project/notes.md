## Materiály
* Sémantický web - základní rozcestník - https://www.w3.org/standards/semanticweb/
* RDF primer - shrnutí principů - https://www.w3.org/TR/rdf11-primer/
* SPARQL - dotazovací jazyk - https://www.w3.org/TR/sparql11-query/
* Stávající prohlížeč - https://xn--slovnk-7va.gov.cz/prohl%C3%AD%C5%BEe%C4%8D
* Endpoint používaný prohlížečem - https://xn--slovnk-7va.gov.cz/sparql
* BP na stejné téma - https://dspace.cvut.cz/handle/10467/94726, zdrojový kód - https://gitlab.fel.cvut.cz/svacefil/bcproject

* Semantic Web University - https://cambridgesemantics.com/blog/semantic-university/
* Old Semantic Facet Search in Angular https://github.com/SemanticComputing/angular-semantic-faceted-search
* RDF metadata - http://purl.org/dc/terms/
* SKOS - https://www.w3.org/TR/skos-reference/ and https://www.w3.org/TR/skos-primer/
* RDF Javascript libraries - https://rdf.js.org/
* Fetch SPARQL lib - https://www.npmjs.com/package/fetch-sparql-endpoint
* SPARQL cheatsheet - https://www.iro.umontreal.ca/~lapalme/ift6281/sparql-1_1-cheat-sheet.pdf
* Supernatural - a natural way of building SPARQL queries - https://github.com/sparna-git/Sparnatural
* Linked Data Fragments (filtrování na straně klienta) - http://videolectures.net/iswc2014_verborgh_querying_datasets/
* Berlin SPARQL benchmark


## Konzultace
- ukazat sequence diagram
- jak na component diagram?
- streaming RDF?
- jak na literals ve SPARQL? (+ string vs rdfjs object)
- text search facet - FILTER contains() nebo jine moznosti?
- pagination? keep inactive facet options? lang?


## TODO
- udelat analyzu facetovych vyhledavacu
- nastinit Linked Data Fragments - argumentovat tim caste volani SPARQL endpointu
- navrhnout architekturu, jak vypada konfigurace facetu, jak vypada vyhledavani

## SPARQL queries
select distinct ?name 
where {
[] foaf:name ?name .
FILTER langMatches(lang(?name), "en")
FILTER contains(?name, "United")
} LIMIT 100
