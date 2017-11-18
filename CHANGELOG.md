## 7.0.0-alpha2
##### 10 november 2017
- __Global__
    - Fixed some typo on CREDITS.md (@geolim4)
    - Added Strict types support (@geolim4)
    - Added grouped namespaces (@geolim4)
    - Added VersionEye mention to credits (@geolim4)
    - Added OPTIONS.md (@geolim4)
    - Removed VersionEye badge :sob: (@geolim4)
    - Improved our fabulous API class to add the changelog/PhpFastCache version support (@geolim4)
    - Updated readme to add php7 strict types mention (@geolim4)
    - Updated EVENTS.md @geolim4)
    - Update withoutComposer.php (@Abs)
    - Updated CREDITS.txt to markdown file (@geolim4)
- __Core__
    - Fixed #529 // Memory leak caused by item tags (@geolim4)
    - Fixed missing sprintf in CacheManager + Added Riak method annotation (@geolim4)
    - Updated API version (@geolim4)
    - Updated composer files (@geolim4)
- __Drivers__
    - Fixed #517 // Couchbase error (@geolim4)
    - Fixed Riak dependency (@geolim4)
- __Tests__
    - Fixed hhvm build with subprocesses (@geolim4)
    - Added test for option "itemDetailedDate" (@geolim4)

## 7.0.0-alpha
##### 18 october 2017
- __Global__
  - Added php7 type hint support. Strict type support is coming in next alphas
  - Added changelog as requested by @rdecourtney in #517
  - Added `phpFastCacheInstanceNotFoundException` exception
- __Drivers__
  - Added Riak driver
  - Fixed wrong type hint returned by Predis
- __Cache Manager__
  - Added custom Instance ID feature as requested in #477
- __Helpers__
  - Modified ActOnAll helper behavior, this helper now returns an array of driver returns and does no longer implements `ExtendedCacheItemPoolInterface`

## 7.0.0-dev
##### 01 october 2017
- Initialized v7 development