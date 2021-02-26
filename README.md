# Abstract_Concrete

Theory:
How children learn their native language must be one of the most debated topics studied and discussed by linguists, psychologists, and cognitive scientists. There are numerous factors that influence children’s language acquisition process and their level of competence as well as performance.
One particular aspect of language acquisition is semantic competence, which is the focus of this study. We create different environments, in which a model (language learner)
acquires the language. These environments are corpora, with different measurable and controllable linguistic features that affect the training of the models. We then conduct tests to examine and quantify the correlation of some of these features to the semantic competence of the language learner. We find out one specific feature, i.e. concreteness influences language acquisition.

To measure the semantic competences of the language learner, we need to quantify them and in order to do do so we could adopt a vector-based representation of words known as distributional semantics. In DS meaning of words are partially represented by the linguistic context in which they appear. For example the word car is defined by the set of words it is associated with in its context, for instance traffic, accident, freeway, etc and is represented as a point in a vector space. Large corpora that contain performance data produced by native speakers is the starting point for DS representations. Computational analysis of such data leads to vector representations of words that can then be used to perform linguistic tests such as the ones in this work,specifically semantic competences. Previously we mentioned that common tests of semantic competences include similarity and relatedness judgements, compatibility and acceptability judgements, as well as lexical relation categorisation. For the scope of this work we test the performance by examining the first two of criteria, i.e. similarity and relatedness.
Semantic relatedness is a more general notion of the relatedness of concepts, while similarity is a special case of relatedness that is tied to the likeness (in the shape or form) of the concepts.

A measure of semantic similarity takes as input two concepts, and returns a numeric score that quantifies how much they are alike. Such a measure is usually based on is-a relations found in the underlying taxonomy or ontology in which the concepts reside. For example, common cold and illness are similar in that a common cold is a kind of illness. Thus, semantic similarity can be viewed as a special case of semantic relatedness that does not include relationships such as antonymy (night/day) and meronymy (root/plant).
The vector-based representation we use for this study is FastText. The models created using this tool can then be tested for their semantic competences.
To test relatedness judgments we use the MEN similarity dataset, which contains two sets of English word pairs (one for training and one for testing) together with human-assigned similarity judgments, obtained by crowd-sourcing using Amazon Mechanical Turk. To test the similarity we use SimLex-999, which essentially is made of 999 word pairs intended to provide a way of measuring how well models capture similarity, rather than relatedness or association. 

Running the experiment:
In order to run a test, execute the file: 


