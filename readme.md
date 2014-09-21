re-working through 
http://cwbuecheler.com/web/tutorials/2013/node-express-mongo/

stopping at: 
  -----
  We're all set. Save that file, and let's restart our node server. Remember how to do that? Go to your command prompt, head for C:\node\nodetest1\ and ctrl-c to kill your server if it's still running from way back before. Then type:
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