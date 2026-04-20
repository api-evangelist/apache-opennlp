# Apache OpenNLP (apache-opennlp)
Apache OpenNLP is a machine learning based toolkit for the processing of natural language text. It supports common NLP tasks such as tokenization, sentence segmentation, part-of-speech tagging, named entity extraction, chunking, parsing, and coreference resolution.

**URL:** [https://raw.githubusercontent.com/api-evangelist/apache-opennlp/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/apache-opennlp/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Machine Learning, Natural Language Processing, NLP, Text Processing, Apache, Open Source, Java

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-04-19

## APIs

### Apache OpenNLP
OpenNLP provides a Java API for NLP tasks including tokenization, sentence detection, POS tagging, named entity recognition, chunking, parsing, and language detection, with support for training custom models.

**Human URL:** [https://opennlp.apache.org/docs/](https://opennlp.apache.org/docs/)

#### Tags:

 - Java, NLP, Text Processing, Apache, Open Source, Machine Learning

#### Properties

- [Documentation](https://opennlp.apache.org/docs/)
- [OpenAPI](openapi/apache-opennlp-tools.yaml)

## Common Properties

- [GitHubOrganization](https://github.com/apache/opennlp)
- [Documentation](https://opennlp.apache.org/)
- [GettingStarted](https://opennlp.apache.org/docs/)
- [SpectralRules](rules/apache-opennlp-spectral-rules.yml)
- [Vocabulary](vocabulary/apache-opennlp-vocabulary.yaml)
- [NaftikoCapability](capabilities/nlp-pipeline-workflow.yaml)
- [JSON-LD](json-ld/apache-opennlp-context.jsonld)

## Features

| Name | Description |
|------|-------------|
| Language Detection | Detects document language using ISO-639-3 classification |
| Sentence Detection | Splits text into individual sentences with character offsets |
| Tokenization | Segments text into words and punctuation with position tracking |
| Named Entity Recognition | Detects persons, locations, organizations, and other named entities |
| POS Tagging | Assigns Penn Treebank POS tags to each token |
| Lemmatization | Reduces tokens to their dictionary base forms |
| Chunking | Identifies noun phrases, verb phrases, and other syntactic chunks |
| Parsing | Builds full syntactic parse trees using constituency parsing |
| Document Categorization | Classifies documents into predefined categories |
| Custom Model Training | Train custom models with Maxent, Perceptron, or Naive Bayes algorithms |

## Use Cases

| Name | Description |
|------|-------------|
| Information Extraction | Extract structured data from unstructured text documents |
| Text Classification | Automatically categorize documents by topic or sentiment |
| Search Enhancement | Improve search relevance with NLP-based query processing |
| Content Analysis | Analyze large text corpora for entities, topics, and patterns |
| Chatbot Development | Build conversational AI with NLP intent and entity extraction |

## Integrations

| Name | Description |
|------|-------------|
| Apache Solr | Integrate OpenNLP with Apache Solr for NLP-enhanced search |
| Apache Lucene | Use OpenNLP analyzers in Lucene text processing pipelines |
| Apache Flink | Real-time NLP processing with Apache Flink data streams |
| UIMA | Apache UIMA framework integration for unstructured information analysis |
| Maven/Gradle | Available on Maven Central for Java build system integration |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Apache OpenNLP Tools API](openapi/apache-opennlp-tools.yaml)

### JSON Schema

- [Text Request](json-schema/apache-opennlp-text-request-schema.json)
- [Tokens Request](json-schema/apache-opennlp-tokens-request-schema.json)
- [Language Detection Result](json-schema/apache-opennlp-language-detection-result-schema.json)
- [Named Entity](json-schema/apache-opennlp-named-entity-schema.json)
- [NER Result](json-schema/apache-opennlp-n-e-r-result-schema.json)
- [POS Tagging Result](json-schema/apache-opennlp-p-o-s-tagging-result-schema.json)
- [Parse Result](json-schema/apache-opennlp-parse-result-schema.json)
- [Model Info](json-schema/apache-opennlp-model-info-schema.json)
- [And more...](json-schema/)

### JSON Structure

- [Apache OpenNLP JSON Structures](json-structure/)

### JSON-LD

- [Apache OpenNLP Context](json-ld/apache-opennlp-context.jsonld)

### Examples

- [Apache OpenNLP Examples](examples/)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [OpenNLP Tools API](capabilities/shared/opennlp-tools.yaml) — Core NLP operations for text processing

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [NLP Pipeline Workflow](capabilities/nlp-pipeline-workflow.yaml) | OpenNLP | 10 | Data Scientist, NLP Engineer, Application Developer |

## Vocabulary

- [Apache OpenNLP Vocabulary](vocabulary/apache-opennlp-vocabulary.yaml) — Unified taxonomy mapping NLP resources, actions, workflows, and personas

## Rules

- [Apache OpenNLP Spectral Rules](rules/apache-opennlp-spectral-rules.yml) — 10 rules enforcing Apache OpenNLP API conventions

## Maintainers

**FN:** Kin Lane

**Email:** info@apievangelist.com
