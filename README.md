Setup of test database

```
$> psql
username=# CREATE DATABASE "bookmark_manager_test";
username=# \c bookmark_manager_test 
username=# CREATE TABLE bookmarks(id SERIAL PRIMARY KEY, url VARCHAR(60));
```
