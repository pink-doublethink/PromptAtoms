---
tags:
- 2025/Dec
- ai/machine_learning/optimization
- ai/deep_learning/attention_mechanisms
- ai/machine_learning/reinforcement_learning
- ai/llm/context_management
- productivity/strategy/problem_solving
author:
- Vladimir Ivanov
---
-----
## почему «блочная» декомпозиция задач побеждает работу с огромным контекстом
-----
Опыт DeepSeek показал неэффективность обучения нейросетей на сверхбольшом контексте (Sparse Attention) по сравнению с традиционным подходом (Full Attention) на блоках около 4000 токенов. 

Основная проблема заключается в «размытии оценки» при Reinforcement Learning: модели сложно определить, за какие именно действия в огромном контексте она получила награду. Технически обучение малыми блоками также выигрывает в скорости («брутфорс» циклов обучения). 

Практический вывод для пользователей — необходимость декомпозиции больших задач на иерархию мелких подзадач, что соответствует логике обучения LLM и повышает качество генерации.

https://huggingface.co/deepseek-ai/DeepSeek-V3.2-Exp

---
## Zero-links
---
- ....

---
## Links
---
- [Source](https://t.me/turboproject/2563)
