---
tag: [Technology/React Difficulty/Base]
---
----
## Как React обрабатывает, или ограничивает использование пропсов определенного типа
----
> [!FAQ]- Ответ
> - **PropTypes** - это один из вариантов перехвата ошибок, связанных с неправильными типа пропсов. С помощью ключивого слова isRequred он позволяет помечать пропсы как обязательные.
> - А компонент с помощью **defoltProps** определяет их значение по умолчанию.
> - PropTypes - определяет тип пропса. Каждый раз когда через пропс передается какое-либо значение, он проверяется на правельный тип. Если будет передан не правильный тип, то в консоль будет выведено сообщение об ошибке. Это гарантирует, что компоненты получают пропсы с верными типами.