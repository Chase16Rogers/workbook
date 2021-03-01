# Day 3
__02/24/21__

## What is a SQL injection?

SQL injection is a typically malicious process by which a "hacker" can attatch SQL code in in a database query, usually just appended to the end of whatever is being run. By this they can essentially do whatever they want with the database. From dropping tables, to altering the data. 

## What are 3 methods SQL injection can be done by?

They can be done through user-input. If the info from a form is going to be sent to a server it would take no effort whatsoever to submit "DROP TABLE)" to the name field.
There is also a means by which to attack the cookies which communicate with the server. I don't entirely understand it but it seems much more involved, as whatever is attatched to the cookies will then have to make their own request? or else somehow make a database query.
Second order is where they sneak something into the server, be it through input or what have you, but it isn't as obvious as drop table, because it is meant to trigger in some other context. This is "spooky" because it isn't as immediately obvious and can avoid some of the sanitization protocols. 

## How can we detect and sanitize SQL injection attacks?

For detection there is firewall technology out there that can detect most sql injections, and there is software to keep an eye on your database and let you know if anything suspicious happens.
As far as prevention goes, the number one thing is to code like you are expecting to be attacked. Control who is alowed to make what queries, give the application the least number of privaleges it needs to run, which means limiting the variety of calls it can make to the server / the server can handle. Using software like dapper to sanitize injections. Finally, have backups. The worst case scenario is always just around the corner, so if the data is important have backups so even if the worst case scenario occurs, it won't be the end of the world.

## Afternoon Challenge

[https://github.com/Chase16Rogers/c-task-master](https://github.com/Chase16Rogers/c-task-master)