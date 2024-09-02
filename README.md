# rmaThesis_repo
 
This repository hosts the main code used and the results obtained in my master's thesis: **A linguistically-informed comparison between multilingual BERT and language-specific BERT models: The case of differential object marking in Romanian**



## Abstract

This thesis presents a linguistically-informed comparative evaluation of multilingual BERT and Romanian-specific BERT models, focusing on their ability to handle the complex grammatical phenomenon of Differential Object Marking (DOM) in Romanian. By framing DOM as an MLM task across a variety of contexts, the aim of the experiment is to see whether language-specific BERT models outperform the multilingual BERT in generating grammatically accurate sentences. Additionally, the research examines how different masking strategies impact the models’ predictions, given the morphologically rich target language and the complexity of how this highly constrained grammatical phenomenon is realised. Results indicate that Romanian-specific BERT models generally perform better in tasks requiring deep linguistic understanding, though the effect of masking strategies varies. This study contributes to the ongoing discourse at the intersection of NLP and linguistics by exploring the linguistic generalizations that Transformer-based models can infer, particularly for less-resourced languages like Romanian.

## Repository structure

- The _main_code_ notebook contains the Python code used to obtain the reported results.
- The _test_sentences_ folder contains the test sentences generated from templates, for each masking strategy (A1 and A2).
- The _word_frequencies_ text file contains the word frequency counts for the words used in object position when manually generating the test sentences.
- The _results_ folder contains the results obtained and the manual annotations.

## Installation and requirements

The notebook containing the code is self-contained and includes all neccessary pips and installs.
