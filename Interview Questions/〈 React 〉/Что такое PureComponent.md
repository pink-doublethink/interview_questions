---
tags:
- Technology/React 
- Difficulty/Base
---
----
## Что такое Pure Component?
----
> [!FAQ]- Show...
> - React Component не реализует ShouldComponent apdate
> - React PureComponent реализует  ShouldComponent apdate поверхностным сравнением пропсов и состояния. 
> - Если метод рендора реакт компонент всегда рендерит одинаковый результат при одних и тех же промисах и состояниях
> - PureComponent не подойдет, если пропсы или состояния имеют сложную структуру, потому что тогда рендер может и прозойти когда он действительно нужен.