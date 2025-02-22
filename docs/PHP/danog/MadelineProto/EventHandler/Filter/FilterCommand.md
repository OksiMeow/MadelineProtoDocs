---
title: "danog\\MadelineProto\\EventHandler\\Filter\\FilterCommand: Allow only messages containing the specified command."
description: ""
image: "https://docs.madelineproto.xyz/favicons/android-chrome-256x256.png"
parent: "MadelineProto API"

---
# `danog\MadelineProto\EventHandler\Filter\FilterCommand`
[Back to index](../../../../index.html)

> Author: Daniil Gentili <daniil@daniil.it>  
  

Allow only messages containing the specified command.  



## Properties
* `$commandTypes`: `\CommandType[]` 

## Method list:
* [`__construct(string $command, list<\danog\MadelineProto\EventHandler\CommandType> $types = [  0 =>   \danog\MadelineProto\EventHandler\CommandType::BANG,  1 =>   \danog\MadelineProto\EventHandler\CommandType::DOT,  2 =>   \danog\MadelineProto\EventHandler\CommandType::SLASH,])`](#__construct)
* [`apply(\danog\MadelineProto\EventHandler\Update $update): bool`](#apply)
* [`initialize(\danog\MadelineProto\EventHandler $API): \danog\MadelineProto\EventHandler\Filter\Filter`](#initialize)
* [`fromReflectionType(\ReflectionType $type): \danog\MadelineProto\EventHandler\Filter\Filter`](#fromreflectiontype)

## Methods:
### `__construct(string $command, list<\danog\MadelineProto\EventHandler\CommandType> $types = [  0 =>   \danog\MadelineProto\EventHandler\CommandType::BANG,  1 =>   \danog\MadelineProto\EventHandler\CommandType::DOT,  2 =>   \danog\MadelineProto\EventHandler\CommandType::SLASH,])`




Parameters:

* `$command`: `string` Command  
* `$types`: `list<\danog\MadelineProto\EventHandler\CommandType>` Command types, if empty all command types are allowed.  


#### See also: 
* [\danog\MadelineProto\EventHandler\CommandType](../../../../danog/MadelineProto/EventHandler/CommandType.html)




### `apply(\danog\MadelineProto\EventHandler\Update $update): bool`




Parameters:

* `$update`: `\danog\MadelineProto\EventHandler\Update`   


#### See also: 
* [`\danog\MadelineProto\EventHandler\Update`: Represents a generic update.](../../../../danog/MadelineProto/EventHandler/Update.html)




### `initialize(\danog\MadelineProto\EventHandler $API): \danog\MadelineProto\EventHandler\Filter\Filter`

Run some initialization logic, optionally returning a new filter to replace the current one.


Parameters:

* `$API`: `\danog\MadelineProto\EventHandler`   


#### See also: 
* [`\danog\MadelineProto\EventHandler`: Event handler.](../../../../danog/MadelineProto/EventHandler.html)




### `fromReflectionType(\ReflectionType $type): \danog\MadelineProto\EventHandler\Filter\Filter`




Parameters:

* `$type`: `\ReflectionType`   


#### See also: 
* `\ReflectionType`




---
Generated by [danog/phpdoc](https://phpdoc.daniil.it)
