---
title: "JURIX 2026 Tutorial"
description: "From Records to Release, a spotlight tutorial at JURIX 2026 on information retrieval and NLP for open government disclosure."
template: narrow.html
---

## From Records to Release: An IR/NLP Tour of the Open Government Disclosure Lifecycle

Spotlight tutorial at JURIX 2026, Toulouse  
8 December 2026, 90 minutes (time and room to follow)  
Presented by [David Graus](../team.md), University of Amsterdam and ICAI OpenGov Lab

## About the tutorial

In 2024, access-to-information laws in 139 countries handled around 6.4 million requests. In the Netherlands this is the *Wet open overheid* (Woo); elsewhere it is usually a Freedom of Information Act (FOIA). Each request, each disclosure decision and each published record raises retrieval and NLP questions, within a fairly well-defined legal framework. Research on these questions is spread over several communities: e-discovery and FOIA search, digital libraries and archives, and legal NLP.

Request-driven disclosure has a lot in common with e-discovery. Both use technology-assisted review to find documents for human review, and both have to deal with sensitive or privileged material. There are also real differences. E-discovery takes place between two parties in litigation. Disclosure is a public-interest process governed by statutory exemptions, where the requester wants as much as possible and the authority aims for a defensible minimum. Government collections are also more varied and spread over many organisations, and whatever is released has to be readable by the general public. We think this makes open government disclosure a research area of its own.

The tutorial is organised around three stages of the disclosure lifecycle:

1. Information management: machine-readability, FAIR publication, metadata, classification and document processing.
2. Request-driven disclosure: FOIA search, technology-assisted review, high-recall and sensitivity-aware search. This is the most developed area in IR.
3. Proactive disclosure: findability of open data, plain language, recommendation and RAG over released records. This is the newest and least studied area.

The material comes from a mapping study by David Graus, Maik Larooij, Maarten Marx and Jaap Kamps (ICAI OpenGov Lab), which we are preparing for peer review. JURIX is the first place we present it, and we would like to hear from attendees what is missing or should be organised differently.

## Program

Timings are approximate.

**0–10 min. Introduction**

- Scale of access-to-information practice: 139 countries, 6.4 million requests per year
- Disclosure as three linked retrieval problems
- How the mapping study was done: scope, search strategy and how we arrived at the three stages

**10–30 min. Information management**

- Machine-readability and the FAIR principles
- Document processing: the effect of OCR errors, redaction detection, page-stream segmentation, and zero-shot vision-language models for the latter two
- Case study: the FAIR Dutch Woo document collection
- Metadata quality, discoverability and missing standards

**30–55 min. Request-driven disclosure**

- E-discovery, technology-assisted review (TAR), continuous active learning (CAL) and ten years of the TREC Legal Track
- Which e-discovery methods apply to disclosure and which do not, building on earlier work linking e-discovery and sensitivity review
- Sensitivity- and exemption-aware search and redaction, including a recent test collection
- Statutory exemptions as computable legal norms
- A FOIA-response pipeline orchestrated by AI, and a locally run LLM for classifying deliberative process privilege
- Links with archival science and legal case retrieval

**55–75 min. Proactive disclosure**

- Publishing documents does not mean people find or use them; Gurstein's critique of open data as "empowering the empowered"
- Schudson's "monitorial citizen", who scans for problems rather than following everything
- Choosing what to publish as a retrieval task: topic detection and tracking, newsworthiness and predicting press attention
- Sentence simplification and plain-language standards
- Recommending released records, and what this can learn from work on news recommenders and democracy
- RAG over disclosed documents, and interpretability with WOOLens

**75–90 min. Open problems and discussion**

- Dependencies between the stages: poor document quality limits retrieval and proactive disclosure, and sensitivity classification determines what can be released proactively
- Errors add up across the stages, which is an argument for small, task-specific components that can be validated, rather than end-to-end systems
- Proactive disclosure lacks benchmarks, while request-driven disclosure has a decade of shared tasks
- Questions and discussion

## Audience

Researchers and practitioners in AI & Law who work on legal information retrieval, e-discovery, regulatory or administrative NLP, open government data or transparency. Also policy researchers and staff at FOIA/Woo authorities.

You should know the basics of IR and NLP (retrieval, classification, text generation). There is no programming or hands-on part.

## Reading

Graus, Larooij, Marx and Kamps, *Information Retrieval for Open Government*. This is the survey the tutorial is based on. Registered attendees will get a pre-print or extended abstract before the session.

Background:

- Oard and Webber, *Information Retrieval for E-Discovery*, Foundations and Trends in IR, 2013
- Grossman and Cormack, *Technology-assisted review in e-discovery can be more effective and more efficient than exhaustive manual review*, Richmond Journal of Law and Technology, 2011
- McDonald and Oard, *Search among sensitive content*, ECIR tutorial, 2021
- Shinde et al., *Tracing the past, predicting the future: A systematic review of AI in archival science*, ASIS&T, 2025
- Wilkinson et al., *The FAIR Guiding Principles for scientific data management and stewardship*, Scientific Data, 2016
- Trippas et al., *Report from the 4th Strategic Workshop on Information Retrieval in Lorne (SWIRL 2025)*, SIGIR Forum, 2025

Work from the OpenGov Lab used in the tutorial:

- Van Heusden, Larooij, Kamps and Marx, *A collection of FAIR Dutch Freedom of Information Act documents*, Scientific Data, 2025. WooZM, the search engine built on this collection, is used as an example throughout.
- Van Heusden, Kamps and Marx, *OpenPSS: An Open Page Stream Segmentation Benchmark*, TPDL, 2024
- Van Heusden, Meijer and Marx, *Redacted text detection using neural image segmentation methods*, IJDAR, 2025
- Van Wijk and Marx, *Spoken Question Answering on Municipal Council Meetings*, ECIR, 2025
- Viira, Marx and Larooij, *ParlaMint widened: a European dataset of freedom of information act documents*, ParlaCLARIN, 2024
- Larooij and Graus, [*To redact, or not to redact? A local LLM for deliberative process privilege classification*](../papers/to-redact-or-not-to-redact.pdf), AIOG at ICAIL, 2026
- Ateş and Graus, *Out of the box: Zero-shot vision-language models for redaction detection and page-stream segmentation*, AIOG at ICAIL, 2026

Several of the papers discussed were presented at the first [AI and Open Government workshop (AIOG)](https://aiog.net) at ICAIL 2026. Other lab publications are on the [Papers](../publications.md) page.

## Presenter

David Graus is assistant professor in Information Retrieval and Natural Language Processing at ILLC, University of Amsterdam, and lab manager of the ICAI OpenGov Lab. David co-organised AIOG 2026.

The mapping study is joint work with Maik Larooij, Maarten Marx and Jaap Kamps, all at the University of Amsterdam and the ICAI OpenGov Lab.

Questions about the tutorial can go to [graus@opengov.nl](mailto:graus@opengov.nl).

## OpenGov Lab

The [ICAI OpenGov Lab](../about.md) is a collaboration between the University of Amsterdam and Dutch government partners, among them the Dutch Government Organization for Information Management.
