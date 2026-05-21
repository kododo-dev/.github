<div align="center">
  <img src="https://avatars.githubusercontent.com/u/253352073" width="72" style="border-radius:50%" />
  <h2>kododo-dev</h2>
  <p>Simple tools for ASP.NET&nbsp;Core &nbsp;·&nbsp; open source &nbsp;·&nbsp; MIT</p>
  <p><sub>Lightweight, focused packages that solve one problem well — without the boilerplate.</sub></p>
</div>

<br>

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

### 🧭 Reiho

Typed request/handler abstraction for Minimal APIs. Define requests, implement handlers, auto-map endpoints — plus a helper for serving embedded SPAs with base-path injection and aggressive asset caching.

`minimal api` &nbsp; `cqrs-lite` &nbsp; `embedded spa` &nbsp; `.net 8+`

```sh
dotnet add package Kododo.Reiho.AspNetCore
```

[![NuGet](https://img.shields.io/nuget/v/Kododo.Reiho.AspNetCore)](https://www.nuget.org/packages/Kododo.Reiho.AspNetCore) &nbsp; [GitHub](https://github.com/kododo-dev/Reiho)

---

## Principles

- **Single responsibility** — each package solves exactly one problem. No utility grab-bags.
- **Minimal surface area** — small public API, opinionated defaults, easy to override.
- **Zero magic** — explicit wiring, readable stack traces, no hidden conventions.
- **MIT licensed** — all packages. No CLAs, no commercial tiers.

---

<sub>[nuget.org / Kododo.*](https://www.nuget.org/profiles/kododo-dev) &nbsp;·&nbsp; issues & PRs welcome &nbsp;·&nbsp; [kododo.dev](https://kododo.dev)</sub>
