fonline-json
============

FOnline JSON module


Installation
-------------

1. Copy all src/*.fos files into your FOnline server scripts directory.
2. In the scripts directory, edit scripts.cfg file by addding the json module to server, client and mapper:

 ```
@ server module json
@ client module json
@ mapper module json
 ```
3. If you use FOnline revision 399 or earlier (the most notable example is FOnline: 2238), uncomment this line in json_h.fos:

 ```
// #define _JSON_REV_PRE400
 ```
In the future a single merged json.fos will be available, so only 2 files will be needed, json.fos and json_h.fos.


Documentation
-------------

Not available yet. For now you can check the poems.fos example in the test directory.


Missing features
----------------

\u escape code in JSON strings isn't implemented yet (the character encoded in the escape code will be skipped).
