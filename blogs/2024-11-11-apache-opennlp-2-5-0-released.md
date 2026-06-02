---
title: Apache OpenNLP 2.5.0 released
url: https://opennlp.apache.org/news/release-250.html
date: '2024-11-11'
author: ''
feed_url: https://opennlp.apache.org/feed.xml
---
The Apache OpenNLP team is pleased to announce the release of Apache OpenNLP 2.5.0. The Apache OpenNLP library is a machine learning based toolkit for the processing of natural language text. It supports the most common NLP tasks, such as tokenization, sentence segmentation, part-of-speech tagging, named entity extraction, chunking, parsing, and coreference resolution. Apache OpenNLP 2.5.0 binary and source distributions are available for download from our download page . The OpenNLP library is distributed by Maven Central as well. See the Maven Dependency page for more details: Maven Dependency What’s new in Apache OpenNLP 2.5.0 In total, this release tackles 62 issues and brings several dependency updates, bug fixes, substantial additions and some corrections for the API!
OpenNLP version 2.5.0 supports thread-safe sentence detection, tokenization and POS-tagging (see: OPENNLP-936). With this release, there is the possibility to disable the POS tag mapper (see: OPENNLP-1600) to achieve a custom mapping. Furthermore, it relies on opennlp-models in version 1.1 which got substantially extended by models for 18 new languages (see: OPENNLP-1615) as listed on the Model page .
The OpenNLP Brat Annotator component has been moved to the OpenNLP sandbox repository due to limited quality and usability concerns (see: OPENNLP-1634). Thereby, several compile and runtime dependencies could be dropped (Jackson, Jersey, etc.) and are thus no longer shipped with the "bin" artifacts. Thank you to everyone who contributed to this release, including all of our users and the people who submitted bug reports, contributed code or documentation enhancements. For a full list of improvements, please see the full list found in Jira . --The Apache OpenNLP Team
