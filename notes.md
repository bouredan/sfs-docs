## Notes

* DB kterou používá slovník.gov.cz je OpenLink Virtuoso



## Materiály
* Sémantický web - základní rozcestník - https://www.w3.org/standards/semanticweb/
* RDF primer - shrnutí principů - https://www.w3.org/TR/rdf11-primer/
* SPARQL - dotazovací jazyk - https://www.w3.org/TR/sparql11-query/
* Stávající prohlížeč - https://xn--slovnk-7va.gov.cz/prohl%C3%AD%C5%BEe%C4%8D
* Endpoint používaný prohlížečem - https://xn--slovnk-7va.gov.cz/sparql
* BP na stejné téma - https://dspace.cvut.cz/handle/10467/94726, zdrojový kód - https://gitlab.fel.cvut.cz/svacefil/bcproject

## Otázky
- dbpedia.org, permissions
- typy facetů? (předchůdce bral ze SKOS)





# Zadání
	V komunitě sémantického webu existuje řešení facetového vyhledávání - https://github.com/SemanticComputing/angular-semantic-faceted-search, ale jeho použitelnost je omezena jednak složitostí a nepřehledností kódu, nízkou mírou konfigurovatelnosti a dále striktní závislostí na Angular 1. Cílem práce by bylo především poskytnout konfigurovatelné komponenty sémantického facetového vyhledávání na druhé mainstreamové platformě pro tvorbu webových aplikací - frameworku React. Zároveň by vyhledávací logika měla být na technologii uživatelského rozhraní nezávislá. Toho by šlo docílit buď implementací bez využití konstruktů platforem Angular či React, nebo vytvořením samostatné serverové služby, která by vyhledávání poskytovala. Rešerše těchto (či dalších) řešení a implementace zvolené varianty by byla součástí práce.

	1. Srovnejte existující přístupy k facetovému vyhledávání, především pak z hlediska využití sémantických technologií.
	2. Navrhněte modul sémantického facetového vyhledávače, který bude umožňovat rozdělení vyhledávání a jeho vizualizace do samostatných modulů.
	3. Naimplementujte prototyp modulu sémantického vyhledávače.
	4. Postup prezentujte na pravidelných konzultacích.