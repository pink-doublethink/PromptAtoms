---
tags:
- 2025/Nov
- computing/hpc/ai-generation
- hardware/gpu/nvidia-50-series
- ai/architecture/data-formats
- ai/algorithms/attention-mechanisms
author:
- Vladimir Ivanov
---
-----
## Революция FP4 на RTX 5090
-----
Репозиторий реализует поддержку формата FP4 для видеокарты RTX 5090 через SageAttention3, что обеспечивает 5-кратное ускорение по сравнению с FlashAttention2 (FP16) и производительность в 1038 TOPS. 

Реальные тесты генерации видео (HunyuanVideo, CogVideoX) показывают прирост скорости в 2.4–3 раза без потери качества благодаря сложной интерполяции. 

Несмотря на сырость программных библиотек, 50-я серия NVIDIA становится безальтернативным выбором для задач AI-генерации, делая остальные GPU устаревшими для этой ниши.

---
## Zero-links
---
- ....

---
## Links
---
- [Source](https://t.me/turboproject/2480)
- https://github.com/thu-ml/SageAttention
