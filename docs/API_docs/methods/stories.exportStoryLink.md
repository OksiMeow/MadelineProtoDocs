---
title: "stories.exportStoryLink"
description: "stories.exportStoryLink parameters, return type and example"
grand_parent: "Telegram RPC API"
parent: "Methods"
image: https://docs.madelineproto.xyz/favicons/android-chrome-256x256.png
redirect_from: /API_docs/methods/stories_exportStoryLink.html
---
# Method: stories.exportStoryLink
[Back to methods index](index.html)



### Parameters:

| Name     |    Type       | Required |
|----------|---------------|----------|
|user\_id|[Username, chat ID, Update, Message or InputUser](/API_docs/types/InputUser.html) | Optional|
|id|[int](/API_docs/types/int.html) | Yes|


### Return type: [ExportedStoryLink](/API_docs/types/ExportedStoryLink.html)

### Can bots use this method: **YES**


### MadelineProto Example ([now async for huge speed and parallelism!](https://docs.madelineproto.xyz/docs/ASYNC.html)):


```php
if (!file_exists('madeline.php')) {
    copy('https://phar.madelineproto.xyz/madeline.php', 'madeline.php');
}
include 'madeline.php';

$MadelineProto = new \danog\MadelineProto\API('session.madeline');
$MadelineProto->start();

$ExportedStoryLink = $MadelineProto->stories->exportStoryLink(user_id: $InputUser, id: $int, );
```

