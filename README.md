# Implement-DDD-with-PoEAA-Java
Samples to Implement 'Domain-Driven Design' with 'Patterns of Enterprise Application Architecture'

**PoEAA involved in this project:**

```
PoEAA
 |`-Domain Logic & DataSource
 |   |`-DomainModel
 |   |   |`-DataMapper
 |   |   |`-TableDataGateway
 |   |   |`-ActiveRecord
 |   |    `-RowDataGateway
 |    `-TransactionScript
 |       |`-RecordObject(*)
 |       |   |`-TableDataGateway
 |       |   |`-ActiveRecord
 |       |    `-RowDataGateway
 |        `-AnemicDomainModel(*)
 |           |`-DataMapper  
 |           |`-TableDataGateway
 |           |`-ActiveRecord
 |            `-RowDataGateway
  `-Supporting
     |`-Repository
     |`-NominalRepositorys(*)
     |`-DAO(*)
     |`-ServiceLayer
     |`-IdentityMap
     |`-UnitOfWork
     |`-PersistenceModel(*)
      `-CQRS(*)
```

**DDD patterns involved in this project:**

```
DDD Patterns
 |`-Modeling
 |   |`-Entity
 |   |`-ValueObject
 |   |`-Aggregate
 |   |`-Repository (= PoEAA: Repository)
 |    `-Factory
  `-LayerArchitecture
     |`-UserInterfaces
     |`-Application (= PoEAA: Service Layer)
     |`-Domain (= PoeAA: DomainModel)
      `-Infrastructure
```



2003/11/25 https://martinfowler.com/bliki/AnemicDomainModel.html
2005/12/15 https://www.iteye.com/topic/17579




