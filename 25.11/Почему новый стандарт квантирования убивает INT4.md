---
tags:
- 2025/Nov
- ai/optimization/nvfp4
- hardware/gpu/blackwell
- ai/models/optimization
- data/infrastructure/ai-efficiency
- industry/standards/computing
author:
- Vladimir Ivanov
---
![[Pasted image 20251130163818.png]]

-----
## Почему новый стандарт квантирования убивает INT4 и как это работает на чипах Blackwell
-----
Технология NVFP4 от Nvidia вытесняет традиционный формат INT4 благодаря более эффективной схеме хранения данных, использующей нелинейные интервалы (знак, экспонента, мантисса). Это решает проблему потери точности на малых и сверхкрупных весах, позволяя моделям уровня FLUX и DeepSeek сохранять качество после сжатия

Вычисления NVFP4 нативно поддерживаются архитектурой Blackwell (RTX 50x), обеспечивая кратный прирост производительности по сравнению с FP8 и FP16. 

Несмотря на сложность калибровки, требующую итеративного тестирования ошибок, и необходимость использования специализированных библиотек или Docker-контейнеров, индустрия (включая xAI) активно переходит на этот стандарт, прогнозируя скорый отказ от INT4 в течение ближайших 6-8 месяцев.

---
## Zero-links
---
- ....

---
## Links
---
- [Source](https://t.me/turboproject/2485)
- https://developer.nvidia.com/blog/introducing-nvfp4-for-efficient-and-accurate-low-precision-inference/
