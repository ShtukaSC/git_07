# git_07
Сотрудники (
идентификатор (первичный ключ, serial)
фамилия (varchar (50))
имя (varchar(50))
отчество (varchar(50))
название проекта (varchar(100)) ?
идентификатор должности (внешний ключ, integer)
идентификатор подразделения (внешний ключ, integer)

Оклад (
идентификатор (первичный ключ, serial)
размер оклада (numeric (10,2))

Должность (
идентификатор (первичный ключ, serial)
название должности (varchar(50))

Тип подразделения (
идентификатор (первичный ключ, serial)
название должности (varchar(50))

Структурное подразделение (
идентификатор (первичный ключ, serial)
название должности (varchar(50))
идентификатор вышестоящего подразделения (внешний ключ, integer) ?

Адрес (
идентификатор (первичный ключ, serial)
название проекта (varchar(100))
город (varchar(50))
улица (varchar(50))
дом (varchar(50))

![image](https://github.com/user-attachments/assets/ae8a31b4-3d81-4ac8-8518-a1a0c3fbcd5a)



Проект (
идентификатор (первичный ключ, serial)
название проекта (varchar(100))
Идентификатор сотрудника (внешний ключ, integer) ??
