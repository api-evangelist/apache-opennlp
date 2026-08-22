# Apache OpenNLP (apache-opennlp)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
