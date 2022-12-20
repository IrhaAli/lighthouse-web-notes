# Week 5 Summary Notes
## Networking
* Computer networking is like human networking. It's like phone calls.
* `TCP (Transmission Control Protocol)`: Allows for the machine to speak to each other until one or both end the connection. TCP is language agnostic (ie. Javascript can talk to Python).
* Just like a phone call one person dials the phone number (ie. IP Address) and puts in the extension (ie. PORT).
* `LAN (Local Area Network)`: The networking happening in a local area (eg. all the networking in my house).
* `NIC (Network Interface Card)`: Acts as the eat and mouth of the computer so computer can talk.
* `WAN (Wide Area Network)`: Opposite of LAN.
* `MAC`: The name of the computer much like my own name.
* `Collision Detection/Avoidance`: Basically when one person talks over another and stops and says go ahead.
* Client is referred to as the person who establishes the connection (ie makes the call). All you need is a phone number (IP Address) and extension (PORT)
* `Types of Events in Networking`: connect, close, send data, recieve data.
* `Event Handler`: is the code you write that describes what to do when one of the above event occurs.
* HTTP & HTML are hypertexts (ie. they are texts that contain links to another text). The most common requests that will be made are HTTP ones.
* `HTTP`: HTTP is a request-response based protocol. A client makes a request to an HTTP server, immediately also sending a message asking for a specific resource, which the server sends down as a response.
* `HTTP Methods`: GET, POST, PUT, DELETE
* HTTP urls have a structure. It contains protocol, domain (host), port, resource path, query parameters, anchor. Read more [here](https://developer.mozilla.org/en-US/docs/Learn/Common_questions/What_is_a_URL)
* HTTP responses vary but the most important pieces of information is status code and body.
* HTTP is not alternative to TCP, but rather the text-based "language" that is used to communicate over a TCP connection.
!["HTTP Request Flow"](/Pictures/request-net-tcp-example.com.png)
* Request library allows us to make HTTP requests (ie. we don't have to make the client file from scratch), although it's not the best one. A better one is `axios`.
* Once an HTTP request has been made and a response is recieved, the response needs to transform into JSON format to be able to read it properly. The process of converting. `Note`: JSON is language independent.
* The process of serialization converts objects (or data structures) into a format that can be stored or transmitted between computers (typically as a string of text). The opposite, going from String → Object is called deserialization. The two main methods that can help achieve this are JSON.parse() and JSON.stringify().
* `API (Application Programming Interface)`: sets of requirements that govern how one application can talk to another.
* TCP is the road and HTTP are the cars on the road.
* Here's how an http link works. Protocol is like what are the customs in each area (the greeting example Mexico vs. Japan). Transport gives you all the ingredients and the computer puts them together to make the recipe (ie. load a WIKI page, for instance). The TCP plays a role in all of this because the you get real time updates that are made to that http link (eg. getting notification on fb while scrolling through it).
* `DNS (Domain Name System)`: is like yellow pages. When you know the name (ie. url) and input it into an internet browser DNS convers it to the phone # (ie. IP add) so the phone call can be made as we know that networking is like calling.
* Front-end developers are mostly HTTP Clients whereas back-end developers are servers.
* HTTP is about understanding three things:
  *  HTTP methods/verbs/functions
  * HTTP Status Code ([cats](https://http.cat/))
  * HTTP response object

## Callbacks for Async Code
* Callback function makes code modular but also leads to nesting.
* The error handling needs to be done at each callback.
* `Note`: Never reassign the parameter of a callback.

## Promises
* They are like promises in real life. Either they are kept or they're not.
* A kept promise is known as resolve().
* A promise that is not kept is known as reject().
* The third state of a promise is pending().
* A promise contains 3 parts (.then(), .finally, .catch())
* .then() gives information on what to do after that specific promise has been resolved.
* .finally() gives information on what to do once all promises have been dealt with (ie. whether rejected or resolved).
* .catch() allows us to deal with any possible errors in one are (unlike callbacks)
* The . syntax allows us to avoid nesting. Also, when using promises, testing code becomes easier.
* Common use of promises is when we want to run network request to fetch data.
* Some commong promise methods are promise.all, promise.any, promise.race, promise.allSettled.



## Problems of this week
* [Snake](https://github.com/IrhaAli/snake-client)
* Intro to Net (networking on [same](https://flex-web.compass.lighthouselabs.ca/workbooks/flex-m02w5/activities/399?journey_step=34&workbook=8) and [different](https://flex-web.compass.lighthouselabs.ca/workbooks/flex-m02w5/activities/2071?journey_step=34&workbook=8) computer)
* [Page Downloader](https://github.com/IrhaAli/page-fetcher)
* [Work Search](https://github.com/IrhaAli/pair-programming-word-search)
* [HTTP Cat Requests](https://github.com/IrhaAli/json-the-cat)
* [ISS Spotter (Callback and Promise)](https://github.com/IrhaAli/iss_spotter)
* [Loan Promise](https://gist.github.com/IrhaAli/6ab2d9d149710c49f93a994cd7a27051)
* [Find Friend](https://flex-web.compass.lighthouselabs.ca/workbooks/flex-m02w5/activities/438?journey_step=34&workbook=8)
* [File Server](https://gist.github.com/IrhaAli/aef2ab695ba626fe87cae27ae82bbc8c)