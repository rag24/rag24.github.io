---
title: " Zero-shot Large Language Models for Automatic Readability Assessment"
collection: publications
category: conferences
permalink: /publication/acl_LAURAE
excerpt: "This paper proposes LAURAE for the automatic readability assessment task, an ensemble method combining combining LLM and readability formula scores, where ensemble weights are determined from the LLM's verbalized confidence scores."
date: 2026-07-07
paperurl: 'https://rag24.github.io/files/acl_readability_LAURAE.pdf'
venue: 'The 64th Annual Meeting of the Association for Computational Linguistics'
citation: 'Grossman, R. & Chen, Y. (2026). Zero-shot Large Language Models for Automatic Readability Assessment. Forthcoming in the 64th Annual Meeting of the Association for Computational Linguistics (ACL 2026).'
---
Unsupervised automatic readability assessment (ARA) methods have important practical and research applications (e.g., ensuring medical or educational materials are suitable for their target audiences). In this paper, we propose a new zero-shot prompting methodology for ARA and present the first comprehensive evaluation of using large language models (LLMs) as an unsupervised ARA method by testing 10 diverse open-source LLMs (e.g., different sizes and developers) on 14 diverse datasets (e.g., different text lengths and languages). Our findings show that our proposed prompting methodology outperforms prior methods on 13 of the 14 datasets. Furthermore, we propose LAURAE, which combines LLM and readability formula scores to improve robustness by capturing both contextual and shallow (e.g., sentence length) features of readability. Our evaluation demonstrates that LAURAE robustly outperforms prior methods across languages, text lengths, and amounts of technical language.
