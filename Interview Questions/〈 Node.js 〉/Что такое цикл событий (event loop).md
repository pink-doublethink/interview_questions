----
## Что такое цикл событий (event loop)?
----
> [!FAQ]- Show...
> - Посколько Node.ks однапоточен, поток выпонения не должен блокироваться, чтобы поток не тратил слишком много времени для выполнения задачи. 
> - В одну единицу времени может выполняться только одна опирация. Цикл событий отвечает за включение этого не блокирующего поведения. 
> - Работа цикла событий планировать отложенные задачи, использующие поток приложения. 
> - Следует помнить, что Node.js использует callback или функции обратного вызова для своей работы. Они возращаются асинхронными функциями, когда их задача завершена. 
> - Подобно событию, создавшему задачу, событие так же выдается при заверщение задачи. Node.js добавляет событие, которое необходимо обработать в очередь событий. 
> - Цикл событий перебирает событие в очереди и планирует когда должны быть выполнены связанные функции обратного вызова. Координирование этого процесса и происходит в EventLoop. 
