Data Types:
char- character data type fixed length/values 1-8000
varchar-character data type,length varies
varchar(max)- when size of colmn data varies and may exceed 8000
nchar-character data type /fixed length stringdata/values 1-4000/column size consistent
nvarchar-character/variable length string data/2 GB max storage size/column size varies
nvarchar(max)-use when data entries vary & stringlength may exceed 4000 byte pairs
binary- fixed length binary-data/length of n bytes/n=1-8000
varbinary-variable length binary data/1-8000
can convert string datatype to binary/varbinary data type -char,varchar,nchar,nvarchar,text,ntext,image
ntext,text,image- to store large Unicode/nonUnicode/binary data, will be removed in future versions of SQL Server-
Constraints:
NOT NULL - Ensures that a column cannot have a NULL value
UNIQUE - Ensures that all values in a column are different
PRIMARY KEY - A combination of a NOT NULL and UNIQUE. Uniquely identifies each row in a table
FOREIGN KEY - Uniquely identifies a row/record in another table
CHECK - Ensures that all values in a column satisfies a specific condition
DEFAULT - Sets a default value for a column when no value is specified
INDEX - Used to create and retrieve data from the database very quickly

