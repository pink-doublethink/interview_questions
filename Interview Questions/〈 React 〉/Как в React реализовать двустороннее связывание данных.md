---
tag: [Technology/React Difficulty/Base]
---
----
## Как в React реализовать двустороннее связывание данных
----
> [!FAQ]- Ответ
> - Данные, которые изменяют представление, обновляют состояние. И наоборот - данные состояние обновляют данные в представление. Компоненты, в которых реализована такая связь, называются управляемыми.
> - Выполнить такую связку можно с помощью setState в классовом компоненте или хука useState в функциональном. 
> - Данные попадающие на UI, поподают в State и обновляют его. Обновление State, вызывает обновление на UI.