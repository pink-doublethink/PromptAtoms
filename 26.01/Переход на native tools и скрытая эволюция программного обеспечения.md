---
tags:
- 2026/Jan
- ai/agents/benchmarking
- ai/architecture/tool-use
- ai/theory/limitations
- software/evolution/encapsulation
author:
- Vladimir Ivanov
---
-----
## переход на native tools и скрытая эволюция программного обеспечения
-----
Автор исследует причины, по которым агент Claude Code успешнее справляется с накладыванием патчей, чем Kilo Code. 

Анализ показал, что Claude Code перешел на использование режима «native tools», что минимизирует синтаксические ошибки инструментов. Хотя тесты (в частности, Berkley) демонстрируют, что этот подход не является универсальным решением для повышения общего IQ модели, в ряде специфических задач он дает значительное преимущество.

Главный вывод: даже если для пользователя софт выглядит неизменным, его внутренняя архитектура может кардинально обновляться всего за несколько месяцев.

https://github.com/x1xhlol/system-prompts-and-models-of-ai-tools/blob/main/Anthropic/Claude%20Code/Tools.json

---
## Zero-links
---
- ....

---
## Links
---
- [Source](https://t.me/turboproject/2854)