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

### POST /students
Přidá nového studenta

#### Parametry:
Name, Lastname, email a age

#### Příklad:
POST http://database.stedro.com:8080/api/v1/students/  
JSON:  
{
"firstName": "IN",  
"lastName": "",  
"age":8,  
"email": "kovac.mail.com"  
}

### DELETE /students/
Smaže studenta podle ID

#### Příklad:
DELETE http://database.stedro.com:8080/api/v1/students/1

### Kontakty
Pokud máte otázky, prosím kontaktujte mě na cerny.michal93@gmail.com


