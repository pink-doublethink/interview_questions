---
tag: [Technology/React Difficulty/Base]
---
----
## Что такое инверсия наследования (Inheritance Inversion)
----
> [!FAQ]- Ответ
> - Inheritance Inversion - это компонент высшего порядка. В нем возращается класс, расширяющий WrappedCompo net.
> ```javascript
> const inheritanceInversionHOC = (WrappedComponet) => {
> 	return class extedsWrappedComponet {
> 		render() {
> 			return super.render()
> 		}
> 	}
> }
> ```
> - Данная техника называется инверсией наследования, посколько вместо расширения класса усилителя с помощью WrappedComponet, последий сам пассивно расширяется. Эти отношения напоминают инверсию. 
> - Инверсия наследования предоставляет доступ HOCу к экзепляру класса WrappedComponet. Это в свою очередь позволяет использовать методы жизненного цикла, состояния, пропсы и рендер данного компонента.
> - Этот ХОК используют либо для перехвата рендера, либо для управления состоянием. 