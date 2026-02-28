---
tags:
- 2026/Feb
- software-engineering/paradigms/agentic-era
- ai/llm/interaction-design
- ai/architecture/kv-cache
- management/methodology/ai-development
author:
- Vladimir Ivanov
---
-----
## почему технические ограничения LLM требуют перехода от Scrum к Waterfall и Agentic Engineering
-----
В контексте выхода GLM-5 и смены парадигмы с «Vibe Coding» на «Agentic Engineering» актуализировалась проблема методов работы с LLM. Опираясь на данные Microsoft Research, автор утверждает, что итеративная подача контекста (аналог Scrum) снижает эффективность нейросетей. 

Причина кроется в механике KV Cache: «замерзание семантики» не позволяет исправлять старые вектора, вынуждая модель создавать ресурсоемкие вектора-корректоры, что повышает риск галлюцинаций. 

Эффективным подходом объявляется «Waterfall»: единовременная загрузка полного технического задания и контекста, позволяющая ИИ-агенту автономно и последовательно «компилировать» задачу в код.

https://arxiv.org/abs/2505.06120

---
## Zero-links
---
- 0 //
- 0 //
- 0 //

---
## Links
---
- [Source](https://t.me/turboproject/3298)