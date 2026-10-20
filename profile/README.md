<p align="center">
  <img src="https://nafphp.github.io/docs/assets/naf-logo-small-square.png" alt="NAF" width="160">
</p>

<p align="center">
  <strong>Not Another Framework.</strong><br>
  A lightweight PHP microframework designed to stay out of your way.<br>
  <em>As simple as possible, as flexible as necessary.</em>
</p>

<p align="center">
  <a href="https://github.com/nafphp/framework"><img alt="Framework" src="https://img.shields.io/badge/Core_Framework-naf%2Fframework-blue?style=flat-square"></a>
  <a href="https://nafphp.github.io/docs"><img alt="Docs" src="https://img.shields.io/badge/Docs-View_on_GitHub_Pages-brightgreen?style=flat-square"></a>
</p>

---

## 🔧 What is NAF?

**NAF** is a microframework for developers who want **full control** over their stack.
The core routes a request and dispatches it. Everything else is a plugin you add when you
need it.

It comes with:

- PSR-based architecture (PSR-3, PSR-4, PSR-7, PSR-11, PSR-18)
- Minimalist routing and dispatching
- A plugin system for optional components — views, forms, sessions, database, and the rest
- A native PHP approach, no complex abstraction layers

📦 *Use what you need. Leave out what you don't.*

---

## 🧩 Official plugins

Choose plugins by what your application needs. Each package links to its repository;
setup and usage are covered in the [documentation](https://nafphp.github.io/docs/).

### Web pages and input

| Plugin | Description |
| --- | --- |
| [`naf/view`](https://github.com/nafphp/view) | Native PHP templating with layout blocks |
| [`naf/form`](https://github.com/nafphp/form) | CSRF protection, validation and input memory |
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
| [`naf/auth-ldap`](https://github.com/nafphp/auth-ldap) | LDAP sign-in through the existing Auth provider contract |
| [`naf/oauth-client`](https://github.com/nafphp/oauth-client) | Sign in with external OAuth2 and OpenID Connect providers |
| [`naf/oauth-server`](https://github.com/nafphp/oauth-server) | OAuth2 authorization server, API protection and OpenID Connect |
| [`naf/rate-limit`](https://github.com/nafphp/rate-limit) | Atomic database-backed rate limits with fixed windows |

### Console and background work

| Plugin | Description |
| --- | --- |
| [`naf/cli`](https://github.com/nafphp/cli) | The `naf` console and your own commands |
| [`naf/queue`](https://github.com/nafphp/queue) | Background jobs and workers |
| [`naf/schedule`](https://github.com/nafphp/schedule) | Recurring tasks in cron syntax |

### Integrations and operations

| Plugin | Description |
| --- | --- |
| [`naf/mail`](https://github.com/nafphp/mail) | Mail delivery with attachments and replaceable transports |
| [`naf/client`](https://github.com/nafphp/client) | A PSR-18 HTTP client |
| [`naf/websocket`](https://github.com/nafphp/websocket) | A PHP WebSocket server for application change notifications |
| [`naf/mcp`](https://github.com/nafphp/mcp) | Let AI agents call into your application |
| [`naf/alexa`](https://github.com/nafphp/alexa) | Alexa+ MCP integration with OAuth setup and diagnostics |
| [`naf/monitoring`](https://github.com/nafphp/monitoring) | Metrics, StatsD export and optional PSR-3 logging integration |

### CMS and Kanban boards

| Plugin | Description |
| --- | --- |
| [`naf/cms`](https://github.com/nafphp/cms) | NafCMS: extensible content management inside a NAF application |
| [`naf/board`](https://github.com/nafphp/board) | Project-isolated Kanban boards and extensions powering Nafinity |

Not sure which of these you need?
**[Start here](https://nafphp.github.io/docs/choosing-packages/)** — it answers that question
before you install anything.

---

## 📚 Documentation

📘 Read the full docs at **[nafphp.github.io/docs](https://nafphp.github.io/docs)**

Coming from NixPHP? The [upgrade guide](https://nafphp.github.io/docs/upgrading-from-nixphp/)
covers the rename in one page.

---

## 🚀 Get started

```bash
composer create-project naf/app my-app
```

Then follow [your first application](https://nafphp.github.io/docs/first-app/).
