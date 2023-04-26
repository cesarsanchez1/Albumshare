NOTE: The #PASSWORD for the mysql database, uses a 'password.txt' file that app.py accesses to get 
        the password for the database. By doing this, we can use different passwords, specified by 
        password.txt without having to share our passwords.

	To run, make a password.txt file located in the same directory as the app.py file that has your DB's 
        password only (no new lines, spaces, characters etc). If you run into problems, 
		you can email me ( csanchez64@fordham.edu ), or you can always just change.
	the #PASSWORD in app.py manually.
	
	1. Open terminal
	2. install all necessary packages found in requirements.txt
	3. run schema.sql using MySQL Workbench
	4. open app.py using your favorite editor
	5. change the '#PASSWORD' in 'app.config['MYSQL_DATABASE_PASSWORD'] = '#PASSWORD' to your root password in MySQL
	6. back to the terminal, run the app 'python app.py runserver'
	7. open your browser, and open the local website 'localhost:5000'