# Cache


* Strategies:
	* cache-aside (most common) - Redis, Memcache
		
		![](images/cache-aside.png)
		
	* read-through
		
		![](images/read-through.PNG)
		
	* write-through - RedisGear, Amazon DAX
		
		![](images/write-through.PNG)
		
	* write-back - RedisGear, Amazon DAX
		
		![](images/write-back.PNG)
	
* Cache Eviction policies:
	* LRU - least recently used
	* LFU - least frequently used
	* noeviction
	* random


