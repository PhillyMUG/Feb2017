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

## Follow along with Python ##
# Windows #
[Python Windows Install Link](http://www.howtogeek.com/197947/how-to-install-python-on-windows/) 

# MAC OS X #
[MAC Install LINK](http://docs.python-guide.org/en/latest/starting/install/osx/)


# Install PIP #
[Install PIP](https://bootstrap.pypa.io/get-pip.py)
