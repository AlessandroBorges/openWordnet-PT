
# OpenWordnet-PT: An Open Access Wordnet for Portuguese

## How to use it?

- You can browse or search the data in our
  [web interface](http://openwordnet-pt.org).

- You can download the RDF files and load it with any RDF library
  available for your preferable programming language.

## About the RDF 

- Based on http://www.w3.org/TR/wordnet-rdf/ and
  http://semanticweb.cs.vu.nl/lod/wn30/ with some modifications. More
  files from the Princeton distribution were considered and not only
  the database files. More properties and classes are included.
  
## Team

- [Alexandre Rademaker](http://arademaker.github.io)
- [Valeria de Paiva](http://www.valeriadepaiva.org)
- [Fredson Aguiar](https://github.com/fredsonerd)

## Contributors

- [Alberto Simoes](http://ambs.perl-hackers.net/en/me.html)
- [Claudia Freitas](http://www.letras.puc-rio.br/br/docente/3/claudia-freitas)
- [Fabricio Chalub](http://github.com/fcbr/)
- [Francis Bond](http://www3.ntu.edu.sg/home/fcbond/)
- [Gerard de Melo](http://gerard.demelo.org/)
- [Hugo Gonçalo Oliveira](https://eden.dei.uc.pt/~hroliv/)
- [Livy Real](http://livyreal.com)


## Related projects

- http://github.com/own-pt/cl-wnbrowser/ a browser and search interface
  for our wordnet powered by Common Lisp and Apache Solr.

- http://compling.hss.ntu.edu.sg/omw/ a browser and search interface
  for all open wordnets. Our OpenWordnet-PT is the Portuguese Wordnet
  available on this site.

- http://nlp.lsi.upc.edu/freeling/ See the freeling directory for
  information and the OpenWordnet-PT version in the format used by
  FreeLing.

- http://ontopt.dei.uc.pt Another wordnet-like ontology in
  Portuguese. It has incorporated OpenWordnet-PT.

## How to cite?

See http://arademaker.github.io/bibliography/coling2012.html

## How to contribute?

Please use the GitHub
[issues]([https://github.com/own-pt/openWordnet-PT/issues) or use the
[web interface](http://wnpt.brlcloud.com/wn/) to make suggestions
about the data.

## History of the Project

The initial version was generated by combining the following data:

- Princeton WordNet 3.0 was used to obtain English glosses and English
  terms for synset IDs.

- The unreleased 2010-12 version of [UWN]
  (http://www.mpi-inf.mpg.de/yago-naga/uwn/) and MENTA provided
  candidate terms in Portuguese, candidate glosses in Portuguese (from
  Wikipedia).

- The EuroWordNet base concept list (`5000_bc.xml`) provides the base
  concept numbers. The original file was mapped from WordNet 2.0 to
  3.0 using the mappings from [WN-Map](http://goo.gl/qg9PJt). When
  multiple mappings for a WordNet 2.0 synset existed, all possible
  WordNet 3.0 synsets were kept. Hence, there may be multiple entries
  with the same base concept number.


## License

<p><a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" src="http://i.creativecommons.org/l/by/4.0/88x31.png" /></a><br /><span xmlns:dct="http://purl.org/dc/terms/" href="http://purl.org/dc/dcmitype/Dataset" property="dct:title" rel="dct:type">openWordnet-PT</span> by <a xmlns:cc="http://creativecommons.org/ns#" href="http://github.com/own-pt/openWordnet-PT" property="cc:attributionName" rel="cc:attributionURL">Alexandre Rademaker (IBM Research)</a> is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a>. Based on a work at <a xmlns:dct="http://purl.org/dc/terms/" href="http://github.com/own-pt/openWordnet-PT" rel="dct:source">http://github.com/own-pt/openWordnet-PT</a>. Permissions beyond the scope of this license may be available at <a xmlns:cc="http://creativecommons.org/ns#" href="http://github.com/own-pt/openWordnet-PT" rel="cc:morePermissions">http://github.com/own-pt/openWordnet-PT</a>.</p>

Also please consult the LICENSE file.

