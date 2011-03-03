Hello World
===========

Description
-----------
This is the README file for the Hello-World project.
Here is an extra line.
And there is another one added from mac.

Quick Install to your local environment
---------------------------------------
Assuming you already have [Apache][apache] + [PHP 5.3][php] + [MySQL][mysql] installed:

Clone the repository to your local environment

    clone git@github.com:keylib/Key-Lib.git

Edit environment configuration file to check parameters

    env.cfg 

Launch following script to init the environment

    make init

This will
  - Create the database as defined in env.cfg
  - Load the dump
  - Do some magic...

Your local environment is ready...

Development Guidelines
----------------------
Perform modification on your local environment
Commit modification to your lcoal environment

    git commit 

Commit modifications when the fix/feature is stable

    git push

Todo
----
The cwfollowing workflow shall be followed ultimatly:
[A successful Git branching model][branching]
   



[keylib]:http://www.keylib.fr
[apache]:http://apache.org
[php]:http://php.net
[mysql]:http://www.mysql.com

[branching]:http://nvie.com/posts/a-successful-git-branching-model/

