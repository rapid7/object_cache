
Object Cache
============

JavaScript object cache with timeout

Introduction
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

---
Viliam Holub, [Logentries](https://logentries.com/)

