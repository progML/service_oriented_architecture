# Лабораторная работа №2

**Доработать веб-сервис и клиентское приложение из лабораторной работы #1 следующим образом:**

- Отрефакторить сервис из лабораторной работы #1, переписав его на фреймворке Spring MVC REST с сохранением функциональности и API.
- Набор функций, реализуемых сервисом, изменяться не должен!
- Развернуть переработанный сервис на сервере приложений Payara.
- Разработать новый сервис, вызывающий API существующего.
- Новый сервис должен быть разработан на базе Spring MVC REST и развёрнут на сервере приложений Tomcat.
- Разработать клиентское приложение, позволяющее протестировать API нового сервиса.
- Доступ к обоим сервисам должен быть реализован с по протоколу https с самоподписанным сертификатом сервера. Доступ к сервисам посредством http без шифрования должен быть запрещён.


**Новый сервис должен располагаться на URL /killer и реализовывать следующие операции:**

- /team/create/id/name : создать новую команду героев и сохранить данные о ней в БД)
- /team/{team-id}/add/hero-id : добавить героя в команду

# Результат

![alt-текст](https://github.com/progML/service_oriented_architecture/blob/master/lab_2/result/result.gif)
