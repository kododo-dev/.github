<div align="center">
  <img src="https://avatars.githubusercontent.com/u/253352073" width="72" style="border-radius:50%" />
  <h2>kododo-dev</h2>
  <p>open source &nbsp;·&nbsp; .NET &amp; TypeScript &nbsp;·&nbsp; MIT</p>
</div>

<br>

> Small, focused libraries for ASP.NET Core — built to eliminate boilerplate without getting in the way.
> Minimal dependencies. Explicit wiring. No magic.

---

## Packages

### [Reiho.AspNetCore](https://github.com/kododo-dev/Reiho) &nbsp;`C#`

Typed request/handler abstraction for Minimal APIs. Define requests, implement handlers, auto-map endpoints — plus a helper for serving embedded SPAs with base-path injection and aggressive asset caching.

`minimal api` &nbsp; `cqrs-lite` &nbsp; `embedded spa` &nbsp; `.net 8+`

```sh
dotnet add package Kododo.Reiho.AspNetCore
```

---

### [ConfigWay](https://github.com/kododo-dev/ConfigWay) &nbsp;`TypeScript + C#`

Runtime configuration editor. Modify `IOptions<T>` values through a built-in web UI without restarting the app.
Validation, PostgreSQL persistence, and authorization support included.

`ioptions` &nbsp; `runtime config` &nbsp; `postgresql` &nbsp; `web ui` &nbsp; `.net 8+`

```sh
dotnet add package Kododo.ConfigWay
```

---

## Principles

- **Single responsibility** — each package solves exactly one problem. No utility grab-bags.
- **Minimal surface area** — small public API, opinionated defaults, easy to override.
- **Zero magic** — explicit wiring, readable stack traces, no hidden conventions.
- **MIT licensed** — all packages. No CLAs, no commercial tiers.

---

<sub>[nuget.org / Kododo.*](https://www.nuget.org/profiles/Kododo) &nbsp;·&nbsp; issues & PRs welcome</sub>
