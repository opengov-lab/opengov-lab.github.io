---
title: "JURIX 2026 Tutorial"
description: "JURIX 2026 spotlight tutorial: a guided IR/NLP tour of the open government disclosure lifecycle, from information management to request-driven and proactive disclosure."
template: narrow.html
---

## From Records to Release: An IR/NLP Tour of the Open Government Disclosure Lifecycle

:material-account: **Presenter:** [David Graus](../team.md) (University of Amsterdam, ICAI OpenGov Lab)  
:material-map-marker: **Venue:** Spotlight tutorial at JURIX 2026, Toulouse  
:material-calendar: **Date:** December 2026 (exact date, time and room to follow)  
:material-timer-outline: **Format:** 90 minutes, lecture and discussion, no coding

## :material-scale-balance: Why this tutorial

Access-to-information laws, such as the Dutch *Wet open overheid* (Woo) and Freedom of Information Acts (FOIA) with counterparts in **139 countries**, handled some **6.4 million requests** in 2024. Every request, every disclosure decision, and every published record is an IR/NLP problem inside a well-framed legal context. The research that underpins it is scattered across e-discovery and FOIA search, digital libraries and archives, and legal NLP.

This tutorial argues that open government disclosure is **not e-discovery done differently**, but a distinct, emerging research area at the intersection of legal IR and NLP. E-discovery is adversarial and litigation-driven; disclosure is a public-interest process governed by statutory exemptions, with asymmetric incentives, heterogeneous and scattered collections, and an extra step e-discovery lacks: what is released must be understandable to the public.

We walk through the disclosure lifecycle using three lenses:

1. **Information management**: machine-readability, FAIR metadata, classification and document processing (the foundation).
2. **Request-driven disclosure**: FOIA search, TAR/CAL, high-recall and sensitivity-aware search (the most mature lens in IR).
3. **Proactive disclosure**: open-data findability, plain language, recommendation and RAG over released records (the newest and least IR-mature stage).

The tutorial is based on a mapping study by David Graus, Maik Larooij, Maarten Marx and Jaap Kamps (ICAI OpenGov Lab). It is the first public presentation of the three-lens taxonomy, ahead of the study's peer review, so attendees get early access to the synthesis and a chance to shape it through discussion.

## :material-calendar-clock: Program

Timings are indicative.

**0–10 min: Introduction: disclosure as an IR/NLP problem**

- Scale and societal stakes: 139 countries, 6.4M requests per year
- Disclosure as three linked retrieval problems, not one
- Mapping-study method: scope, search strategy, and how the three lenses were derived

**10–30 min: Lens 1: Information management**

- Machine-readability and the FAIR principles
- Metadata, classification and document processing: OCR error impact, redaction detection, page-stream segmentation, and zero-shot vision-language models for both
- Case study: the FAIR Dutch Woo document collection
- Metadata quality, discoverability, and open gaps in standardization

**30–55 min: Lens 2: Request-driven (passive) disclosure**

- E-discovery, technology-assisted review (TAR) and continuous active learning (CAL), and a decade of TREC Legal Track evaluation
- What carries over and what does not: bridging the e-discovery and sensitivity-review literatures
- Sensitivity- and exemption-aware search and redaction, and a recent test collection
- Statutory exemptions as computable legal norms
- An AI-orchestrated FOIA-response pipeline, and a local LLM for deliberative process privilege
- Touchpoints with archival science and legal case retrieval

**55–75 min: Lens 3: Proactive disclosure**

- Publishing is not use: findability, barriers, and open data as "empowering the empowered"
- Normative framing: the "monitorial citizen" who scans rather than tracks
- Deciding what to publish as a retrieval problem: topic detection and tracking, newsworthiness and press-attention prediction
- Making released text understandable: sentence simplification and plain-language standards
- Recommendation for released records, and the democratic framing it inherits from news recommendation
- RAG over disclosed corpora, and interpretability (WOOLens)

**75–90 min: Synthesis, open problems and discussion**

