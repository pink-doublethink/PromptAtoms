---
tags:
- 2026/Feb
- devops/ai_infrastructure/technical_debt
- pkm/project_context/storage_strategy
- management/risk_mitigation/vendor_lock
- engineering/portability/architecture
author:
- Vladimir Ivanov
---
![[Pasted image 20260226130655.png]]

-----
## Опасность vendor lock и важность независимости от истории чата 
-----
Сокращённый текст: Ошибка зацикливания в Kilo Code связана с некорректным формированием запросов к Gemini и ChatGPT, что решается перезапуском сессии

Этот сбой иллюстрирует риски хранения контекста исключительно в истории чата: при наличии документации и семантической разметки в коде потеря переписки не критична. 

Автор предостерегает от жесткой привязки к конкретным вендорам (vendor lock), рекомендуя сохранять гибкость для быстрой миграции на более совершенные или стабильные инструменты.


---
## Zero-links
---
- 0 //
- 0 //
- 0 //

---
## Links
---
- [Source](https://t.me/turboproject/3402)