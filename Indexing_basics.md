# MYSQL

1. In MySQl, if you make a key primary key, an index is created by default on it.
2. The index uses a DS -> B+ Tree. (key, pointer to the actual block)

# Cons
When ever a DML Operation (insert, update, delete) is done you need to update the index as well. So DML puts pressure on the performance of index.


## RESOURCES



https://www.freecodecamp.org/news/database-indexing-at-a-glance-bb50809d48bd/