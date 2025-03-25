# Security and Authentication in MongoDB on Windows

## Introduction
Security in the network and electronic world is a today standard. The multiple databases available have or must have a security feature, MongoDB is not the exception.

This is a documentation of the completion of the [Laboratory](https://drive.google.com/file/d/1dG9ne1fEfwhPbPnFe3X4J-dNrHQt7dWE/view?pli=1.md), from the "Fundamentals of Non Relational Databases" course, that has the same title as this documentation.


## Content
The original order of steps in the laboratory where reordered for a better navigation and learning.

Personally, the best way to go through this documentation is in this order:

1. [Create Users](CreateUsers.md).
2. [Enable Authentication](EnableAuthentication.md).
3. [SSL Configuration](SSLConfiguration.md).
4. [MongoDB Compass Authentication](MongoDBCompass.md).

It important to know that the **SSL Configuration** did not work as intended, its just the steps made until an error appear.


## Mongo Configuration File
You can view the content of the [Mongo.cfg file](Mongocfg_file.md), this if you want to use the MongoDB configuration used for this laboratory.


## End Note
Enabling and using security and authentication in MongoDB is a excelent choice and practice. It lets you share your database with other people without worring for your data, and generates a secure connection to your database, this secures the data from networks attackers.

