---
aliases: 
- как малая модель раскрыла семантическую силу XML 
tags:
- 2025/Sep
- ai/embeddings/gemma
- ai/evaluation/benchmarking
- ai/applications/semantic_search
- ai/deployment/on_device_ml
- ai/embeddings/structured_data
author:
- Vladimir Ivanov
---
-----
##  Дело не в модели, а в XML 
-----
Google выпустила компактную модель эмбедингов EmbeddingGemma (300М), которая лидирует в бенчмарке MTEB для своего класса и может работать на маломощных устройствах без доступа к интернету. Несмотря на это, её качество уступает крупным моделям Gemini, так как она хуже справляется с семантическими обобщениями. 

Практический тест показал неожиданно высокую эффективность векторизации структурированных XML-графов, которые в семантическом поиске по коду часто оказываются релевантнее самого исходного кода.

---
## Zero-links
---
- [[0 ИИ-модели и системы]]
- [[0 Платформы, бенчмарки и стандарты]]
- [[0 Структуры данных и модели знаний]]
- [[0 Прикладные подходы и кейсы]]

---
## Links
---
- [Source](https://t.me/turboproject/2193)
- https://huggingface.co/blog/embeddinggemma
- https://huggingface.co/spaces/webml-community/semantic-galaxy