<div align="center">
  <img src="https://avatars.githubusercontent.com/u/253352073" width="72" style="border-radius:50%" />
  <h2>kododo-dev</h2>
  <p>Small tools that do one job well &nbsp;·&nbsp; open source &nbsp;·&nbsp; MIT</p>
  <p><sub>Self-hosted apps for any stack and lightweight libraries for ASP.NET&nbsp;Core.</sub></p>
</div>

<br>

## Self-hosted apps

Run them with Docker and use them from any platform.

### 🌐 Polyglot

Translation management for apps on any platform. Translators edit strings in a web UI with sign-in, roles and a change history. Your apps read them as plain JSON through a read-only API with an OpenAPI document. Runs on your own PostgreSQL.

`translations` &nbsp; `docker` &nbsp; `postgresql` &nbsp; `rest api` &nbsp; `openapi` &nbsp; `any stack`

```sh
docker pull ghcr.io/kododo-dev/polyglot
```

[Demo](https://kododo.dev/polyglot/demo) &nbsp; [GitHub](https://github.com/kododo-dev/Polyglot) &nbsp; [Quick start](https://github.com/kododo-dev/Polyglot#quick-start) &nbsp; [Docker image](https://github.com/kododo-dev/Polyglot/pkgs/container/polyglot)

<br>

## Libraries for ASP.NET Core

NuGet packages you add to your own app.

### ⏱️ RunWay

Persistent background job queue. Priority scheduling, automatic retries, timeout support, outbox pattern, recurring jobs, and a built-in web dashboard.

`background jobs` &nbsp; `scheduler` &nbsp; `outbox` &nbsp; `postgresql` &nbsp; `.net 8+`

```sh
dotnet add package Kododo.RunWay
```

[![NuGet](https://img.shields.io/nuget/v/Kododo.RunWay)](https://www.nuget.org/packages/Kododo.RunWay) &nbsp; [Demo](https://kododo.dev/runway/demo) &nbsp; [GitHub](https://github.com/kododo-dev/RunWay)

---

### 🎚️ ConfigWay

Runtime configuration editor. Modify `IOptions<T>` values through a built-in web UI without restarting the app. Validation, PostgreSQL persistence, and authorization included.

`ioptions` &nbsp; `runtime config` &nbsp; `postgresql` &nbsp; `web ui` &nbsp; `.net 8+`

```sh
dotnet add package Kododo.ConfigWay
```

[![NuGet](https://img.shields.io/nuget/v/Kododo.ConfigWay)](https://www.nuget.org/packages/Kododo.ConfigWay) &nbsp; [Demo](https://kododo.dev/configway/demo) &nbsp; [GitHub](https://github.com/kododo-dev/ConfigWay)

---

### 🗣️ CultureWay

Runtime localization editor. Edit translated strings and manage languages through a built-in web UI without a rebuild or restart. Works with `IStringLocalizer` and existing `.resx` files. Polyglot is built on it.

`localization` &nbsp; `istringlocalizer` &nbsp; `resx` &nbsp; `postgresql` &nbsp; `web ui` &nbsp; `.net 8+`

```sh
dotnet add package Kododo.CultureWay
```

[![NuGet](https://img.shields.io/nuget/vpre/Kododo.CultureWay)](https://www.nuget.org/packages/Kododo.CultureWay) &nbsp; [Demo](https://kododo.dev/cultureway/demo) &nbsp; [GitHub](https://github.com/kododo-dev/CultureWay)

---

### 🧭 Reiho

Typed request/handler abstraction for Minimal APIs. Define requests, implement handlers, auto-map endpoints. Also a helper for serving embedded SPAs with base-path injection and aggressive asset caching.

`minimal api` &nbsp; `cqrs-lite` &nbsp; `embedded spa` &nbsp; `.net 8+`

```sh
dotnet add package Kododo.Reiho.AspNetCore
```

[![NuGet](https://img.shields.io/nuget/v/Kododo.Reiho.AspNetCore)](https://www.nuget.org/packages/Kododo.Reiho.AspNetCore) &nbsp; [GitHub](https://github.com/kododo-dev/Reiho)

<br>

## Principles

- **Single responsibility.** Each project solves exactly one problem. No utility grab-bags.
- **Minimal surface area.** Small public API, opinionated defaults, easy to override.
- **Zero magic.** Explicit wiring, readable stack traces, no hidden conventions.
- **MIT licensed.** Every project. No CLAs, no commercial tiers.

---

<sub>[kododo.dev](https://kododo.dev) &nbsp;·&nbsp; [nuget.org / Kododo.*](https://www.nuget.org/profiles/kododo-dev) &nbsp;·&nbsp; issues & PRs welcome</sub>
