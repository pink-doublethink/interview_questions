---
tag: [Technology/React Difficulty/Base]
---
----
## Что такое предохранители (Error Boundaries)
----
> [!FAQ]- Ответ
> - Предохранители - это реакт компоненты, которые перехватывают любые ошибки, возникающие в дереве потомков. После чего выводят ошибку в консоль или показывают резервный UI вместо сломанного.
> - Предохранители перехватывают ошибки в методах жизненного цикла и в конструкторах любых дочерних компонентов. 
> - Предохранители не перехватыют сообщения в обработчках событий, в асинхронном коде, при SSR и при выбрасывание исключения в самом предохранители. 
> - Классовый компонент становиться предохранителям, когда в нем определяются методы **getDerivedStateFromError(1)** или **componentDidCatch(2)**. Оба служат для обработки ошибки, но задачи у них разные:
> 1. Первый используется для рендеринга запасного UI, после возникновения ошибки.
> 2. Второй используется для вывода ошибки в консоль 
