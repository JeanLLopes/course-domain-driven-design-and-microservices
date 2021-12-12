### Events Driven Architecture and Domain Events

**EDA**: Event Driven Architecture

<br>

![image](https://user-images.githubusercontent.com/12099889/145731671-e09a7f78-23b8-4e4e-8adf-0af14d64a5f1.png)

<br>

Event messages may contains _Meta data_ or _State data_

- **State data**
  - Is a complete data with all informations about event, example:
    - Event CustomerCreated: (Id, Name, Surname, Address, ...)         


- **Meta data**
  - Is a basic data with about event, example:
    - Event CustomerCreated: (Id)]
    - In this case, when consulme the event need coonsult a API or service, if need more infomations about new customer   

<br>

![image](https://user-images.githubusercontent.com/12099889/145731924-455ee9af-ef29-45b6-b921-fd88ed557981.png)
