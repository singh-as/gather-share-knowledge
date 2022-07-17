# Topics

* Cache - Redis, Memcache
	* Strategies:
		* cache-aside (most common)
		
			![](images/cache-aside.png)
				
		* read-through
		* write-through - RedisGear, Amazon DAX
		* write-back - RedisGear, Amazon DAX
		* write-around
		
	* Eviction policies:
		* LRU - least recently used
		* LFU - least frequently used
		* noeviction
		* random

