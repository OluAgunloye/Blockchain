blockchain
=====

blockchain websocket api


methods
-----

- **constructor**(): creates a new socket and calls **open**
- **subscribe**(address, callback)
- **unsubscribe**(address, callback)
- **open**()
- **close**()

events
-----

- **connect**: function()
- **connectFailed**: function(errorDescription)
- **disconnect** function()
- **error**: function(error)

notes
-----

- subscriptions persist
- see tests for example

license
---

ISC
