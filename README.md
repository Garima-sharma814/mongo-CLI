# db-CLI
Can't remember all the Commands to query your database?\
Or are you checking the documentation for every query you want to perform?

### This CLI is for you :)

db-CLI is a command-line interface that makes all the commands user friendly as possible. This CLI is easy to customize, as for now it is made for normal users database by default with Firstname, lastname.\
You can customize it as per your requirements by doing some minor changes in the code.

## How to use this CLI?
- Fork the repository;
- Open terminal, `cd` over to root directory i.e. type `cd ~`;
- Type `db-cli --version`. If you get the version as `1.0.0` or higher if new releases are already launched, you're all set and good to go.

## Can I customize the database schema?
- Yes, you can customize the structure of the database. But how? 
- Analyze your requirements, which type of database you're trying to create;
- How many fields are required for your DB, goto [models/dbdata.js](https://github.com/Garima-sharma814/db-CLI/blob/master/models/dbdata.js), and make changes in the fields according to the requirements;

### Don't want to use MongoDB locally?
- Using an online server to store your data? No worries goto [config/db.js](https://github.com/Garima-sharma814/db-CLI/blob/master/config/db.js) and change the connection string.

#### You can edit the code right from Github editor
- Goto the file you want to edit;
- Press . Now you can edit straight from Github.
