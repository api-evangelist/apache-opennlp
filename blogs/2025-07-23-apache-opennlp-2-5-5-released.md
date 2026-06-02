---
title: Apache OpenNLP 2.5.5 released
url: https://opennlp.apache.org/news/release-255.html
date: '2025-07-23'
author: ''
feed_url: https://opennlp.apache.org/feed.xml
---
The Apache OpenNLP team is pleased to announce the release of Apache OpenNLP 2.5.5. The Apache OpenNLP library is a machine learning based toolkit for the processing of natural language text. It supports the most common NLP tasks, such as tokenization, sentence segmentation, part-of-speech tagging, named entity extraction, chunking, parsing, and coreference resolution. Apache OpenNLP 2.5.5 binary and source distributions are available for download from our download page . The OpenNLP library is distributed by Maven Central as well. See the Maven dependency page for more details. What’s new in Apache OpenNLP 2.5.5 In total, this release tackles 27 issues, brings multiple dependency updates, bug fixes (e.g. OPENNLP-1545), and several additions.
Accessing (computed) probabilities is now possible in thread-safe probabilistic ME classes via the probs() method (OPENNLP-1757)
Loading of pre-trained OpenNLP (UD) models from the classpath was made (even) easier (see: OPENNLP-1729).
The 2.5.5 release relies on version 1.3 of the opennlp-models , providing access to pre-trained models for a total of 36 languages. For further details, check the full list of changes via the project’s issue tracker. --The Apache OpenNLP Team
