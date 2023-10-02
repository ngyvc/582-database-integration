# Integrate the database in php

Note: **Read carefully** any errors when you **access the php page directly**.

## Add connection information in `php/db_connect.php`

Open [`php/db_connect.php`](template/php/db_connect.php) and change the `$user`, `$pass` and `$db` information to match the information from the [setup](SETUP.md) page.

`$db` refers to the selected database name in plesk.
`$user` refers to the user name of the selected database in plesk.
`$pass` refers to the user password of the selected database in plesk.

## Edit select information in `php/select.php`

When reading (not writing) from the database, you will have to execute a `SELECT` command.
Open [`php/select.php`](template/php/select.php), there will be 3 spots to change information.

1. On `line 13`, edit `SELECT` statement to reference the table you wish to select.
2. On `line 27`, make sure you **match the number of `$field` variables** to match the number of expected fields from the database.
3. On `line 32`, edit the output array varibales to **match the number of `$field` variables** and the **expected output names** (names on the left side of the `=>`, the right side ones doesn't matter as much, it just have to match the same ones from step 2).

## Edit insert information in `php/insert.php`

When writing to the database, you will have to execute an `INSERT` command.
Open [`php/insert.php`](template/php/insert.php), there will be 3 spots to change information.

1. On `line 13`, edit `INSERT` statement to reference the table you wish to select.
2. On the same line, edit **the names and number of `$field` variables** to match the field names ***from the database*** to be inserted to.
3. On `line 22`, update the **bind parameter types and variables** to match the field names ***from the form*** that is sending the data to this page.
