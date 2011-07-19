
Object Cache
============

JavaScript object cache with timeout

What is this
------------

A simple in-memory JavaScript object cache, indexed by a string or an object.

Used, for instance, to cache AJAX requests/responses.

Example
-------

    // Create cache object with up to 1000 elements
    var cache = new ObjectCache( 1000);
    
    // Save the object in cache, key may be an object
    cache.put( key, value)
    // Query the request in the cache
    cache.get( key);
    // Query the key, must not be older than a minute
    cache.get( request, 60*1000);

The Latest Version
------------------

You can find the latest version in our [repository](https://github.com/logentries/object_cache).

Licensing
---------

Shared under the Creative Commons Attribution 3.0 Unported License
<http://creativecommons.org/licenses/by/3.0/>

---
Contact: Viliam Holub, vilda@logentries.com, [Logentries](https://logentries.com/)

