# `Complete MongoDB Course:`
## `Introduction:`
### `What is Mongodb:`
- MongoDB is an Open-Sourse, Document-Oriented No-Sql Database Management System.
- [Mongodb](https://www.github.com/mongodb/mongo)
- Casendra, MySql, MongoDb, Oracle.
- A Database that Stores Information in a Document. 
- In the Form of .JSON Format.
- Designed for Flexibility, Scalability, and Performance in Handling Unstructure or Semi-Structure Data. 
### `More About Mongodb:`
- MongoDb Software -> 10gen -> MongoDb
- It was Created  by a company 10gen whisvh is now known as Mongodb, Inc. The company was founded by Eliot Horowitz and Dwight Merriman in 2007. the first version  of mongodb was release in 2009.  
- Hu**mongo**us - Mongos

|`SQl`|`NoSQl`|
|---|-----|
|SQL Database are Relational Databases.| NoSql Databsae are Non-Relational Databases.|
|They use Structured tables to Store data in rows and columns.|Theey Provide Flexibility in data Storage, allowing  varied data types and Structure.|
|Sutable for applications with well defined schemas and fixed data structures.|Ideal For Applications with Dynamic or evolving Data Models.|
|E-Commarce Platform, Hr Management etc.|Content Management System (CMS), Social Media Platforms, Gaming etc.|
|Examples: MySql, PostgreSQL, Oracle.|Examples: MongoDb, CAssendra, Redies|
- SQl: Ingormation, Rows, Columns, Tables, Databases, Fix ROws & Columns - .sql
- NoSQl: Collection: Students, 2-Documents, Embbeded Documents, Flexible - .json
- Inside One Collections, We can have Multiple Documents.

### `Mongodb Teminologies:`
- `Database` - Multiple `Collections` - Multiple `Documents` (Schemaless)

### `Key Features of Mongodb:`
- Flexible Schemaless Design:
    - Mongodb allows dynamic, Schemaless data Structures.
    - Easily Accommodate Changing data requirements.
- Scalability and Performance:
    - Horizontal Scaling Supports large Datasets and High traffic.
    - Optimize read and Write Operations for fast Performance.
    - Document Oriented Storage
- Dynamic Queries:
    - Rich query language with support for complex queries. 
    - utilize index to speedup queryexecution.
- Aggregation Framework (Inbult Functions): 
    - Perform advanced data transformations and analysis.(avg() - E-Commarce 5-Star Rating Review System)
    - Process data using multiple pipeline stages.   
- Open Source and Community: (Copy and Create your Own Database, Expert Suggest Changes)
    - Mongodb is Open Source with a Vibrant Community.
    - Regular Updates, Improvements, and Support.
### `How Mongodb Works:`
- Frontend: Html, CSS, JS, React.js, Next.Js.
- Backend: Node.js, Express.js, Next.js, Python.
- Database: Mongodb Server, Storage Engine (WiredTiger or MMAPV1-❌), Read & Write Data Files operations on Database  
### `JSON VS BSON:`
- json-> .json Format, Easy to READ & WRITE | bson-> .byte Binary Format, Not Easy to Read & Write. 
- In MongoDb, We Write in Json Format only but behind the scenes data is Stored in BSON (Binary JSON) Format, A Binary representation of JSON.
- By Utilizing Bson, Mongodb can achive Higher read  and Write Speeds, reduced Storage Requirements, and improved data manipulation capabibilities making  it well-suited for handling large and complex datasets while maintaining performance effeciency.
### `Installing Mongodb:`
- [MongodB Community & Server](https://www.mongodb.com/try/download/community)
- [MongodB Shell & Playground](https://www.mongodb.com/try/download/shell)
- [MongodB Database Tools](https://www.mongodb.com/try/download/database-tools)
### `MAnaging Database In Mongodb:`
- Creating | Deleting Databases
- Creating | Deleting Collections 
### `Managing Databases & Collections:`
```json
show dbs;
use <database_name>;
db.dropDatabase();

show Collections;
db.createCollection("<collection_name>");
db.<collection_name>.drop();
```
### `MongoDb Databases & Collections Commands:`
```json
show dbs;
admin      40.00 KiB
config     72.00 KiB
local     112.00 KiB
testapp1   96.00 KiB

show databases;
admin      40.00 KiB
config     72.00 KiB
local     112.00 KiB
testapp1   96.00 KiB

use students;
switched to db students
// You Won't see a adatabase listed in the output of the show dbs command until that database contain at least one collection with data in it.

show collections;

db.createCollection("data");
{ ok: 1 }

show collections;
data

show databases;
admin      40.00 KiB
config    108.00 KiB
local     112.00 KiB
students    8.00 KiB
testapp1   96.00 KiB

db.data.drop();
true

show collections;

db.dropDatabase();
{ ok: 1, dropped: 'students' }

show databases;
admin      40.00 KiB
config    108.00 KiB
local     112.00 KiB
testapp1   96.00 KiB
```



















































































- Delete ```node_modules``` Before Uploding on github.
- Download Project in your pc:
    - Intialise ```node_modules``` in your project by using ```npm install``` command:
    - This will install ```mongoose``` in your dependancies in ```package.json```:
- Download and Install MongoDb and It Will Automatically Start Your Server:
    1. [MongodB Community & Server](https://www.mongodb.com/try/download/community)
    2. [MongodB Shell & Playground](https://www.mongodb.com/try/download/shell)
    3. [MongodB Database Tools](https://www.mongodb.com/try/download/database-tools)