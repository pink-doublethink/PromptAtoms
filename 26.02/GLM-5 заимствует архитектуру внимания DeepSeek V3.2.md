---
tags:
- 2026/Feb
- ml/architecture/adaptation
- ml/transformers/sparse-attention
- ml/llm/context-management
- ai/models/glm-strategy
author:
- Vladimir Ivanov
---
![[Pasted image 20260209154034.png]]

-----
## GLM-5 заимствует архитектуру внимания DeepSeek V3.2, отказываясь от классики Gemini 
-----
В репозиториях GLM на GitHub обнаружены изменения для версии GLM-5, указывающие на копирование механизма разреженного внимания (Sparse Attention) из DeepSeek V3.2 (DSA). 

В отличие от метода Big Bird (Gemini), использующего фиксированные скользящие окна и якорные токены, DSA применяет динамический отбор релевантных токенов через сверхбыстрый индексатор (Lightning Indexer). Это позволяет гибко работать с контекстом и ключевыми словами, хотя и требует специфического обучения для удержания последовательностей. 

Таким образом, GLM продолжает агрессивную стратегию заимствования удачных архитектурных решений у конкурентов, таких как Anthropic и DeepSeek.

https://arxiv.org/html/2512.02556v1

---
## Zero-links
---
- ....

---
## Links
---
- [Source](https://t.me/turboproject/3124)