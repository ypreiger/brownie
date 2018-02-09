Brownie, the brownfield application
====================================

What is it?
-----------

"Brownie" is a made-up historical WebLogic application inspired by several real-world monolithic applications.


What to do with it?
-------------------

Build the application and try to make it run on Red Hat JBoss EAP 7.

Take care: it is not a piece of cake.


$ git clone https://github.com/Maarc/brownie.git
$ cd brownie
$ mvn clean eclipse:clean eclipse:eclipse install


License
-------

Brownie is licensed under the [MIT license](./LICENSE.txt) and embeds [2048](https://github.com/gabrielecirulli/2048).
