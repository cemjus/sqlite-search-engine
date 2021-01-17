# WEB INTERFACE FOR SQLITE ENGINE
Provides a solution for storing and searching in JSON data using an inverted index.
  - adding documents
  - reading documents
  - updating documents
  - removing documents
  - document search

### Features to do:
- adding JSON documents
- browsing documents
- ability to edit or delete certain document
 - search in documents where:
    - the VALUE for the given KEY field matches the given value.
    - The VALUE for the given KEY field does not match the given value.
    - The field matches one of the specified values.
    - the VALUE for the given KEY field is in the given range.
    - the VALUE for the given KEY field is not in the given range.
    - the (KEY/VALUE/PATH/ANY) field with a given value exists 
    - the (KEY/VALUE/PATH/ANY) field with a given value does not exist.



### Installation
- Backend
    - run BackendApplication.java
    - Swagger: http://localhost:1111/swagger-ui.html

- Frontend
    - npm start
    - http://localhost:3000/