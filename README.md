# Messenger
User's messenger

User messenger Application

1) Create User 
  login
  pass
  name/ second name/ third name
  birthday
  registration date
  role

2) Servlet "/api/user/" POST
  2.1) Save user with "user" role
    login
    name/ second name/ third name
    birthday
  
3) Save user with "user" role

4) "admin" should be registered at start of app

5) Servlet "/api/login" POST
  login
  pass
  
6) Add to response attribute {user}

7) Create Messege
  send date
  from user
  to user
  text
  
8) Servlet "api/messege" 
  GET - A list of currency user will be shown
  POST - Send a message
    text
    to user
    

9) Servlet "/api/message" GET
  5.1) A list of messages will be shown
    From {user}
    To {user}
    
10) Create a listener that should read statistics

11) Servlet /api/admin/statistics GET
  Statistics will be shown
  
12) Add JSP for all content

13) Add Security filters
