## notes on LOD 

From LAMLOD18 talk by Conal Touhy 

Linked open data basics 

project to to build a Linked Open data API 

- take advantage of the CIDOC conceptual Reference Model, the international standard for the controlled exchange of cultural heritage information 
- allow the collection data to be richly interlinked with other people’s data, and repurposed in interesting ways 
- 
Identifiers

URIs as identifiers for everything 
- URIs are globally unique (can float free)
- the domain name system provides a system of ownership and control 
- even terms (like ‘subject’ or ‘creation-date’) are identified with URIs
- every identifier is a hyperlink to its own definition 
- not just for identifying web pages, tweets etc 
- also for people, places, flavours of ice-cream

Resource Description Framework (RDF) 
 Encode data as simple 3-‘word sentences ‘triples’
- subject, predicate, object  the cat / sat / on the mat /
- each word is either an identifier, or a ‘literal’ value like ‘Curtin University’ or “2018-09-24”
- to represent more complex data, just create more triples 
- any knowledge is just a list of triples, so combing two sets of data means just concatenating two triples

graphs and Datasets
some terms for RDF data management 
- a set of triples grouped together is called a ‘graph’ 
- a graph that’s saved as a file with a name is called a ‘named graph’
- a set of graphs can be managed as a group, called a ’dataset’

Abstract Model vs File Format 
- the abstract model of RDF is a common basis for the Linked Data effort 
- but the triples can be encoded in many many different ways
- - in text based formats like Turtle, N3 etc
	- xml based formats like RDF/XML, Trix etc
	- embedded in html pages as RDFa or micro formats, or GRDLL
	- in csv files using ‘CSV on the Web Metada’
	- in JSON files using “JSON-LD Contexts”
