<table>
<tr>
<td width="300" valign="top">

<img src="ascii_art_neutral.png" width="300" alt="ASCII ART">

</td>
<td valign="top">

### Dhaval Rasputala
**Backend Developer (Go) — open to internship / junior backend roles**

I build backend systems and like understanding what's actually happening under the abstractions — how a write becomes durable, how a request gets authorized. Currently building an Rate Limiting Gateway([limitr](https://github.com/dhavalrasputala/limitr)) , and exploring distributed systems fundamentals through [Distributed_Key_Value_Store](https://github.com/dhavalrasputala/Distributed_Key_Value_Store).

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

### [limitr](https://github.com/dhavalrasputala/limitr)
A lightweight , dependency-free API Gateway built in pure GO Add Proxys,Rate Limit Users,and answers one question fast : *is this user trying to DDOS attack our APIs?*

- Configurable File to define rate limits , add more proxy & configure Auth keys
- Added Authorization to Stop Unauthorized users to alter global rate limit
- tested with 500  request & 200 concurrent Users

**Stack:** Go . access control . rate limiting . concurrency

---

## Tech Stack

![Go](https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white)
![python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white)
![GraphQL](https://img.shields.io/badge/GraphQL-E10098?style=for-the-badge&logo=graphql&logoColor=white)
![Kafka](https://img.shields.io/badge/Kafka-231F20?style=for-the-badge&logo=apachekafka&logoColor=white)

---

## Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/dhavalrasputala)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:dhavalrasputala@gmail.com)
