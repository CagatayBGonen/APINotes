# APINotes
This is my notes for API.

## API = "Application Programing Interface"
- No user interface
- APIs are used to communicate with other applications
  - Amazon need credit cart information from Visa
  - Thus, Amazon send request with its API and Visa get that request with its API
  - Then, Visa will sents respons With its API to Amazon's API. 
  - All works if API understand each other. 
- API should accept multiply format (JSON,XML,..).

### API --> Data Base
- insert / update / delete / read => API's Tasks / operations
- we should give URL to these operations (End Points).
- You can have many URL in your API because you can have variety of options for every tasks.
  - you can insert student, parents, grade, teacher to data base.
  - You can also upodate each of them. Thus, you will need many URL(End Points).

- As an API automation tester, you will check all endpoints if they are working as expected.
##
### HTTP Request Methods:
(In computer programming, create, read, update, and delete (CRUD) are the four basic operations of persistent storage.)
1) GET Method: It is for reading data from database (Read --> R in CRUD)
2) POST Method: It is for creating new data in database (Create --> C in CRUD)
3) PUT Method: It is for update in database in database (Update --> U in CRUD)
4) PATCH(Yama) Match: It is for partial update in database (Update --> U in CRUD)
5) DELETE Method: It is for deleting data from database (Delete --> D in CRUD)
   
### HTTP Status Code:
- 1XX : It means the request is received and the process is continuing
- 2XX : It means the action was successfully recieved, understood, and accepted
- 3XX : It means further actions must be taken to complete the request
- 4XX : It means the request contains incorrect syntax or cannot be fulfilled
- 5XX : It means server is down

Note: In API testing, status code must be tested first. If the status code is 2XX then you can test the details.
## POSTMAN
It is an application to test endpoints of an API manually
### REST ASSURED LIBRARY
It is an library in Java, it is used to test endpoints in automation
- We first use Postman manually, then according to result we write our automation script. 

