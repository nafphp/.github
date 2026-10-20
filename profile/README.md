<p align="center">
  <a href="https://github.com/nafphp/framework">
    <img src="https://nafphp.github.io/docs/assets/naf-logo-small-square.png" alt="NAF logo" width="160" height="160">
  </a>
</p>

<h1 align="center">Not Another Framework.</h1>

<p align="center">
  <a href="https://github.com/nafphp/framework/actions/workflows/php.yml"><img src="https://github.com/nafphp/framework/actions/workflows/php.yml/badge.svg?branch=main" alt="Framework build"></a>
  <a href="https://github.com/nafphp/docs/actions/workflows/docs.yml"><img src="https://github.com/nafphp/docs/actions/workflows/docs.yml/badge.svg?branch=main" alt="Documentation build"></a>
  <a href="https://packagist.org/packages/naf/framework"><img src="https://img.shields.io/packagist/v/naf/framework" alt="Packagist version"></a>
  <a href="https://nafphp.github.io/docs/install/"><img src="https://img.shields.io/badge/PHP-8.3%2B-777BB4" alt="PHP 8.3 or newer"></a>
  <a href="https://github.com/nafphp/framework/blob/main/LICENSE"><img src="https://img.shields.io/github/license/nafphp/framework" alt="License"></a>
</p>

NAF is a small PHP framework for websites, APIs and services. You write your application
with ordinary PHP classes and namespaced helper functions. The
[core](https://github.com/nafphp/framework) takes care of routing, dependency injection,
configuration and HTTP requests and responses.

When you need more, install a plugin with Composer. NAF finds and loads your installed
plugins automatically, so you don't need to register them by hand.

## Getting started

To create your first project, you'll need PHP 8.3 or newer and Composer:

```bash
composer create-project naf/app my-app
```

Your new project comes with views, forms and sessions already installed. The
[installation guide](https://nafphp.github.io/docs/install/) helps you get it running.
From there, [your first application](https://nafphp.github.io/docs/first-app/) walks you
through building an HTML page and a JSON endpoint.

## Plugins

Pick the plugins that fit your project. If you're unsure where to start, the
[package selection guide](https://nafphp.github.io/docs/choosing-packages/) helps you choose.
Each plugin's guide walks you through its setup.

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

You'll find step-by-step guides and complete examples in the
[NAF documentation](https://nafphp.github.io/docs/). When you need to look up a helper, the
[function index](https://nafphp.github.io/docs/function-index/) lists its signature.

If you're bringing over a NixPHP application, the
[migration guide](https://nafphp.github.io/docs/upgrading-from-nixphp/) explains what to change.
