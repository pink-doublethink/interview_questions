---
tag: [Technology/React Difficulty/Base]
---
----
## Что такое компонент-переключатель (Switching Component)
----
> [!FAQ]- Ответ
> - Компонент переключатель - компонент, который рендерит один из нескольких компонентов. Это своеобразный реакт паттерн, который помогает реализовать удобный механиз отрисовки нескольких компонентов, на основании кого-либо условия.
> - Основная идея переключателя реализована в его структуре ввиде объекта, содержащий ключи и соотвествующие им компоненты. 
> - Получая пропсы, компонент переключателя считывает их значения ключа. После чего по этому значению возращает нужный компонент, который с помощью спреад опиратора передает пропсы. 