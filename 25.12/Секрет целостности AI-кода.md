---
tags:
- 2025/Dec
- ai/llm/training
- ai/software_architecture/design
- ai/machine_learning/scaling
- software_engineering/quality/architecture
author:
- Vladimir Ivanov
---
![[Pasted image 20251230151708.png]]

-----
## почему SQL-схема эффективнее функций при генерации сложных приложений
-----
Исследование методов обучения LLM работе с большими кодовыми базами (Repo-level Training, Long-Context SFT, Verifiable RL) выявило, что наиболее надежным связующим звеном логики для нейросетей являются не декларации функций, а структуры хранения данных.

Поскольку функции динамичны, а данные статичны и строги, для эффективного масштабирования AI-приложений рекомендуется строить архитектуру вокруг SQL-баз. 

Использование схемы `CREATE TABLE` в качестве фундамента позволяет активировать самый мощный паттерн интеграции кода у модели, предотвращая распад приложения на несвязанные фрагменты.

Самые важные источники из анализа
https://arxiv.org/abs/2502.10325
https://arxiv.org/abs/2402.19173
https://arxiv.org/abs/2406.11931
https://arxiv.org/abs/2403.05530
https://arxiv.org/abs/2305.20050
https://arxiv.org/abs/2402.19173

---
## Zero-links
---
- ....

---
## Links
---
- [Source](https://t.me/turboproject/2564)
