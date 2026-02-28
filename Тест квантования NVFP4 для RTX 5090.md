---
tags:
- 2026/Jan
- ai/models/analysis
- ai/optimization/quantization
- hardware/gpu/compatibility
- ai/optimization/evaluation
author:
- Vladimir Ivanov
---
-----
## компромисс между качеством и объемом памяти 
-----
 Обнаружена модель в формате NVFP4 объемом 20 Гб, которая помещается в память RTX 5090. Изначальное предположение о использовании качественного метода «сэндвич» (смешанная точность) не подтвердилось: проверка выявила «любительское» тотальное квантование всех весов, кроме слоев Embeddings и Output. 
 
 Несмотря на это, модель останется работоспособной, так как более профессиональная версия «сэндвич» могла бы превысить лимит видеопамяти.

https://huggingface.co/GadflyII/GLM-4.7-Flash-NVFP4

---
## Zero-links
---
- ....

---
## Links
---
- [Source](https://t.me/turboproject/2907)