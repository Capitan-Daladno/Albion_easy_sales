Albion Easy Sales
========================


Приложение создано для упрощения продаж в компьютерной игре Albion Online. <br/>
Тестовый вариант задеплоин на [heroku](https://albion-easy-sales.herokuapp.com/events/ "Открыть приложение на heroku")

Сценарий создания события (продавец):
---------------------
Продавец (seller) создает событие (event) и добавляет в него участников (user).

Сценарий завершения продажи (продавец):
---------------------
После завершения продажи, продавец вносит сумму в поле event_money и меняет статус события.<br/>
В итоге: участникам на баланс прибавляются средства.

Сценарий получения средств (участник):
--------------------
Участник открывает сайт и видит сколько денег у него на счету.<br/>
Обращается к продавцу или казначею, чтобы получить средства.
Получает средства.

Сценарий выдачи средств (продавец):
------------------
К продавцу обращается участник.<br/>
Продавец выдает средства участнику и обнуляет баланс участника на сайте.
