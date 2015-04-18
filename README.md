These example applications illustrate various key LoopBack features.  In some cases, they have accompanying step-by-step instructions (tutorials).  The applications fall into several categories:

- [Getting started](#getting-started)
- [Tutorial series](#tutorial-series)
- [Topic-specific examples](#topic-specific-examples)
- [FAQ examples](#faq-examples)
- [Community examples](#community-examples)
- [Deprecated examples](#deprecated-examples)

##Getting started

**Start here!**

Read [Getting started with LoopBack](http://docs.strongloop.com/display/LB/Getting+started+with+LoopBack) to create [loopback-getting-started](https://github.com/strongloop/loopback-getting-started).

"Getting started (intermediate)" is a work in progress: 
[loopback-getting-started-intermediate](https://github.com/strongloop/loopback-getting-started-intermediate).

##Tutorial series

Each repository contains a complete application, along with step-by-step instructions to recreate it 
in the README.

Complete these in the order listed below.  When a step contains multiple repositories, you need only follow 
one of them before going to the next step; you don't have to finish all of them. For example, follow  `loopback-example-mysql` in step one, then go to step two.

###The basics

Teaches the basics on models, connectors, datasources, automigration and
discovery.

- [loopback-example-mongodb](https://github.com/strongloop/loopback-example-mongodb)
- [loopback-example-mssql](https://github.com/strongloop/loopback-example-mssql)
- [loopback-example-mysql](https://github.com/strongloop/loopback-example-mysql)
- [loopback-example-postgresql](https://github.com/strongloop/loopback-example-postgresql)
- [loopback-example-oracle](https://github.com/strongloop/loopback-example-oracle)

###Relations and filters

Teaches the basics of model relations and basic filtering via REST.

- [loopback-example-relations](https://github.com/strongloop/loopback-example-relations)

###Adding application logic

Teaches the basics of remote methods, remote hooks, model hooks, boot scripts, and middleware.

- [loopback-example-app-logic](https://github.com/strongloop/loopback-example-app-logic)

###Access control

- [loopback-example-access-control](https://github.com/strongloop/loopback-example-access-control)

##Topic-specific examples

You can follow these examples in any order since they are self-contained and specific
to a particular topic.

|WIP|Name                                                                                        |Description                                                                           |
|:-:|:-------------------------------------------------------------------------------------------|:-------------------------------------------------------------------------------------|
|   |[loopback-component-push](https://github.com/strongloop/loopback-component-push)            |LoopBack 2.x examples available in the `examples` dir                                 |
|   |[loopback-component-storage](https://github.com/strongloop/loopback-component-storage)      |LoopBack 2.0 examples available in the `examples` dir                                 |
|   |[loopback-example-APIClientApp](https://github.com/strongloop/loopback-example-apiclientapp)|                                                                                      |
|   |[loopback-example-angular](https://github.com/strongloop/loopback-example-angular)          |A simple todo list using AngularJS on the client side and LoopBack on the server side.|
|   |[loopback-example-app](https://github.com/strongloop/loopback-example-app)                  |A full stack LoopBack application (iCars)                                             |
|   |[loopback-example-boot-scripts](https://github.com/strongloop/loopback-example-boot-scripts)|How to use the LoopBack boot script generator                                         |
|   |[loopback-example-component](https://github.com/strongloop/loopback-example-component)      |                                                                                      |
|   |[loopback-example-pubsub](https://github.com/strongloop/loopback-example-pubsub)            |                                                                                      |
|   |[loopback-example-offline-sync](https://github.com/strongloop/loopback-example-offline-sync)|Offline sync with Loopback                                                            |
|   |[loopback-example-passport](https://github.com/strongloop/loopback-example-passport)        |PassportJS with Loopback                                                              |
| ✔ |[loopback-example-recipes](https://github.com/strongloop/loopback-example-recipes)          |                                                                                      |
| ✔ |[loopback-example-remote](https://github.com/strongloop/loopback-example-remote)            |How to use the LoopBack remote connector                                              |
|   |[loopback-example-ssl](https://github.com/strongloop/loopback-example-ssl)                  |SSL with LoopBack                                                                     |

**Examples on docs.strongloop.com**:

- [Creating a LoopBack iOS app: part one](http://docs.strongloop.com/display/LB/Creating+a+LoopBack+iOS+app:+part+one)
- [Creating a LoopBack iOS app: part two](http://docs.strongloop.com/display/LB/Creating+a+LoopBack+iOS+app:+part+two)
- [Push notifications](http://docs.strongloop.com/display/LB/Tutorial:+Push+notifications)

##FAQ examples

Example repositories for frequently-asked questions.

- [loopback-faq-email](https://github.com/strongloop/loopback-faq-email)
- [loopback-faq-middleware](https://github.com/strongloop/loopback-faq-middleware)
- [loopback-faq-model-hooks](https://github.com/strongloop/loopback-faq-model-hooks)
- [loopback-faq-rest-connector](https://github.com/strongloop/loopback-faq-rest-connector)
- [loopback-faq-user-management](https://github.com/strongloop/loopback-faq-user-management)
- [loopback-faq-model-relations](https://github.com/strongloop/loopback-faq-model-relations) - WIP
- [loopback-faq-build-automation](https://github.com/strongloop/loopback-faq-build-automation) - WIP

##Community examples

These are examples contributed by the LoopBack community. Let us know if you have an example to
contribute and we'll send you some swag in return for your efforts!

- [loopback-angular-admin](https://github.com/beeman/loopback-angular-admin)
- [loopback-examples-ios](https://github.com/strongloop-community/loopback-examples-ios)
- [loopback-example-user-organization](https://github.com/strongloop-community/loopback-example-user-organization)

##Deprecated examples

###LoopBack 1.x examples

These examples have not been updated for LoopBack 2.x.

- [loopback-component-example-office-supplies](https://github.com/strongloop/loopback-example-office-supplies)
- [sample-applications](https://github.com/strongloop-community/sample-applications)
- [loopback-example-proxy](https://github.com/strongloop/loopback-example-proxy)

### Other deprecated examples

These are either outdated or replaced with better examples.

- [loopback-example-angular-starter](https://github.com/strongloop/loopback-example-angular-starter) replaced with [loopback-example-angular](http://github.com/strongloop/loopback-example-angular)
- [loopback-example-coffee-shop](https://github.com/strongloop/loopback-example-coffee-shop) replaced with [loopback-getting-started-intermediate](http://github.com/strongloop/loopback-getting-started-intermediate)
- [loopback-example-customAPI](https://github.com/strongloop/loopback-example-customAPI) replaced with [loopback-getting-started](http://github.com/strongloop/loopback-getting-started)
- [loopback-example-full-stack](https://github.com/strongloop/loopback-example-full-stack) renamed to [loobpack-example-offline-sync](https://github.com/strongloop/loopback-example-offline-sync)
- [loopback-example-datasourceAPI](https://github.com/strongloop/loopback-example-datasourceAPI) replaced with [loopback-getting-started](http://github.com/strongloop/getting-started)
- [loopback-example-database](https://github.com/strongloop/loopback-example-database) replaced with 5 separate repos:
    - [loopback-example-mongodb](https://github.com/strongloop/loopback-example-mongodb)
    - [loopback-example-mssql](https://github.com/strongloop/loopback-example-mssql)
    - [loopback-example-mysql](https://github.com/strongloop/loopback-example-mysql)
    - [loopback-example-postgresql](https://github.com/strongloop/loopback-example-postgresql)
    - [loopback-example-oracle](https://github.com/strongloop/loopback-example-oracle)
- [loopback-example-extendedAPI](https://github.com/strongloop/loopback-example-extendedAPI) replaced with [loopback-getting-started](http://github.com/strongloop/loopback-getting-started)
- [loopback-example-relations-basic](https://github.com/strongloop/loopback-example-relations-basic) replaced with [loopback-example-model-relations](http://github.com/strongloop/loopback-example-model-relations)
- [loopback-example-model-relations](https://github.com/strongloop/loopback-example-model-relations) replaced with [loopback-example-relations](http://github.com/strongloop/loopback-example-relations)
- [loopback-example-mySimpleAPI](https://github.com/strongloop/loopback-example-mySimpleAPI) replaced with [loopback-getting-started](http://github.com/strongloop/loopback-getting-started)
