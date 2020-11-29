# Cert_Keys
Java spring boot

Cert_Keys - Web-приложени по формированию CVCA сертификатов.
## Необходимые параметры по генерации самоподписного и связующего сертификата   (9 шт):
* Страна
* Имя УЦ
* Алгоритм шифрования
* Роль
* Тип
* Алгоритм подписи
* Дата начала действия сертификата
* Дата окончания действия сертификата
## Так же необходимо заполнение участников церемонии, которые включают в себя следующие параметры (6шт):
* Имя 
* Фамилия
* Отчество
* Орган 
* Позиция
* Причина

## Для реализации данного проекта необходимо
1. Развернуть БД (PostgraceSQL) - в данном приложении реализован принцип code first. Используются две таблицы(Сертификат, участники церемонии) с отношениями many-to-many.
2. Доделать Core. На данном этапе формируется сертификат с передаваемыми параметрами, далее необходимо реализовать передачу сертификата пользователю (клиенту) по необходимости.
### Все классы и функции названы в соответствии с выполняемыми функциями и т.д.

### Более подробные инструкции выполнения задачи находятся в файле: [CommandsToAssign](https://github.com/KevinPozitive/Cert_Keys/blob/master/CommandsToAssign)
