[QueryItem="test"]
PREFIX : <http://vocab.acdh/defc2cidoc#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX xsd: <http://www.w3.org/2001/XMLSchema#>
PREFIX xml: <http://www.w3.org/XML/1998/namespace>
PREFIX cidoc-crm: <http://www.cidoc-crm.org/cidoc-crm/>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>

SELECT ?area 
WHERE {
	?area a cidoc-crm:E27_Site .
	
	
}

[QueryItem="areaname"]
PREFIX : <http://vocab.acdh/defc2cidoc#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX xsd: <http://www.w3.org/2001/XMLSchema#>
PREFIX xml: <http://www.w3.org/XML/1998/namespace>
PREFIX cidoc-crm: <http://www.cidoc-crm.org/cidoc-crm/>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>

SELECT ?area ?site ?name ?sitename
WHERE {
	?area a cidoc-crm:E27_Site .
	?area cidoc-crm:P89_falls_within ?site .
	?site cidoc-crm:P1_is_identified_by ?sitename .
	?area cidoc-crm:P90_has_value ?name .
	
}
