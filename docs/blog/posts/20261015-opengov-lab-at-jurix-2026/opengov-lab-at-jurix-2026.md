---
date:
  created: 2026-10-15
categories:
  - conference
authors:
  - dgraus
title: OpenGov Lab at JURIX 2026, a spotlight tutorial and three papers
description: The OpenGov Lab contributes a spotlight tutorial on the open government disclosure lifecycle and three papers to JURIX 2026 in Toulouse. The papers cover the legal function of citations in Dutch case law, how well the DSA Transparency Database taxonomy fits platform terms and conditions, and a neuro-symbolic model of the actio pauliana in Dutch insolvency law.
---

The OpenGov Lab is heading to Toulouse for **JURIX 2026**, the International Conference on Legal Knowledge and Information Systems. We are presenting a spotlight tutorial and three papers.

<!-- more -->

## Spotlight tutorial: From Records to Release

On 8 December, David Graus presents [**From Records to Release: An IR/NLP Tour of the Open Government Disclosure Lifecycle**](../../../tutorials/jurix-2026.md), a 90-minute spotlight tutorial.

Access-to-information laws in 139 countries handled around 6.4 million requests in 2024. Every request, disclosure decision and published record raises retrieval and NLP questions, but research on them is spread over e-discovery and FOIA search, digital libraries and archives, and legal NLP. The tutorial brings these together around three stages of the disclosure lifecycle:

1. **Information management**: machine-readability, FAIR publication, metadata and document processing.
2. **Request-driven disclosure**: FOIA search, technology-assisted review and sensitivity-aware search.
3. **Proactive disclosure**: findability, plain language, recommendation and RAG over released records.

The tutorial is based on a mapping study by David Graus, Maik Larooij, Maarten Marx and Jaap Kamps. JURIX is the first place we present it, and we would like to hear from attendees what is missing or should be organised differently. There is no programming involved. The full programme and reading list are on the [tutorial page](../../../tutorials/jurix-2026.md).

## Papers

### Semantic classification of legal citations with Large Language Models
*Thijs Beers, Marc van Opijnen, Maarten Marx*

Dutch case law is increasingly analysed as a citation network, but citations are usually treated as identical links. That loses their legal function, and a high in-degree gets read as legal authority when it may not be. This paper tests whether LLMs can classify citations between Dutch judgments by their legal function. Three models (GPT-5-mini, Claude Haiku 4.5 and Gemini 2.5 Flash) classified a gold standard of 259 manually annotated citations zero-shot. The models recognise the two largest functions well (best accuracy 0.89), but macro-F1 stays at 0.52 because the minority classes are hard to pick up. A context window of two paragraphs before and after the citation works best, and more context does not help. A second verification pass makes things worse, as the verifier systematically pushes predictions away from the dominant class. Typing citations also changes how the network reads: supporting citations are unevenly spread over judgments, so the ranking of central judgments shifts once only supporting relations are counted.

### Towards More Granular Reasoning: Mapping the DSA Transparency Database Taxonomy to Platform Terms and Conditions Using Large Language Models
*Alyson Ranucci, Eline Leijten, David Graus*

Under the Digital Services Act, online platforms submit their content moderation decisions and a Statement of Reasons to the DSA Transparency Database, classified into seventeen high-level categories. More than 99.8% of these statements cite a breach of the platform's own terms and conditions rather than a legal provision, so the database is mostly a record of contractual enforcement. Whether its categories actually describe those contractual rules had not been examined. This paper maps the terms and conditions of 31 online services, 447 policy documents in total, against the taxonomy, using a few-shot GPT-4.1 classifier evaluated on 75 annotated chunks.

Two findings stand out. How well the categories apply varies sharply by type of service: unsafe products account for 17.5% of assignments for marketplaces and 0.2% for adult platforms, while negative effects on civic discourse reach 9.9% within the Meta family and are absent for adult platforms, Booking.com and Wikipedia. The categories also overlap and are hard to tell apart, with a residual catch-all category making up 21.4% of all assignments. The authors argue that minimal, catch-all reporting follows from the database's design rather than from platforms being unwilling, and propose a schema that differentiates by service type and adds mandatory attributes derived from the platforms' own governance language.

### Machina Pauliana: A neuro-symbolic approach to the actio pauliana in Dutch insolvency law
*Daan Boven, Gregor Behnke, David Graus*

The *actio pauliana* of Article 42 of the Dutch Bankruptcy Act (Faillissementswet) lets an insolvency practitioner avoid transactions that prejudiced creditors. Applying it takes both structured, rule-based reasoning and a feel for open-textured terms developed in case law. This paper presents a neuro-symbolic model of the article. The symbolic core is written in [Catala](https://catala-lang.org/) in a literate style that keeps statute and formalisation aligned, with open-textured terms represented as boolean inputs. A neural routine turns the facts of a case into those inputs, and neural subroutines resolve the open-textured terms by case-based reasoning over Dutch civil judgments. These are retrieved by filtering on the requirement at hand and following the procedural chain of a case. Segmenting and labelling the judgments reaches high precision and recall on a gold standard of 100 judgments. On ten hand-annotated cases the model handles most criteria reasonably, but struggles with the knowledge requirement. Retrieval depth shows no clear quantitative effect, although the retrieved judgments give the model's answers explicit grounding in prior case law.

## See you in Toulouse

Congratulations to all authors! If you are attending JURIX 2026, come find us at the tutorial or the paper sessions. Questions about the tutorial can go to [graus@opengov.nl](mailto:graus@opengov.nl).
