---
tags:
- 2026/Jan
- research/tool-comparison/patching
- issues/kilo-code/stability
- research/data-formats/llm-performance
- issues/kilo-code/hallucinations
- guides/optimization/configuration
author:
- Vladimir Ivanov
---
-----
## почему нестандартные патчи ломают логику LLM в отличие от подхода Claude
-----
Сравнение показывает, что механизм наложения патчей в Kilo Code работает нестабильно из-за использования перегруженного маркерами формата, чуждого для большинства LLM.

В отличие от Claude Code, который применяет стандартный JSON (нативный для SFT-обучения моделей), Kilo Code использует "кулибинский" декларативный подход. 

Это несоответствие обучающей выборке провоцирует галлюцинации у нейросети и требует дополнительных настроек или отключения данного режима для корректной работы.

---
## Zero-links
---
- ....

---
## Links
---
- [Source](https://t.me/turboproject/2855)