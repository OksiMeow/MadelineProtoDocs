---
title: "danog\\MadelineProto\\Settings\\TLSchema: TL schema settings."
description: ""
image: "https://docs.madelineproto.xyz/favicons/android-chrome-256x256.png"
parent: "MadelineProto API"

---
# `danog\MadelineProto\Settings\TLSchema`
[Back to index](../../../index.html)

> Author: Daniil Gentili <daniil@daniil.it>  
  

TL schema settings.  




## Method list:
* [`needsUpgrade(): bool`](#needsupgrade)
* [`upgrade(): void`](#upgrade)
* [`getLayer(): int`](#getlayer)
* [`setLayer(int $layer): self`](#setlayer)
* [`getMTProtoSchema(): string`](#getmtprotoschema)
* [`setMTProtoSchema(string $MTProtoSchema): self`](#setmtprotoschema)
* [`getAPISchema(): string`](#getapischema)
* [`setAPISchema(string $APISchema): self`](#setapischema)
* [`getSecretSchema(): string`](#getsecretschema)
* [`setSecretSchema(string $secretSchema): self`](#setsecretschema)
* [`getOther(): array`](#getother)
* [`setOther(array $other): self`](#setother)

## Methods:
### `needsUpgrade(): bool`

Returns whether the TL parser should re-parse the TL schemes.



### `upgrade(): void`

Signal that scheme was re-parsed.



### `getLayer(): int`

Get TL layer version.



### `setLayer(int $layer): self`

Set TL layer version.


Parameters:

* `$layer`: `int` TL layer version.  



### `getMTProtoSchema(): string`

Get MTProto schema path.



### `setMTProtoSchema(string $MTProtoSchema): self`

Set MTProto schema path.


Parameters:

* `$MTProtoSchema`: `string` MTProto schema path.  



### `getAPISchema(): string`

Get API schema path.



### `setAPISchema(string $APISchema): self`

Set API schema path.


Parameters:

* `$APISchema`: `string` API schema path.  



### `getSecretSchema(): string`

Get secret schema path.



### `setSecretSchema(string $secretSchema): self`

Set secret schema path.


Parameters:

* `$secretSchema`: `string` Secret schema path.  



### `getOther(): array`

Get the value of other.



### `setOther(array $other): self`

Set the value of other.


Parameters:

* `$other`: `array`   



---
Generated by [danog/phpdoc](https://phpdoc.daniil.it)
