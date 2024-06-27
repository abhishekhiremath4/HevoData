Welcome to the Hevo Data Assessment by Abhishek Hiremath (Dated 27th June '24)

Steps taken to complete the project are as below:
Step 1 - Download docker desktop from docker website, Pull the postgreSQL from the docker image
Step 2 - create the container start the postgreSQL
Step 3 - Type below command to start postgres from cmd
	execution code - docker exec -it postgres psql -U postgres
Step 4 - create the tables raw_orders,raw_customers, raw_payments and then import the csv data provided into the tables with the SQl queries attached file into GitHub Repo
	File name - Create tables.txt
Step 5 - Login to hevo test account account id - abhishek.hiremath@cloud.com
	pipeline details: Name - PostgreSQL Source - Position: Jun 26, 2024 21:18:54 IST, Seq No: 0/15A9C10
Step 6 - Connect the database host to the hevo account by entering the database username, password and database name.
	Note - I have established the connection from hevo to my database by using ngrok tunnel.
Step 7 - select the tables and further mention the schema and destination while creating the pipeline for data to get transfered.
	Snowflake database - Schema - PUBLIC.
Step 8 - Once the data is transfered to Snowflake, connect the dbt cloud to snowflake database with schema
	(Achieve this by entering valid credentials of snowflake account with proper privileges to the user)
Step 9 - Create a project in dbt cloud and execute the queryfile uploaded in the GitHub repo
	FileName - dbt_project code
Step 10 - output file has been uploaded to the GitHub repo
	FileName - csv.csv

Thankyou