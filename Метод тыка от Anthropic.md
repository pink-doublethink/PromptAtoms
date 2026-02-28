---
tags:
- 2025/Dec
- ai/machine_learning/rl
- software_eng/debugging/ai_assisted
- software_eng/testing/methodology
- ai/prompt_engineering/best_practices
author:
- Vladimir Ivanov
---
-----
## почему для фикса багов Claude нужны repro-скрипты, а не обычные тесты 
-----
Anthropic раскрыла детали RL-обучения модели Claude: вместо классического TDD нейросеть использует «динамические тесты» в виде скриптов для воспроизведения ошибок (repro-scripts). 

Эти скрипты служат «песочницей», где ИИ итеративно диагностирует проблему и проверяет гипотезы. 

Хотя автор текста предпочитает Log Driven Development (анализ больших логов), для эффективного исправления сложных багов в Claude пользователям рекомендуется запрашивать именно создание диагностических скриптов-песочниц, так как это соответствует нативной методологии обучения модели.

https://www.anthropic.com/engineering/swe-bench-sonnet

---
## Zero-links
---
- ....

---
## Links
---
- [Source](https://t.me/turboproject/2657)
