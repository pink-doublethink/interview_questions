----
## Что такое редьюсер (Reducer)?
----
> [!FAQ]- Ответ
> - **Редюсер** - это чистая функция, определяющая изменение состояния приложения. Она использует опирации для определения характера изменений. 
> - Redux управляет состоянием приложения с помощью единственного хранилища. Так что они действуют согласовано. Изменения состояния зависит от действий пользователя или сетевых запросов. 
> - Если состоянием приложения управляется Redux, то изменения происходят в редюсере. И это едиственное место где происходит изменение состоянием.
> - Редюсер использует текущие состояние приложения и опирацию для определения нового состояния. Редюсер принимает два аргумента - текущие состояние и экшен. 
> - Экшен это объект представляет из себя объект, который с помощью типа описывает происходящие изменения. И, если у экшена есть свойство payloat, то через него экшен передает в редюсер данные для изменения состояния.