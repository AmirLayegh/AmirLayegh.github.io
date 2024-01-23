---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
- Wiki-based Prompts for Enhancing Relation Extraction using Language Models [Accepted at SAC2024][[PDF]](/files/SAC2024%20(4).pdf).

Prompt-tuning and instruction-tuning of language models have exhibited significant results in few-shot Natural Language Processing (NLP) tasks, such as Relation Extraction (RE), which involves identifying relationships between entities within a sentence. However, the effectiveness of these methods relies heavily on the design of the prompts. A compelling question is whether incorporating external knowledge can enhance the language model's understanding of NLP tasks. In this paper, we introduce {\em wiki-based} prompt construction that leverages Wikidata as a source of information to craft more informative prompts for both prompt-tuning and instruction-tuning of language models in RE. Our experiments show that using wiki-based prompts enhances cutting-edge language models in RE, emphasizing their potential for improving RE tasks.

- ContrastNER: Contrastive-based Prompt Tuning for
Few-shot NER [[LINK]](/files/ContrastNER!%20Contrastive-based%20Prompt%20Tuning%20for%20Few-shot%20NER.pdf) (Presented at COMPSAC2023)

Prompt-based language models have produced encouraging results in numerous applications, including Named Entity Recognition (NER) tasks. NER aims to identify entities in a sentence and provide their types. However, the strong performance of most available NER approaches is heavily dependent on the design of discrete prompts and a verbalizer to map the model-predicted outputs to entity categories, which are complicated undertakings. To address these challenges, we present ConstrastNER, a prompt-based NER framework that employs both discrete and continuous tokens in prompts and uses a contrastive learning approach to learn the continuous prompts and forecast entity types. The experimental results demonstrate that ContrastNER obtains competitive performance to the state-of-the-art NER methods in high-resource settings and outperforms the state-of-the-art models in low-resource circumstances without requiring extensive manual prompt engineering and verbalizer design.

- A survey of big data pipeline orchestration tools from the perspective of the datacloud project [[LINK]](https://ceur-ws.org/Vol-3036/paper05.pdf)

This paper presents a survey of existing tools for Big Data pipeline orchestration based on a comparative framework developed in the DataCloud project. We propose criteria for evaluating the tools to support reusability, flexible pipeline communication modes, and separation of concerns in Big Data pipeline descriptions. This survey aims to identify research and technological gaps and to recommend approaches for filling them. Further work in the DataCloud project is oriented towards the design, implementation, and practical evaluation of the recommended approaches.
