# Flat_File_SSIS
Open new project 
Go to Solution Explorer
create new SSIS package --->Right Click SSIS Package ----> new SSIS package
Name the SSIS Package.

1.create Data FLow and add source file (FLAT FILE)--set path
2.create Destination source OLE-DB 
3.open destination database -->create table schema that represents source headers as table headers -->Check if the 
table schema matches source records.
4.Get back to visual studio and check destination field and establish connection
5.Edit the destination OLE-DB for SQL server or any RDMS.
6.Create new server connection mentioning DB-SERVER name where database is created.
7.Check for delimiters, assign headers if flat file carries first row as headers.
8.Test Connection successful
9.Check mappings if they have been mapped perfectly.
10.Click OK
11.Now run SSIS package by clicking Start.
12.You can now check if the records has been updated successfully.
