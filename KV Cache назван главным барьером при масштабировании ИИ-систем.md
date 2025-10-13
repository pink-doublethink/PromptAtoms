---
aliases: 
- Тирания первого промпта 
tags:
- 2025/Sep
- ai/scalability/multi_tenant
- ai_systems/engineering/challenges
- ai/performance/resource_management
- ai_systems/architecture/evolution
author:
- Vladimir Ivanov
---
-----
##  Тирания первого промпта
-----
При переходе от однопользовательских к многопользовательским ИИ-системам ключевой проблемой для разработчиков становится не вес моделей, а размер KV Cache. 

Наибольшая нагрузка на память происходит на этапе prefill, при обработке первоначального запроса, что является главным техническим барьером. Новые архитектуры, такие как Mamba, частично решают эту проблему.

---
## Zero-links
---
- [[0 Фундаментальные архитектуры и их компоненты]]
- [[0 Прикладные подходы и кейсы]]
- [[0 Внутренние процессы и состояния модели]]

---
## Links
---
- [Source](https://t.me/turboproject/2158)
- https://huggingface.co/spaces/gaunernst/kv-cache-calculator