# Part-of-Speech-Tagging-HMM-
Part-of-Speech-Tagging(HMM) to predict tags for words in sentences using Hidden Markov Models


## Introduction
In this notebook, you'll use the Pomegranate(opens in a new tab) library to build a hidden Markov model for part of speech tagging with a universal tagset(opens in a new tab). Hidden Markov models have been able to achieve >96% tag accuracy with larger tagsets on realistic text corpora. Hidden Markov models have also been used for speech recognition and speech generation, machine translation, gene recognition for bioinformatics, and human gesture recognition for computer vision, and more.

The notebook already contains some code to get you started. You only need to add some new functionality in the areas indicated to complete the project; you will not need to modify the included code beyond what is requested. Sections that begin with 'IMPLEMENTATION' in the header indicate that you must provide code in the block that follows. Instructions will be provided for each section, and the specifics of the implementation are marked in the code block with a 'TODO' statement. Please be sure to read the instructions carefully!

NOTE: There is an optional warmup exercise to introduce the Pomegranate API included in the project files. Just launch the HMM warmup (optional).ipynb file first to get started there, then complete the hmm tagger.ipynb notebook. (Only the tagger will be submitted for review.)

You must complete sections 1 to 3 below to pass the project. Please note that section 4 is optional. It is provided as a reference and resource if you wish to further explore HMM taggers.

Review the provided interface to load and access the text corpus
For both Most Frequent Class (MFC) tagger and the HMM model we'll build, we need to estimate the frequency of tags & words from the frequency counts of observations in the training corpus.
Build a Most Frequent Class (MFC) tagger to use as a baseline
Implement Pair Counts and Most Frequent Class
Build an HMM Part of Speech tagger and compare to the MFC baseline
Implement Unigram Counts, Bigram Counts, Starting Counts, Ending Counts, and Basic HMM Tagger using the Pomegranate HMM library.
(Optional) Improve the HMM tagger
