---
date:
  created: 2026-10-15
categories:
  - conference
authors:
  - dgraus
title: OpenGov Lab at JURIX 2026, three papers and a spotlight tutorial
description: The OpenGov Lab contributes three papers and a spotlight tutorial to JURIX 2026 in Toulouse. The papers cover the legal function of citations in Dutch case law, how well the DSA Transparency Database taxonomy fits platform terms and conditions, and a neuro-symbolic model of the actio pauliana in Dutch insolvency law.
image: jurix-2026-banner.webp
---

The OpenGov Lab is heading to Toulouse for **JURIX 2026**, the 39th International Conference on Legal Knowledge and Information Systems. We are presenting three papers and a spotlight tutorial.

![JURIX 2026, the 39th International Conference on Legal Knowledge and Information Systems, Toulouse](jurix-2026-banner.webp)

<!-- more -->

## Papers

### Semantic classification of legal citations with Large Language Models
*Thijs Beers, Marc van Opijnen, Maarten Marx*

Citation networks of (Dutch) case law typically treat every citation equally, so a high in-degree gets read as legal authority. This paper tests whether LLMs can classify citations between judgments by their legal function; e.g., supportive, dismissive, or neutral). This paper finds models tend to recognize the most frequent functions well, but struggle with rarer ones. Finally, counting only supporting citations (instead of all) noticeably changes which judgments come out as central and hence authorative. 

### Towards More Granular Reasoning: Mapping the DSA Transparency Database Taxonomy to Platform Terms and Conditions Using Large Language Models
*Alyson Ranucci, Eline Leijten, David Graus*

Almost all content moderation decisions in the DSA Transparency Database cite a platform's own terms and conditions, not the DSA's pre-determined seventeen categories of reasons for content moderation. Using an LLM, this paper maps the terms and conditions of 31 online platforms (VLOPs en VLOSEs) onto the DSA's transparency database seventeen categories. The paper finds these categories fit some types of platforms much better than others, and they overlap, which makes catch-all reporting (the "other" category) a predictable result of the database's design. 

### Machina Pauliana: A neuro-symbolic approach to the actio pauliana in Dutch insolvency law
*Daan Boven, Gregor Behnke, David Graus*

The *actio pauliana* (Article 42 of the Dutch Bankruptcy Act) lets an insolvency practitioner undo transactions that harmed creditors. This paper models the article with a symbolic core written in [Catala](https://catala-lang.org/), while neural components resolve open-textured terms through case-based reasoning, using an advanced RAG pipeline over over Dutch civil judgments. 

## Spotlight tutorial: From Records to Release

On 8 December, David Graus presents [**From Records to Release: An IR/NLP Tour of the Open Government Disclosure Lifecycle**](../../../tutorials/jurix-2026.md), a 90-minute spotlight tutorial.

Access-to-information laws in 139 countries handled around 6.4 million requests in 2024. Every request, disclosure decision and published record raises retrieval and NLP questions, but research on them is spread over e-discovery and FOIA search, digital libraries and archives, and legal NLP. The tutorial brings these together around three stages of the disclosure lifecycle:

1. **Information management**: machine-readability, FAIR publication, metadata and document processing.
2. **Request-driven disclosure**: FOIA search, technology-assisted review and sensitivity-aware search.
3. **Proactive disclosure**: findability, plain language, recommendation and RAG over released records.

The tutorial is based on a mapping study by David Graus, Maik Larooij, Maarten Marx and Jaap Kamps. JURIX is the first place we present it, and we would like to hear from attendees what is missing or should be organised differently. There is no programming involved. The full programme and reading list are on the [tutorial page](../../../tutorials/jurix-2026.md).

## See you in Toulouse

Congratulations to all authors! If you are attending JURIX 2026, come find us at the paper sessions or the tutorial. Questions about the tutorial can go to [graus@opengov.nl](mailto:graus@opengov.nl).
