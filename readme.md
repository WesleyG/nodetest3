re-working through 
http://cwbuecheler.com/web/tutorials/2013/node-express-mongo/

stopping at: 
  -----
  We are officially reading and writing from a MongoDB database using Node.js, Express, and Jade. You are now what the kids call a "full stack" developer (probably not a GOOD one, just yet, but I didn't promise that).
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