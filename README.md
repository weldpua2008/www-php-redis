Includes very basic counter application - single php file index.php 

The usage is as follows:
http://localhost/index.php
this will return current value of counter
http://localhost/index.php?add=24
this call will increment the counter by provided value
http://localhost/index.php?reset
this call will reset the counter

Ansible script (http://docs.ansible.com/intro.html)  that will install environment where this app can run.
apache/ngnix can be used
php version doesn't matter
Redis database is used to store the value.
Expected result:
Ansible script (.yml file)  that I can run on clean machine that will install this app.
