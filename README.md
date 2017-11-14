# Share Links Backend

Husband and I want to be able to send funny links to each other
without any of the Internet giants being able to watch.

## Plan

Simple chrome extension that starts a websocket to this service.

This service listens for messages on the websockets and echos
them out to all connected sockets.

## To think about

* Authentication
    
    Simple at the moment - don't upload the URLs to github, but will need
    something more complex than that.
    
* Offline storage
  
    If I see a funny while husband is asleep, he should get a notification
    next time he opens chrome.
