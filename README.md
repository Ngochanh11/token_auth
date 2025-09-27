5. token_auth

a. go to profile

Vào postman chọn phương thức get và nhập url: http://localhost:3000/api/auth/profile

chonj Body -> raw(json) va nhap {"username": "admin", "password": "12345"}  =>Send

<img width="1607" height="915" alt="image" src="https://github.com/user-attachments/assets/d4373d12-685f-4a37-8d77-0ea559fe9eef" />

b. register

Vào postman chọn phương thức post và nhập url: http://localhost:3000/api/auth/register

chonj Body -> raw(json) va nhap {"username": "admin", "password": "12345", "email": "huynhthingochanh9a3@gmail.com"}  =>Send

<img width="1614" height="875" alt="image" src="https://github.com/user-attachments/assets/32cc23d5-d9fd-4da1-9c91-e1200374b135" />

Check database

<img width="1248" height="993" alt="image" src="https://github.com/user-attachments/assets/4d841b34-32b5-463b-8462-2c39e3d0ea3d" />

c. login

Vào postman chọn phương thức post và nhập url: http://localhost:3000/api/auth/login

Chọn Body -> raw(json) va nhập {"username": "admin", "password": "12345", "email": "huynhthingochanh9a3@gmail.com"}  =>Send

<img width="1602" height="903" alt="image" src="https://github.com/user-attachments/assets/b00434bc-3b13-4f1c-b1e9-3b004d482fe1" />

Copy token to acces resource later.

d. Go to profile with token

Mở postman chọn phương thức GET và nhập url: http://localhost:3000/api/auth/profile

Chọn Authorization , tại mục Auth type chọn Bearer Token và nhập token đã copy từ login bên trên => Send

<img width="1516" height="897" alt="image" src="https://github.com/user-attachments/assets/c2430ba8-2d2f-474e-bbb9-b277de836278" />

