pbl
===
EiNSTeiN_ - <einstein@g3nius.org>

Parses new leaks from pastebin (and other similar sites) to find interesting data.

Setup
-----
1. Edit database.py and add your mysql database information.
2. Import the SQL schema in your database.
3. Add your user in the database ```insert into users (username, password) values ('einstein', 'md5-hash-of-password')```
4. Run ```make``` to generate javascript code.
5. Edit pbl-daemon.py with the correct installation path, and copy it to /etc/init.d

