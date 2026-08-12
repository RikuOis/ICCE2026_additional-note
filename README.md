# ICCE2026-Agent-Assessment: Supplementary Materials

This repository contains the supplementary materials for the paper titled **"LLM-Based Agent Assessment and Revision Support in Problem Posing Learning"** submitted to the 34th International Conference on Computers in Education (ICCE 2026).

## Overview

Problem posing is a well-established learning activity that fosters deep conceptual understanding. However, providing immediate, personalized, and scalable feedback on learner-generated questions poses a significant challenge. 

This repository provides supplementary details for our proposed **Agent-Assessment** approach, including full system prompts, evaluation protocols for Reflection Rate, detailed classification tables, high-resolution process diagrams, and sample data formats. By making these materials publicly accessible, we aim to ensure methodology transparency and reproducibility.

## Citation (APA 7th Edition)

If you reference this work or use the supplementary materials, please cite as follows:

> Anonymous Authors. (2026). *LLM-Based Agent Assessment and Revision Support in Problem Posing Learning* [Supplementary materials]. GitHub. https://github.com/RikuOis/ICCE2026-Agent-Assessment

```bibtex
@misc{icce2026_agent_assessment,
  author       = {Anonymous Authors},
  title        = {LLM-Based Agent Assessment and Revision Support in Problem Posing Learning},
  year         = {2026},
  howpublished = {\url{https://github.com/RikuOis/ICCE2026-Agent-Assessment}},
  note         = {Supplementary materials for ICCE 2026 submission}
}
```

## Repository Structure

```text
ICCE2026-Agent-Assessment/
├── README.md
├── LICENSE
├── prompts/
│   └── system_prompt_assessment.md             # System prompt for LLM agent assessment
├── protocols/
│   └── coding_protocol_reflection_rate.md      # Coding protocol for calculating Reflection Rate
├── figures/
│   ├── figure1_proposed_process.png            # Proposed process for agent assessment & revision support
│   ├── figure2_system_architecture.png         # Overall system architecture
│   └── figure3_agent_assessment_interface.png  # User interface screenshot of the system
├── tables/
│   ├── table1.md      # Detailed definitions and categories of format errors
│   ├── table2.md      # Step-by-step experimental procedure schedule
│   ├── table3.md      # Summary of identified issues, assessments, corrections, and reflection rate
│   ├── table4.md      # Spearman's rank correlation coefficients between variables and reflection rate
│   └── table5.md      # Reflection rates by assessment item
└── data_sample/
    └── quiz_data_format.csv                    # Anonymized sample quiz data format
```

## Mapping of Paper Figures and Tables

To optimize space in the main manuscript and maintain high clarity, full descriptions, high-resolution figures, and extended data tables are made available in this repository. Below is the mapping between paper labels and repository files:

### Figures Mapping

| Paper Label | Description | Repository File Path |
| :--- | :--- | :--- |
| **Figure 1** | Overview of Proposed Agent Assessment and Revision Support Process | [`figures/figure1_proposed_process.png`](figures/figure1_proposed_process.png) |
| **Figure 2** | System Architecture of the Agent Assessment Platform | [`figures/figure2_system_architecture.png`](figures/figure2_system_architecture.png) |
| **Figure 3** | User Interface of the Agent Assessment System | [`figures/figure3_agent_assessment_interface.png`](figures/figure3_agent_assessment_interface.png) |

### Tables Mapping

| Paper Label | Description | Repository File Path |
| :--- | :--- | :--- |
| **Table 1** | Detailed Classification and Definitions of Format Errors | [`tables/table1.md`](tables/table1.md) |
| **Table 2** | Complete Step-by-Step Experimental Procedure | [`tables/table2.md`](tables/table2.md) |
| **Table 3** | Summary of Identified Issues, Assessments, Corrections, and Reflection Rate | [`tables/table3.md`](tables/table3.md) |
| **Table 4** | Spearman’s Rank Correlation Coefficients Between Variables and Reflection Rate | [`tables/table4.md`](tables/table4.md) |
| **Table 5** | Reflection Rates by Assessment Item | [`tables/table5.md`](tables/table5.md) |

### Supplementary Files Mapping

| Manuscript Reference | Description | Repository File Path |
| :--- | :--- | :--- |
| **System Prompt** | Prompt template used by the LLM agent for item assessment | [`prompts/system_prompt_assessment.md`](prompts/system_prompt_assessment.md) |
| **Reflection Rate Protocol** | Coding protocol and criteria for evaluating learner reflection rate | [`protocols/coding_protocol_reflection_rate.md`](protocols/coding_protocol_reflection_rate.md) |

## License

This repository is distributed under the terms of the MIT License. See [LICENSE](LICENSE) for details.