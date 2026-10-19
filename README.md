# The Second Brain Project

**Engineering context for intelligent decisions**

This repository contains the teaching materials for a six-laboratory Second Brain project. It explores how structured knowledge, source provenance, graph relationships, and bounded AI judgment can help professionals assemble decision-relevant context and examine complex questions.

The central idea is that a model’s answer depends on the knowledge made available to it: how that knowledge is represented, connected, dated, sourced, and tested. The labs move from retrieval and structured context toward adaptive, tool-mediated research. They are designed as educational experiments, not as claims that graph-based methods always outperform simpler approaches.

**Author:** Alejandro Reynoso  
**Repository:** [alexdibol/ai_second_brain_lab](https://github.com/alexdibol/ai_second_brain_lab)

## Start here

- [Foundational monograph: *The Second Brain — Engineering Context for Intelligent Decisions*](https://github.com/alexdibol/ai_second_brain_lab/blob/main/the%20second%20brain%20project.pdf) — the conceptual framework, laboratory designs, comparative methodology, and teaching roadmap.
- [MIT License](https://github.com/alexdibol/ai_second_brain_lab/blob/main/LICENSE) — license for this repository.

## The six laboratories

The laboratories begin with professional and institutional decision problems, then test how the same knowledge-engineering principles extend to broader intellectual inquiry. The monograph describes the full intended design; the links below identify the artifacts currently present in the repository.

### Lab 1 — Regulatory intelligence during a payment-system crisis

**Question:** During a synthetic payment-system crisis, which measures fall within an authority’s legal competence, which require coordination or legislation, and what risks remain?

The lab models legal sources, atomic provisions, institutions, regulated activities, and proposed interventions in a source-backed, date-aware knowledge graph. Students examine authority chains, adverse provisions, exceptions, and missing dependencies. The objective is a defensible, reviewable decision process—not an automatically generated emergency rule.

| Material | Link |
| --- | --- |
| Monograph | [Regulatory intelligence monograph (PDF)](https://github.com/alexdibol/ai_second_brain_lab/blob/main/lab_01/regulatory_intelligence_github.pdf) |
| Slide presentation | [Regulatory intelligence slides (PDF)](https://github.com/alexdibol/ai_second_brain_lab/blob/main/lab_01/slides_regulatory_intelligence.pdf) |
| Colab notebook | [Open notebook in Google Colab](https://colab.research.google.com/github/alexdibol/ai_second_brain_lab/blob/main/lab_01/colab_notebook_regulatory_intelligence.ipynb) · [Notebook on GitHub](https://github.com/alexdibol/ai_second_brain_lab/blob/main/lab_01/colab_notebook_regulatory_intelligence.ipynb) |

### Lab 2 — Trading intelligence and rapid contagion

**Question:** How might an operational or supply-chain shock travel through a network of firms before its effects are fully visible in market data?

Students investigate a synthetic universe of roughly 500 listed companies and trace relationships such as supplier dependence, financing, ownership, competition, and shared infrastructure. The notebook frames graph propagation as a transparent scenario engine that complements conventional risk measures. It distinguishes real-economy exposure from tradable alpha and generates evidence-based hypotheses for analyst review, not automatic trading orders.

| Material | Link |
| --- | --- |
| Monograph | [Market contagion monograph (PDF)](https://github.com/alexdibol/ai_second_brain_lab/blob/main/lab_02/contagion_second_brain_github.pdf) |
| Slide presentation | [Market contagion slides (PDF)](https://github.com/alexdibol/ai_second_brain_lab/blob/main/lab_02/slides_contagion_second_brain_github.pdf) |
| Colab notebook | [Open notebook in Google Colab](https://colab.research.google.com/github/alexdibol/ai_second_brain_lab/blob/main/lab_02/TRADING_CONTAGION_SECOND_BRAIN_github.ipynb) · [Notebook on GitHub](https://github.com/alexdibol/ai_second_brain_lab/blob/main/lab_02/TRADING_CONTAGION_SECOND_BRAIN_github.ipynb) |

### Lab 3 — Multinational M&A opportunity discovery

**Question:** Can a knowledge graph reveal strategically complementary acquisition candidates that conventional company-by-company screening may miss—and expose the constraints that could make a candidate infeasible?

The lab places students in an advisory team serving a financial-services group seeking expansion in payments, market infrastructure, and related technology. A synthetic multinational company universe connects ownership, licenses, products, technology, distribution, and jurisdiction. Students compare tabular, semantic, graph-guided, and hybrid discovery; separate strategic fit from regulatory feasibility and transaction economics; and prepare an evidence-linked shortlist and investment-committee memorandum.

| Material | Link |
| --- | --- |
| Monograph | [M&A discovery monograph (PDF)](https://github.com/alexdibol/ai_second_brain_lab/blob/main/lab_03/second_brain_investment_banking_github.pdf) |
| Slide presentation | [M&A discovery slides (PDF)](https://github.com/alexdibol/ai_second_brain_lab/blob/main/lab_03/slides_second_brain_investment_banking_github.pdf) |
| Colab notebook | [Open notebook in Google Colab](https://colab.research.google.com/github/alexdibol/ai_second_brain_lab/blob/main/lab_03/SECOND_BRAIN_INVESTMENT_BANKING_github.ipynb) · [Notebook on GitHub](https://github.com/alexdibol/ai_second_brain_lab/blob/main/lab_03/SECOND_BRAIN_INVESTMENT_BANKING_github.ipynb) |

### Lab 4 — Central-bank institutional memory

**Question:** How can a central-bank policy team draw on past liquidity and financial-stability episodes without confusing historical analogy with causal evidence, overlooking legal and operational constraints, or allowing hindsight to distort what policymakers knew at the time?

This laboratory turns a **synthetic institutional-memory vault** into an auditable decision-support workflow. Markdown notes encode historical episodes, policy decisions, transmission mechanisms, instruments, indicators, authorities, constraints, research, counterarguments, and observed outcomes. The notes contain genuine Obsidian `[[wikilinks]]` so their connections remain navigable inside the vault, while typed relationships are also represented in NetworkX knowledge graphs.

Students formulate a hypothetical funding-market disruption, retrieve relevant notes, follow bounded multi-hop paths, and compare strong and weak historical precedents. Temporal cutoffs and source identifiers help distinguish information available at a past decision date from later evaluations. The Claude Haiku judgment stage synthesizes a bounded evidence packet, and controlled adaptive discovery may propose additional evidence subject to deterministic validation. The final output is a **traceable, conditional policy-committee memorandum**, accompanied by provenance and integrity checks. The example is educational and does not delegate real policy authority to an AI model.

The ten-code-cell sequence covers environment setup; vault generation; parsing and indexing; derived precedent, causal, authority/constraint, and evidence graphs; query formulation; governed traversal; precedent testing; LLM judgment; bounded adaptive discovery; and the final memorandum and audit. The notebook may generate additional artifacts in Google Drive when executed; those generated outputs are distinct from the three published teaching materials below.

| Material | Link |
| --- | --- |
| Monograph | [Central-bank institutional memory monograph (PDF)](https://github.com/alexdibol/ai_second_brain_lab/blob/main/lab_04/second_brain_central_bank_github.pdf) |
| Slide presentation | [Central-bank institutional memory Beamer slides (PDF)](https://github.com/alexdibol/ai_second_brain_lab/blob/main/lab_04/slides_beamer_second_brain_central_bank.pdf) |
| Colab notebook | [Open notebook in Google Colab](https://colab.research.google.com/github/alexdibol/ai_second_brain_lab/blob/main/lab_04/colab_notebook_second_brain_central_bank.ipynb) · [Notebook on GitHub](https://github.com/alexdibol/ai_second_brain_lab/blob/main/lab_04/colab_notebook_second_brain_central_bank.ipynb) |

### Lab 5 — Autonomous legal research and endogenous graph navigation

**Question:** Can an LLM choose what evidence to investigate next within a bounded legal-research environment, while deterministic tools constrain and audit every action?

This capstone uses a synthetic Mexican legal system and three incomplete consultations. A shared vault of fictional records is organized across five overlapping graph layers. The LLM may propose an allowed action—such as inspect a record, follow a typed relationship, search a domain, test an exception, or recommend stopping. A deterministic gateway validates and executes the action, applies research budgets, updates the evidence state, and records the trace. Students compare semantic retrieval, fixed graph traversal, and bounded adaptive navigation before producing a conditional memorandum for human review.

| Material | Link |
| --- | --- |
| Monograph | [Legal knowledge and intelligence monograph (PDF)](https://github.com/alexdibol/ai_second_brain_lab/blob/main/lab_05/legal%20knowledge%20and%20intelligence.pdf) |
| Slide presentation | [Legal knowledge and intelligence slides (PDF)](https://github.com/alexdibol/ai_second_brain_lab/blob/main/lab_05/slides%20legal%20knowledge%20and%20intelligence.pdf) |
| Colab notebook | [Open notebook in Google Colab](https://colab.research.google.com/github/alexdibol/ai_second_brain_lab/blob/main/lab_05/colab%20notebook%20legal%20knowledge%20and%20intelligence.ipynb) · [Notebook on GitHub](https://github.com/alexdibol/ai_second_brain_lab/blob/main/lab_05/colab%20notebook%20legal%20knowledge%20and%20intelligence.ipynb) |

### Lab 6 — The Literary Second Brain: from institutional intelligence to humanistic inquiry

**Question:** Can the same Second Brain architecture used for financial, legal, and institutional intelligence help us navigate an interconnected universe of classic literature and investigate fundamental questions about identity, suffering, freedom, power, and mortality—without confusing graph connectivity with literary interpretation or textual evidence?

**Lab 6 is a deliberate generalization, not a departure from the project.** The broader reading project considers **84 completed classic works** across literary and philosophical traditions. The computational literary atlas used in this laboratory is an evolving, structured representation of that universe; it should **not** be assumed to contain complete, independently verified primary texts for all 84 books. Its notes, links, and proposed interpretations are the research material to examine critically, not established conclusions.

The laboratory treats the literary corpus as a **knowledge vault**: Markdown notes represent works, authors, concepts, movements, existential questions, and proposed reading circuits. Students restore and audit the physical Obsidian vault, compare its wikilinks with the supplied directed multigraph, inspect the reliability and provisional status of relationships, and construct readable local graph maps instead of relying on an opaque cloud of nodes. They formulate five humanistic questions, select starting library cards, and define a transparent navigation policy.

Two investigators then explore the same atlas from comparable starting points. **Agent A** follows explicit deterministic scoring and traversal rules; **Agent B** uses bounded Claude-assisted judgment to choose among authorized neighboring records. The laboratory preserves each path, its direction, relationship types, uncertainty statuses, and supporting vault excerpts, and compares routes using descriptive measures such as works visited, node-type diversity, provisional-link share, and path overlap. The final artifacts are **traceable reading journeys, comparative evidence packets, and reproducible reports**—not automatically validated answers to philosophical questions.

The pedagogical insight generalizes beyond literature: a well-constructed Second Brain can help explore **scientific research, archival collections, institutional histories, policy records, legal corpora, and other knowledge vaults**. Across domains, the same disciplines remain essential: source integrity, meaningful typed connections, transparent retrieval, explicit uncertainty, constrained LLM initiative, and human responsibility for interpretation.

| Material | Link |
| --- | --- |
| Monograph | [The Literary Second Brain monograph (PDF)](https://github.com/alexdibol/ai_second_brain_lab/blob/main/lab_06/literary_second_brain_github.pdf) |
| Slide presentation | [The Literary Second Brain Beamer slides (PDF)](https://github.com/alexdibol/ai_second_brain_lab/blob/main/lab_06/slides_literary_second_brain_github.pdf) |
| Colab notebook | [Open notebook in Google Colab](https://colab.research.google.com/github/alexdibol/ai_second_brain_lab/blob/main/lab_06/colab_notebook_literary_second_brain_tex.ipynb) · [Notebook on GitHub](https://github.com/alexdibol/ai_second_brain_lab/blob/main/lab_06/colab_notebook_literary_second_brain_tex.ipynb) |

## Intellectual sequence

The six labs investigate complementary forms of structured knowledge, first in professional decision-making and then in broader humanistic inquiry:

1. **Authority and constraints** — determine what an institution may do and what evidence supports that authority.
2. **Economic transmission** — trace how shocks can propagate through interdependent firms and markets.
3. **Strategic discovery** — find opportunities through combinations of capabilities and relationships.
4. **Institutional learning** — compare current conditions with past decisions while preserving chronology and dissent.
5. **Adaptive research judgment** — let an AI system select among bounded evidence-seeking actions, with deterministic execution and human responsibility.
6. **Humanistic generalization** — apply vault engineering, graph navigation, and bounded LLM exploration to classical literature and existential questions while keeping retrieval distinct from interpretation.

Across the series, the workflow is:

**Knowledge → Context → Judgment → Action → Learning**

The project compares information architectures where appropriate, including direct model prompting, curated long context, semantic or vector retrieval, fixed graph traversal, and bounded LLM-guided navigation. The purpose is to test when structure improves completeness, traceability, responsiveness, or decision quality—not to assume that it does. Source quality, graph design, temporal validity, and evaluation discipline remain decisive.

## Repository layout

- `the second brain project.pdf` — foundational monograph describing the original five-lab series; Lab 6 extends the research program.
- `lab_01/` — regulatory intelligence monograph, slides, and notebook.
- `lab_02/` — market contagion monograph, slides, notebook, and a placeholder local README.
- `lab_03/` — M&A discovery monograph, slides, notebook, and a placeholder local README.
- `lab_04/` — central-bank institutional memory monograph, Beamer slides, Colab notebook, and a placeholder local README.
- `lab_05/` — autonomous legal research monograph, slides, and notebook.
- `lab_06/` — Literary Second Brain monograph, Beamer slides, Colab notebook, and a placeholder local README.
- `docs/index.html` — public landing page for the laboratory series (its Lab 6 presentation may require a separate update).

## How to use the materials

The PDFs introduce the problem, conceptual architecture, and teaching sequence. The notebooks provide executable demonstrations and are designed for Google Colab; open them using the Colab links above. Where a notebook generates synthetic firms, records, events, or legal material, treat that material as simulated educational data. Review the source and assumptions before adapting a notebook for another purpose.

The foundational monograph describes the intended experimental designs and safeguards. A proposed design in the monograph should not be read as a claim that every experiment has already been completed or that a particular method has empirically prevailed.

## Responsible use, AI assistance, and authorship

AI tools assisted with coding and writing during preparation of some repository materials. **Alejandro Reynoso is responsible for the project’s design, academic content, supervision and direction of the work, and final editorial decisions.** AI assistance does not replace or assume the author’s intellectual or editorial responsibility.

The project is educational. The companies, crises, transactions, networks, consultations, and legal records used in the professional laboratories are synthetic unless a source is explicitly identified otherwise. Lab 6 instead draws on named literary works and an evolving interpretive atlas; its graph links, summaries, and hypotheses should not be mistaken for verified primary-text quotations or established literary influence. The legal materials in the capstone do not state current Mexican law and do not constitute legal advice. The market and M&A exercises are not investment recommendations, and simulated outputs are not validated trading signals, valuations, or transaction advice. Professional decisions require current authoritative evidence and qualified human review.

## License

The repository is released under the [MIT License](https://github.com/alexdibol/ai_second_brain_lab/blob/main/LICENSE). See the [LICENSE file](LICENSE) for the complete terms.

**Copyright © 2026 Alejandro Reynoso.**
