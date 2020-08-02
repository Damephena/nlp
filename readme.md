# Natural Language Processing

This is a repository of ML-NLP projects I have spent time learning from and working on.

- HMM tagger

In this notebook, [Pomegranate](https://github.com/jmschrei/pomegranate) library is used to build a hidden Markov model for part of speech tagging with a [universal tagset](http://www.petrovi.de/data/universal.pdf). Hidden Markov models have been able to achieve >96% tag accuracy with larger tagsets on realistic text corpora. Hidden Markov models have also been used for speech recognition and speech generation, machine translation, gene recognition for bioinformatics, and human gesture recognition for computer vision, and more.

Repository forked from [Udacity](https://github.com/Udacity) NLP repo.

A number of steps were carried out before applying `.add_states()`, `.add_transition()` and `.bake()`
These included:
`emission_probability` and `transition_probability` using `tag_unigrams`, `tag_bigrams`, start emission probabilty etc.
