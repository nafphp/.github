# NAF

[![Framework build](https://github.com/nafphp/framework/actions/workflows/php.yml/badge.svg?branch=main)](https://github.com/nafphp/framework/actions/workflows/php.yml)
[![Documentation build](https://github.com/nafphp/docs/actions/workflows/docs.yml/badge.svg?branch=main)](https://github.com/nafphp/docs/actions/workflows/docs.yml)
[![Packagist version](https://img.shields.io/packagist/v/naf/framework)](https://packagist.org/packages/naf/framework)
[![PHP 8.3 or newer](https://img.shields.io/badge/PHP-8.3%2B-777BB4)](https://nafphp.github.io/docs/install/)
[![License](https://img.shields.io/github/license/nafphp/framework)](https://github.com/nafphp/framework/blob/main/LICENSE)

NAF (Not Another Framework) is a PHP microframework for web applications, APIs and services.
The [core](https://github.com/nafphp/framework) handles routing, controller dispatch,
dependency injection, configuration, events and HTTP responses. Composer plugins add
templates, persistence, authentication and background jobs.

Application code uses ordinary PHP classes and namespaced functions. Controllers receive
services through their constructors, and route handlers return PSR-7 responses. The core
uses a PSR-11 container and PSR-3 logging.

## Getting started

You need PHP 8.3 or newer and Composer.

```bash
composer create-project naf/app my-app
```

The starter includes the framework, views, forms and sessions.
Follow the [installation guide](https://nafphp.github.io/docs/install/) to run it, then build
[your first application](https://nafphp.github.io/docs/first-app/).

## Plugins

Install plugins as Composer dependencies of your application. The
[package selection guide](https://nafphp.github.io/docs/choosing-packages/) covers what each
one needs and when to use it.

### Web pages and input

| Plugin | Description |
| --- | --- |
| [`naf/view`](https://github.com/nafphp/view) | PHP templates, layouts and reusable partials |
| [`naf/form`](https://github.com/nafphp/form) | Form validation, CSRF protection and input repopulation |
| [`naf/session`](https://github.com/nafphp/session) | Session and flash message support |
| [`naf/flow`](https://github.com/nafphp/flow) | Reactive JavaScript components and HTML updates for PHP views |
| [`naf/i18n`](https://github.com/nafphp/i18n) | Translations and pluralisation |

### Data and files

| Plugin | Description |
| --- | --- |
| [`naf/database`](https://github.com/nafphp/database) | Configured PDO connections and database migrations |
| [`naf/orm`](https://github.com/nafphp/orm) | Entity mapping and repositories on top of PDO |
| [`naf/storage`](https://github.com/nafphp/storage) | Named storage disks, streams and local, S3 or WebDAV adapters |

### Security and identity

| Plugin | Description |
| --- | --- |
| [`naf/auth`](https://github.com/nafphp/auth) | Authentication, permission checks and policies with your own user model |
| [`naf/rbac`](https://github.com/nafphp/rbac) | Database-backed roles, permissions and grant management |
| [`naf/auth-ldap`](https://github.com/nafphp/auth-ldap) | LDAP authentication through Auth providers |
| [`naf/oauth-client`](https://github.com/nafphp/oauth-client) | Sign in with external OAuth2 and OpenID Connect providers |
| [`naf/oauth-server`](https://github.com/nafphp/oauth-server) | OAuth2 authorization server, API protection and OpenID Connect |
| [`naf/rate-limit`](https://github.com/nafphp/rate-limit) | Atomic database-backed rate limits with fixed windows |

### Console and background work

| Plugin | Description |
| --- | --- |
| [`naf/cli`](https://github.com/nafphp/cli) | Application commands through the `naf` console |
| [`naf/queue`](https://github.com/nafphp/queue) | Background jobs and workers |
| [`naf/schedule`](https://github.com/nafphp/schedule) | Recurring tasks in cron syntax |

### Integrations and operations

| Plugin | Description |
| --- | --- |
| [`naf/mail`](https://github.com/nafphp/mail) | Mail delivery with attachments and replaceable transports |
| [`naf/client`](https://github.com/nafphp/client) | A PSR-18 HTTP client |
| [`naf/websocket`](https://github.com/nafphp/websocket) | A PHP WebSocket server for application change notifications |
| [`naf/mcp`](https://github.com/nafphp/mcp) | Expose application tools over the Model Context Protocol |
| [`naf/alexa`](https://github.com/nafphp/alexa) | Alexa+ MCP integration with OAuth setup and diagnostics |
| [`naf/monitoring`](https://github.com/nafphp/monitoring) | Metrics, StatsD export and optional PSR-3 logging integration |

### CMS and Kanban boards

| Plugin | Description |
| --- | --- |
| [`naf/cms`](https://github.com/nafphp/cms) | NafCMS content management with pages, media and custom content types |
| [`naf/board`](https://github.com/nafphp/board) | Kanban boards with project isolation and an extension API; used by Nafinity |

## Documentation

The [NAF documentation](https://nafphp.github.io/docs/) covers the framework, plugins and
complete application examples. The [function index](https://nafphp.github.io/docs/function-index/)
lists public helpers and their signatures.

For existing NixPHP applications, see the
[migration guide](https://nafphp.github.io/docs/upgrading-from-nixphp/).
