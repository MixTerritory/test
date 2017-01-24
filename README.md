1. [Auth](#auth)
    1.1. [User login](#user-login)

## Auth
#### User login

   request:
   ```
   [POST] /auth/login

   form parameters:
       email - user email
       password - user password
   ```

   response:
   ```
   {
     "token": "3kn4rk3j2n423n4nfk23n434m..."
     "landlordId": "7aa98630-d355-11e6-a271-7907a449581a",
     "firstName": "f1",
     "lastName": "f2",
     "email": "test@mail.com"
   }
   ```
