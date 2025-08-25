# A linguistically-informed comparison between multilingual BERT and language-specific BERT models: The case of differential object marking in Romanian
 
This repository hosts the main code used and the results obtained in my master's thesis: **A linguistically-informed comparison between multilingual BERT and language-specific BERT models: The case of differential object marking in Romanian**



## Abstract

Current linguistic challenge datasets for language models focus on phenomena that exist in English. This may lead to a lack of attention for typological features beyond English. This is particularly an issue for multilingual models, which may be biased towards English by
their training data and this bias may be amplified if benchmarks are also English-centered. We present the syntactically and semantically complex language phenomenon of Differential Object Marking (DOM) in Romanian as a challenging Masked Language Modelling task and compare the performance of monolingual and multilingual models. Results indicate that Romanian-specific BERT models perform better than equivalent multilingual one in representing this phenomenon.

## Repository structure

- The _main_code_ notebook contains the Python code used to obtain the reported results.
- The _test_sentences_ folder contains the test sentences generated from templates, for each masking strategy (A1 and A2) -- please see paper Appendices for translations and grammatical annotations.
- The _word_frequencies_ text file contains the word frequency counts for the words used in object position when manually generating the test sentences.
- The _results_ folder contains the results obtained and the manual annotations.

## Additional resources
For transparency and replication reasons, the following additional resources used for the experiments described in this paper are available:
- The test sentences obtained from the templates, as well as the resulting predictions from each language model version are included in this repository.
- The three pretrained models tested can be found on HuggingFace:
    a. Google BERT models: \href{https://huggingface.co/google-bert}{here}.
    b. Romanian BERT: \href{https://huggingface.co/dumitrescustefan}{here}.
    c. RoBERT: \href{https://huggingface.co/readerbench}{here}.

## Installation and requirements

The notebook containing the code is self-contained and includes all neccessary pips and installs.
