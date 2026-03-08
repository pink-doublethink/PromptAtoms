---
tags:
- 2026/Feb
- software/lm_studio/api
- ai/protocols/mcp
- software/lm_studio/performance
- ai/infrastructure/benchmarking
- hardware/architecture/optimization
- hardware/gpu/egpu
author:
- Vladimir Ivanov
---
![[Pasted image 20260205230322.png]]

-----
## Поддержка MCP и техническое превосходство скорости над vLLM 
-----
LM Studio получил обновление Rest API до v1, что обеспечивает поддержку протокола MCP для простой интеграции локальных ИИ-агентов.

Технический анализ показывает, что в однопользовательском режиме LM Studio работает быстрее серверных аналогов (например, vLLM) за счет отсутствия «лишних» оптимизаций под многопользовательскую нагрузку и минимизации обмена данными между CPU и GPU, что особенно заметно при использовании внешних видеокарт.

https://lmstudio.ai/docs/developer/core/mcp

---
## Zero-links
---
- ....

---
## Links
---
- [Source](https://t.me/turboproject/3074)