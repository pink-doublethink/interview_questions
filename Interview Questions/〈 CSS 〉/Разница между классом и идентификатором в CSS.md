---
tag: [Technology/CSS Difficulty/Base]
---
----
## Разница между классом и идентификатором в CSS?
----
> [!FAQ]- Ответ
> - К классам лучше добавлять стили, а к id - события в JS. Дело тут в том, что id должен быть уникальным, а класс может встречаться на странице много раз. 
> - Id у html элемента должен быть только один. В то время как классов на одном элементе может быть несколько. 
> - У id высокая специфичност, поэтому чтобы в дальнешем переопределить стиль нужно будет написать длинную цыпочку селекторов, что не очень удобно. 
