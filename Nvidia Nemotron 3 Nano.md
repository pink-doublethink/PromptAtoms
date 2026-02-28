---
tags:
- 2025/Dec
- ai/models/slm
- ai/engineering/optimization
- ai/research/architectures
- software/devops/deployment
author:
- Vladimir Ivanov
---
-----
## доступная мощь для RTX 5080 и программные барьеры для массового пользователя
-----
Nvidia выпустила модель Nemotron 3 Nano на базе MoE, которая сопоставима по результатам с Qwen3 30B, но работает в 2-3 раза быстрее. 

Благодаря гибридной архитектуре (трансформеры и Mamba) модель экономично расходует память и способна работать на видеокартах уровня RTX 5080. 

Несмотря на техническое превосходство формата NVFP4 над конкурентами, его массовое внедрение тормозится отсутствием простых решений для Windows, так как инженеры отдают приоритет сложным запускам через Docker в WSL.

https://x.com/ArtificialAnlys/status/2000602570092675402

---
## Zero-links
---
- ....

---
## Links
---
- [Source](https://t.me/turboproject/2603)
