# Spark-Bloom-Filters-and-Broadcast-Joins

Spark Broadcast Variables:

https://spark.apache.org/docs/2.2.0/rdd-programming-guide.html#broadcast-variables

“Broadcast variables allow the programmer to keep a read-only variable cached on each
machine rather than shipping a copy of it with tasks. They can be used, for example, to give
every node a copy of a large input dataset in an efficient manner.”

Definition: Bloom Filter

https://en.wikipedia.org/wiki/Bloom_filter

Bloom filters are efficient probabilistic data structures constructed of a set of values to be
used for membership tests. It can tell you if an arbitrary element being tested might be in
the set, or definitely not in the set, that is false positives are allowed, but false negatives
are not. 

Implement a broadcast join using Bloom filters. 

Using broadcast join and a bloom filter, filter all rows in Table A for only those containing
‘model’ in Table B. The common key is the ‘model’ column.
