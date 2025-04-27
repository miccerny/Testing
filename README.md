# Testování databáze studentů přes REST API
 
## Popis
Testování Rest-API v metodách GET, POST a DELETE

## Nástroje
- Postman -> použití metod GET, POST, DELETE a další
- MySQL -> ověření studentů v databázi

## API Endpoints
http://database.stedro.com:8080/api/v1/students/

### GET /students
Získá seznam všech studentů

#### Screenshot testu
![](https://github.com/miccerny/Testing/blob/3b5d695045410f437de2dd7da9e82f80f58421da/GetMetoda.PNG)

### POST /students
Přidá nového studenta

#### Parametry:
Name, Lastname, email a age

#### Příklad:

### POST 
http://database.stedro.com:8080/api/v1/students/  -> již nefunkční databáze
JSON:  
{
"firstName": "6541916",  
"lastName": "Carl",  
"age": 9,  
"email": "asdasd@mail.com"  
}

##### Screenshot testu
![](https://github.com/miccerny/Testing/blob/eca6de8ace913cf02fc0a31149bdff09c9d46d61/PostMetoda.PNG)


### DELETE /students/
Smaže studenta podle ID

#### Příklad:
DELETE http://database.stedro.com:8080/api/v1/students/1 -> již nefunkční databáze

![](https://github.com/miccerny/Testing/blob/eca6de8ace913cf02fc0a31149bdff09c9d46d61/DeleteMetoda.PNG)





