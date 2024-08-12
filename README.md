# microservices

Всем доброго дня:) \
Первое, что необходимо решить - целесообразность данного занятия и готовность коллектива к этому. Имею в виду, что прежде чем внедрять в свою инфру микросервисную архитектуру - нужно определиться, что есть сильная команда разработчиков, которая и на монолитной инфре хорошо себя показывает, а также команда DevOps инженеров, которая по скиллам способна вывести данный проект. Еще надо смотреть на отсутствие техдолга, проблем во взаимодействии между бизнесом и так далее.
Плюсы микросервисов:
  1) Различные технологии для различных сервисов и проектов
  2) Устойчивость к ошибкам
  3) Масштабируемость (в том числе автоскейлинг)
  4) Простота развертывания продукта на уже имеющейся инфре (в понятии стендов - тест, прод, клоны и т.п.)
  5) Возможность не вести постоянную документацию, ведь все и так описано в манифестах
Минусы микросервисов:
  1) Сложность развертывания, так как продукт не из самых легких
  2) Сложность в разработке ПО (микросервисы усложняют взаимодействие ПО и систем, на которых он крутится)
  3) Сложность поддержки - сама инфраструктура в плане технологий сложнее в осознании и в ведении для новых специалистов

В целом, из преимуществ и недостатков это все, пожалуй, что могу отметить. В данном случае я бы порекомендовал вводить микросервисную архитектуру, так как это повысит стабильность выхода релизов, а соответственно и пользователи будут довольны. Также система уже существует, ее можно спокойно поделить на микросервисы, нежели чем продумывать все заранее.
