---
tags:
- 2025/Nov
- cs/search_systems/architecture
- ai/neural_networks/analysis
- infrastructure/optimization/computing
- cs/algorithms/query_processing
author:
- Vladimir Ivanov
---
-----
##  Анатомия Perplexity
-----
Споры о качестве Perplexity объясняются архитектурой модели Sonar, основанной на дообученной Llama 3.3 (70B). 

Она превосходит конкурентов в поиске редких источников, но заметно уступает Gemini и Claude в глубокой интерпретации контекста. 

Для баланса Perplexity использует режим Auto: простые поисковые запросы (80-90%) обрабатывает быстрый и экономичный Sonar на чипах Cerebras, а сложные задачи, требующие понимания, перенаправляются на Claude Sonnet.


---
## Links
---
- [Source](https://t.me/turboproject/2383)
- https://www.perplexity.ai/hub/blog/meet-new-sonar
