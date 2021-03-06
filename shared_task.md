---
layout: main
title: Shared Task
order: 3
collection: pages_2022
permalink: /shared_task
---

# Shared Tasks

**We will have awards for shared task winners!**

We plan to host two shared tasks: UnifiedSKG and FinQA. We will accept system descriptions of our shared tasks as workshop submissions. Please check the [Call for Papers](https://suki-workshop.github.io/cfp) for paper submission details.

Both shared tasks have the same timelines:

- **Feb 15, 2022**:             Shared Task Launch
- **June 8, 2022**:             Result Submission Deadline
- **June 15, 2022**:            System Description Submission Deadline

All deadlines are 11:59 PM UTC -12h (Anywhere on Earth).

## UnifiedSKG
[UnifiedSKG](https://github.com/HKUNLP/UnifiedSKG) is a recently proposed framework that unifies and multi-tasks 21 structured knowledge grounding tasks including table/database/knowledge-base/apis semantic parsing, question answering, data-to-text, and factual verification. For this shared task, we consider the following 4 datasets: 
- [Spider](https://yale-lily.github.io/spider) for database semantic parsing
- [GrailQA](https://dki-lab.github.io/GrailQA/) for knowledge graph semantic parsing/question answering
- [WikiTableQuestions](https://ppasupat.github.io/WikiTableQuestions/) for table question answering
- [SParC](https://yale-lily.github.io/sparc) for multi-turn database semantic parsing
- [TabFact](https://tabfact.github.io/index.html) for table factual verification.

Models are allowed to train on the training sets of these datasets, and we will evaluate the model using the test sets of these datasets. We provide unified data formats and simple but strong SOTA/baseline models in this [Github repo](https://github.com/HKUNLP/UnifiedSKG). 

Our UnifiedSKG shared task has two subtasks focusing on two aspects, ***Generalization*** and ***Multi-Task Learning***. We will report a joint score on the 5 datasets (also consider the size of your submitted models).
  - ***Generalization***: The goal of this subtask is to propose general structured knowledge encoding for table/database/knowledge-base/apis, general methods for integrating structured & unstructured (e.g., user NL requests) inputs, and effective structured knowledge retrival methods. For this subtask, models are allowed to train on the training set of individual tasks separately, and we will evaluate the model on the corresponding test sets. For more details, please follow the setting used in [Table 2 of the paper](https://arxiv.org/pdf/2201.05966.pdf). 
  - ***Multi-Task Learning***: The goal of this subtask is to propose effective multi-tasking methods that jointly learn structured knowledge and integrate structured & unstructured inputs. For this subtask, models are allowed to use all the training sets together in a multi-task learning fashion, and we will evaluate the model on the test sets. Please follow the setting used in [Table 4 of the paper](https://arxiv.org/pdf/2201.05966.pdf).

## FinQA
FinQA is a large-scale dataset on answering deep questions over financial data, aiming to automate the analysis of a large corpus of financial documents. Please check our [FinQA paper](https://arxiv.org/pdf/2109.00122.pdf) for more details. The dataset, code and instructions can be found at [Github](https://github.com/czyssrs/FinQA).

The final evaluation of the model will be based on the results on the private test set. Please first submit your results to both leaderboards.
- Public Test: This phase evaluates algorithms on the FinQA public test set where the references are available. A submission needs to consist of results on the entire public test set to be considered as a valid submission.
The leaderboard for the public test set is hosted here on [Codalab](https://codalab.lisn.upsaclay.fr/competitions/1846).
- Private Test: This phase evaluates algorithms on the FinQA private test set with all references heldout. A submission needs to consist of results on the entire test set to be considered as a valid submission. This phase is aimed at the final evaluation of the model and one is not allowed to create multiple submissions using multiple teams.
The leaderboard for the private test set is hosted here on [Codalab](https://codalab.lisn.upsaclay.fr/competitions/4138).

Please first submit your results on the FinQA test set to the leaderboard, and then submit your paper following the [Call for Paper](https://suki-workshop.github.io/cfp). **To be eligible for result archives and consideration for awards, we kindly request you to send the following information to zhiyuchen@cs.ucsb.edu using your main contact email:**
- Team name.
- Team members.
- The username used in CodaLab submissions.
- The forum link to your paper submission on Openreview.

Please check the [FinQA challenge](https://finqasite.github.io/challenge.html) website for more details. 
