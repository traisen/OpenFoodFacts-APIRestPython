# Open Food Facts API Rest Python #

This README would normally document whatever steps are necessary to get your application up and running.

### What is this repository for? ###

* Quick summary
* Version

## Setup for localhost

* Install python 3
* Install mongodb
* Install pip
* Install requirements : 
    $ pip install -r requirements.txt
* Download the database from : http://world.openfoodfacts.org/data/openfoodfacts-mongodbdump.tar.gz
* Import to local mongodb : 
    $ mongorestore -d off -c products /foldertodump/products.bson
* Launch api : 
    $ python3 runApiRESTServer.py 
* That's all !

## Documentation

## Creators

**Scot Scriven**
- <https://github.com/itchix>

## Copyright and license

    Copyright 2015 Scriven Scot
    
    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at
    
        http://www.apache.org/licenses/LICENSE-2.0
    
    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
