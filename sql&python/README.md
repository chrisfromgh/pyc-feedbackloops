# SQL & Python
https://2023.pycascades.com/program/talks/demystifying-sqlite-with-python/

sqlite comes with python

`import sqlite3`

you can load a database into memory using sqlite.connect(':memory')

Then to run sql commands you create the cursor object `cursor = comm.cursor()`

wtf are indexes
so indexes can be used to optimize the search of a database when searching for a condition

multilevel indexes or b-tree indexes
binary tree algorithim

the primary key or or id of the sqlite database is stored as a b-tree index so that it can help with storage and retrieval of info from the db

