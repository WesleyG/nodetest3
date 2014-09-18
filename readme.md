re-working through 
http://cwbuecheler.com/web/tutorials/2013/node-express-mongo/

stopping at: 
  -----
  Now that we've got one record, let's add a a couple more. In your Mongo console, type the following:
  -----

MongoDB

  enter into command prompt:

  $ mongod --dbpath /Users/wes/node_projects/nodetest3/data

  they when it's done enter into command prompt:

  $ mongo

  then in mongo console enter

  > use nodetest3

  to enter data:

  > db.usercollection.insert({ "username" : "testuser1", "email" : "testuser1@testdomain.com" })

  to view data:

  > db.usercollection.find().pretty()