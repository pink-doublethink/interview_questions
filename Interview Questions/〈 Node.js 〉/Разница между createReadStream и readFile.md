----
## Разница между createReadStream и readFile?
----
> [!FAQ]- Show...
> Node.js предоставляет два метода для просмотра и запуска документов - **readFile** и **createReadStream**.
> - readFile это полностью буфиризированная процедура, которая работает только когда весь документ целиком помещается в барьер, а так же просматривается. Это процедура трубет БОЛЬШОГО объема памяти и выполняется очень медленно для больших документов. 
> - createReadStream использует частичную буфиризацию файла, в процессе которой документ разбивается на небольшие части, которые называются **чанки**. 
> После чего эти чанки частично передаются пользователю и в конечном итоге собираются в готовый целостный документ. Когда передача окончена, чанки удаляются из барьера. Поэтому метод createReadStream намного эфективнее при обработке больших документов. 
