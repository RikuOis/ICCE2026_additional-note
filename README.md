# LLM-Based Agent Assessment for Supporting Quiz Correction in Learning by Quiz Creation (Paper 356)

This repository contains the supplementary materials for the paper titled **"LLM-Based Agent Assessment for Supporting Quiz Correction in Learning by Quiz Creation"** submitted to the 34th International Conference on Computers in Education (ICCE 2026).

## Overview

Problem posing is a well-established learning activity that fosters deep conceptual understanding. However, providing immediate, personalized, and scalable feedback on learner-generated questions poses a significant challenge. 

This repository provides supplementary details for our proposed **Agent-Assessment** approach, including full system prompts, evaluation protocols for Reflection Rate, detailed classification tables, high-resolution process diagrams, and sample data formats. By making these materials publicly accessible, we aim to ensure methodology transparency and reproducibility.

## Citation (APA 7th Edition)

If you reference this work or use the supplementary materials, please cite as follows:

> Anonymous Authors. (2026). *LLM-Based Agent Assessment for Supporting Quiz Correction in Learning by Quiz Creation* [Supplementary materials]. GitHub. https://github.com/RikuOis/ICCE2026-LLM-Based-Agent-Assessment-for-Supporting-Quiz-Correction-in-Learning-by-Quiz-Creation

```bibtex
@misc{icce2026_356,
  author       = {Anonymous Authors},
  title        = {LLM-Based Agent Assessment for Supporting Quiz Correction in Learning by Quiz Creation},
  year         = {2026},
  howpublished = {\url{https://github.com/RikuOis/ICCE2026-LLM-Based-Agent-Assessment-for-Supporting-Quiz-Correction-in-Learning-by-Quiz-Creation}},
  note         = {Supplementary materials for ICCE 2026 submission}
}
```

## Repository Structure

```text
ICCE2026-Agent-Assessment/
├── README.md
├── prompts/
│   └── Systemprompt for Assessment Agent.txt   # System prompt for LLM agent assessment
├── protocols/
│   └── coding protocols for refrection rate.md # Coding protocol for calculating Reflection Rate
├── figures/
│   ├── Figure0.png                             # Distribution of reflection rate per student (histogram)
│   ├── Figure1.jpg                             # Proposed process for agent assessment & revision support
│   ├── Figure2.jpg                             # System architecture and multi-agent configuration
│   ├── Figure3.jpg                             # Technical architecture and data flow diagram
│   └── Figure4.png                             # User interface screenshot of the system
└── tables/
    ├── table1.md                               # Detailed definitions and categories of format errors
    ├── table2.md                               # Step-by-step experimental procedure schedule
    ├── table3.md                               # Operational definitions and coding criteria for assessment variables
    ├── table4.md                               # Concrete examples of agent feedback, student revisions, and coding judgments
    ├── table5.md                               # Summary of identified issues, assessments, corrections, and reflection rate
    ├── table6.md                               # Spearman's rank correlation coefficients between variables and reflection rate
    └── table7.md                               # Reflection rates by assessment item
```

## Mapping of Paper Figures and Tables

To optimize space in the main manuscript and maintain high clarity, full descriptions, high-resolution figures, and extended data tables are made available in this repository. Below is the mapping between paper labels and repository files:

### Figures Mapping

| Paper Label | Description | Repository File Path |
| :--- | :--- | :--- |
| **Figure 0** | Distribution of Reflection Rate per Student ($n=19$) | [`figures/Figure0.png`](figures/Figure0.png) |
| **Figure 1** | Overview of Proposed Agent Assessment and Revision Support Process | [`figures/Figure1.jpg`](figures/Figure1.jpg) |
| **Figure 2** | System Architecture and Multi-Agent Configuration | [`figures/Figure2.jpg`](figures/Figure2.jpg) |
| **Figure 3** | Technical Architecture and Data Flow Diagram | [`figures/Figure3.jpg`](figures/Figure3.jpg) |
| **Figure 4** | User Interface of the Agent Assessment and Revision System | [`figures/Figure4.png`](figures/Figure4.png) |

### Tables Mapping

| Paper Label | Description | Repository File Path |
| :--- | :--- | :--- |
| **Table 1** | Detailed Classification and Definitions of Format Errors | [`tables/table1.md`](tables/table1.md) |
| **Table 2** | Complete Step-by-Step Experimental Procedure | [`tables/table2.md`](tables/table2.md) |
| **Table 3** | Operational Definitions and Coding Criteria for Assessment Variables | [`tables/table3.md`](tables/table3.md) |
| **Table 4** | Concrete Examples of Agent Feedback, Student Revisions, and Coding Judgments | [`tables/table4.md`](tables/table4.md) |
| **Table 5** | Summary of Identified Issues, Assessments, Corrections, and Reflection Rate | [`tables/table5.md`](tables/table5.md) |
| **Table 6** | Spearman’s Rank Correlation Coefficients Between Variables and Reflection Rate | [`tables/table6.md`](tables/table6.md) |
| **Table 7** | Reflection Rates by Assessment Item | [`tables/table7.md`](tables/table7.md) |

### Supplementary Files Mapping

| Manuscript Reference | Description | Repository File Path |
| :--- | :--- | :--- |
| **System Prompt** | Prompt template used by the LLM agent for item assessment | [`prompts/Systemprompt for Assessment Agent.txt`](prompts/Systemprompt%20for%20Assessment%20Agent.txt) |
| **Reflection Rate Protocol** | Coding protocol and criteria for evaluating learner reflection rate | [`protocols/coding protocols for refrection rate.md`](protocols/coding%20protocols%20for%20refrection%20rate.md) |

## License

This repository is distributed under the terms of the MIT License.