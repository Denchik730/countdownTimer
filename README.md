# Таймер обратного отсчета
------
## Описание:
Данный функционал решает реализует таймер обратного отсчета на веб странице

### Инструкция  по использованию::
Вызываем функцию setClock с двумя аргументами:
1) Родительский блок таймера, включающий в себя блоки для разных единиц отсчета
2) Дата окончания отсчета
### Техники и технологии:
Функционал обновления таймера (потраченного времени) реализуется при помощи timeInterval, и останавливается когда общая разница между текщуей и датой окончания становится равно нулю

