---
tags:
- 2025/Dec
- ai/llm/knowledge-retention
- ai/llm/hallucinations
- science/architecture/gpt
- aiprompt-engineering/optimization
author:
- Vladimir Ivanov
---
![[Pasted image 20251230152617.png]]

-----
## научное обоснование пользы «доменной активации» для борьбы с галлюцинациями
-----
В тексте разбирается исследование «Understanding LLM Behaviors via Compression», где галлюцинации нейросетей объясняются нехваткой весов для запоминания редких фактов. Ученые выявили иерархию хранения знаний в GPT: сначала определяется домен, затем факт, и только потом синтаксис. 

Это открытие научно подтверждает эффективность эмпирического метода «доменной активации» — явного указания предметной области в промпте, что помогает модели точнее фильтровать факты и избегать выдумок.

https://www.emergentmind.com/papers/2504.09597

---
## Zero-links
---
- ....

---
## Links
---
- [Source](https://t.me/turboproject/2596)
