Project Description:
A basic password management that generates random passwords when given a username and URL. PBKDF2 will be used to derive the cypher key from the master password. The master password is EUID, and the same master password will be required for all operations. Passwords are encrypted and just one master password is required to access the "vault." The vault includes all passwords that have been saved. To generate, save, and query for new passwords, use a terminal interface. The encrypted passwords for a specific URL will be kept in. dat file format.

Tools: Python and PostgreSQL 

Libraries :
•	Argparse
•	os
•	Psycopg2
•	sql_statements
•	db_connect
•	Password_generator
•	master_password
•	hashlib
