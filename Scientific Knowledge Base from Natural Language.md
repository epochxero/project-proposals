## Generating Knowledge Bases From Scientific Publications

### Summary: 
Tshitoyan et al. (2019) demonstrated the substantial power word embeddings have to uncover latent scientific knowledge over an expansive scientific corpora. In their work, they discussed the possibility of future work utilizing more powerful models such as BERT, which is both more powerful, and may be able to exploit the full text of the articles rather than just the abstract. This leaves some very low hanging fruit for initial research with just the substitution of one model for another, with the possible addition of more data. But we can go further.

This paper was lauded for its ability to pull meaning from unstructured data, however the output of this model is primitive. It returns the cosine similarity between a certain property and various materials, with the loose assumption being that materials ranked as more similar are likely to have that property. While effective in recalling rough associations, it is a substantial reduction in the complexity of the relationships between entities. That higher fidelity output would ideally take the form of a graph that could not only demonstrate similarity between entities, but directly characterize the nature of their relation. 

COMET is “an adaptation framework for constructing commonsense knowledge bases from language models by training the language model on a seed set of knowledge tuples” (Bosselut et al., 2019). It can then take this seed as well as a language model in order to add novel nodes. In essence, it converts natural language into a knowledge base, achieving extremely high results on ConceptNet (Speer, Chin, & Havasi, 2016) and ATOMIC (Sap et al., 2018). COMET works well even with only 10% of the training data, suggesting smaller knowledge bases would still be viable, and is stated to be domain-agnostic. This makes it ideal for more domain-specific applications.

These two works, along with PropNet (https://github.com/materialsintelligence/propnet), a materials science knowledge graph, may allow for substantial advancement of the SOTA of NLP assisted scientific discovery. While expanding on the ability of NLP to uncover relations from article text, the addition of a knowledge base output would allow for far more complex, and useful, inferences. 

### Areas of Study: 
NLP, commonsense reasoning, materials science, possilbly graph neural networks

### Minimum Required Skills: 
Python, PyTorch (or Tensorflow), experience with text processing and NLP, ability to read understand and evaluate relevant literature
