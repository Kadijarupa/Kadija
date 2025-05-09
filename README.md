# PHP Login System with MySQL

## Setup Instructions

1. Create a MySQL database named `login_demo`.
2. Run this SQL to create the users table:

```sql
CREATE TABLE users (
  id INT AUTO_INCREMENT PRIMARY KEY,
  name VARCHAR(100),
  email VARCHAR(100) UNIQUE,
  password VARCHAR(255)
);
```

3. Run `insert_user.php` once to insert a sample user:
- Email: john@example.com
- Password: 12345

4. Open `index.html` in browser and use credentials above to log in.

Make sure XAMPP or another local server is running.