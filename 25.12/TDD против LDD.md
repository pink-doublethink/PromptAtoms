---
tags:
- 2025/Dec
- software_engineering/methodology
- software_testing/ai_integration
- productivity/ai/llm_optimization
- software_engineering/devops/log_analysis
author:
- Vladimir Ivanov
---
-----
## почему «человеческие» паттерны разработки неэффективны для ИИ 
-----
Автор критикует использование классического Test Driven Development (TDD) при разработке с помощью ИИ, ссылаясь на пример инструмента для Gemini CLI.

Аргументируется, что LLM не проходили специального обучения (SFT) для написания тестов до кода, из-за чего справляются с этим хуже, чем с генерацией самого кода. 

В качестве более эффективной альтернативы предлагается Log Driven Development (LDD), где тесты пишутся постфактум, а ИИ используется для анализа огромных массивов логов — задача, с которой модели справляются лучше людей благодаря механизму Attention.

https://github.com/gemini-cli-extensions/conductor/blob/main/templates/workflow.md

---
## Zero-links
---
- ....

---
## Links
---
- [Source](https://t.me/turboproject/2652)
