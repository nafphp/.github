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

| Plugin | Description |
| --- | --- |
| [`naf/view`](https://github.com/nafphp/view) | Native PHP templating with layout blocks |
| [`naf/form`](https://github.com/nafphp/form) | CSRF protection, validation and input memory |
| [`naf/session`](https://github.com/nafphp/session) | Session and flash message support |
| [`naf/database`](https://github.com/nafphp/database) | PDO connection, migrations and query helpers |
| [`naf/orm`](https://github.com/nafphp/orm) | Models and repositories on top of PDO |
| [`naf/i18n`](https://github.com/nafphp/i18n) | Translations and pluralisation |
| [`naf/cli`](https://github.com/nafphp/cli) | The `naf` console and your own commands |
| [`naf/mail`](https://github.com/nafphp/mail) | Send mail, with attachments |
| [`naf/client`](https://github.com/nafphp/client) | A PSR-18 HTTP client |
| [`naf/queue`](https://github.com/nafphp/queue) | Background jobs and workers |
| [`naf/schedule`](https://github.com/nafphp/schedule) | Recurring tasks in cron syntax |
| [`naf/auth`](https://github.com/nafphp/auth) | Logins, roles, permissions and policies |
| [`naf/oauth-client`](https://github.com/nafphp/oauth-client) | Sign in with Google, Microsoft or any OIDC provider |
| [`naf/oauth-server`](https://github.com/nafphp/oauth-server) | Be the provider: OAuth2 and OpenID Connect |
| [`naf/mcp`](https://github.com/nafphp/mcp) | Let AI agents call into your application |

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
