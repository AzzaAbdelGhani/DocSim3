# DocSim3
DocSim3 is a benchmark dataset for evaluating the multilingual semantic similarity of long documents. 

DocSim3 was created based on transforming three Wikipedia-entry based datasets to a dataset that is multilinugal and contains long-documents. The three datasets are:

- [WikipediaSimilarity353 Test Collection](http://community.nzdl.org/wikipediaSimilarity/) [[1]](#1)
- [WikiSRS-similarity and WikiSRS-relatedness](https://github.com/OSU-slatelab/WikiSRS/blob/master/dataset) [[2]](#2)


For each term in these datasets, the corresponding Wikipedia article is extracted and obtianed in the other langugaes (Arabic, English, Spanish, French, Russian, Portuguese). In data folder, the multilingual version of each dataset can be found, plus the DocSim3 datsaet which is a concatination of all the datasets. 


## References
<a id="1">[1]</a> 
David Milne, Ian H. Witten (2008). 
An effective, low-cost measure of semantic relatedness obtained from Wikipedia links. 
In Proceedings of the first AAAI Workshop on Wikipedia and Artificial Intelligence, Chicago, I.L

<a id="2">[2]</a> 
D Newman-Griffis, A M Lai, and E Fosler-Lussier. 
"Jointly Embedding Entities and Text with Distant Supervision". 
In Proceedings of the 3rd Workshop on Representation Learning for NLP (Repl4NLP), 2018.
