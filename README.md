# apmorgan-bank-validation
I am working on a script realted to validation of bank data
* We would declare all the variables with key values.
* All the secrets would be feteched from the key vault.
* we would be creating a mount point for the ADLS gen 2 location.
* We would be creating the JDBC connection to the Azure SQL. And fetch the table which contains valid schema format for all the tables.
* Finally we would be define a logic which checks for duplicates in the source file and also checks the data column has valid format or not. If any of the above condition fails. The notebook exits with the error message.
* If the above conditions are passed the notebooks moves to the staging folder from landing folder. If the above fails the notebooks moves to the rejected folder from landing folder.
