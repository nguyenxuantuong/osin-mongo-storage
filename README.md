# osin-mongo-storage
mongo storage for OAuth2 go osin server

This package implements the storage interface for [OSIN](https://github.com/RangelReale/osin) with [MongoDB](http://www.mongodb.org/) using [mgo](http://labix.org/mgo).
It's similar to this implementation [Osin storage](https://github.com/martint17r/osin-mongo-storage) but work with the latest changes of Osin (client was implemented as interface instead of struct).

##How to use
Just initialize it with mgo session and mongo dbname and use it like the default osin storage.