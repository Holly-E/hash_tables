# hash_tables
Practicing hash tables in JS  

Runtime Insertion = O(1) and Search = O(1). Same insertion runtime as linked lists. Faster search runtime than linked lists and binary search trees.  

They are great for storing and retrieving just about anything. The main negative is that they do not store references to other pieces of data in the data   structure.

Hash table has a pre-determined length. When multiple pieces of data (nodes as key/value pairs) get hashed to the same bucket, it’s called a collision. In a collision we chain our nodes together in a linked list. If you dont make your buckets correctly you could end up with many collisions containing long linked lists, which will impact the run time.
