### Domain Drive Designer - Tactical Patterns

<br>

Model driven designer is composted with
- Entiti
- Value Objects 
- Agregates

<br>

## Entities

The entities have, atributes, bahaviors and validations

Not have a repository methods or public setters availables

<br>

![image](https://user-images.githubusercontent.com/12099889/145570893-36ea3282-cb29-45a0-9bac-ddd4979f23fd.png)

<br>

![image](https://user-images.githubusercontent.com/12099889/145570905-162b1359-1095-4169-a1aa-75fb92a784af.png)

<br>

![image](https://user-images.githubusercontent.com/12099889/145570921-e230ec51-8cc0-41a4-af95-9a61947dac63.png)

<br>

## Value Objects

The value objects not is save on database

The value objects not have a unique identity

One Entity can have any Value objects, but a value objects never have a Entity

![image](https://user-images.githubusercontent.com/12099889/145571949-9b0836ca-1f0e-419e-bedc-0215ad03ad32.png)

<br>

![image](https://user-images.githubusercontent.com/12099889/145571968-1329b979-6ced-45c5-985b-1b8c4db21cb0.png)

<br>

For save on database, you use a method available in Value Objects

![image](https://user-images.githubusercontent.com/12099889/145572054-de845421-03ee-4842-8770-995d05f77e99.png)

<br>

## Aggregates

An aggregate may contains, Agregates, Entity and Value Objects

All changes in aggregates are save atomicaly

![image](https://user-images.githubusercontent.com/12099889/145573983-d76c8bd1-9133-42ad-8857-878117529f83.png)

<br>

![image](https://user-images.githubusercontent.com/12099889/145574004-3d57db47-8805-46fc-97dc-03db71c27a82.png)

<br>

![image](https://user-images.githubusercontent.com/12099889/145574741-b7031a21-ad8a-4c4a-adb3-b9457e5a4129.png)

<br>

![image](https://user-images.githubusercontent.com/12099889/145574795-079bec1b-3f96-4b22-a480-66b1bb2af757.png)






