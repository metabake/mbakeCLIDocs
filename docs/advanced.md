
# ADVANCED / Mobile, Custom Elements, etc.


## Mobile apps

A responsive web app can easily become machine compiled into IOS and Android. *As single code base*. 
If you are in a rush or have limited resources but need a mobile or a cross platform app:
 you should convert to Electron first. It seems like Electron step is an extra step to slow you down: but doing Electron
 app first saves you time - even if you never release the Electron app.
 
You can of course add any needed native plugins from Capacitor (by Ionic)
; but most apps don't need any Capacitor (by Ionic)
 plugins.

## Custom Elements

Custom Elements are built into the browser.

[Custom Elements example](https://github.com/intuition-dev/mbToolBelt/tree/master/custel/custel1)

An example of keyboard driven F12 Custom Elements coming V1.1.


## Other


### Lazy Loading

Lazy loading .js and other assets enables very fast UX. More here:
[Lazy loading](https://github.com/intuition-dev/mbToolBelt/tree/master/lazyLoading)


### HTTP-RPC 

You can use REST and JSON-RPC. Or our HTTP-RPC:
[HTTP-RPC example](https://github.com/intuition-dev/mbToolBelt/tree/master/http-rpc)

Service calls, when done by back-end developers must include the front-end API call to that
service. You can't have a back-end developer write a service that a different developer then calls front-end.
The person that wrote the service must also write the front-end API that calls that service.


### SQLite Full Text Search

Here is example of using SQLite for FTS:
[SQLite FTS](https://github.com/INTUITION-dev/INTU/blob/master/examples/CRUD/node-srv/lib/CDB.ts)
Optionally FTS could be stored in RAM


---
[Edit this file](https://github.com/INTUITION-dev/INTUDocs/tree/master/docs)

