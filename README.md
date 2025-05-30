# PostgreSQL_Assignment
1. Create a new user (role) with a password:</br>
<pre>CREATE USER admin WITH PASSWORD 'your_secure_password';</pre>
2. Create a new database owned by this user:</br>
<pre>CREATE DATABASE university_db OWNER admin;</pre>
3. (Optional but good) Grant all privileges on this database to the new user:</br>
<pre>GRANT ALL PRIVILEGES ON DATABASE university_db TO admin;</pre>
![image](https://github.com/user-attachments/assets/2574e464-4371-413b-8f92-dde47f091a76)
 CREATE TABLE student</br>
![image](https://github.com/user-attachments/assets/3c75567b-ab51-4387-a401-75335dd9e5e9)
</br>
<pre>ALTER TABLE students</pre>
![image](https://github.com/user-attachments/assets/982a3ef2-8018-4002-87e7-e3394e20455d)</br>
![image](https://github.com/user-attachments/assets/37d6579e-d42a-44f6-8d2e-f9253f0470e2)
![image](https://github.com/user-attachments/assets/586887f4-ea1e-4e4f-aaae-e21af323727a)
![image](https://github.com/user-attachments/assets/16cc0e69-e457-451c-885c-3f06316f61d7)

</br>
</br>
<pre>INSERT INTO student</pre>

![image](https://github.com/user-attachments/assets/bf4c5ef7-1ee3-44e2-b93e-e4383f4c290a)
<pre>SELECT * FROM students;</pre>
![image](https://github.com/user-attachments/assets/20b334bf-6958-41cc-bf30-057efeba5529)
<pre>SELECT * FROM students WHERE first_name LIKE 'B%'OR first_name LIKE 'C%'</pre>
![image](https://github.com/user-attachments/assets/d53c9147-decc-49d1-9589-9e4f40926340)
<pre>UPDATE students SET dob = '2003-08-13'WHERE student_id = 2</pre>
![image](https://github.com/user-attachments/assets/505c2a8f-b005-4a2a-b15a-2e5d6c9c29c7)
<pre> ASE/DESC</pre>
![image](https://github.com/user-attachments/assets/2484cd89-2321-46dc-b62f-ad12a07c8ef1)
![image](https://github.com/user-attachments/assets/c88a5499-8395-44ad-b04c-2383b290b0f3)</bR>
 ORDER BY dob ASE</br>
![image](https://github.com/user-attachments/assets/38576e20-4299-41fb-ae43-91ec253ad151)</br>
 last_name DESC, first_name ASE</br>
![image](https://github.com/user-attachments/assets/77ab8cfb-5238-43ad-b190-b9cce6329642)
<pre> LIMIT </pre>
![image](https://github.com/user-attachments/assets/bc13f7e3-05a2-4cd1-ab0b-184cca9715c8)
![image](https://github.com/user-attachments/assets/4bf3ff17-9f89-4369-a783-2ef05765cd09)
![image](https://github.com/user-attachments/assets/a303ac9b-6b89-44cf-94cc-0fe556a27ced)
![image](https://github.com/user-attachments/assets/1af783b6-adbf-40bd-ab4c-1fc43dd75de2)
</br>
-----------------------------------------------------------------------------------------------------------------------------------------------</br>
![image](https://github.com/user-attachments/assets/dae01639-2ccb-4d83-8074-b069df6bc673)
![image](https://github.com/user-attachments/assets/926460b5-030b-4af3-874d-bf424a09d2f8)
![image](https://github.com/user-attachments/assets/8aec10f5-a985-4f49-b044-e951a368fbcc)
</br>
![image](https://github.com/user-attachments/assets/39c6e7f7-f012-4c7a-a7b1-34105538e165)

![image](https://github.com/user-attachments/assets/9c9db5ac-5238-4e95-9162-23b935bf5fb1)
<pre>GROUP BY</pre>
![image](https://github.com/user-attachments/assets/6d333682-8c1c-4f70-9f9c-5dea46e434b7)

![image](https://github.com/user-attachments/assets/153090ba-2e65-4eef-9bba-f1c611c405e1)

