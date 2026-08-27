> \[!WARNING]
> This project is looking for a new home. I'm no longer maintaining it.
> Please let me know if you want to take over maintainance for it.
> Write me an email to <timo@furrer.life>

# Awesome asyncio with stars

> A carefully curated list of awesome Python asyncio frameworks, libraries, software and resources.

The Python [asyncio](https://docs.python.org/3/library/asyncio.html) module introduced to the standard library with Python 3.4 provides infrastructure for writing single-threaded concurrent code using coroutines, multiplexing I/O access over sockets and other resources, running network clients and servers, and other related primitives.

Asyncio is not really a brand-new technology however it appears to be very trending since a few years - especially in the Python community and with the release of Python 3.4 in March 2014.
Thus, it's pretty hard to keep yourself up-to-date with the most awesome packages out there.
Find some of those *awesome* packages here and if you are missing one we count on you to [create an Issue or a Pull Request](https://github.com/timofurrer/awesome-asyncio/blob/master/CONTRIBUTING.md) ⭐ 5,118 | 🐛 22 | 📅 2025-12-01 with your suggestion.

## Contents

* [Web Frameworks](#web-frameworks)
* [Message Queues](#message-queues)
* [Database Drivers](#database-drivers)
* [Networking](#networking)
* [GraphQL](#graphql)
* [Testing](#testing)
* [Alternative Loops](#alternative-loops)
* [Misc](#misc)
* [Writings](#writings)
* [Talks](#talks)
* [Alternatives to asyncio](#alternatives-to-asyncio)

***

## Web Frameworks

*Libraries to build web applications.*

* [FastAPI](https://github.com/tiangolo/fastapi) ⭐ 101,873 | 🐛 79 | 🌐 Python | 📅 2026-08-26 - A very high performance Python 3.6+ API framework based on type hints. Powered by Starlette and Pydantic.
* [sanic](https://github.com/channelcat/sanic) ⭐ 18,645 | 🐛 145 | 🌐 Python | 📅 2026-07-29 - Python 3.5+ web server that's written to go fast.
* [aiohttp](https://github.com/KeepSafe/aiohttp) ⭐ 16,529 | 🐛 225 | 🌐 Python | 📅 2026-08-27 - Http client/server for asyncio (PEP-3156).
* [Starlette](https://github.com/encode/starlette) ⭐ 12,573 | 🐛 61 | 🌐 Python | 📅 2026-08-26 - A lightweight ASGI framework/toolkit for building high performance services.
* [uvicorn](https://github.com/encode/uvicorn) ⭐ 10,928 | 🐛 86 | 🌐 Python | 📅 2026-08-24 - The lightning-fast ASGI server.
* [websockets](https://github.com/aaugustin/websockets/) ⭐ 5,714 | 🐛 1 | 🌐 Python | 📅 2026-08-26 - A library for building WebSocket servers and clients in Python with a focus on correctness and simplicity.
* [Quart](https://github.com/pallets/quart) ⭐ 3,658 | 🐛 27 | 🌐 Python | 📅 2026-08-25 - An asyncio web microframework with the same API as Flask.
* [autobahn](https://github.com/crossbario/autobahn-python) ⭐ 2,543 | 🐛 187 | 🌐 Python | 📅 2026-07-15 - WebSocket and WAMP supporting asyncio and Twisted, for clients and servers.
* [Django](https://www.djangoproject.com/) - An established, high-level Python web framework with a huge community and ecosystem.
* [Tornado](http://www.tornadoweb.org/en/stable/) - Performant web framework and asynchronous networking library.

## Message Queues

*Libraries to implement applications using message queues.*

* [pyzmq](https://github.com/zeromq/pyzmq) ⭐ 4,164 | 🐛 52 | 🌐 Python | 📅 2026-08-20 - Python bindings for ZeroMQ.
* [crossbar](https://github.com/crossbario/crossbar) ⭐ 2,064 | 🐛 305 | 🌐 Python | 📅 2026-07-27 - Crossbar.io is a networking platform for distributed and microservice applications.
* [aiokafka](https://github.com/aio-libs/aiokafka) ⭐ 1,399 | 🐛 190 | 🌐 Python | 📅 2026-08-09 - Client for Apache Kafka.
* [asyncio-nats](https://github.com/nats-io/asyncio-nats) ⭐ 1,244 | 🐛 113 | 🌐 Python | 📅 2026-08-21 - Client for the NATS messaging system.
* [aiozmq](https://github.com/aio-libs/aiozmq) ⭐ 431 | 🐛 33 | 🌐 Python | 📅 2026-03-26 - Alternative Asyncio integration with ZeroMQ.
* [aioamqp](https://github.com/Polyconseil/aioamqp) ⭐ 281 | 🐛 35 | 🌐 Python | 📅 2023-05-19 - AMQP implementation using asyncio.

## Database Drivers

*Libraries to connect to databases.*

* [redis-py](https://github.com/redis/redis-py) ⭐ 13,621 | 🐛 89 | 🌐 Python | 📅 2026-08-26 - Redis Python Client (which includes [aioreadis](https://github.com/aio-libs/aioredis) ⚠️ Archived now).
* [asyncpg](https://github.com/MagicStack/asyncpg) ⭐ 8,075 | 🐛 300 | 🌐 Python | 📅 2026-02-27 - Fast PostgreSQL Database Client Library for Python/asyncio.
* [Tortoise ORM](https://github.com/tortoise/tortoise-orm) ⭐ 5,614 | 🐛 541 | 🌐 Python | 📅 2026-08-24 - native multi-backend ORM with Django-like API and easy relations management.
* [pymongo](https://github.com/mongodb/mongo-python-driver) ⭐ 4,352 | 🐛 18 | 🌐 Python | 📅 2026-08-26 - The Official MongoDB Python driver, offering both synchronous and asynchronous APIs.
* [Beanie](https://beanie-odm.dev) - An async MongoDB ODM built on [pymongo](https://github.com/mongodb/mongo-python-driver) ⭐ 4,352 | 🐛 18 | 🌐 Python | 📅 2026-08-26 and [Pydantic](https://pydantic-docs.helpmanual.io).
* [Databases](https://github.com/encode/databases) ⚠️ Archived - Async database access for SQLAlchemy core, with support for PostgreSQL, MySQL, and SQLite.
* [GINO](https://github.com/fantix/gino) ⭐ 2,793 | 🐛 54 | 🌐 Python | 📅 2022-02-12 - is a lightweight asynchronous Python ORM based on [SQLAlchemy](https://www.sqlalchemy.org/) core, with [asyncpg](https://github.com/MagicStack/asyncpg) ⭐ 8,075 | 🐛 300 | 🌐 Python | 📅 2026-02-27 dialect.
* [Prisma Client Python](https://github.com/RobertCraigie/prisma-client-py) ⚠️ Archived - An auto-generated, fully type safe ORM powered by Pydantic and tailored specifically for your schema - supports SQLite, PostgreSQL, MySQL, MongoDB, MariaDB and more.
* [Piccolo](https://github.com/piccolo-orm/piccolo) ⭐ 1,937 | 🐛 41 | 🌐 Python | 📅 2026-08-07 - An ORM / query builder which can work in async and sync modes, with a nice admin GUI, and ASGI middleware.
* [aiomysql](https://github.com/aio-libs/aiomysql) ⭐ 1,896 | 🐛 117 | 🌐 Python | 📅 2026-03-27 - Library for accessing a MySQL database
* [aiopg](https://github.com/aio-libs/aiopg/) ⭐ 1,431 | 🐛 88 | 🌐 Python | 📅 2025-12-03 - Library for accessing a PostgreSQL database.
* [peewee-async](https://github.com/05bit/peewee-async) ⭐ 763 | 🐛 4 | 🌐 Python | 📅 2026-08-27 - ORM implementation based on [peewee](https://github.com/coleifer/peewee) ⭐ 11,986 | 🐛 0 | 🌐 Python | 📅 2026-08-27 and aiopg.
* [asyncpgsa](https://github.com/CanopyTax/asyncpgsa) ⭐ 507 | 🐛 15 | 🌐 Python | 📅 2024-02-17 - Asyncpg with sqlalchemy core support.
* [aioodbc](https://github.com/aio-libs/aioodbc) ⭐ 326 | 🐛 39 | 🌐 Python | 📅 2023-10-28 - Library for accessing a ODBC databases.
* [aioinflux](https://github.com/plugaai/aioinflux) ⚠️ Archived - InfluxDB client built on top of aiohttp.
* [aioes](https://github.com/aio-libs/aioes) ⚠️ Archived - Asyncio compatible driver for elasticsearch.
* [aiocouchdb](https://github.com/aio-libs/aiocouchdb) ⭐ 54 | 🐛 8 | 🌐 Python | 📅 2018-05-09 - CouchDB client built on top of aiohttp (asyncio).

## Networking

*Libraries to communicate in your network.*

* [httpx](https://github.com/encode/httpx) ⭐ 15,444 | 🐛 143 | 🌐 Python | 📅 2026-03-29 - asynchronous HTTP client for Python 3 with [requests](https://github.com/psf/requests) ⭐ 54,252 | 🐛 234 | 🌐 Python | 📅 2026-08-25 compatible API.
* [AsyncSSH](https://github.com/ronf/asyncssh) ⭐ 1,753 | 🐛 14 | 🌐 Python | 📅 2026-08-16 - Provides an asynchronous client and server implementation of the SSHv2 protocol.
* [aiodns](https://github.com/saghul/aiodns) ⭐ 592 | 🐛 15 | 🌐 Python | 📅 2026-08-18 - Simple DNS resolver for asyncio.
* [aioping](https://github.com/stellarbit/aioping) ⭐ 92 | 🐛 10 | 🌐 Python | 📅 2024-01-21 - Fast asyncio implementation of ICMP (ping) protocol.

## GraphQL

*Libraries to build GraphQL servers.*

* [Ariadne](https://ariadnegraphql.org) - Schema-first Python library for implementing GraphQL servers.
* [Tartiflette](https://tartiflette.io/) - Schema-first Python 3.6+ GraphQL engine built on top of `libgraphqlparser`.
* [Strawberry](https://strawberry.rocks) - Code-first Python 3 GraphQL server with Django, Flask and FastAPI/Starlette support.

## Testing

*Libraries to test asyncio based applications.*

* [pytest-asyncio](https://github.com/pytest-dev/pytest-asyncio) ⭐ 1,658 | 🐛 50 | 🌐 Python | 📅 2026-08-26 - Pytest support for asyncio.
* [aioresponses](https://github.com/pnuckowski/aioresponses) ⭐ 557 | 🐛 65 | 🌐 Python | 📅 2026-06-23 - Helper for mock/fake web requests in Python aiohttp package.
* [asynctest](https://github.com/Martiusweb/asynctest/) ⭐ 310 | 🐛 50 | 🌐 Python | 📅 2024-04-22 - Enhance the standard unittest package with features for testing. asyncio libraries
* [aresponses](https://github.com/CircleUp/aresponses) ⭐ 106 | 🐛 5 | 🌐 Python | 📅 2024-07-11 - Asyncio http mocking. Similar to the [responses](https://github.com/getsentry/responses) ⭐ 4,345 | 🐛 40 | 🌐 Python | 📅 2026-08-26 library used for [requests](https://github.com/requests/requests) ⭐ 54,252 | 🐛 234 | 🌐 Python | 📅 2026-08-25.
* [aiomock](https://github.com/nhumrich/aiomock/) ⭐ 28 | 🐛 0 | 🌐 Python | 📅 2024-04-19 - A python mock library that supports async methods.

## Alternative Loops

*Alternative asyncio loop implementations.*

* [uvloop](https://github.com/MagicStack/uvloop) ⭐ 11,888 | 🐛 155 | 🌐 Cython | 📅 2026-07-14 - Ultra fast implementation of asyncio event loop on top of libuv.

## Misc

*Other awesome asyncio libraries.*

* [aiofiles](https://github.com/Tinche/aiofiles/) ⭐ 3,255 | 🐛 58 | 🌐 Python | 📅 2026-08-26 - File support for asyncio.
* [ruia](https://github.com/howie6879/ruia) ⭐ 1,738 | 🐛 9 | 🌐 Python | 📅 2023-07-01 - An async web scraping micro-framework based on asyncio.
* [asgiref](https://github.com/django/asgiref) ⭐ 1,631 | 🐛 67 | 🌐 Python | 📅 2026-08-10 - Backend utils for ASGI to WSGI integration, includes sync\_to\_async and async\_to\_sync function wrappers.
* [aiocache](https://github.com/argaen/aiocache) ⭐ 1,438 | 🐛 67 | 🌐 Python | 📅 2026-06-28 - Cache manager for different backends.
* [aiorun](https://github.com/cjrh/aiorun) ⭐ 468 | 🐛 2 | 🌐 Python | 📅 2026-08-20 - A `run()` function that handles all the usual boilerplate for startup and graceful shutdown.
* [kubernetes\_asyncio](https://github.com/tomplus/kubernetes_asyncio) ⭐ 436 | 🐛 31 | 🌐 Python | 📅 2026-08-12 - Asynchronous client library for Kubernetes.
* [aiomisc](https://github.com/aiokitchen/aiomisc) ⭐ 425 | 🐛 10 | 🌐 Python | 📅 2026-07-10 - Miscellaneous utils for `asyncio`.
* [aiopath](https://github.com/alexdelorenzo/aiopath) ⭐ 197 | 🐛 26 | 🌐 Python | 📅 2026-02-05 - Asynchronous `pathlib` for asyncio.
* [aiozipkin](https://github.com/aio-libs/aiozipkin) ⭐ 193 | 🐛 23 | 🌐 Python | 📅 2026-08-17 - Distributed tracing instrumentation for asyncio with zipkin
* [aiochan](https://github.com/zh217/aiochan) ⭐ 184 | 🐛 1 | 🌐 Python | 📅 2022-11-29 - CSP-style concurrency with channels, select and multiprocessing on top of asyncio.
* [aioserial](https://github.com/changyuheng/aioserial) ⭐ 145 | 🐛 15 | 🌐 Python | 📅 2022-07-25 - A drop-in replacement of [pySerial](https://github.com/pyserial/pyserial) ⭐ 3,565 | 🐛 340 | 🌐 Python | 📅 2026-05-19.
* [async\_property](https://github.com/ryananguiano/async_property) ⭐ 98 | 🐛 7 | 🌐 Python | 📅 2026-04-16 - Python decorator for async properties.
* [aiodebug](https://github.com/qntln/aiodebug) ⭐ 65 | 🐛 0 | 📅 2022-01-04 - A tiny library for monitoring and testing asyncio programs.
* [aiosc](https://github.com/artfwo/aiosc) ⭐ 39 | 🐛 0 | 🌐 Python | 📅 2026-07-11 -  Lightweight Open Sound Control implementation.
* [taskiq](https://taskiq-python.github.io/) - Asynchronous distributed task manager (like celery, but async).

## Writings

*Documentation, blog posts, and other awesome writing about asyncio.*

* [Official asyncio documentation](https://docs.python.org/3/library/asyncio.html) - Asynchronous I/O, event loop, coroutines and tasks.
* [Short well-written intro to asyncio](https://masnun.com/python-generators-coroutines-native-coroutines-and-async-await/) - Generators, Coroutines, Native Coroutines and async/await.
* [AsyncIO for the Working Python Developer](https://hackernoon.com/asyncio-for-the-working-python-developer-5c468e6e2e8e) - A gentle introduction to asynchronous programming from basic examples working up to URL fetching.
* [Test limits of Python aiohttp](https://pawelmhm.github.io/asyncio/python/aiohttp/2016/04/22/asyncio-aiohttp.html) - Making 1 million requests with python-aiohttp.
* [ASGI (Asynchronous Server Gateway Interface)](https://asgi.readthedocs.io/en/latest/) - A spiritual successor to WSGI, intended to provide a standard interface between async-capable Python web servers, frameworks, and applications.
* [First Principles Introduction to Asyncio](https://hackernoon.com/a-simple-introduction-to-pythons-asyncio-595d9c9ecf8c) - A no-buzzword first principles introduction to the internal workings of asyncio.
* [Developing and Testing an Asynchronous API with FastAPI and Pytest](https://testdriven.io/blog/fastapi-crud/) - This tutorial looks at how to develop and test an asynchronous API with FastAPI using Test-Driven Development (TDD).
* [Python Concurrency with asyncio](https://www.manning.com/books/python-concurrency-with-asyncio) - Learn how to speed up slow Python code with concurrent programming and the cutting-edge asyncio library.

## Talks

*Recordings of awesome talks about asyncio.*

* [Topics of Interest (Python Asyncio)](https://youtu.be/ZzfHjytDceU) | [screencast](https://youtu.be/lYe8W04ERnY) | [slides](https://speakerdeck.com/dabeaz/topics-of-interest-async) - PyCon Brasil 2015 keynote (David Beazley).
* [Python Asynchronous I/O Walkthrough](https://www.youtube.com/playlist?list=PLpEcQSRWP2IjVRlTUptdD05kG-UkJynQT) - 8-part code walkthrough (Philip Guo).
* [Async/await in Python 3.5 and why it is awesome](https://www.youtube.com/watch?v=m28fiN9y_r8\&t=132s) - EuroPython 2016 (Yury Selivanov).
* [Fear and Awaiting in Async: A Savage Journey to the Heart of the Coroutine Dream](https://www.youtube.com/watch?v=E-1Y4kSsAFc) | [screencast](https://www.youtube.com/watch?v=Bm96RqNGbGo) - PyOhio 2016 keynote (David Beazley).
* [Asynchronous Python for the Complete Beginner](https://www.youtube.com/watch?v=iG6fr81xHKA) | [slides](https://speakerdeck.com/pycon2017/miguel-grinberg-asynchronous-python-for-the-complete-beginner) - PyCon 2017 (Miguel Grinberg).
* [Demystifying Python's Async and Await Keywords](https://www.youtube.com/watch?v=F19R_M4Nay4) - JetBrains TV 2020 (Michael Kennedy)

## Alternatives to asyncio

*Alternative approaches to async programming in Python, some of which attempt to support some compatibility with `asyncio`, others are not compatible at all.*

* [trio](https://github.com/python-trio/trio) ⭐ 7,307 | 🐛 322 | 🌐 Python | 📅 2026-08-27 - Pythonic async I/O for humans and snake people.
  * [trio-asyncio](https://github.com/python-trio/trio-asyncio) ⭐ 204 | 🐛 31 | 🌐 Python | 📅 2026-05-18 - re-implementation of the asyncio mainloop on top of Trio.
* [curio](https://github.com/dabeaz/curio) ⚠️ Archived - The coroutine concurrency library.
  * [Curio-Asyncio Bridge](https://github.com/dabeaz/curio/issues/190) ⚠️ Archived - basic curio -> asyncio coroutine bridge.
* [AnyIO](https://github.com/agronholm/anyio) ⭐ 2,538 | 🐛 105 | 🌐 Python | 📅 2026-08-25 - High level asynchronous concurrency and networking framework that works on top of either trio or asyncio.

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-27._
