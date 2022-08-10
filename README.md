# Postman

## Тестирование API

**API** — это интерфейс прикладного программирования , или программный интерфейс приложения, с помощью которого одна программа может взаимодействовать с другим. API позволяет передавать информацию из одной программы в другой, минуя интерфейс взаимодействия с пользователем.

**Как это работает?** представить, что вы сидите в ресторане, выбирает блюдо в меню. Подходит официант, и вы производите заказ. Официант передаёт ваш заказ на кухню, там происходит волшебство, и через Французское время перед вами появилось готовое блюдо. API работает по такому же принципу, как и ваш запрос, передаёт информацию о системе, решает её и возвращает ответ.

**Какие бывают? API** может быть внутренним, индивидуальным — когда программные компоненты покрываются и используются внутри системы. Может быть, публичным — в случае, когда он предоставляет пользователям другие возможности или программа получает информацию, которую можно интегрировать в свои приложения.

Для программ общения между собой, их API необходимо построить по единому стандарту. Одним из них является REST — стандарт архитектуры приложений и сайтов, использующий протокол HTTP . Особенность REST в том, что сервер не запоминает состояние пользователя между запросами. Идентифицирующими словами, идентификация пользователя (авторизационный токен) и все параметры выполнения операции передаются в каждом запросе. Этот крайне близкий подход прост и удобен, что почти возвращает всех.

**Стратегия тестирования API**

***Стратегия тестирования*** - это высокоуровневое описание устойчивого к тестированию, из которого впоследствии может быть составлен подробный план тестирования с редко встречающимися тестами и тестами. Наша первая задача — это функциональное тестирование, чтобы убедиться, что API работает правильно.

Основными задачами функционального тестирования являются API :

уверенность, что реализация API работает корректно, как и ожидалось - без ошибок;
выявлено, что реализация API работает в соответствии со спецификацией безопасности (которая позже становится нашей документацией по API );
регрессий между написанным кодом(слиянием) и релизом.