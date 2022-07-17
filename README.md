# Topics

* Caching Strategies:
	- cache-aside (most common) - Redis, Memcache
	
	![](images/cache-aside.png)
		
	- read-through
	- write-through
		+ RedisGear, Amazon DAX
	- write-back
		+ RedisGear, Amazon DAX
	- write-around
	
	Cache Eviction policies:
	* 	LRU - least recently used
	* 	LFU - least frequently used
	* 	noeviction
	* 	random

