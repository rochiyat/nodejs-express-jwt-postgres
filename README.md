# simple-jwt-nodejs
Simple JWT Node JS, versi sederhana implementasi JWT pada nodejs dengan menggunakan library jsonwebtoken

# Tools Project
- nodejs versi berapa aja
- visual studio code
- postman

# Running Project
node index.js

# Test Project
Buka postman atau command line unix
## curl --location --request POST 'http://localhost:9000/user/generateToken'
## curl --location 'http://localhost:9000/user/validateToken' \
--header 'token_header_key: eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ0aW1lIjoxNjg0NTU4OTY5MDUwLCJ1c2VySWQiOiJyb2NoaXlhdCIsImV4cGlyZXNJbiI6IjI0aCIsImlhdCI6MTY4NDU1ODk2OX0.Na-jwThU9FYcWTcAlrBTd44XfUCt019B7HH1umf1ev4'
_ubah token dengan token response dari API generateToken_
## curl --location 'http://localhost:9000/user/verifyAuthToken' \
--header 'Authorization: Barier eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ0aW1lIjoxNjg0NTU4OTY5MDUwLCJ1c2VySWQiOiJyb2NoaXlhdCIsImV4cGlyZXNJbiI6IjI0aCIsImlhdCI6MTY4NDU1ODk2OX0.Na-jwThU9FYcWTcAlrBTd44XfUCt019B7HH1umf1ev4'
_ubah token dengan token response dari API generateToken_
