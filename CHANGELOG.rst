Version 1.4.0
-------------
*You will lose stored passwords during the upgrade to this version*
 * Added a prefix in redis in front of the storage keys, making the redis safer to share with other applications
 * Small test and syntax improvements

Version 1.3.0
-------------
* Quote urls to fix bug with ending in '='
* Mock redis
* Drop support for python 2.6 and python 3.3

Version 1.2.0
-------------
* Added Fernet cryptography to the stored keys, prevent access to full text passwords if someone has access to Redis
