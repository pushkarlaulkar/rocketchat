After deploying run below command in MongoDB container

`rs.initiate({"_id" : "rs0", "members" : [{"_id" : 0, "host" : "mongodb:27017", "priority" : 10}]})`
