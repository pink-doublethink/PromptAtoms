---
tags:
- 2026/Jan
- software/methodology/dbc
- engineering/ai-development/evolution
- cs/formal-methods/hoare-logic
- software-engineering/ai-development/specifications
- ml/training/sft
author:
- Vladimir Ivanov
---
![[Pasted image 20260203210708.png]]

-----
## почему «микро-ТЗ» и Docstrings вытеснили логику Хоара в эпоху нейросетей 
-----
Современные AI-контракты, несмотря на схожесть по месту размещения и цели (предъявление требований к коду) с классическим контрактным программированием (DbC) 1980-х, имеют принципиально иную природу.

Классический подход базировался на строгой логике Хоара (предусловие/постусловие) для верификации, что оказалось неэффективным для обучения LLM, так как ведет к «подгонке» решений. Вместо этого AI-контракты эволюционировали из Python Docstrings и методологии Spec-Driven Development, представляя собой семантические «микро-ТЗ». 

Нейросети понимают такой формат благодаря этапу SFT (Supervised Fine-Tuning) и обучению на парах «задание — код», а не на жестких тестовых условиях.


---
## Zero-links
---
- ....

---
## Links
---
- [Source](https://t.me/turboproject/3015)