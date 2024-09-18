[quieries.sql 2.0.txt](https://github.com/user-attachments/files/17049489/quieries.sql.2.0.txt)![photo_2024-09-18_21-37-32](https://github.com/user-attachments/assets/e437c11a-d37a-46a6-b0a7-6d24575b2d5e)

![photo_2024-09-18_21-37-43](https://github.com/user-attachments/assets/71234634-ab63-457f-a356-a80be0e4707f)

![photo_2024-09-18_21-37-53](https://github.com/user-attachments/assets/18ea8101-9f47-46e9-ad3a-4503b2b7cc47)

![photo_2024-09-18_21-38-09](https://github.com/user-attachments/assets/505d8356-85c3-4f73-bfb9-237c95eefb04)

[UplCREATE DATABASE my_database;

USE my_database;

CREATE TABLE users (
    id INT AUTO_INCREMENT PRIMARY KEY,
    name VARCHAR(255),
    age INT,
    email VARCHAR(255)
);

INSERT INTO users (name, age, email) VALUES
('John', 30, 'john@example.com'),
('Alice', 25, 'alice@example.com'),
('Bob', 35, 'bob@example.com');

SELECT * FROM users;

WasDELETE FROM users WHERE name = 'Bob';oading quieries.sql 2.0.txt…]()
