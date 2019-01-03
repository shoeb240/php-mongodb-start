# php-mongodb-start
Mongodb in php for beginners

## Install MongoDb Server
Download [MongoDb](https://www.mongodb.com/download-center/community) and follow installation steps [here](https://docs.mongodb.com/manual/administration/install-community/)

For my Mac I did following
```
brew update
brew install mongodb
sudo mkdir -p /data/db
sudo chmod -R 777 /data/db
```

Now run MongoDb
```
mongod
```

## MongoDb PHP Extension
Download MongoDb php driver [here](https://pecl.php.net/package/mongodb) and put it in php/ext folder and add extenstion in php.ini
```
extension=php_mongodb.dll
```

## MongoDb PHP Library
Install MongoDb PHP library using composer in your project folder
```
composer require "mongodb/mongodb=^1.0.0"
```
