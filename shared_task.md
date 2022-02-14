---
layout: main
title: Shared Task
order: 3
collection: pages_2022
permalink: /shared_task
---

# Call for Shared Task

We plan to host two shared tasks: UnifiedSKG and FinQA. We accept system descriptions of our shared tasks as workshop submissions.

## UnifiedSKG
[UnifiedSKG](https://github.com/HKUNLP/UnifiedSKG) is a recently proposed framework that unifies and multi-tasks 21 structured knowledge grounding tasks including table/database/knowledge-base/apis semantic parsing, question answering, data-to-text, and factual verification. We provide unified data formats and strong but simple SOTA/baseline models in this [Github repo](https://github.com/HKUNLP/UnifiedSKG). 

For the test datasets of the shared task, we consider 4 datasets with a hidden test split, including [Spider](https://yale-lily.github.io/spider) (database semantic parsing), [GrailQA](https://dki-lab.github.io/GrailQA/)(knowledge graph semantic parsing/question answering), [SParC](https://yale-lily.github.io/sparc)(multi-turn database semantic parsing), and [TabFact](https://tabfact.github.io/index.html) (table factual verification). We will report a joint score on the 4 tasks (also consider the size of your submitted models).

Our UnifiedSKG shared task focues on two aspects, ***Generalization*** and ***Multi-Tasking***:
  - ***Generalization***: The goal of this subtask is to propose general structured knowledge encoding for table/database/knowledge-base/apis, general methods for integrating structured & unstructured (e.g., user NL requests) inputs, and effective structured knowledge retrival methods. For this subtask, please follow the setting used in [Table 2 of the paper](https://arxiv.org/pdf/2201.05966.pdf).
  - ***Multi-Tasking***: The goal of this subtask is to propose effective multi-tasking methods that jointly learn structured knowledge and integrate structured & unstructured inputs. Please follow the setting used in [Table 4 of the paper](https://arxiv.org/pdf/2201.05966.pdf).

<!-- - **[HybridQA](https://hybridqa.github.io/)/[FinQA](https://codalab.lisn.upsaclay.fr/competitions/1846)**: The HybridQA challenge is in the Wikipedia domain, where a multi-hop question requires the model to navigate across a set of given tables and passages to find the answer. The questions in these datasets are annotated to necessitate information aggregation across the two modalities (texts and tables). Also, the FinQA challenge is in the finance domain, where a question requires the model to reason across the numerical in the given passage and table. The questions in FinQA test the ability to perform numerical reasoning by integrating knowledge sources in a real-world specialized domain. -->

## FinQA
FinQA is a large-scale dataset on answering deep questions over financial data, aiming to automate the analysis of a large corpus of financial documents. Please check our [FinQA paper](https://arxiv.org/pdf/2109.00122.pdf) for more details. The dataset, code and instructions can be found at [Github](https://github.com/czyssrs/FinQA).

The leaderboard is hosted on [codalab](https://codalab.lisn.upsaclay.fr/competitions/1846). Please first submit your results on the FinQA test set to the leaderboard.

<!-- ## Important Dates
- **April 15, 2022**:             Shared Task Track Submission deadline
- **April 9-April 29, 2022**:     Review period
- **May 6, 2022**:                Notification of acceptance
- **May 20, 2022**:               Camera-ready version deadline

All deadlines are 11:59 PM UTC -12h (Anywhere on Earth). -->

