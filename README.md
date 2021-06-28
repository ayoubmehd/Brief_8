# Brief 8 - comerce web site

## Instructions of installation

### Clone this repo
```copy
git clone https://github.com/ayoubmehd/brief_8
```

### Open PHPMyAdmin and create a database.
![Create daabase](/images/create_database.png)

### Import the *e_commerce_brief_8.sql* file using the PHPMyAdmin import tool
![Import database](/images/import_database.png)

### put the code directory in your server's root

### Open the wp-config.php and change: DB_NAME, DB_USER, and DB_PASSWORD to your own
![Change db credentials](/images/change_db_credentials.png)

### Back to the database, in the wp_options table change the options:
- siteurl
- home

to your site URL
![Change option](/images/change_options.png)

## Credentials
username: admin
password: 123456