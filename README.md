npm install express

1. simple_auth source code

a.node basic_auth.js

GET http://localhost:3000

Authorization -> Type : Basic Auth

Username: admin

Password: 12345

<img width="975" height="558" alt="image" src="https://github.com/user-attachments/assets/eb053a6f-c823-4895-8080-c59587817e4c" />


/public

<img width="975" height="691" alt="image" src="https://github.com/user-attachments/assets/212e5cbe-727e-4c04-a2f6-41d5e9c80f86" />

/secure

<img width="975" height="667" alt="image" src="https://github.com/user-attachments/assets/9441a3da-7c84-4b6a-88a3-9c46604ba517" />


b.node cookie_auth.js

POST http://localhost:3001/login
Body -> raw
{"username":"admin", "password":"12345"}

<img width="975" height="538" alt="image" src="https://github.com/user-attachments/assets/12ac933b-67d0-4074-a8c5-e56bac403aec" />

Show cookie in mongoDB

<img width="975" height="295" alt="image" src="https://github.com/user-attachments/assets/5a581adf-48f6-477a-96dd-e155bb0be2c6" />

/profile

<img width="968" height="751" alt="image" src="https://github.com/user-attachments/assets/f259bdc8-5e87-40d6-93d4-f0f76da3b7fd" />

/logout

<img width="926" height="759" alt="image" src="https://github.com/user-attachments/assets/662ca06b-b097-40a0-9cd7-68224debbd2e" />

check cookie in mongoDB

<img width="975" height="533" alt="image" src="https://github.com/user-attachments/assets/7b955bb5-3c23-4388-bc0e-5fafb4379658" />
