---
title: "danog\\MadelineProto\\Settings\\Peer: Peer database settings."
description: ""
image: "https://docs.madelineproto.xyz/favicons/android-chrome-256x256.png"
parent: "MadelineProto API"

---
# `danog\MadelineProto\Settings\Peer`
[Back to index](../../../index.html)

> Author: Daniil Gentili <daniil@daniil.it>  
  

Peer database settings.  




## Method list:
* [`getFullInfoCacheTime(): int`](#getfullinfocachetime)
* [`setFullInfoCacheTime(int $fullInfoCacheTime): self`](#setfullinfocachetime)
* [`getFullFetch(): bool`](#getfullfetch)
* [`setFullFetch(bool $fullFetch): self`](#setfullfetch)
* [`getCacheAllPeersOnStartup(): bool`](#getcacheallpeersonstartup)
* [`setCacheAllPeersOnStartup(bool $cacheAllPeersOnStartup): self`](#setcacheallpeersonstartup)

## Methods:
### `getFullInfoCacheTime(): int`

Get cache time for full peer information (seconds).



### `setFullInfoCacheTime(int $fullInfoCacheTime): self`

Set cache time for full peer information (seconds).


Parameters:

* `$fullInfoCacheTime`: `int` Cache time for full peer information (seconds).  



### `getFullFetch(): bool`

Get should madeline fetch the full member list of every group it meets?



### `setFullFetch(bool $fullFetch): self`

Set should madeline fetch the full member list of every group it meets?


Parameters:

* `$fullFetch`: `bool` Should madeline fetch the full member list of every group it meets?  



### `getCacheAllPeersOnStartup(): bool`

Get whether to cache all peers on startup for userbots.



### `setCacheAllPeersOnStartup(bool $cacheAllPeersOnStartup): self`

Set whether to cache all peers on startup for userbots.


Parameters:

* `$cacheAllPeersOnStartup`: `bool` Whether to cache all peers on startup for userbots.  



---
Generated by [danog/phpdoc](https://phpdoc.daniil.it)
