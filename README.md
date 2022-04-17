show dbs /  show databases :: Show All Databases

db :: Show Current Database

use restapi :: Create Or Switch Database

db.dropDatabase() :: drop data base

db.createCollection('product') :: Create Table

show collections :: Show Tables

db.product.drop() :: "DELETE" Delete Table

db.product.insertOne({name:"apple",price:10}) :: "INSERT" Insert Record In table

db.product.find() :: "SELECT"  Show Records In Table

db.product.find({price:10}) :: "Where Query"  Where Query Or Find Or Filter Data In Table 

db.product.findOne({price:"10"}) :: SELECT OR FIND ONLY ONE RECORD RETURN

db.product.insertMany({name:"mango",price:30},{name:"banana",price:20}) :: MULTIPLE INSERT

db.product.find().pretty() :: Pretty Print Record Display
