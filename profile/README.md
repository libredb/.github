<div align="center">

<img src="https://raw.githubusercontent.com/libredb/libredb-studio/main/public/logo.svg" width="110" alt="LibreDB" />

# Hi, we're LibreDB 👋

**Database tools we'd want to use ourselves. Most of them open source, all of them built on one foundation.**

[Try Studio live](https://app.libredb.org) · [Website](https://libredb.org) · [Discussions](https://github.com/orgs/libredb/discussions) · [LinkedIn](https://www.linkedin.com/company/libredb)

</div>

---

We make three things.

Two are open source and free: a web-based SQL/NoSQL IDE that runs in your browser, and a small embeddable database engine you can read end to end. The third is **LibreDB Platform**, a commercial product for teams and enterprises, and it's what pays for the open-source work. So Studio and the engine stay free, and stay maintained.

One foundation, three products. Here's the tour.

## LibreDB Studio: the open-source SQL/NoSQL web IDE

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://github.com/libredb/libredb-studio/blob/main/LICENSE)
[![Quality Gate](https://sonarcloud.io/api/project_badges/measure?project=libredb_libredb-studio&metric=alert_status)](https://sonarcloud.io/project/overview?id=libredb_libredb-studio)
[![DeepWiki](https://img.shields.io/badge/Docs-DeepWiki-blue?logo=gitbook)](https://deepwiki.com/libredb/libredb-studio)

A professional database editor that lives in your browser. No install, and it works on a 4K monitor or a phone. It sits between heavy desktop clients and bare CLIs: the power of DataGrip, reachable from a URL.

- **AI-native:** NL2SQL with your choice of model (Gemini, OpenAI, or a local LLM)
- **A real IDE:** Monaco engine, schema-aware autocomplete, multi-tab workspace, visual EXPLAIN
- **See your schema:** interactive ER diagrams, schema diff, migration SQL, snapshot timeline
- **SQL and NoSQL:** PostgreSQL, MySQL, Oracle, SQL Server, MongoDB, Redis, SQLite
- **Enterprise-ready:** RBAC, SSO (OIDC), query auditing, Docker & Kubernetes

<p align="center">
  <a href="https://app.libredb.org">
    <img src="https://raw.githubusercontent.com/libredb/libredb-studio/main/public/screenshots/hero-editor.png" width="80%" alt="LibreDB Studio" />
  </a>
</p>

**[Try it live demo](https://app.libredb.org)** &nbsp;·&nbsp; **[Source & deploy guide →](https://github.com/libredb/libredb-studio)**

## LibreDB: the engine underneath

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://github.com/libredb/libredb-database/blob/main/LICENSE)
[![npm](https://img.shields.io/npm/v/@libredb/libredb.svg)](https://www.npmjs.com/package/@libredb/libredb)
[![Coverage](https://sonarcloud.io/api/project_badges/measure?project=libredb_libredb-database&metric=coverage)](https://sonarcloud.io/summary/new_code?id=libredb_libredb-database)

> *Multi-model without the magic. One core, three lenses, every line tested.*

A small, readable, embeddable database written in TypeScript. Key-value, document, and relational APIs are thin *lenses* over a single ordered key-value core, not three engines bolted together. Zero runtime dependencies, in-memory or file-backed, with crash recovery proven by deterministic simulation testing.

The kernel is under 600 lines. You can open the source and actually learn how a database works.

```sh
bun add @libredb/libredb
```

It's pre-alpha and aimed at test and dev environments today: small enough to understand, serious enough to grow.

**[Try the playground](https://libredb.org/playground)** &nbsp;·&nbsp; **[Explore the source →](https://github.com/libredb/libredb-database)**

## LibreDB Platform: for teams, and how we keep the lights on

Distributing database credentials by hand doesn't scale, and it isn't safe. **Platform** replaces that with a managed, multi-tenant workspace: admins decide who can reach which database, every query is logged, and teams collaborate without anyone copy-pasting a connection string.

Built on the same Studio engine, with governance on top: RBAC, encrypted credentials, full query audit, billing and plans. This is the commercial product that funds everything above it.

**[See plans & book a demo →](https://libredb.github.io)**

## How it all fits together

```
LibreDB            →   LibreDB Studio      →   LibreDB Platform
the embeddable         the open-source         the governed,
database engine        IDE built on it         multi-tenant product
(open source)          (open source)           (commercial)
```

Start anywhere. Embed the engine in your app, run Studio for your own databases, or bring Platform in when your team needs control and an audit trail.

## Get involved

The open-source projects are built in the open, and we'd love your help.

- ⭐ Star [Studio](https://github.com/libredb/libredb-studio) and [the engine](https://github.com/libredb/libredb-database) if they're useful to you
- 🐛 Open an issue or a PR. Both repos welcome contributions.
- 💬 Say hello in [Discussions](https://github.com/orgs/libredb/discussions)
- 💖 [Sponsor us](https://github.com/sponsors/libredb) to help keep Studio and the engine free

<div align="center">
<br/>

[![Studio](https://github-readme-stats.vercel.app/api/pin/?username=libredb&repo=libredb-studio&theme=default)](https://github.com/libredb/libredb-studio)
[![Engine](https://github-readme-stats.vercel.app/api/pin/?username=libredb&repo=libredb-database&theme=default)](https://github.com/libredb/libredb-database)

<sub>Made by the LibreDB team · <a href="https://libredb.org">libredb.org</a></sub>

</div>
