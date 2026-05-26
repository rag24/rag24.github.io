---
title: "Multilingual Disparities in LLM-Based Safety Judgments: Evidence from Brand Safety Applications"
collection: publications
category: conferences
permalink: /publication/mellm
excerpt: "We evaluate LLM brand-safety ratings on aligned multilingual news and find systematic language-conditioned disparities across 10,467 Euronews articles and 13 languages."
date: 2026-07-07
paperurl: 'https://rag24.github.io/files/65_Multilingual_Disparities_in.pdf'
venue: 'The 1st Workshop on Multilinguality in the Era of Large Language Models'
citation: 'Songjiang Liu, Riley Grossman, Mike Smith, Cristian Borcea, Yi Chen (2026). Multilingual Disparities in LLM-Based Safety Judgments: Evidence from Brand Safety Applications. Forthcoming in the The 1st Workshop on Multilinguality in the Era of Large Language Models (MeLLM 2026).'
---
Multilingual LLMs are increasingly used as context-aware judges in real-world information systems under the assumption that equivalent content receives equivalent judgments across languages. We examine this assumption through brand safety, a global application where automated ratings can affect advertisers' reputations, publishers' revenues, and users' access to news. We construct a benchmark of LLM-generated safety ratings for 10,467 semantically aligned news articles across 13 languages. We find systematic cross-lingual disagreement appearing in more than 96% of cases where at least one language receives a non-zero risk rating. Suitability ratings differ significantly by language, controlling for run, category, and article. In the main model, English, German, and French content is generally rated more strictly, while Polish, Hungarian, Greek, Turkish, and Persian content is rated more leniently. Robustness checks with two additional LLMs show that significant language effects persist, though directional patterns vary by model. These findings show that multilingual LLM safety judgments can produce unequal outcomes for semantically equivalent content.