- Cross-lens dependencies: document quality sets a ceiling for retrieval and proactive disclosure; sensitivity classification feeds proactive release
- Why errors cascade across lenses, favouring narrow, validated, task-specific components over end-to-end systems
- Benchmark immaturity in Lens 3, against a decade of shared-task evaluation in Lens 2
- Open Q&A

## :material-account-group-outline: Who it is for

AI & Law researchers and practitioners working on legal information retrieval, e-discovery, regulatory or administrative NLP, open government data and government transparency, as well as policy researchers and practitioners from FOIA/Woo authorities.

**Prerequisites:** general familiarity with IR/NLP concepts (retrieval, classification, text generation). There is no hands-on or coding component, so no programming is required.

## :material-book-open-variant: Materials

**The survey.** Graus, D., Larooij, M., Marx, M., & Kamps, J. *Information Retrieval for Open Government*, the full survey underlying this tutorial, is being finalized for peer review. A pre-print or extended abstract will be made available to registered attendees ahead of the session.

**Foundational reading**

- Oard & Webber, *Information Retrieval for E-Discovery* (Foundations and Trends in IR, 2013)
- Grossman & Cormack, *Technology-assisted review in e-discovery can be more effective and more efficient than exhaustive manual review* (Richmond Journal of Law and Technology, 2011)
- McDonald & Oard, *Search among sensitive content* (ECIR tutorial, 2021)
- Shinde et al., *Tracing the past, predicting the future: A systematic review of AI in archival science* (ASIS&T, 2025)
- Wilkinson et al., *The FAIR Guiding Principles for scientific data management and stewardship* (Scientific Data, 2016)

**OpenGov Lab work featured in the tutorial**

- Van Heusden, Larooij, Kamps & Marx, *A collection of FAIR Dutch Freedom of Information Act documents* (Scientific Data, 2025), and the [Woogle](https://woogle.wooverheid.nl) search engine built on it, used as a running example
- Van Heusden, Kamps & Marx, *OpenPSS: An Open Page Stream Segmentation Benchmark* (TPDL, 2024)
- Van Heusden, Meijer & Marx, *Redacted text detection using neural image segmentation methods* (IJDAR, 2025)
- Van Wijk & Marx, *Spoken Question Answering on Municipal Council Meetings* (ECIR, 2025)
- Viira, Marx & Larooij, *ParlaMint widened: a European dataset of freedom of information act documents* (ParlaCLARIN, 2024)
- Larooij & Graus, [*To redact, or not to redact? A local LLM for deliberative process privilege classification*](../papers/to-redact-or-not-to-redact.pdf) (AIOG @ ICAIL, 2026)
- Ateş & Graus, *Out of the box: Zero-shot vision-language models for redaction detection and page-stream segmentation* (AIOG @ ICAIL, 2026)

**Community signals**

- Trippas et al., *Report from the 4th Strategic Workshop on Information Retrieval in Lorne (SWIRL 2025)* (SIGIR Forum, 2025), which names FOIA search as an emerging IR topic
- The [1st AI and Open Government (AIOG) workshop](https://aiog.net) at ICAIL 2026, co-organized by the presenter

See all lab publications on the [Papers](../publications.md) page.

## :material-account: Presenter

**David Graus** is an assistant professor in Information Retrieval and Natural Language Processing at ILLC, University of Amsterdam, and Lab Manager of the ICAI OpenGov Lab. He co-organized the first AI and Open Government (AIOG) workshop at ICAIL 2026.

The underlying mapping study is co-authored with **Maik Larooij**, **Maarten Marx** and **Jaap Kamps** (University of Amsterdam, ICAI OpenGov Lab).

Questions about the tutorial: [graus@opengov.nl](mailto:graus@opengov.nl)

## :material-domain: About the OpenGov Lab

The [ICAI OpenGov Lab](../about.md) is a collaboration between the University of Amsterdam and partners in the Dutch national government, including the Dutch Government Organization for Information Management, which grounds this work in current Dutch disclosure practice.
