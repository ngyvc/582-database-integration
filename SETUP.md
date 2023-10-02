# Setup a database on plesk

Simple database integration example

## Log-in on plesk and select databases.

![Alt text](<img/Screenshot 2023-10-01 at 3.45.21 PM.jpg>)

## Click on `+ Add Database`.

![Alt text](<img/Screenshot 2023-10-01 at 3.46.04 PM.jpg>)

## Set your `Database name`, `Database user name` and `Password`.

![Alt text](<img/Screenshot 2023-10-01 at 3.46.32 PM.jpg>)

## Once your database is created, you can select `phpMyAdmin`.

![Alt text](<img/Screenshot 2023-10-01 at 3.46.45 PM.jpg>)

## Create a database inside phpMyAdmin

## Once you opened phpMyAdmin, you should see `Create new table` option, add the `Table name` and change the `Number of columns` to match the different sets of data. (You can always add more later).

![Alt text](<img/Screenshot 2023-10-01 at 3.47.09 PM.jpg>)

## Add the `Name` of your fields and select the `type`.

![Alt text](<img/Screenshot 2023-10-01 at 3.47.36 PM.jpg>)

## Note: `ID` should always be your first field and it should be of type `INT` (integer) and make sure you `check` the `A_I` (auto increment) option to set the ID as your `PRIMARY` key.

![Alt text](<img/Screenshot 2023-10-01 at 3.48.02 PM.jpg>)

## For any fields that needs alphabet characters, chose `VARCHAR` (variable characters). 

![Alt text](<img/Screenshot 2023-10-01 at 3.48.51 PM.jpg>)

## Change the length for each of the fields, default for `INT` with `PRIMARY` key will automatically be set to `11` in length.

![Alt text](<img/Screenshot 2023-10-01 at 3.49.31 PM.jpg>)

## Click on `Save` to add the table, or `Preview SQL` to preview your command.

![Alt text](<img/Screenshot 2023-10-01 at 3.49.42 PM.jpg>)

![Alt text](<img/Screenshot 2023-10-01 at 3.49.51 PM.jpg>)

## Once you have created your table, you will be presented with your table's structure.

![Alt text](<img/Screenshot 2023-10-01 at 3.50.08 PM.jpg>)

## You can select your new table on the left side menu and you will see the `Browser` tab open with the default `SELECT *` command.

![Alt text](<img/Screenshot 2023-10-01 at 3.51.01 PM.jpg>)

![Alt text](<img/Screenshot 2023-10-01 at 4.01.03 PM.jpg>)

## You can select the `Insert` tab.

![Alt text](<img/Screenshot 2023-10-01 at 4.01.21 PM.jpg>)

## Add a new entry, make sure you ***do not*** add anything to the ID field, or else your entries will have duplicate primary key. Click `Go` when you are ready to add an entry.

![Alt text](<img/Screenshot 2023-10-01 at 4.02.02 PM.jpg>)

## Once the entry is added, you will see `1 row inserted` and the new row `id` along with the SQL command that was just executed.

![Alt text](<img/Screenshot 2023-10-01 at 4.02.14 PM.jpg>)

## If you click on `Go` again, it will execute the code again.

![Alt text](<img/Screenshot 2023-10-01 at 4.02.18 PM.jpg>)

## If you did, you will see the execution message again.

![Alt text](<img/Screenshot 2023-10-01 at 4.02.27 PM.jpg>)

## Click on `Browse` to see the results.

<!-- ![Alt text](<img/Screenshot 2023-10-01 at 4.02.35 PM.jpg>) -->

![Alt text](<img/Screenshot 2023-10-01 at 4.02.48 PM.jpg>)
