# Feb2017
Code Examples and Presentation for PhillyMUG February 2017

## Installing MongoDB ##
```curl -O https://fastdl.mongodb.org/osx/mongodb-osx-x86_64-3.2.6.tgz```

## Simple Blog Application ##
```
use blog
db.users.insert( { "username" : "mlynn", "password" : "top secret", "lang" : "EN" } )
db.users.findOne()
{
    "_id" : ObjectId("573afff65ee4be80385332a7"),
    "username" : "mlynn",
    "password" : "top secret",
    "lang" : "EN"
}
```
