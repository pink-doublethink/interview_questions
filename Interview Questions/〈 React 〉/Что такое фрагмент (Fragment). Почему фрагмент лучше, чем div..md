---
tag: [Technology/React Difficulty/Base]
---
----
## Что такое фрагмент (Fragment). Почему фрагмент лучше, чем div.
----
> [!FAQ]- Ответ
> - Fragment - это распространный паттерн реакт, который используется в компонентах, возращающий несколько элементов. 
> - Fragment позволяет формировать дочерные элементы, без создания DOM узлов. Это специальный тэг JSX, который не отрисовывает в DOM дереве.
> -  Fragment приемущество фрагмент перед пустыми оборочивающими скобками:
> 1. Фрагмент использует меньше памяти. Это положительно сказывается в разветленных DOM элементах.
> 2. Некоторые механизмы CSS(Flexbox, Grid) используют срез родитель/ребенок. Поэтому создание допольнительных div может повредить макету страницы
> 3. Удобнее пользоваться инспектором DOM, т.к. он фрагмент не будет на нем отображаться. 

