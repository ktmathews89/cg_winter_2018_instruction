---
title: Learn Ajax
permalink: /1_2018/lesson_11/0_learn_ajax
---

# Learn AJAX Lesson

AJAX sending and receiving data

Up until now, we have been using data that we hard coded (students information) in our javascript file.

In real

API what is it?

    * data endpoint
    * send REQUEST (address: url, other information: info in regards to what data you want back)
    * receive RESPONSE (success/error, data)


JSON

* data structure
    so far, we have been using javascript objects or arrays to organize the data our website uses
    JSON is another way we can do that

Javascript Object Literal
```
{
    id: 1,
    name: Tasha,
}
```

JSON
```
{
    'id': '1',
    'name': 'Tasha'
}
```

So similar, why not use Javascript Objects?

Backends or API endpoint (where your API request is directed to)... could be receiving your request in a lot of different language. A regular javascript object might not translate to a different language and therefore unable to be read.

JSON can be used in A LOT of different languages, making it ideal to use when sending data to other sites :) Also it can be translated into a string and back to minimize the size of data that will transfer.


## Build A Trivia App With an API

There are a lot of public APIs out there that you can use to build an web application with. For this project, we are going to us a Trivia API, called [Open Trivia Database](https://opentdb.com/api_config.php).

However, there are A BUNCH of fun APIs out there... If you want to forge your own path ahead, feel free to browse through the below APIs and create you own application!

[Donald Trump Quotes](https://docs.tronalddump.io/)

[Dad Jokes](https://icanhazdadjoke.com/api)

[NBA Stats](https://any-api.com/nba_com/nba_com/docs/_teamgamelog/GET)

[Robot Avatars](https://robohash.org/)


Anyways! I spent way too long looking through those... okay. Ready to build something! If you are just going to proceed with the Trivia App... continue below.

### Project Setup
