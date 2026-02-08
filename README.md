<!--lint disable double-link-->

# Awesome FastAPI | [![Awesome](https://awesome.re/badge-flat.svg)](https://github.com/sindresorhus/awesome) ⭐ 435,876 | 🐛 68 | 📅 2026-01-28 with stars

> A curated list of awesome things related to FastAPI.

[FastAPI](https://fastapi.tiangolo.com/) is a modern, high-performance, batteries-included Python web framework that's perfect for building RESTful APIs.

## Contents

* [Third-Party Extensions](#third-party-extensions)
  * [Admin](#admin)
  * [Auth](#auth)
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

* [FastAPI Admin](https://github.com/fastapi-admin/fastapi-admin) ⭐ 3,703 | 🐛 74 | 🌐 Python | 📅 2025-04-05 - Functional admin panel that provides a user interface for performing CRUD operations on your data. Currently only works with the Tortoise ORM.
* [SQLAlchemy Admin](https://github.com/aminalaee/sqladmin) ⭐ 2,646 | 🐛 107 | 🌐 Python | 📅 2026-02-04 - Admin Panel for FastAPI/Starlette that works with SQLAlchemy models.
* [FastAPI Amis Admin](https://github.com/amisadmin/fastapi-amis-admin) ⭐ 1,514 | 🐛 77 | 🌐 Python | 📅 2025-12-15 - A high-performance, efficient and easily extensible FastAPI admin framework.
* [Starlette Admin](https://github.com/jowilf/starlette-admin) ⭐ 976 | 🐛 95 | 🌐 Python | 📅 2026-01-26 - Admin framework for FastAPI/Starlette, supporting SQLAlchemy, SQLModel, MongoDB, and ODMantic.
* [Piccolo Admin](https://github.com/piccolo-orm/piccolo_admin) ⭐ 467 | 🐛 46 | 🌐 Python | 📅 2026-01-31 - A powerful and modern admin GUI, using the Piccolo ORM.

### Auth

* [FastAPI Users](https://github.com/fastapi-users/fastapi-users) ⭐ 5,985 | 🐛 4 | 🌐 Python | 📅 2026-02-05 - Account management, authentication, authorization.
* [AuthX](https://github.com/yezz123/AuthX) ⭐ 1,141 | 🐛 1 | 🌐 Python | 📅 2026-01-26 - Customizable Authentications and Oauth2 management for FastAPI.
* [FastAPI JWT Auth](https://github.com/IndominusByte/fastapi-jwt-auth) ⭐ 829 | 🐛 61 | 🌐 Python | 📅 2024-04-12 - JWT auth (based on [Flask-JWT-Extended](https://github.com/vimalloc/flask-jwt-extended) ⭐ 1,591 | 🐛 17 | 🌐 Python | 📅 2024-12-30).
* [FastAPI Login](https://github.com/maxrdu/fastapi_login) ⭐ 823 | 🐛 1 | 🌐 Python | 📅 2025-05-20 - Account management and authentication (based on [Flask-Login](https://github.com/maxcountryman/flask-login) ⭐ 3,681 | 🐛 20 | 🌐 Python | 📅 2025-08-27).
* [FastAPI Azure Auth](https://github.com/Intility/fastapi-azure-auth) ⭐ 667 | 🐛 16 | 🌐 Python | 📅 2025-11-01 - Azure AD authentication for your APIs with single and multi tenant support.
* [FastAPI Permissions](https://github.com/holgi/fastapi-permissions) ⭐ 651 | 🐛 18 | 🌐 Python | 📅 2023-10-16 - Row-level permissions.
* [FastAPI Simple Security](https://github.com/mrtolkien/fastapi_simple_security) ⭐ 472 | 🐛 1 | 🌐 Python | 📅 2023-12-19 - Out-of-the-box API key security manageable through path operations.
* [FastAPI Cloud Auth](https://github.com/tokusumi/fastapi-cloudauth) ⭐ 441 | 🐛 37 | 🌐 Python | 📅 2023-05-17 - Simple integration between FastAPI and cloud authentication services (AWS Cognito, Auth0, Firebase Authentication).
* [FastAPI Auth](https://github.com/dmontagu/fastapi-auth) ⭐ 262 | 🐛 5 | 🌐 Python | 📅 2023-02-14 - Pluggable auth that supports the OAuth2 Password Flow with JWT access and refresh tokens.
* [FastAPI Security](https://github.com/jacobsvante/fastapi-security) ⭐ 246 | 🐛 2 | 🌐 Python | 📅 2023-08-02 - Implements authentication and authorization as dependencies in FastAPI.

### Databases

#### ORMs

* [GINO](https://github.com/python-gino/gino) ⭐ 2,812 | 🐛 55 | 🌐 Python | 📅 2022-02-12 - A lightweight asynchronous ORM built on top of SQLAlchemy core for Python asyncio.
  * [FastAPI Example](https://github.com/leosussan/fastapi-gino-arq-uvicorn) ⭐ 559 | 🐛 4 | 🌐 Python | 📅 2022-12-08
* [Prisma Client Python](https://github.com/RobertCraigie/prisma-client-py) ⚠️ Archived - An auto-generated, fully type safe ORM powered by Pydantic and tailored specifically for your schema - supports SQLite, PostgreSQL, MySQL, MongoDB, MariaDB and more.
  * [FastAPI Example](https://github.com/RobertCraigie/prisma-client-py/tree/main/examples/fastapi-basic) ⚠️ Archived
* [ORM](https://github.com/encode/orm) ⚠️ Archived - An async ORM.
* [Piccolo](https://github.com/piccolo-orm/piccolo) ⭐ 1,854 | 🐛 61 | 🌐 Python | 📅 2026-02-06 - An async ORM and query builder, supporting Postgres and SQLite, with batteries (migrations, security, etc).
  * [FastAPI Examples](https://github.com/piccolo-orm/piccolo_examples) ⭐ 109 | 🐛 1 | 🌐 Python | 📅 2025-03-06 - Using FastAPI with Piccolo.
* [Tortoise ORM](https://tortoise.github.io) - An easy-to-use asyncio ORM (Object Relational Mapper) inspired by Django.
  * [Aerich](https://github.com/tortoise/aerich) ⭐ 1,087 | 🐛 26 | 🌐 Python | 📅 2026-02-07 - Tortoise ORM migrations tools.
  * [FastAPI Example](https://tortoise.github.io/examples/fastapi.html) - An example of the Tortoise-ORM FastAPI integration.
  * [Tutorial: Setting up Tortoise ORM with FastAPI](https://web.archive.org/web/20200523174158/https://robwagner.dev/tortoise-fastapi-setup/)
* [FastAPI SQLAlchemy](https://github.com/mfreeborn/fastapi-sqlalchemy) ⭐ 758 | 🐛 20 | 🌐 Python | 📅 2024-04-09 - Simple integration between FastAPI and [SQLAlchemy](https://www.sqlalchemy.org/).
* [Fastapi-SQLA](https://github.com/dialoguemd/fastapi-sqla) ⭐ 433 | 🐛 12 | 🌐 Python | 📅 2026-02-07 - SQLAlchemy extension for FastAPI with support for pagination, asyncio, and pytest.
* [Edgy ORM](https://github.com/dymmond/edgy) ⭐ 420 | 🐛 1 | 🌐 Python | 📅 2026-01-26 - Complex databases made simple.
* [Saffier ORM](https://github.com/tarsil/saffier) ⭐ 152 | 🐛 10 | 🌐 Python | 📅 2026-01-26 - The only Python ORM you will ever need.
* [FastAPIwee](https://github.com/Ignisor/FastAPIwee) ⭐ 108 | 🐛 1 | 🌐 Python | 📅 2021-07-09 - A simple way to create REST API based on [PeeWee](https://github.com/coleifer/peewee) ⭐ 11,927 | 🐛 0 | 🌐 Python | 📅 2026-02-07 models.
* [ormar](https://collerek.github.io/ormar/) - Ormar is an async ORM that uses Pydantic validation and can be used directly in FastAPI requests and responses so you are left with only one set of models to maintain. Alembic migrations included.
  * [FastAPI Example](https://collerek.github.io/ormar/latest/fastapi/) - Using FastAPI with ormar.
* [SQLModel](https://sqlmodel.tiangolo.com/) - SQLModel (which is powered by Pydantic and SQLAlchemy) is a library for interacting with SQL databases from Python code, with Python objects.

#### Query Builders

* [Databases](https://github.com/encode/databases) ⚠️ Archived - Async SQL query builder that works on top of the [SQLAlchemy Core](https://docs.sqlalchemy.org/en/latest/core/) expression language.
* [PyPika](https://github.com/kayak/pypika) ⭐ 2,884 | 🐛 229 | 🌐 Python | 📅 2026-02-04 - A SQL query builder that exposes the full richness of the SQL language.
* [asyncpgsa](https://github.com/CanopyTax/asyncpgsa) ⭐ 511 | 🐛 14 | 🌐 Python | 📅 2024-02-17 - A wrapper around [asyncpg](https://github.com/MagicStack/asyncpg) ⭐ 7,928 | 🐛 258 | 🌐 Python | 📅 2025-11-24 for use with [SQLAlchemy Core](https://docs.sqlalchemy.org/en/latest/core/).

#### ODMs

* [PynamoDB](https://github.com/pynamodb/PynamoDB) ⭐ 2,646 | 🐛 317 | 🌐 Python | 📅 2026-01-06 - A pythonic interface to Amazon's DynamoDB.
* [Beanie](https://github.com/BeanieODM/beanie) ⭐ 2,637 | 🐛 105 | 🌐 Python | 📅 2026-02-06 - Asynchronous Python ODM for MongoDB, based on [Motor](https://motor.readthedocs.io/en/stable/) and [Pydantic](https://docs.pydantic.dev/latest/), which supports data and schema migrations out of the box.
* [MongoEngine](http://mongoengine.org/) - A Document-Object Mapper (think ORM, but for document databases) for working with MongoDB from Python.
* [Motor](https://motor.readthedocs.io/) - Asynchronous Python driver for MongoDB.
* [ODMantic](https://art049.github.io/odmantic/) - AsyncIO MongoDB ODM integrated with [Pydantic](https://docs.pydantic.dev/latest/).

#### Other Tools

* [Pydantic-SQLAlchemy](https://github.com/tiangolo/pydantic-sqlalchemy) ⭐ 1,408 | 🐛 9 | 🌐 Python | 📅 2025-11-25 - Convert SQLAlchemy models to [Pydantic](https://docs.pydantic.dev/latest/) models.
* [FastAPI-CamelCase](https://nf1s.github.io/fastapi-camelcase/) - CamelCase JSON support for FastAPI utilizing [Pydantic](https://docs.pydantic.dev/latest/).
  * [CamelCase Models with FastAPI and Pydantic](https://medium.com/analytics-vidhya/camel-case-models-with-fast-api-and-pydantic-5a8acb6c0eee) - Accompanying blog post from the author of the extension.

### Dependency Injection

* [Wireup](https://github.com/maldoinc/wireup) ⭐ 346 | 🐛 14 | 🌐 Python | 📅 2026-02-02 - Inject dependencies with zero runtime overhead in FastAPI; Share dependencies across web, cli or other interfaces.

### Developer Tools

* [Manage FastAPI](https://github.com/ycd/manage-fastapi) ⭐ 1,894 | 🐛 22 | 🌐 Python | 📅 2024-03-01 - CLI tool for generating and managing FastAPI projects.
* [FastAPI Code Generator](https://github.com/koxudaxi/fastapi-code-generator) ⭐ 1,383 | 🐛 79 | 🌐 Python | 📅 2026-01-19 - Create a FastAPI app from an OpenAPI file, enabling schema-driven development.
* [FastAPI Versioning](https://github.com/DeanWay/fastapi-versioning) ⭐ 844 | 🐛 35 | 🌐 Python | 📅 2023-07-25 - API versioning.
* [FastAPI MVC](https://github.com/fastapi-mvc/fastapi-mvc) ⭐ 787 | 🐛 24 | 🌐 Python | 📅 2026-02-07 - Developer productivity tool for making high-quality FastAPI production-ready APIs.
* [FastAPI Client Generator](https://github.com/dmontagu/fastapi_client) ⭐ 432 | 🐛 11 | 🌐 Python | 📅 2023-07-06 - Generate a mypy- and IDE-friendly API client from an OpenAPI spec.
* [FastAPI Profiler](https://github.com/sunhailin-Leo/fastapi_profiler) ⭐ 363 | 🐛 1 | 🌐 Python | 📅 2024-05-17 - A FastAPI Middleware of joerick/pyinstrument to check your service performance.
* [msgpack-asgi](https://github.com/florimondmanca/msgpack-asgi) ⭐ 275 | 🐛 1 | 🌐 Python | 📅 2026-02-03 - Automatic [MessagePack](https://msgpack.org/) content negotiation.
* [Jupyter Notebook REST API](https://github.com/Invictify/Jupter-Notebook-REST-API) ⭐ 169 | 🐛 11 | 🌐 Jupyter Notebook | 📅 2022-12-08 - Run your Jupyter notebooks as RESTful API endpoints.
* [FastAPI Cruddy Framework](https://github.com/mdconaway/fastapi-cruddy-framework) ⭐ 126 | 🐛 0 | 🌐 Python | 📅 2026-01-30 - A companion library to FastAPI designed to bring the development productivity of Ruby on Rails, Ember.js or Sails.js to the FastAPI ecosystem.

### Email

* [FastAPI Mail](https://github.com/sabuhish/fastapi-mail) ⭐ 970 | 🐛 20 | 🌐 Python | 📅 2026-01-08 - Lightweight mail system for sending emails and attachments (individual and bulk).

### Utils

* [Strawberry GraphQL](https://github.com/strawberry-graphql/strawberry) ⭐ 4,607 | 🐛 446 | 🌐 Python | 📅 2026-02-07 - Python GraphQL library based on dataclasses.
* [FastAPI Utilities](https://github.com/fastapiutils/fastapi-utils) ⭐ 2,302 | 🐛 64 | 🌐 Python | 📅 2025-03-03 - Reusable utilities: class-based views, response inferring router, periodic tasks, timing middleware, SQLAlchemy session, OpenAPI spec simplification.
* [SlowApi](https://github.com/laurents/slowapi) ⭐ 1,902 | 🐛 91 | 🌐 Python | 📅 2025-08-10 - Rate limiter (based on [Flask-Limiter](https://flask-limiter.readthedocs.io)).
* [FastAPI Cache](https://github.com/long2ice/fastapi-cache) ⭐ 1,818 | 🐛 104 | 🌐 Python | 📅 2025-06-30 - A tool to cache FastAPI response and function results, with support for Redis, Memcached, DynamoDB, and in-memory backends.
* [FastAPI Pagination](https://github.com/uriyyo/fastapi-pagination) ⭐ 1,614 | 🐛 8 | 🌐 Python | 📅 2026-02-06 - Pagination for FastAPI.
* [FastAPI FastCRUD](https://github.com/benavlabs/fastcrud) ⭐ 1,476 | 🐛 20 | 🌐 Python | 📅 2026-01-27) - Robust async CRUD operations and flexible endpoint creation utilities.
* [Prometheus FastAPI Instrumentator](https://github.com/trallnag/prometheus-fastapi-instrumentator) ⭐ 1,421 | 🐛 66 | 🌐 Python | 📅 2025-10-01 - A configurable and modular Prometheus Instrumentator for your FastAPI application.
* [OpenTelemetry FastAPI Instrumentation](https://github.com/open-telemetry/opentelemetry-python-contrib/tree/main/instrumentation/opentelemetry-instrumentation-fastapi) ⭐ 991 | 🐛 783 | 🌐 Python | 📅 2026-02-06 - Library provides automatic and manual instrumentation of FastAPI web frameworks, instrumenting http requests served by applications utilizing the framework.
* [FastAPI Contrib](https://github.com/identixone/fastapi_contrib) ⭐ 745 | 🐛 15 | 🌐 Python | 📅 2022-09-12 - Opinionated set of utilities: pagination, auth middleware, permissions, custom exception handlers, MongoDB support, and Opentracing middleware.
* [FastAPI Limiter](https://github.com/long2ice/fastapi-limiter) ⭐ 735 | 🐛 24 | 🌐 Python | 📅 2026-02-06 - A request rate limiter for FastAPI.
* [ASGI Correlation ID](https://github.com/snok/asgi-correlation-id) ⭐ 629 | 🐛 4 | 🌐 Python | 📅 2024-10-17 - Request ID logging middleware.
* [FastAPI Events](https://github.com/melvinkcx/fastapi-events) ⭐ 611 | 🐛 11 | 🌐 Python | 📅 2024-12-21 - Asynchronous event dispatching/handling library for FastAPI and Starlette.
* [FastAPI Plugins](https://github.com/madkote/fastapi-plugins) ⭐ 609 | 🐛 3 | 🌐 Python | 📅 2025-07-09 - Redis and Scheduler plugins.
* [Starlette Context](https://github.com/tomwojcik/starlette-context) ⭐ 608 | 🐛 27 | 🌐 Python | 📅 2026-01-19 - Allows you to store and access the request data anywhere in your project, useful for logging.
* [FastAPI SocketIO](https://github.com/pyropy/fastapi-socketio) ⚠️ Archived - Easy integration for FastAPI and SocketIO.
* [Starlette Exporter](https://github.com/stephenhillier/starlette_exporter) ⭐ 411 | 🐛 10 | 🌐 Python | 📅 2024-10-15 - One more prometheus integration for FastAPI and Starlette.
* [FastAPI MQTT](https://github.com/sabuhish/fastapi-mqtt) ⭐ 382 | 🐛 5 | 🌐 Python | 📅 2024-05-22 - An extension for the MQTT protocol.
* [Starlette Prometheus](https://github.com/perdy/starlette-prometheus) ⭐ 379 | 🐛 15 | 🌐 Python | 📅 2024-05-20 - Prometheus integration for FastAPI and Starlette.
* [FastAPI Cache](https://github.com/comeuplater/fastapi_cache) ⭐ 309 | 🐛 9 | 🌐 Python | 📅 2021-09-30 - A simple lightweight cache system.
* [FastAPI Injectable](https://github.com/JasperSui/fastapi-injectable) ⭐ 282 | 🐛 1 | 🌐 Python | 📅 2026-02-03 - Use FastAPI's dependency injection outside route handlers in CLI tools, background tasks, workers, and more.
* [FastAPI Chameleon](https://github.com/mikeckennedy/fastapi-chameleon) ⭐ 231 | 🐛 1 | 🌐 Python | 📅 2025-04-04 - Adds integration of the Chameleon template language to FastAPI.
* [Apitally](https://github.com/apitally/apitally-py) ⭐ 216 | 🐛 1 | 🌐 Python | 📅 2026-02-07 - API analytics, monitoring, and request logging for FastAPI.
* [FastAPI Lazy](https://github.com/yezz123/fastango) ⭐ 204 | 🐛 3 | 🌐 Python | 📅 2024-04-29 - Lazy package to start your project using FastAPI.
* [FastAPI Jinja](https://github.com/AGeekInside/fastapi-jinja) ⭐ 160 | 🐛 1 | 🌐 Python | 📅 2024-11-16 - Adds integration of the Jinja template language to FastAPI.
* [FastAPI FeatureFlags](https://github.com/Pytlicek/fastapi-featureflags) ⭐ 157 | 🐛 4 | 🌐 Python | 📅 2024-06-10 - Simple implementation of feature flags for FastAPI.
* [Starlette OpenTracing](https://github.com/acidjunk/starlette-opentracing) ⭐ 153 | 🐛 1 | 🌐 Python | 📅 2021-11-17 - Opentracing support for Starlette and FastAPI.
* [FastAPI Listing](https://github.com/danielhasan1/fastapi-listing) ⭐ 143 | 🐛 6 | 🌐 Python | 📅 2025-02-28 - A library to design/build listing APIs using component-based architecture, inbuilt query paginator, sorter, django-admin like filters & much more.
* [FastAPI CloudEvents](https://github.com/sasha-tkachev/fastapi-cloudevents) ⭐ 123 | 🐛 1 | 🌐 Python | 📅 2025-07-26 - [CloudEvents](https://cloudevents.io/) integration for FastAPI.
* [FastAPI ServiceUtils](https://github.com/skallfass/fastapi_serviceutils) ⭐ 121 | 🐛 2 | 🌐 Python | 📅 2021-07-29 - Generator for creating API services.
* [FastAPI Opentracing](https://github.com/wesdu/fastapi-opentracing) ⭐ 112 | 🐛 7 | 🌐 Python | 📅 2023-02-06 - Opentracing middleware and database tracing support for FastAPI.
* [FastAPI Websocket Pub/Sub](https://github.com/authorizon/fastapi_websocket_pubsub) ⭐ 104 | 🐛 0 | 🌐 Python | 📅 2021-12-10 - The classic pub/sub pattern made easily accessible and scalable over the web and across your cloud in realtime.
* [Prerender Python Starlette](https://github.com/BeeMyDesk/prerender-python-starlette) ⚠️ Archived - Starlette middleware for Prerender.
* [FastAPI Websocket RPC](https://github.com/authorizon/fastapi_websocket_rpc) ⭐ 94 | 🐛 0 | 🌐 Python | 📅 2021-12-10 - RPC (bidirectional JSON RPC) over Websockets made easy, robust, and production ready.

## Resources

### Official Resources

* [Documentation](https://fastapi.tiangolo.com/) - Comprehensive documentation.
* [Tutorial](https://fastapi.tiangolo.com/tutorial/) - Official tutorial showing you how to use FastAPI with most of its features, step by step.
* [Source Code](https://github.com/fastapi/fastapi) ⭐ 94,884 | 🐛 175 | 🌐 Python | 📅 2026-02-07 - Hosted on GitHub.
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

* [FastAPI Best Practices](https://github.com/zhanymkanov/fastapi-best-practices) ⭐ 16,384 | 🐛 9 | 📅 2026-01-10 - Collection of best practices in a GitHub repo.
* [FastAPI-Dishka-FastStream](https://github.com/faststream-community/fastapi-dishka-faststream) ⭐ 296 | 🐛 0 | 🌐 Python | 📅 2026-01-03 - Combines FastAPI, dishka, faststream, sqlalchemy, pydantic.

## Hosting

### PaaS

(Platforms-as-a-Service)

* [AWS Elastic Beanstalk](https://aws.amazon.com/elasticbeanstalk/)
* [Deta](https://www.deta.sh/) ([example](https://dev.to/athulcajay/fastapi-deta-ni5))
* [Fly](https://fly.io) ([tutorial](https://fly.io/docs/python/frameworks/fastapi/), [Deploy from a Git repo](https://github.com/fly-apps/hello-fastapi) ⭐ 15 | 🐛 2 | 🌐 Python | 📅 2024-07-31)
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

* [Chalice](https://github.com/aws/chalice) ⭐ 11,064 | 🐛 492 | 🌐 Python | 📅 2025-05-29
* [Vercel](https://vercel.com/) - (formerly Zeit) ([example](https://github.com/Snailedlt/Markdown-Videos) ⭐ 179 | 🐛 28 | 🌐 Python | 📅 2025-11-21).
* [Mangum](https://mangum.io/) - Adapter for running ASGI applications with AWS Lambda and API Gateway.

Compute:

* [Google Cloud Run](https://cloud.google.com/run) ([example](https://github.com/anthonycorletti/cloudrun-fastapi) ⭐ 288 | 🐛 0 | 🌐 Python | 📅 2024-10-07)
* [AWS Lambda](https://aws.amazon.com/lambda/) ([example](https://github.com/iwpnd/fastapi-aws-lambda-example) ⭐ 142 | 🐛 3 | 🌐 Python | 📅 2021-07-23)
* [Google Cloud Functions](https://cloud.google.com/functions)
* [Azure Functions](https://azure.microsoft.com/en-us/products/functions/)

## Projects

### Boilerplate

* [Full Stack FastAPI and PostgreSQL - Base Project Generator](https://github.com/fastapi/full-stack-fastapi-template) ⭐ 41,443 | 🐛 10 | 🌐 TypeScript | 📅 2026-02-07 - Full Stack FastAPI Template
  , which includes FastAPI, React, SQLModel, PostgreSQL, Docker, GitHub Actions, automatic HTTPS, and more (developed by the creator of FastAPI, [Sebastián Ramírez](https://github.com/tiangolo)).
* [FastAPI template](https://github.com/s3rius/FastAPI-template) ⭐ 2,734 | 🐛 39 | 🌐 Python | 📅 2025-11-28 - Flexible, lightweight FastAPI project generator. It includes support for SQLAlchemy, multiple databases, CI/CD, Docker, and Kubernetes.
* [FastAPI and React Template](https://github.com/Buuntu/fastapi-react) ⭐ 2,575 | 🐛 42 | 🌐 Python | 📅 2023-10-06 - Full stack cookiecutter boilerplate using FastAPI, TypeScript, Docker, PostgreSQL, and React.
* [openapi-python-client](https://github.com/openapi-generators/openapi-python-client) ⭐ 1,901 | 🐛 94 | 🌐 Python | 📅 2026-02-06 - Generate modern FastAPI Python clients (via FastAPI) from OpenAPI.
* [fastapi-alembic-sqlmodel-async](https://github.com/jonra1993/fastapi-alembic-sqlmodel-async) ⭐ 1,266 | 🐛 9 | 🌐 Python | 📅 2024-04-01 - This is a project template which uses FastAPI, Alembic, and async SQLModel as ORM.
* [FastAPI Nano](https://github.com/rednafi/fastapi-nano) ⭐ 1,035 | 🐛 2 | 🌐 Python | 📅 2025-01-01 - Simple FastAPI template with factory pattern architecture.
* [Full Stack FastAPI and MongoDB - Base Project Generator](https://github.com/mongodb-labs/full-stack-fastapi-mongodb) ⭐ 814 | 🐛 8 | 🌐 TypeScript | 📅 2025-05-09 - Full stack, modern web application generator, which includes FastAPI, MongoDB, Docker, Celery, React frontend, automatic HTTPS and more.
* [cookiecutter-fastapi](https://github.com/arthurhenrique/cookiecutter-fastapi) ⭐ 700 | 🐛 1 | 🌐 Python | 📅 2025-08-25 - Cookiecutter template for FastAPI projects using: Machine Learning, Poetry, Azure Pipelines and pytest.
* [cookiecutter-spacy-fastapi](https://github.com/microsoft/cookiecutter-spacy-fastapi) ⭐ 623 | 🐛 6 | 🌐 Python | 📅 2022-11-28 - Quick deployments of spaCy models with FastAPI.
* [FastAPI Model Server Skeleton](https://github.com/eightBEC/fastapi-ml-skeleton) ⭐ 597 | 🐛 8 | 🌐 Python | 📅 2026-01-08 - Skeleton app to serve machine learning models production-ready.
* [fastapi-gino-arq-uvicorn](https://github.com/leosussan/fastapi-gino-arq-uvicorn) ⭐ 559 | 🐛 4 | 🌐 Python | 📅 2022-12-08 - Template for a high-performance async REST API, in Python. FastAPI + GINO + Arq + Uvicorn (w/ Redis and PostgreSQL).
* [FastAPI on Google Cloud Run](https://github.com/anthonycorletti/cloudrun-fastapi) ⭐ 288 | 🐛 0 | 🌐 Python | 📅 2024-10-07 - Boilerplate for API building with FastAPI, SQLModel, and Google Cloud Run.
* [FastAPI and Tortoise ORM](https://github.com/prostomarkeloff/fastapi-tortoise) ⭐ 225 | 🐛 0 | 🌐 Python | 📅 2024-06-27 - Powerful but simple template for web APIs w/ FastAPI (as web framework) and Tortoise-ORM (for working via database without headache).
* [fastapi-starter-project](https://github.com/mirzadelic/fastapi-starter-project) ⭐ 216 | 🐛 0 | 🌐 Python | 📅 2022-11-27 - A project template which uses FastAPI, SQLModel, Alembic, Pytest, Docker, GitHub Actions CI.
* [FastAPI with Firestore](https://github.com/anthonycorletti/firestore-fastapi) ⭐ 135 | 🐛 2 | 🌐 Python | 📅 2024-10-07 - Boilerplate for API building with FastAPI and Google Cloud Firestore.
* [Uvicorn Poetry FastAPI Project Template](https://github.com/max-pfeiffer/uvicorn-poetry-fastapi-project-template) ⭐ 107 | 🐛 5 | 🌐 Python | 📅 2025-10-01 - Cookiecutter project template for starting a FastAPI application. Runs in a Docker container with Uvicorn ASGI server on Kubernetes. Supports AMD64 and ARM64 CPU architectures.
* [Pywork](https://github.com/vutran1710/YeomanPywork) ⚠️ Archived - [Yeoman](https://yeoman.io/) generator to scaffold a FastAPI app.

### Docker Images

* [uvicorn-gunicorn-fastapi-docker](https://github.com/tiangolo/uvicorn-gunicorn-fastapi-docker) ⭐ 2,910 | 🐛 4 | 🌐 Python | 📅 2026-02-06 - Docker image with Uvicorn managed by Gunicorn for high-performance FastAPI web applications in Python 3.7 and 3.6 with performance auto-tuning.
* [inboard](https://github.com/br3ndonland/inboard) ⭐ 317 | 🐛 0 | 🌐 Python | 📅 2026-02-02 - Docker images to power your FastAPI apps and help you ship faster.
* [uvicorn-poetry](https://github.com/max-pfeiffer/uvicorn-poetry) ⭐ 142 | 🐛 6 | 🌐 Python | 📅 2025-10-01 - Docker image with Uvicorn ASGI server for running Python web applications on Kubernetes. Uses Poetry for managing dependencies and setting up a virtual environment. Supports AMD64 and ARM64 CPU architectures.
* [uvicorn-gunicorn-poetry](https://github.com/max-pfeiffer/uvicorn-gunicorn-poetry) ⭐ 133 | 🐛 0 | 🌐 Python | 📅 2024-04-21 - Docker image with Gunicorn using Uvicorn workers for running Python web applications. Uses Poetry for managing dependencies and setting up a virtual environment. Supports AMD64 and ARM64 CPU architectures.

### Open Source Projects

* [Polar](https://github.com/polarsource/polar) ⭐ 9,382 | 🐛 309 | 🌐 Python | 📅 2026-02-06 - A funding and monetization platform for developers, built with FastAPI, SQLAlchemy, Alembic, and Arq.
* [Dispatch](https://github.com/Netflix/dispatch) ⚠️ Archived - Manage security incidents.
* [RealWorld Example App - postgres](https://github.com/nsidnev/fastapi-realworld-example-app) ⚠️ Archived
* [TermPair](https://github.com/cs01/termpair) ⭐ 1,727 | 🐛 1 | 🌐 TypeScript | 📅 2022-06-22 - View and control terminals from your browser with end-to-end encryption.
* [Awesome FastAPI Projects](https://github.com/Kludex/awesome-fastapi-projects) ⭐ 1,593 | 🐛 11 | 🌐 TypeScript | 📅 2026-02-03 - Organized list of projects that use FastAPI.
* [FastAPI with Observability](https://github.com/Blueswen/fastapi-observability) ⭐ 1,067 | 🐛 6 | 🌐 Python | 📅 2025-05-11 - Observe FastAPI app with three pillars of observability: Traces (Tempo), Metrics (Prometheus), Logs (Loki) on Grafana through OpenTelemetry and OpenMetrics.
* [Bitcart](https://github.com/bitcart/bitcart) ⭐ 886 | 🐛 29 | 🌐 Python | 📅 2026-02-06 - Platform for merchants, users and developers which offers easy setup and use.
* [FastAPI with Celery, RabbitMQ, and Redis](https://github.com/GregaVrbancic/fastapi-celery) ⭐ 667 | 🐛 1 | 🌐 Python | 📅 2026-01-07 - Minimal example utilizing FastAPI and Celery with RabbitMQ for task queue, Redis for Celery backend, and Flower for monitoring the Celery tasks.
* FastAPI CRUD Example:
  * [Async flavor](https://github.com/testdrivenio/fastapi-crud-async) ⭐ 561 | 🐛 4 | 🌐 Python | 📅 2024-02-05
  * [Sync Flavor](https://github.com/testdrivenio/fastapi-crud-sync) ⭐ 165 | 🐛 1 | 🌐 Python | 📅 2024-02-05
* [RealWorld Example App - mongo](https://github.com/markqiu/fastapi-mongodb-realworld-example-app) ⭐ 534 | 🐛 0 | 🌐 Python | 📅 2022-10-05
* [JSON-RPC Server](https://github.com/smagafurov/fastapi-jsonrpc) ⭐ 419 | 🐛 11 | 🌐 Python | 📅 2026-01-12 - JSON-RPC server based on FastAPI.
* [Bunnybook](https://github.com/pietrobassi/bunnybook) ⭐ 399 | 🐛 0 | 🌐 Python | 📅 2022-04-28 - A tiny social network built with FastAPI, React+RxJs, Neo4j, PostgreSQL, and Redis.
* [Sprites as a service](https://github.com/ljvmiranda921/sprites-as-a-service) ⭐ 399 | 🐛 16 | 🌐 Vue | 📅 2023-11-10 - Generate your personal 8-bit avatars using Cellular Automata.
* [Bali](https://github.com/bali-framework/bali) ⭐ 372 | 🐛 10 | 🌐 Python | 📅 2025-09-10 - Simplify Cloud Native Microservices development base on FastAPI and gRPC.
* [FuturamaAPI](https://github.com/koldakov/futuramaapi) ⭐ 355 | 🐛 3 | 🌐 Python | 📅 2026-02-07 - A REST and GraphQL playground built with best practices, providing WebSockets, SSE, callbacks, secret messages, and more.
* [redis-streams-fastapi-chat](https://github.com/leonh/redis-streams-fastapi-chat) ⭐ 348 | 🐛 0 | 🌐 Python | 📅 2025-11-15 - A simple Redis Streams backed chat app using Websockets, Asyncio and FastAPI/Starlette.
* [DogeAPI](https://github.com/yezz123/DogeAPI) ⭐ 248 | 🐛 2 | 🌐 Python | 📅 2024-05-14 - API with high performance to create a simple blog and CRUD with OAuth2PasswordBearer.
* [FastAPI Websocket Broadcast](https://github.com/kthwaite/fastapi-websocket-broadcast) ⭐ 227 | 🐛 4 | 🌐 Python | 📅 2025-04-24 - Websocket 'broadcast' demo.
* [Markdown-Videos](https://github.com/Snailedlt/Markdown-Videos) ⭐ 179 | 🐛 28 | 🌐 Python | 📅 2025-11-21 - API for generating thumbnails to embed into your markdown content.
* [Slackers](https://github.com/uhavin/slackers) ⚠️ Archived - Slack webhooks API.
* [Universities](https://github.com/ycd/universities) ⭐ 164 | 🐛 2 | 🌐 Python | 📅 2021-06-10 - API service for obtaining information about +9600 universities worldwide.
* [Astrobase](https://github.com/anthonycorletti/astrobase) ⭐ 159 | 🐛 1 | 🌐 Python | 📅 2023-02-06 - Simple, fast, and secure deployments anywhere.
* [Mailer](https://github.com/rclement/mailer) ⭐ 151 | 🐛 4 | 🌐 Python | 📅 2026-02-07 - Dead-simple mailer micro-service for static websites.
* [OPAL (Open Policy Administration Layer)](https://github.com/authorizon/opal) ⭐ 103 | 🐛 1 | 🌐 Python | 📅 2024-08-12 - Real-time authorization updates on top of Open-Policy; built with FastAPI, Typer, and FastAPI WebSocket pub/sub.
* [Coronavirus-tg-api](https://github.com/egbakou/coronavirus-tg-api) ⭐ 102 | 🐛 9 | 🌐 Python | 📅 2022-12-08 - API for tracking the global coronavirus (COVID-19, SARS-CoV-2) outbreak.
* [Nemo](https://github.com/harshitsinghai77/nemo-backend) ⭐ 102 | 🐛 1 | 🌐 Python | 📅 2025-02-15 - Be productive with Nemo.
* [OSBot-Fast-API](https://github.com/owasp-sbot/OSBot-Fast-API) ⭐ 89 | 🐛 0 | 🌐 Python | 📅 2026-02-04 - Type-safe FastAPI wrapper that provides middleware, HTTP event tracking, AWS Lambda integration, test utilities, and auto-conversion between Type\_Safe, Pydantic, and dataclasses.
* [JeffQL](https://github.com/yezz123/JeffQL/) ⭐ 31 | 🐛 4 | 🌐 Python | 📅 2024-04-29 - Simple authentication and login API using GraphQL and JWT.

## Sponsors

Please support this open source project by checking out our sponsors:

<a href="https://testdriven.io/courses/tdd-fastapi/?ref=awesome-fastapi" target="_blank" title="Learn to build high-quality web apps with best practices"><img src="images/testdriven.svg"></a>
