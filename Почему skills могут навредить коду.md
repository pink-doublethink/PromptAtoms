---
tags:
- 2026/Jan
- LLL
- prompt_engineering/dynamic-prompts
- ai/prompt-engineering/benchmarking
- ai/llm-architecture/context-management
- ai/prompt-engineering/antipatterns
author:
- Vladimir Ivanov
---
-----
## Почему skills могут навредить коду, пока MCP незаметно «съедают» контекст
-----
Использование «skills» (динамических промптов) часто уступает статичным инструкциям, так как модель может упустить критические данные, например, API фреймворков. Автор советует использовать skills только для специфических практик, а общие протоколы оставлять в основном контексте, избегая излишнего дробления (over-engineering). 

Особое внимание уделяется парадоксу: пытаясь сэкономить место на описании инструментов, разработчики часто игнорируют, как MCP-серверы автоматически перегружают контекст огромными объемами технических деклараций. 

📎 https://vercel.com/blog/agents-md-outperforms-skills-in-our-agent-evals

---
## Zero-links
---
- ....

---
## Links
---
- [Source](https://t.me/turboproject/3002)