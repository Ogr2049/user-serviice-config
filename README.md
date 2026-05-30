User Service Config

Внешний репозиторий конфигураций для микросервисной платформы User Service. Реализует паттерн External Configuration - отделение кода приложения от настроек.

Использование: Конфигурации загружаются автоматически через Spring Cloud Config Server.

Основной проект: https://github.com/Ogr2049/Seven-Task_Ig


Структура:
1)config/user-service-module.yml - настройки основного сервиса.

2)config/api-gateway.yml - настройки API Gateway.

3)config/discovery-server.yml - настройки Eureka Server.