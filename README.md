# 😃 php-crud

**Step 01** <br>
to see this project online, import file `php_crud.sql` on your phpmyadmin <br>
or you can also make new database by yourself and use this code to make table :

```
CREATE TABLE `crud` (
  `id` int(255) NOT NULL AUTO_INCREMENT,
  `first_name` varchar(255) NOT NULL,
  `last_name` varchar(255) NOT NULL,
  `email` varchar(255) NOT NULL,
  `gender` varchar(255) NOT NULL,
  PRIMARY KEY (`id`)
)
```

**Step 02** <br>
Download the above files. Create a folder named crud inside htdocs folder in xampp directory. Finally, copy the crud folder inside htdocs folder. Now, visit [localhost/crud](http://localhost/crud) in your browser and you should see the application.
