# database-week4-.........
-- Question 1 🗑️
-- Drop an index named IdxPhone from the customers table
DROP INDEX IdxPhone ON customers;

-- Question 2 👤
-- Create a user named 'bob' with a secure password, restricted to localhost
CREATE USER 'bob'@'localhost' IDENTIFIED BY 'S$cu3r3!';

-- Question 3 🔑
-- Grant INSERT privilege to the user 'bob' on the salesDB database
GRANT INSERT ON salesDB.* TO 'bob'@'localhost';

-- Question 4 🔐
-- Change the password for the user 'bob' to a new secure one
ALTER USER 'bob'@'localhost' IDENTIFIED BY 'P$55!23';
