mongo-infrastructure
====================

Extensions for mongodb driver, infrastructure for mocking mongo objects

.sln file here: Infrastructure/Infrastructure.sln

nuget package: https://www.nuget.org/packages/MongoDbInfrastructure

====================

репозиторий включает в себя: 
- методы-расширения для более удобной работы со стандартным C# драйвером для mongoDB - так называемый синтаксический сахар;
- реализацию восстановления соединения с сервером mongoDB при обрыве связи;
- пример реализации удобной инфраструктуры, предоставляющей доступ к базам данных mongoDB и их коллекциям;
- пример создания и настройки mock'ов для объектов mongoDB в юнит тестах
