# cosmos-db-migrations
Migrations for Data Model changes for Cosmos DB



When you start using Cosmos DB for a while you will certainly have a need for migrating old data to new data, and other types of migrations.

On Entity Framework - there are Code First and DB migrations, but nothing like that exists for Cosmos. This project is about solving this problem.



## Console / Command Line

```
Update-Database
```

Will execute all pending migrations


```
Add-Migration
```

Will add new migration to your Migrations project



## App Startup

To run pending migrations on app startup add:


## Azure Pipelines or General Continuous integration

To run pending migrations as a part of rollout do:


## Status
We are already using this project internally but it is not quite ready for public consumption.
If you are interested in early version please contact us at:
eric@pandaflow.io
