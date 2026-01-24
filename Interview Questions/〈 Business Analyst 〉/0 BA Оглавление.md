----
## BA: Оглавление
---
----
### Base
----
- [[Какие типы диаграмм использовали]]
- [[Какие виды требований вы знаете]]
- [[Как происходит сбор требований с заказчика]]
- [[Что такое Use Case]]
- [[Что такое User Story]]
- [[Чем Use Case отличается от User Story]]
- [[Что такое сервис-ориентированная архитектура]]
- [[Что это такое SOAP и где применяется]]
- [[Расскажите как вы видите процесс разработки]]
- [[Какие виды состояний НТТР бывают]]
- [[Что такое топик и раздел]]
- [[Брокеры сообщений и устройство Kafka]]
- [[Какие плюсы и минусы микросервисов вы знаете]]
- [[Что такое идемпотентность]]
- [[Какие брокеры сообщений знаешь и чем они отличаются]]
- [[Триггеры в БД что это такое, какой контекст использования]]
- [[Как реализуется связь многие ко многим]]
- [[Расскажите НТТР лучше применять глаголы и можно ли удалить что-нибудь в GET запросе]]
- [[Что такое гарантированная доставка сообщений И какими механизмами ее можно обеспечить]]
----
### Intermediate
---
- [[Как вы описываете REST API в OpenAPI YAML на основе бизнес-контекста]]
- [[Как вы строите ERD на основе требований]]
- [[Какие типы интеграций вы реализовывали (sync,async)]]
- [[Как вы декомпозируете систему на сервисы]]
- [[Как вы встраиваете кеш (Redis) в архитектуру для снижения latency]]
- [[Чем ресурс отличается от endpoint при проектировании REST]]
- [[Как вы валидируете сообщения по схеме]]
- [[Какие механизмы (JWT, OAuth2) вы применяли]]
- [[Чем User Task отличается от Manual Task в BPMN-модели]]
- [[В каких частях HTTP-запроса допустимо передавать данные и почему]]
- [[Из каких частей состоит HTTP-запрос и ответ]]
- [[Как вы формулируете профессиональную мотивацию перехода, опираясь на рост сложности задач и ответственности]]
- [[В какой кросс-функциональной команде вы работали и как распределялись зоны ответственности]]
- [[В каком формате (User Story, Job Story,  SRS) вы фиксируете требования и какие обязательные поля используете]]
- [[Как вы документируете API по OpenAPI - структура, эндпоинты, схемы, ошибки]]
- [[Как вы выделяете bounded context и агрегаты при проектировании доменной модели]]
- [[Как вы используете Swagger UI и Postman в жизненном цикле API]]
- [[Какие типы диаграмм (ERD, Sequence, BPMN, C4) вы применяли и для каких задач]]
- [[Как вы структурируете проектную документацию в Confluence или аналогах]]
- [[Какие инструменты вы применяете для контрактного тестирования и автогенерации документации]]
- [[В каком сценарии вы выберете GraphQL вместо REST, и как решаете вопросы N+1 и кеширования]]
- [[Как в рамках аналитической платформы вы спроектируете data mart для витрины продаж]]
- [[Какие классы SQL-задач вы решали в продакшене (оконные функции, CTE, оптимизация планов выполнения), и в каких СУБД]]
- [[Какие типы JOIN вы применяете при проектировании запросов к реляционной БД, и в каких сценариях (INNER, LEFT, RIGHT, FULL, CROSS)]]
- [[В каком аналитическом сценарии вы выберете UNION ALL вместо UNION, и как это влияет на производительность и семантику результата]]
- [[Как вы выбираете между CHAR и VARCHAR при проектировании схемы БД с учётом хранения, индексации и частоты обновлений]]
- [[Какие стратегии масштабирования вы применяли для backend-систем (scale-up, scale-out), и какими инфраструктурными средствами они реализованы]]
- [[В каком сценарии высокой нагрузки вы предпочтёте горизонтальное масштабирование сервиса, и какие ограничения есть у вертикального]]
- [[Как вы спроектируете репликацию БД для read-heavy API (master–replica), и какой тип согласованности выберете]]
- [[Какой shard key вы выберете для пользовательского сервиса с 10+ млн записей, и как это отразится на запросах и транзакциях]]
- [[Какой shard key вы выберете для пользовательского сервиса с 10 млн записей, и как это отразится на запросах и транзакциях]]
- [[В каком случае вы примените table partitioning (range,list,hash) и как это влияет на планы выполнения запросов]]
- [[Какие NFR вы формализуете для высоконагруженного API (latency, availability, throughput) и как они измеряются]]
- [[Как эти механизмы разделяются в REST-сервисе с OAuth2, OpenID Connect]]
----
### Advanced
---
- Text
- Text 


1. How would you design a data mart for a sales dashboard within an analytical platform (grain, sources, update frequency), and what SQL query (SELECT with aggregations) would you use to retrieve KPIs for a given period?
2. What types of SQL tasks have you solved in production (window functions, CTEs, execution plan optimization), and in which DBMS (PostgreSQL/MySQL/Oracle)?
3. What types of JOINs do you use when designing queries for a relational database, and in what scenarios (INNER, LEFT, RIGHT, FULL, CROSS)?
4. In what analytical scenario would you choose UNION ALL instead of UNION, and how does this affect performance and the semantics of the result?
5. How do you choose between CHAR and VARCHAR when designing a database schema, considering storage, indexing, and update frequency?
6. What scaling strategies have you used for backend systems (scale-up, scale-out), and what infrastructure tools were used to implement them?
7. In what high-load scenario would you prefer horizontal scaling of a service, and what are the limitations of vertical scaling?
8. How would you design database replication for a read-heavy API (master-replica), and what type of consistency would you choose?
9. What shard key would you choose for a user service with 10+ million records, and how would this affect queries and transactions?
10. In what case would you apply table partitioning (range/list/hash) and how does this affect query execution plans?
11. What NFRs (Non-Functional Requirements) do you formalize for a high-load API (latency, availability, throughput) and how are they measured?
12. How are these mechanisms separated in a REST service with OAuth2/OpenID Connect?