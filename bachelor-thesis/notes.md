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
* RDF JavaScript libraries - https://rdf.js.org/
* Fetch SPARQL lib - https://www.npmjs.com/package/fetch-sparql-endpoint
* SPARQL cheatsheet - https://www.iro.umontreal.ca/~lapalme/ift6281/sparql-1_1-cheat-sheet.pdf
* Supernatural - a natural way of building SPARQL queries - https://github.com/sparna-git/Sparnatural
* Linked Data Fragments (filtrování na straně klienta) - http://videolectures.net/iswc2014_verborgh_querying_datasets/
* o angular facet vyhledavaci, dobry na zdroj https://seco.cs.aalto.fi/publications/2016/koho-et-al-sparql-faceter.pdf
* Berlin SPARQL benchmark
* Sampo-UI - https://github.com/SemanticComputing/sampo-ui

## Konzultace
- návrh budoucí čas?

## TODO
- přidat labely k listingům, ale nevím jak
- ukazat network tab SFS vyhledávače
- možná přidat sekci o Linked Data Fragments - potenciálně velmi vhodné využití pro faceto vyhledávání
- dodělat unit testy na sfs-api a jejich sekci

## poznámky
- mozna zminit gettery settery
- možná přidat zmínku o principech oop


(GROUP_CONCAT(?typeId) AS ?typeIds) (GROUP_CONCAT(?typeLabel) AS ?typeLabels)
    (GROUP_CONCAT(?superClassId) AS ?superClassIds) (GROUP_CONCAT(?superClassLabel) AS ?superClassLabels)

GROUP BY ?_id ?_label ?definition ?schemeId ?schemeLabel
