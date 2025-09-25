npm install express

1. simple_auth source code

a.node basic_auth.js

GET http://localhost:3000

Authorization -> Type : Basic Auth

Username: admin

Password: 12345

![1758800949554](image/README/1758800949554.png)

2.node cookie_auth.js

POST http://localhost:3001/login
Body -> raw
{"username":"admin", "password":"12345"}
![1758801395656](image/README/1758801395656.png)

Show cookie in mongoDB

![1758801608509](image/README/1758801608509.png)
