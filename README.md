<!--lint disable double-link-->

# Awesome FastAPI | [![Awesome](https://awesome.re/badge-flat.svg)](https://github.com/sindresorhus/awesome) ⭐ 458,031 | 🐛 67 | 📅 2026-04-19 with stars

> A curated list of awesome things related to FastAPI.

[FastAPI](https://fastapi.tiangolo.com/) is a modern, high-performance, batteries-included Python web framework that's perfect for building RESTful APIs.

## Contents

* [Third-Party Extensions](#third-party-extensions)
  * [Admin](#admin)
  * [Auth](#auth)
  * [CyberSecurity](#cybersecurity)
  * [Databases](#databases)
  * [Dependency Injection](#dependency-injection)
  * [Developer Tools](#developer-tools)
  * [Email](#email)
  * [Utils](#utils)
* [Resources](#resources)
  * [Official Resources](#official-resources)
  * [External Resources](#external-resources)
  * [Podcasts](#podcasts)
  * [Articles](#articles)
  * [Tutorials](#tutorials)
  * [Talks](#talks)
  * [Videos](#videos)
  * [Courses](#courses)
  * [Best Practices](#best-practices)
* [Hosting](#hosting)
  * [PaaS](#paas)
  * [IaaS](#iaas)
  * [Serverless](#serverless)
* [Projects](#projects)
  * [Boilerplate](#boilerplate)
  * [Docker Images](#docker-images)
  * [Open Source Projects](#open-source-projects)
* [Sponsors](#sponsors)

## Third-Party Extensions

### Admin

* [FastAPI Admin](https://github.com/fastapi-admin/fastapi-admin) ⭐ 3,757 | 🐛 75 | 🌐 Python | 📅 2025-04-05 - Functional admin panel that provides a user interface for performing CRUD operations on your data. Currently only works with the Tortoise ORM.
* [SQLAlchemy Admin](https://github.com/aminalaee/sqladmin) ⭐ 2,712 | 🐛 77 | 🌐 Python | 📅 2026-04-19 - Admin Panel for FastAPI/Starlette that works with SQLAlchemy models.
* [FastAPI Amis Admin](https://github.com/amisadmin/fastapi-amis-admin) ⭐ 1,539 | 🐛 77 | 🌐 Python | 📅 2025-12-15 - A high-performance, efficient and easily extensible FastAPI admin framework.
* [Starlette Admin](https://github.com/jowilf/starlette-admin) ⭐ 989 | 🐛 87 | 🌐 Python | 📅 2026-04-20 - Admin framework for FastAPI/Starlette, supporting SQLAlchemy, SQLModel, MongoDB, and ODMantic.
* [Piccolo Admin](https://github.com/piccolo-orm/piccolo_admin) ⭐ 467 | 🐛 41 | 🌐 Python | 📅 2026-03-06 - A powerful and modern admin GUI, using the Piccolo ORM.

### Auth

* [FastAPI Users](https://github.com/fastapi-users/fastapi-users) ⭐ 6,098 | 🐛 5 | 🌐 Python | 📅 2026-03-30 - Account management, authentication, authorization.
* [AuthX](https://github.com/yezz123/AuthX) ⭐ 1,168 | 🐛 5 | 🌐 Python | 📅 2026-04-20 - Customizable Authentications and Oauth2 management for FastAPI.
* [FastAPI JWT Auth](https://github.com/IndominusByte/fastapi-jwt-auth) ⭐ 826 | 🐛 61 | 🌐 Python | 📅 2024-04-12 - JWT auth (based on [Flask-JWT-Extended](https://github.com/vimalloc/flask-jwt-extended) ⭐ 1,586 | 🐛 18 | 🌐 Python | 📅 2024-12-30).
* [FastAPI Login](https://github.com/maxrdu/fastapi_login) ⭐ 823 | 🐛 1 | 🌐 Python | 📅 2025-05-20 - Account management and authentication (based on [Flask-Login](https://github.com/maxcountryman/flask-login) ⭐ 3,679 | 🐛 19 | 🌐 Python | 📅 2025-08-27).
* [FastAPI Azure Auth](https://github.com/Intility/fastapi-azure-auth) ⭐ 673 | 🐛 16 | 🌐 Python | 📅 2025-11-01 - Azure AD authentication for your APIs with single and multi tenant support.
* [FastAPI Permissions](https://github.com/holgi/fastapi-permissions) ⭐ 658 | 🐛 18 | 🌐 Python | 📅 2023-10-16 - Row-level permissions.
* [FastAPI Simple Security](https://github.com/mrtolkien/fastapi_simple_security) ⭐ 471 | 🐛 1 | 🌐 Python | 📅 2023-12-19 - Out-of-the-box API key security manageable through path operations.
* [FastAPI Cloud Auth](https://github.com/tokusumi/fastapi-cloudauth) ⭐ 437 | 🐛 37 | 🌐 Python | 📅 2023-05-17 - Simple integration between FastAPI and cloud authentication services (AWS Cognito, Auth0, Firebase Authentication).
* [FastAPI Auth](https://github.com/dmontagu/fastapi-auth) ⭐ 268 | 🐛 5 | 🌐 Python | 📅 2023-02-14 - Pluggable auth that supports the OAuth2 Password Flow with JWT access and refresh tokens.
* [FastAPI Security](https://github.com/jacobsvante/fastapi-security) ⚠️ Archived - Implements authentication and authorization as dependencies in FastAPI.
* [FastAPI Casbin Auth](https://github.com/officialpycasbin/fastapi-casbin-auth) ⭐ 21 | 🐛 6 | 🌐 Python | 📅 2026-04-14 - Authorization which supports various access control models like RBAC, ReBAC and ABAC through Casbin.

### CyberSecurity

* [FastAPI Guard](https://github.com/rennf93/fastapi-guard) ⭐ 730 | 🐛 1 | 🌐 Python | 📅 2026-04-22 - Rate Limiting, Automatically Ban IPs, Penetration Attack Detection, Whitelist/blacklist (countries, IPs, Cloud Providers), User Agent Filtering, Geolocation, Redis integration for persistence, and more.

### Databases

#### ORMs

* [GINO](https://github.com/python-gino/gino) ⭐ 2,810 | 🐛 55 | 🌐 Python | 📅 2022-02-12 - A lightweight asynchronous ORM built on top of SQLAlchemy core for Python asyncio.
  * [FastAPI Example](https://github.com/leosussan/fastapi-gino-arq-uvicorn) ⭐ 557 | 🐛 5 | 🌐 Python | 📅 2022-12-08
* [Piccolo](https://github.com/piccolo-orm/piccolo) ⭐ 1,892 | 🐛 40 | 🌐 Python | 📅 2026-04-15 - An async ORM and query builder, supporting Postgres and SQLite, with batteries (migrations, security, etc).
  * [FastAPI Examples](https://github.com/piccolo-orm/piccolo_examples) ⭐ 108 | 🐛 1 | 🌐 Python | 📅 2025-03-06 - Using FastAPI with Piccolo.
* [ORM](https://github.com/encode/orm) ⚠️ Archived - An async ORM.
* [Tortoise ORM](https://tortoise.github.io) - An easy-to-use asyncio ORM (Object Relational Mapper) inspired by Django.
  * [Aerich](https://github.com/tortoise/aerich) ⭐ 1,090 | 🐛 28 | 🌐 Python | 📅 2026-04-08 - Tortoise ORM migrations tools.
  * [FastAPI Example](https://tortoise.github.io/examples/fastapi.html) - An example of the Tortoise-ORM FastAPI integration.
  * [Tutorial: Setting up Tortoise ORM with FastAPI](https://web.archive.org/web/20200523174158/https://robwagner.dev/tortoise-fastapi-setup/)
* [FastAPI SQLAlchemy](https://github.com/mfreeborn/fastapi-sqlalchemy) ⭐ 756 | 🐛 20 | 🌐 Python | 📅 2024-04-09 - Simple integration between FastAPI and [SQLAlchemy](https://www.sqlalchemy.org/).
* [Fastapi-SQLA](https://github.com/dialoguemd/fastapi-sqla) ⭐ 443 | 🐛 12 | 🌐 Python | 📅 2026-04-21 - SQLAlchemy extension for FastAPI with support for pagination, asyncio, and pytest.
* [Edgy ORM](https://github.com/dymmond/edgy) ⭐ 427 | 🐛 1 | 🌐 Python | 📅 2026-04-11 - Complex databases made simple.
* [Saffier ORM](https://github.com/tarsil/saffier) ⭐ 150 | 🐛 0 | 🌐 Python | 📅 2026-04-20 - The only Python ORM you will ever need.
* [FastAPIwee](https://github.com/Ignisor/FastAPIwee) ⭐ 106 | 🐛 1 | 🌐 Python | 📅 2021-07-09 - A simple way to create REST API based on [PeeWee](https://github.com/coleifer/peewee) ⭐ 11,961 | 🐛 1 | 🌐 Python | 📅 2026-04-20 models.
* [FastSQLA](https://github.com/hadrien/FastSQLA) ⭐ 82 | 🐛 0 | 🌐 Python | 📅 2026-02-26 - Async SQLAlchemy 2.0+ extension for FastAPI with SQLModel support, built-in pagination & more.
* [ormar](https://collerek.github.io/ormar/) - Ormar is an async ORM that uses Pydantic validation and can be used directly in FastAPI requests and responses so you are left with only one set of models to maintain. Alembic migrations included.
  * [FastAPI Example](https://collerek.github.io/ormar/latest/fastapi/) - Using FastAPI with ormar.
* [SQLModel](https://sqlmodel.tiangolo.com/) - SQLModel (which is powered by Pydantic and SQLAlchemy) is a library for interacting with SQL databases from Python code, with Python objects.

#### Query Builders

* [Databases](https://github.com/encode/databases) ⚠️ Archived - Async SQL query builder that works on top of the [SQLAlchemy Core](https://docs.sqlalchemy.org/en/latest/core/) expression language.
* [PyPika](https://github.com/kayak/pypika) ⭐ 2,900 | 🐛 230 | 🌐 Python | 📅 2026-02-04 - A SQL query builder that exposes the full richness of the SQL language.
* [asyncpgsa](https://github.com/CanopyTax/asyncpgsa) ⭐ 510 | 🐛 15 | 🌐 Python | 📅 2024-02-17 - A wrapper around [asyncpg](https://github.com/MagicStack/asyncpg) ⭐ 8,000 | 🐛 268 | 🌐 Python | 📅 2026-02-27 for use with [SQLAlchemy Core](https://docs.sqlalchemy.org/en/latest/core/).

#### ODMs

* [MongoEngine](https://github.com/MongoEngine/mongoengine) ⭐ 4,352 | 🐛 348 | 🌐 Python | 📅 2026-03-10 - A Document-Object Mapper (think ORM, but for document databases) for working with MongoDB from Python.
* [Beanie](https://github.com/BeanieODM/beanie) ⭐ 2,675 | 🐛 86 | 🌐 Python | 📅 2026-04-20 - Asynchronous Python ODM for MongoDB, based on [Motor](https://motor.readthedocs.io/en/stable/) and [Pydantic](https://docs.pydantic.dev/latest/), which supports data and schema migrations out of the box.
* [PynamoDB](https://github.com/pynamodb/PynamoDB) ⭐ 2,649 | 🐛 317 | 🌐 Python | 📅 2026-01-06 - A pythonic interface to Amazon's DynamoDB.
* [Motor](https://motor.readthedocs.io/) - Asynchronous Python driver for MongoDB.
* [ODMantic](https://art049.github.io/odmantic/) - AsyncIO MongoDB ODM integrated with [Pydantic](https://docs.pydantic.dev/latest/).

#### Other Tools

* [Pydantic-SQLAlchemy](https://github.com/tiangolo/pydantic-sqlalchemy) ⭐ 1,404 | 🐛 9 | 🌐 Python | 📅 2025-11-25 - Convert SQLAlchemy models to [Pydantic](https://docs.pydantic.dev/latest/) models.
* [FastAPI-CamelCase](https://nf1s.github.io/fastapi-camelcase/) - CamelCase JSON support for FastAPI utilizing [Pydantic](https://docs.pydantic.dev/latest/).
  * [CamelCase Models with FastAPI and Pydantic](https://medium.com/analytics-vidhya/camel-case-models-with-fast-api-and-pydantic-5a8acb6c0eee) - Accompanying blog post from the author of the extension.

### Dependency Injection

* [Wireup](https://github.com/maldoinc/wireup) ⭐ 388 | 🐛 18 | 🌐 Python | 📅 2026-04-18 - Inject dependencies with zero runtime overhead in FastAPI; Share dependencies across web, cli or other interfaces.

### Developer Tools

* [Manage FastAPI](https://github.com/ycd/manage-fastapi) ⭐ 1,902 | 🐛 22 | 🌐 Python | 📅 2024-03-01 - CLI tool for generating and managing FastAPI projects.
* [FastAPI Code Generator](https://github.com/koxudaxi/fastapi-code-generator) ⭐ 1,385 | 🐛 81 | 🌐 Python | 📅 2026-04-23 - Create a FastAPI app from an OpenAPI file, enabling schema-driven development.
* [FastAPI Versioning](https://github.com/DeanWay/fastapi-versioning) ⭐ 846 | 🐛 35 | 🌐 Python | 📅 2023-07-25 - API versioning.
* [FastAPI MVC](https://github.com/fastapi-mvc/fastapi-mvc) ⭐ 798 | 🐛 33 | 🌐 Python | 📅 2026-04-14 - Developer productivity tool for making high-quality FastAPI production-ready APIs.
* [FastAPI Client Generator](https://github.com/dmontagu/fastapi_client) ⭐ 431 | 🐛 11 | 🌐 Python | 📅 2023-07-06 - Generate a mypy- and IDE-friendly API client from an OpenAPI spec.
* [FastAPI Profiler](https://github.com/sunhailin-Leo/fastapi_profiler) ⭐ 366 | 🐛 0 | 🌐 Python | 📅 2026-03-24 - A FastAPI Middleware of joerick/pyinstrument to check your service performance.
* [msgpack-asgi](https://github.com/florimondmanca/msgpack-asgi) ⭐ 278 | 🐛 1 | 🌐 Python | 📅 2026-02-03 - Automatic [MessagePack](https://msgpack.org/) content negotiation.
* [Jupyter Notebook REST API](https://github.com/Invictify/Jupter-Notebook-REST-API) ⭐ 167 | 🐛 11 | 🌐 Jupyter Notebook | 📅 2022-12-08 - Run your Jupyter notebooks as RESTful API endpoints.
* [FastAPI Cruddy Framework](https://github.com/mdconaway/fastapi-cruddy-framework) ⭐ 126 | 🐛 0 | 🌐 Python | 📅 2026-04-13 - A companion library to FastAPI designed to bring the development productivity of Ruby on Rails, Ember.js or Sails.js to the FastAPI ecosystem.
* [python-cqrs](https://github.com/pypatterns/python-cqrs) ⭐ 49 | 🐛 3 | 🌐 Python | 📅 2026-04-06 - Event-Driven Architecture Framework with CQRS, Transaction Outbox, Saga orchestration, seamless FastAPI/FastStream integration.

### Email

* [FastAPI Mail](https://github.com/sabuhish/fastapi-mail) ⭐ 993 | 🐛 27 | 🌐 Python | 📅 2026-03-06 - Lightweight mail system for sending emails and attachments (individual and bulk).

### Utils

* [Strawberry GraphQL](https://github.com/strawberry-graphql/strawberry) ⭐ 4,649 | 🐛 451 | 🌐 Python | 📅 2026-04-22 - Python GraphQL library based on dataclasses.
* [FastAPI Utilities](https://github.com/fastapiutils/fastapi-utils) ⭐ 2,307 | 🐛 69 | 🌐 Python | 📅 2025-03-03 - Reusable utilities: class-based views, response inferring router, periodic tasks, timing middleware, SQLAlchemy session, OpenAPI spec simplification.
* [SlowApi](https://github.com/laurents/slowapi) ⭐ 1,957 | 🐛 102 | 🌐 Python | 📅 2026-04-21 - Rate limiter (based on [Flask-Limiter](https://flask-limiter.readthedocs.io)).
* [FastAPI Cache](https://github.com/long2ice/fastapi-cache) ⭐ 1,857 | 🐛 106 | 🌐 Python | 📅 2025-06-30 - A tool to cache FastAPI response and function results, with support for Redis, Memcached, DynamoDB, and in-memory backends.
* [FastAPI Pagination](https://github.com/uriyyo/fastapi-pagination) ⭐ 1,645 | 🐛 7 | 🌐 Python | 📅 2026-04-23 - Pagination for FastAPI.
* [FastAPI FastCRUD](https://github.com/benavlabs/fastcrud) ⭐ 1,509 | 🐛 22 | 🌐 Python | 📅 2026-03-11) - Robust async CRUD operations and flexible endpoint creation utilities.
* [Prometheus FastAPI Instrumentator](https://github.com/trallnag/prometheus-fastapi-instrumentator) ⭐ 1,448 | 🐛 67 | 🌐 Python | 📅 2025-10-01 - A configurable and modular Prometheus Instrumentator for your FastAPI application.
* [OpenTelemetry FastAPI Instrumentation](https://github.com/open-telemetry/opentelemetry-python-contrib/tree/main/instrumentation/opentelemetry-instrumentation-fastapi) ⭐ 1,032 | 🐛 672 | 🌐 Python | 📅 2026-04-22 - Library provides automatic and manual instrumentation of FastAPI web frameworks, instrumenting http requests served by applications utilizing the framework.
* [FastAPI Limiter](https://github.com/long2ice/fastapi-limiter) ⭐ 768 | 🐛 29 | 🌐 Python | 📅 2026-02-06 - A request rate limiter for FastAPI.
* [FastAPI Contrib](https://github.com/identixone/fastapi_contrib) ⭐ 741 | 🐛 15 | 🌐 Python | 📅 2022-09-12 - Opinionated set of utilities: pagination, auth middleware, permissions, custom exception handlers, MongoDB support, and Opentracing middleware.
* [ASGI Correlation ID](https://github.com/snok/asgi-correlation-id) ⭐ 637 | 🐛 4 | 🌐 Python | 📅 2024-10-17 - Request ID logging middleware.
* [FastAPI Plugins](https://github.com/madkote/fastapi-plugins) ⭐ 616 | 🐛 3 | 🌐 Python | 📅 2025-07-09 - Redis and Scheduler plugins.
* [FastAPI Events](https://github.com/melvinkcx/fastapi-events) ⭐ 610 | 🐛 11 | 🌐 Python | 📅 2024-12-21 - Asynchronous event dispatching/handling library for FastAPI and Starlette.
* [Starlette Context](https://github.com/tomwojcik/starlette-context) ⭐ 608 | 🐛 3 | 🌐 Python | 📅 2026-04-14 - Allows you to store and access the request data anywhere in your project, useful for logging.
* [FastAPI SocketIO](https://github.com/pyropy/fastapi-socketio) ⚠️ Archived - Easy integration for FastAPI and SocketIO.
* [Starlette Exporter](https://github.com/stephenhillier/starlette_exporter) ⭐ 412 | 🐛 10 | 🌐 Python | 📅 2024-10-15 - One more prometheus integration for FastAPI and Starlette.
* [FastAPI MQTT](https://github.com/sabuhish/fastapi-mqtt) ⭐ 387 | 🐛 5 | 🌐 Python | 📅 2024-05-22 - An extension for the MQTT protocol.
* [Starlette Prometheus](https://github.com/perdy/starlette-prometheus) ⭐ 378 | 🐛 15 | 🌐 Python | 📅 2024-05-20 - Prometheus integration for FastAPI and Starlette.
* [Pydantic Resolve](https://github.com/allmonday/pydantic-resolve) ⭐ 319 | 🐛 1 | 🌐 Python | 📅 2026-04-22 -  Turns pydantic class into a powerful composable computing container by introducing resolve and post-process hooks.
* [FastAPI Cache](https://github.com/comeuplater/fastapi_cache) ⭐ 306 | 🐛 10 | 🌐 Python | 📅 2026-04-13 - A simple lightweight cache system.
* [FastAPI Injectable](https://github.com/JasperSui/fastapi-injectable) ⭐ 290 | 🐛 1 | 🌐 Python | 📅 2026-04-14 - Use FastAPI's dependency injection outside route handlers in CLI tools, background tasks, workers, and more.
* [FastAPI Chameleon](https://github.com/mikeckennedy/fastapi-chameleon) ⭐ 228 | 🐛 1 | 🌐 Python | 📅 2025-04-04 - Adds integration of the Chameleon template language to FastAPI.
* [Apitally](https://github.com/apitally/apitally-py) ⭐ 219 | 🐛 4 | 🌐 Python | 📅 2026-04-20 - API analytics, monitoring, and request logging for FastAPI.
* [FastAPI Lazy](https://github.com/yezz123/fastango) ⭐ 202 | 🐛 3 | 🌐 Python | 📅 2024-04-29 - Lazy package to start your project using FastAPI.
* [FastAPI Jinja](https://github.com/AGeekInside/fastapi-jinja) ⭐ 158 | 🐛 1 | 🌐 Python | 📅 2024-11-16 - Adds integration of the Jinja template language to FastAPI.
* [FastAPI FeatureFlags](https://github.com/Pytlicek/fastapi-featureflags) ⭐ 154 | 🐛 4 | 🌐 Python | 📅 2024-06-10 - Simple implementation of feature flags for FastAPI.
* [Starlette OpenTracing](https://github.com/acidjunk/starlette-opentracing) ⭐ 151 | 🐛 1 | 🌐 Python | 📅 2021-11-17 - Opentracing support for Starlette and FastAPI.
* [FastAPI Listing](https://github.com/danielhasan1/fastapi-listing) ⭐ 140 | 🐛 6 | 🌐 Python | 📅 2025-02-28 - A library to design/build listing APIs using component-based architecture, inbuilt query paginator, sorter, django-admin like filters & much more.
* [FastAPI CloudEvents](https://github.com/sasha-tkachev/fastapi-cloudevents) ⭐ 121 | 🐛 1 | 🌐 Python | 📅 2025-07-26 - [CloudEvents](https://cloudevents.io/) integration for FastAPI.
* [FastAPI ServiceUtils](https://github.com/skallfass/fastapi_serviceutils) ⭐ 119 | 🐛 2 | 🌐 Python | 📅 2021-07-29 - Generator for creating API services.
* [FastAPI Opentracing](https://github.com/wesdu/fastapi-opentracing) ⭐ 110 | 🐛 7 | 🌐 Python | 📅 2023-02-06 - Opentracing middleware and database tracing support for FastAPI.
* [FastAPI Websocket Pub/Sub](https://github.com/authorizon/fastapi_websocket_pubsub) ⭐ 102 | 🐛 0 | 🌐 Python | 📅 2021-12-10 - The classic pub/sub pattern made easily accessible and scalable over the web and across your cloud in realtime.
* [Prerender Python Starlette](https://github.com/BeeMyDesk/prerender-python-starlette) ⚠️ Archived - Starlette middleware for Prerender.
* [FastAPI Websocket RPC](https://github.com/authorizon/fastapi_websocket_rpc) ⭐ 92 | 🐛 0 | 🌐 Python | 📅 2021-12-10 - RPC (bidirectional JSON RPC) over Websockets made easy, robust, and production ready.
* [FastAPI Shield](https://github.com/jymchng/fastapi-shield) ⭐ 19 | 🐛 3 | 🌐 Python | 📅 2026-01-23 - General FastAPI library for writing any generic endpoint decorators capable of lazy dependencies injection.

## Resources

### Official Resources

* [Documentation](https://fastapi.tiangolo.com/) - Comprehensive documentation.
* [Tutorial](https://fastapi.tiangolo.com/tutorial/) - Official tutorial showing you how to use FastAPI with most of its features, step by step.
* [Source Code](https://github.com/fastapi/fastapi) ⭐ 97,541 | 🐛 169 | 🌐 Python | 📅 2026-04-22 - Hosted on GitHub.
* [Discord](https://discord.com/invite/VQjSZaeJmf) - Chat with other FastAPI users.

### External Resources

* [TestDriven.io FastAPI](https://testdriven.io/blog/topics/fastapi/) - Multiple FastAPI-specific articles that focus on developing and testing production-ready RESTful APIs, serving up machine learning models, and more.

### Podcasts

* [Build The Next Generation Of Python Web Applications With FastAPI](https://www.pythonpodcast.com/fastapi-web-application-framework-episode-259/) - In this episode of [Podcast Init](https://www.pythonpodcast.com/), the creator of FastAPI, [Sebastián Ramirez](https://tiangolo.com/), shares his motivations for building FastAPI and how it works under the hood.
* [FastAPI on PythonBytes](https://pythonbytes.fm/episodes/show/123/time-to-right-the-py-wrongs?time_in_sec=855) - Nice overview of the project.

### Articles

* [FastAPI has Ruined Flask Forever for Me](https://medium.com/data-science/fastapi-has-ruined-flask-forever-for-me-73916127da)
* [Why we switched from Flask to FastAPI for production machine learning](https://medium.com/@calebkaiser/why-we-switched-from-flask-to-fastapi-for-production-machine-learning-765aab9b3679) - In-depth look at why you may want to move from Flask to FastAPI.

### Tutorials

* [Async SQLAlchemy with FastAPI](https://stribny.name/posts/fastapi-asyncalchemy/) - Learn how to use SQLAlchemy asynchronously.
* [Deploy Machine Learning Models with Keras, FastAPI, Redis and Docker](https://medium.com/analytics-vidhya/deploy-machine-learning-models-with-keras-fastapi-redis-and-docker-4940df614ece)
* [Developing and Testing an Asynchronous API with FastAPI and Pytest](https://testdriven.io/blog/fastapi-crud/) - Develop and test an asynchronous API with FastAPI, Postgres, Pytest, and Docker using Test-Driven Development.
* [FastAPI for Flask Users](https://amitness.com/posts/fastapi-vs-flask) - Learn FastAPI with a side-by-side code comparison to Flask.
* [Implementing FastAPI Services – Abstraction and Separation of Concerns](https://camillovisini.com/coding/abstracting-fastapi-services) - FastAPI application and service structure for a more maintainable codebase.
* [Introducing FARM Stack - FastAPI, React, and MongoDB](https://www.mongodb.com/docs/languages/python/pymongo-driver/current/integrations/fastapi-integration/) - Getting started with a complete FastAPI web application stack.
* [Multitenancy with FastAPI, SQLAlchemy and PostgreSQL](https://mergeboard.com/blog/6-multitenancy-fastapi-sqlalchemy-postgresql/) - Learn how to make FastAPI applications multi-tenant ready.
* [Porting Flask to FastAPI for ML Model Serving](https://www.pluralsight.com/tech-blog/porting-flask-to-fastapi-for-ml-model-serving/) - Comparison of Flask vs FastAPI.
* [Real-time data streaming using FastAPI and WebSockets](https://stribny.name/posts/real-time-data-streaming-using-fastapi-and-websockets/) - Learn how to stream data from FastAPI directly into a real-time chart.
* [Running FastAPI applications in production](https://stribny.name/posts/fastapi-production/) - Use Gunicorn with systemd for production deployments.
* [Serving Machine Learning Models with FastAPI in Python](https://medium.com/@8B_EC/tutorial-serving-machine-learning-models-with-fastapi-in-python-c1a27319c459) - Use FastAPI to quickly and easily deploy and serve machine learning models in Python as a RESTful API.
* [Streaming video with FastAPI](https://stribny.name/posts/fastapi-video/) - Learn how to serve video streams.
* [Using Hypothesis and Schemathesis to Test FastAPI](https://testdriven.io/blog/fastapi-hypothesis/) - Apply property-based testing to FastAPI.

### Talks

* [PyConBY 2020: Serve ML models easily with FastAPI](https://www.youtube.com/watch?v=z9K5pwb0rt8) - From the talk by Sebastian Ramirez you will learn how to easily build a production-ready web (JSON) API for your ML models with FastAPI, including best practices by default.
* [PyCon UK 2019: FastAPI from the ground up](https://www.youtube.com/watch?v=3DLwPcrE5mA) - This talk shows how to build a simple REST API for a database from the ground up using FastAPI.

### Videos

* [Building a Stock Screener with FastAPI](https://www.youtube.com/watch?v=5GorMC2lPpk) - A you build a web-based stock screener with FastAPI, you'll be introduced to many of FastAPI's features, including Pydantic models, dependency injection, background tasks, and SQLAlchemy integration.
* [Building Web APIs Using FastAPI](https://www.youtube.com/watch?v=Pe66M8mn-wA) - Use FastAPI to build a web application programming interface (RESTful API).
* [FastAPI - A Web Framework for Python](https://www.youtube.com/watch?v=PUhio8CprhI\&list=PL5gdMNl42qynpY-o43Jk3evfxEKSts3HS) - See how to do numeric validations with FastAPI.
* [FastAPI vs. Django vs. Flask](https://www.youtube.com/watch?v=9YBAOYQOzWs) - Which framework is best for Python in 2020? Which uses async/await the best? Which is the fastest?
* [Serving Machine Learning Models As API with FastAPI](https://www.youtube.com/watch?v=mkDxuRvKUL8) - Build a machine learning API with FastAPI.

### Courses

* [Test-Driven Development with FastAPI and Docker](https://testdriven.io/courses/tdd-fastapi/) - Learn how to build, test, and deploy a text summarization microservice with Python, FastAPI, and Docker.
* [Modern APIs with FastAPI and Python](https://training.talkpython.fm/courses/modern-fastapi-apis) - A course designed to get you creating new APIs running in the cloud with FastAPI quickly.
* [Full Web Apps with FastAPI Course](https://training.talkpython.fm/courses/full-html-web-applications-with-fastapi) - You'll learn to build full web apps with FastAPI, equivalent to what you can do with Flask or Django.
* [The Definitive Guide to Celery and FastAPI](https://testdriven.io/courses/fastapi-celery/) - Learn how to add Celery to a FastAPI application to provide asynchronous task processing.

### Best Practices

* [FastAPI Best Practices](https://github.com/zhanymkanov/fastapi-best-practices) ⭐ 17,057 | 🐛 12 | 📅 2026-04-14 - Collection of best practices in a GitHub repo.
* [FastAPI Clean Example](https://github.com/ivan-borovets/fastapi-clean-example) ⭐ 537 | 🐛 0 | 🌐 Python | 📅 2026-04-17 - Clean Architecture backend example built with FastAPI.
* [FastAPI-Dishka-FastStream](https://github.com/faststream-community/fastapi-dishka-faststream) ⭐ 314 | 🐛 0 | 🌐 Python | 📅 2026-04-22 - Combines FastAPI, dishka, faststream, sqlalchemy, pydantic.

## Hosting

### PaaS

(Platforms-as-a-Service)

* [AWS Elastic Beanstalk](https://aws.amazon.com/elasticbeanstalk/)
* [Fly](https://fly.io) ([tutorial](https://fly.io/docs/python/frameworks/fastapi/), [Deploy from a Git repo](https://github.com/fly-apps/hello-fastapi) ⭐ 16 | 🐛 2 | 🌐 Python | 📅 2026-02-27)
* [Google App Engine](https://cloud.google.com/appengine)
* [Heroku](https://www.heroku.com/) ([Step-by-step tutorial](https://tutlinks.com/create-and-deploy-fastapi-app-to-heroku/), [ML model on Heroku tutorial](https://testdriven.io/blog/fastapi-machine-learning/))
* [Microsoft Azure App Service](https://azure.microsoft.com/en-us/products/app-service/)

### IaaS

(Infrastructure-as-a-Service)

* [AWS EC2](https://aws.amazon.com/ec2/)
* [Google Compute Engine](https://cloud.google.com/compute)
* [Digital Ocean](https://www.digitalocean.com/)
* [Linode](https://www.linode.com/)

### Serverless

Frameworks:

* [Chalice](https://github.com/aws/chalice) ⭐ 11,046 | 🐛 495 | 🌐 Python | 📅 2025-05-29
* [Vercel](https://vercel.com/) - (formerly Zeit) ([example](https://github.com/Snailedlt/Markdown-Videos) ⭐ 174 | 🐛 28 | 🌐 Python | 📅 2025-11-21).
* [Mangum](https://mangum.io/) - Adapter for running ASGI applications with AWS Lambda and API Gateway.

Compute:

* [Google Cloud Run](https://cloud.google.com/run) ([example](https://github.com/anthonycorletti/cloudrun-fastapi) ⭐ 287 | 🐛 0 | 🌐 Python | 📅 2024-10-07)
* [AWS Lambda](https://aws.amazon.com/lambda/) ([example](https://github.com/iwpnd/fastapi-aws-lambda-example) ⭐ 142 | 🐛 3 | 🌐 Python | 📅 2021-07-23)
* [Google Cloud Functions](https://cloud.google.com/functions)
* [Azure Functions](https://azure.microsoft.com/en-us/products/functions/)

## Projects

### Boilerplate

* [Full Stack FastAPI and PostgreSQL - Base Project Generator](https://github.com/fastapi/full-stack-fastapi-template) ⭐ 42,800 | 🐛 28 | 🌐 TypeScript | 📅 2026-04-21 - Full Stack FastAPI Template
  , which includes FastAPI, React, SQLModel, PostgreSQL, Docker, GitHub Actions, automatic HTTPS, and more (developed by the creator of FastAPI, [Sebastián Ramírez](https://github.com/tiangolo)).
* [FastAPI template](https://github.com/s3rius/FastAPI-template) ⭐ 2,776 | 🐛 41 | 🌐 Python | 📅 2026-04-22 - Flexible, lightweight FastAPI project generator. It includes support for SQLAlchemy, multiple databases, CI/CD, Docker, and Kubernetes.
* [FastAPI and React Template](https://github.com/Buuntu/fastapi-react) ⭐ 2,583 | 🐛 42 | 🌐 Python | 📅 2023-10-06 - Full stack cookiecutter boilerplate using FastAPI, TypeScript, Docker, PostgreSQL, and React.
* [openapi-python-client](https://github.com/openapi-generators/openapi-python-client) ⭐ 1,936 | 🐛 109 | 🌐 Python | 📅 2026-04-10 - Generate modern FastAPI Python clients (via FastAPI) from OpenAPI.
* [fastapi-alembic-sqlmodel-async](https://github.com/vargasjona/fastapi-alembic-sqlmodel-async) ⭐ 1,272 | 🐛 9 | 🌐 Python | 📅 2026-03-09 - This is a project template which uses FastAPI, Alembic, and async SQLModel as ORM.
* [FastAPI Nano](https://github.com/rednafi/fastapi-nano) ⭐ 1,035 | 🐛 3 | 🌐 Python | 📅 2025-01-01 - Simple FastAPI template with factory pattern architecture.
* [Full Stack FastAPI and MongoDB - Base Project Generator](https://github.com/mongodb-labs/full-stack-fastapi-mongodb) ⭐ 812 | 🐛 8 | 🌐 TypeScript | 📅 2025-05-09 - Full stack, modern web application generator, which includes FastAPI, MongoDB, Docker, Celery, React frontend, automatic HTTPS and more.
* [cookiecutter-fastapi](https://github.com/arthurhenrique/cookiecutter-fastapi) ⭐ 707 | 🐛 1 | 🌐 Python | 📅 2025-08-25 - Cookiecutter template for FastAPI projects using: Machine Learning, Poetry, Azure Pipelines and pytest.
* [cookiecutter-spacy-fastapi](https://github.com/microsoft/cookiecutter-spacy-fastapi) ⭐ 621 | 🐛 6 | 🌐 Python | 📅 2022-11-28 - Quick deployments of spaCy models with FastAPI.
* [FastAPI Model Server Skeleton](https://github.com/eightBEC/fastapi-ml-skeleton) ⭐ 604 | 🐛 8 | 🌐 Python | 📅 2026-01-08 - Skeleton app to serve machine learning models production-ready.
* [fastapi-gino-arq-uvicorn](https://github.com/leosussan/fastapi-gino-arq-uvicorn) ⭐ 557 | 🐛 5 | 🌐 Python | 📅 2022-12-08 - Template for a high-performance async REST API, in Python. FastAPI + GINO + Arq + Uvicorn (w/ Redis and PostgreSQL).
* [FastAPI on Google Cloud Run](https://github.com/anthonycorletti/cloudrun-fastapi) ⭐ 287 | 🐛 0 | 🌐 Python | 📅 2024-10-07 - Boilerplate for API building with FastAPI, SQLModel, and Google Cloud Run.
* [FastAPI and Tortoise ORM](https://github.com/prostomarkeloff/fastapi-tortoise) ⭐ 223 | 🐛 0 | 🌐 Python | 📅 2024-06-27 - Powerful but simple template for web APIs w/ FastAPI (as web framework) and Tortoise-ORM (for working via database without headache).
* [fastapi-starter-project](https://github.com/mirzadelic/fastapi-starter-project) ⭐ 216 | 🐛 0 | 🌐 Python | 📅 2022-11-27 - A project template which uses FastAPI, SQLModel, Alembic, Pytest, Docker, GitHub Actions CI.
* [FastAPI with Firestore](https://github.com/anthonycorletti/firestore-fastapi) ⭐ 134 | 🐛 2 | 🌐 Python | 📅 2024-10-07 - Boilerplate for API building with FastAPI and Google Cloud Firestore.
* [Uvicorn Poetry FastAPI Project Template](https://github.com/max-pfeiffer/uvicorn-poetry-fastapi-project-template) ⭐ 105 | 🐛 5 | 🌐 Python | 📅 2025-10-01 - Cookiecutter project template for starting a FastAPI application. Runs in a Docker container with Uvicorn ASGI server on Kubernetes. Supports AMD64 and ARM64 CPU architectures.
* [Pywork](https://github.com/vutran1710/YeomanPywork) ⚠️ Archived - [Yeoman](https://yeoman.io/) generator to scaffold a FastAPI app.

### Docker Images

* [uvicorn-gunicorn-fastapi-docker](https://github.com/tiangolo/uvicorn-gunicorn-fastapi-docker) ⭐ 2,912 | 🐛 8 | 🌐 Python | 📅 2026-03-25 - Docker image with Uvicorn managed by Gunicorn for high-performance FastAPI web applications in Python 3.7 and 3.6 with performance auto-tuning.
* [inboard](https://github.com/br3ndonland/inboard) ⭐ 319 | 🐛 0 | 🌐 Python | 📅 2026-04-04 - Docker images to power your FastAPI apps and help you ship faster.
* [uvicorn-poetry](https://github.com/max-pfeiffer/uvicorn-poetry) ⭐ 140 | 🐛 6 | 🌐 Python | 📅 2025-10-01 - Docker image with Uvicorn ASGI server for running Python web applications on Kubernetes. Uses Poetry for managing dependencies and setting up a virtual environment. Supports AMD64 and ARM64 CPU architectures.
* [uvicorn-gunicorn-poetry](https://github.com/max-pfeiffer/uvicorn-gunicorn-poetry) ⭐ 131 | 🐛 0 | 🌐 Python | 📅 2024-04-21 - Docker image with Gunicorn using Uvicorn workers for running Python web applications. Uses Poetry for managing dependencies and setting up a virtual environment. Supports AMD64 and ARM64 CPU architectures.

### Open Source Projects

* [Polar](https://github.com/polarsource/polar) ⭐ 9,707 | 🐛 323 | 🌐 Python | 📅 2026-04-22 - A funding and monetization platform for developers, built with FastAPI, SQLAlchemy, Alembic, and Arq.
* [Dispatch](https://github.com/Netflix/dispatch) ⚠️ Archived - Manage security incidents.
* [RealWorld Example App - postgres](https://github.com/nsidnev/fastapi-realworld-example-app) ⚠️ Archived
* [TermPair](https://github.com/cs01/termpair) ⭐ 1,732 | 🐛 2 | 🌐 Rust | 📅 2026-03-25 - View and control terminals from your browser with end-to-end encryption.
* [Awesome FastAPI Projects](https://github.com/Kludex/awesome-fastapi-projects) ⭐ 1,600 | 🐛 13 | 🌐 TypeScript | 📅 2026-03-30 - Organized list of projects that use FastAPI.
* [FastAPI with Observability](https://github.com/Blueswen/fastapi-observability) ⭐ 1,088 | 🐛 6 | 🌐 Python | 📅 2026-04-12 - Observe FastAPI app with three pillars of observability: Traces (Tempo), Metrics (Prometheus), Logs (Loki) on Grafana through OpenTelemetry and OpenMetrics.
* [Bitcart](https://github.com/bitcart/bitcart) ⭐ 927 | 🐛 41 | 🌐 Python | 📅 2026-04-22 - Platform for merchants, users and developers which offers easy setup and use.
* [FastAPI with Celery, RabbitMQ, and Redis](https://github.com/GregaVrbancic/fastapi-celery) ⭐ 668 | 🐛 1 | 🌐 Python | 📅 2026-01-07 - Minimal example utilizing FastAPI and Celery with RabbitMQ for task queue, Redis for Celery backend, and Flower for monitoring the Celery tasks.
* FastAPI CRUD Example:
  * [Async flavor](https://github.com/testdrivenio/fastapi-crud-async) ⭐ 562 | 🐛 4 | 🌐 Python | 📅 2024-02-05
  * [Sync Flavor](https://github.com/testdrivenio/fastapi-crud-sync) ⭐ 163 | 🐛 1 | 🌐 Python | 📅 2024-02-05
* [RealWorld Example App - mongo](https://github.com/markqiu/fastapi-mongodb-realworld-example-app) ⭐ 532 | 🐛 0 | 🌐 Python | 📅 2022-10-05
* [JSON-RPC Server](https://github.com/smagafurov/fastapi-jsonrpc) ⭐ 420 | 🐛 11 | 🌐 Python | 📅 2026-04-17 - JSON-RPC server based on FastAPI.
* [Bunnybook](https://github.com/pietrobassi/bunnybook) ⭐ 399 | 🐛 0 | 🌐 Python | 📅 2022-04-28 - A tiny social network built with FastAPI, React+RxJs, Neo4j, PostgreSQL, and Redis.
* [Sprites as a service](https://github.com/ljvmiranda921/sprites-as-a-service) ⭐ 399 | 🐛 16 | 🌐 Vue | 📅 2023-11-10 - Generate your personal 8-bit avatars using Cellular Automata.
* [FuturamaAPI](https://github.com/koldakov/futuramaapi) ⭐ 386 | 🐛 3 | 🌐 Python | 📅 2026-04-20 - A REST and GraphQL playground built with best practices, providing WebSockets, SSE, callbacks, secret messages, and more.
* [Bali](https://github.com/bali-framework/bali) ⭐ 372 | 🐛 10 | 🌐 Python | 📅 2025-09-10 - Simplify Cloud Native Microservices development base on FastAPI and gRPC.
* [redis-streams-fastapi-chat](https://github.com/leonh/redis-streams-fastapi-chat) ⭐ 351 | 🐛 0 | 🌐 Python | 📅 2025-11-15 - A simple Redis Streams backed chat app using Websockets, Asyncio and FastAPI/Starlette.
* [DogeAPI](https://github.com/yezz123/DogeAPI) ⭐ 245 | 🐛 2 | 🌐 Python | 📅 2024-05-14 - API with high performance to create a simple blog and CRUD with OAuth2PasswordBearer.
* [FastAPI Websocket Broadcast](https://github.com/kthwaite/fastapi-websocket-broadcast) ⭐ 226 | 🐛 4 | 🌐 Python | 📅 2025-04-24 - Websocket 'broadcast' demo.
* [Markdown-Videos](https://github.com/Snailedlt/Markdown-Videos) ⭐ 174 | 🐛 28 | 🌐 Python | 📅 2025-11-21 - API for generating thumbnails to embed into your markdown content.
* [Slackers](https://github.com/uhavin/slackers) ⚠️ Archived - Slack webhooks API.
* [Universities](https://github.com/ycd/universities) ⭐ 162 | 🐛 2 | 🌐 Python | 📅 2021-06-10 - API service for obtaining information about +9600 universities worldwide.
* [Astrobase](https://github.com/anthonycorletti/astrobase) ⭐ 159 | 🐛 1 | 🌐 Python | 📅 2023-02-06 - Simple, fast, and secure deployments anywhere.
* [Mailer](https://github.com/rclement/mailer) ⭐ 149 | 🐛 9 | 🌐 Python | 📅 2026-04-21 - Dead-simple mailer micro-service for static websites.
* [OPAL (Open Policy Administration Layer)](https://github.com/authorizon/opal) ⭐ 101 | 🐛 1 | 🌐 Python | 📅 2024-08-12 - Real-time authorization updates on top of Open-Policy; built with FastAPI, Typer, and FastAPI WebSocket pub/sub.
* [Coronavirus-tg-api](https://github.com/egbakou/coronavirus-tg-api) ⭐ 100 | 🐛 9 | 🌐 Python | 📅 2022-12-08 - API for tracking the global coronavirus (COVID-19, SARS-CoV-2) outbreak.
* [Nemo](https://github.com/harshitsinghai77/nemo-backend) ⭐ 100 | 🐛 1 | 🌐 Python | 📅 2025-02-15 - Be productive with Nemo.
* [OSBot-Fast-API](https://github.com/owasp-sbot/OSBot-Fast-API) ⭐ 87 | 🐛 0 | 🌐 Python | 📅 2026-02-04 - Type-safe FastAPI wrapper that provides middleware, HTTP event tracking, AWS Lambda integration, test utilities, and auto-conversion between Type\_Safe, Pydantic, and dataclasses.
* [JeffQL](https://github.com/yezz123/JeffQL/) ⭐ 31 | 🐛 4 | 🌐 Python | 📅 2024-04-29 - Simple authentication and login API using GraphQL and JWT.

## Sponsors

Please support this open source project by checking out our sponsors:

<a href="https://testdriven.io/courses/tdd-fastapi/?ref=awesome-fastapi" target="_blank" title="Learn to build high-quality web apps with best practices"><img src="images/testdriven.svg"></a>
