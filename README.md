# nodeauth
This is user login system on Node.js and MongoDB. As node.js authentication middleware I used Passport. For hashing password used BCrypt.

How to use

git clone

and run node.js server (for example): node server.js

Then run database, (for example, for Windows OS) mongod --storageEngine=mmapv1 --dbpath C:\mongodb\bin

Then open http://localhost:3000/ and you can see user login system. First you may register, then you can login and see main page (members area)
