---
title: "messagePeerVote"
description: "messagePeerVote attributes, type and example"
nav_exclude: true
image: https://docs.madelineproto.xyz/favicons/android-chrome-256x256.png
---
# Constructor: messagePeerVote  
[Back to constructors index](/API_docs/constructors/index.html)



### Attributes:

| Name     |    Type       | Required |
|----------|---------------|----------|
|peer|[Peer](/API_docs/types/Peer.html) | Yes|
|option|[bytes](/API_docs/types/bytes.html) | Yes|
|date|[int](/API_docs/types/int.html) | Yes|



### Type: [MessagePeerVote](/API_docs/types/MessagePeerVote.html)


### Example:

```
$messagePeerVote = ['_' => 'messagePeerVote', 'peer' => Peer, 'option' => 'bytes', 'date' => int];
```  
