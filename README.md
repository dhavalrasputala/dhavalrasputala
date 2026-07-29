<table>
<tr>
<td width="300" valign="top">

<img src="ascii_art_neutral.png" width="300" alt="ASCII ART">

</td>
<td valign="top">

### Dhaval Rasputala
**Backend Developer (Go) — open to internship / junior backend roles**

I build backend systems and like understanding what's actually happening under the abstractions — how a write becomes durable, how a request gets authorized. Currently building an Rate Limiting Gateway(private repo) , and exploring distributed systems fundamentals through [Distributed_Key_Value_Store](https://github.com/dhavalrasputala/Distributed_Key_Value_Store).

📫 dhavalrasputala@gmail.com · [LinkedIn](https://linkedin.com/in/dhavalrasputala)

</td>
</tr>
</table>

---

## Featured Projects

### [Distributed_Key_Value_Store](https://github.com/dhavalrasputala/Distributed_Key_Value_Store)
A key-value store written in Go from scratch — no external database, just a write-ahead log, an in-memory map, and leader → follower replication. Built to answer a specific question: what actually happens on disk in the moments after a database says a write is "durable."

- Every write is fsync'd to a WAL before it's considered committed; full state rebuild on startup by replaying the log
- Leader → follower replication over HTTP, with concurrent-safe reads/writes verified via `go test -race`
- Load-tested at 10,000 concurrent requests (0 failures)  see repo for the full breakdown
- README documents current limitations : no quorum acks, no leader election yet, no follower catch-up path

**Stack:** Go · HTTP · WAL/durability · concurrency

### [GateKeeper](https://github.com/dhavalrasputala/GateKeeper)
A lightweight, dependency-free RBAC (role-based access control) engine for Go — manages users, roles, and permissions, and answers one question fast: *can this user do this action on this resource?*

- Typed sentinel errors throughout (`errors.Is`-compatible) instead of generic error strings
- Defensive copies on reads so callers can't mutate internal engine state
- Fully tested; zero external dependencies

**Stack:** Go · access control · API design

---

## Tech Stack

![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![Java](https://img.shields.io/badge/Java-007396?style=flat-square&logo=openjdk&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-FF9900?style=flat-square&logo=amazonaws&logoColor=white)
![GraphQL](https://img.shields.io/badge/GraphQL-E10098?style=flat-square&logo=graphql&logoColor=white)
![Kafka](https://img.shields.io/badge/Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white)

---

## Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/dhavalrasputala)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:dhavalrasputala@gmail.com)
