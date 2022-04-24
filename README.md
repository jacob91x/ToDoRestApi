REST api for ToDo application.

Structure of ToDo's:
- id,
- title,
- description,
- complete %
- done status.

Missed requirements:
- ServiceStack v. >=5.8,
- data persisted in db using ORM (postgresql/mysql/mariadb) - database in memory,
- xunit for unit/integration tests,

Tested in Postman.

JSON sample of ToDo's: 
{
    "ExpiryDate": "2022-04-24T23:30:00.000Z",
    "Title":"ToDo",
    "Description": "Create ToDo Rest Api",
    "CompleteLevel": 40,
    "IsDone":false
}