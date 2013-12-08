Plist Java Android Library
==========================

Fork from excellent https://code.google.com/p/plist/


## What's new ?

* Conversion from SVN to Git (no big deal).
* Better support for generics in NSArray. It can now retreives directly array containings child types of NSObject such as NSDictionary or NSNumber.  
For example: `((NSArray<NSDictionary>) dictionary.objectForKey(key)).getArray();` returns NSDictionary typed objects rather than NSObject. You can now skip one bothering casting step.
