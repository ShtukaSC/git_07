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

Проект (
идентификатор (первичный ключ, serial)
название проекта (varchar(100))
Идентификатор сотрудника (внешний ключ, integer) ??


![image](https://github.com/user-attachments/assets/6411c7c9-d0a1-45d7-8f83-e2d859f4fa18)
![image](https://github.com/user-attachments/assets/558e290b-5919-4e91-8a77-902958669861)
![image](https://github.com/user-attachments/assets/9f2601dc-b7ee-4e26-81af-9fb448919fd7)
![image](https://github.com/user-attachments/assets/ea695689-f94a-4519-af77-dfecd78b85b0)
![image](https://github.com/user-attachments/assets/6f1b3521-fb65-484a-9e1c-0c764bf4cedf)
![image](https://github.com/user-attachments/assets/542b85b6-e141-45be-a965-747c2d0c23e4)
![image](https://github.com/user-attachments/assets/1f361968-59a2-485b-aa16-43e38fdded97)





