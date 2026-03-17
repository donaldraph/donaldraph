```
$ whoami
```
# Donald — Building toward SRE from the ground up

```
donald@localhost:~$ cat /etc/system-release
Training: Cloud Infrastructure → SRE
Status:   In progress
Started:  From zero
```

I'm not a cloud engineer yet. This GitHub is where I'm becoming one — every lab, every broken config, every debugging session, documented in real time.

---

## `$ systemctl status sre-training`

```
● sre-training.service - 9-Month SRE Transformation Program
     Active: active (running) since Week 1
      Phase: 1/6 — Linux Foundations
   Uptime:  Week 1 of 36
```

### Infrastructure Status

| Phase | Module | Weeks | Light | Status |
|:------|:-------|:-----:|:-----:|:-------|
| **MONTH 1** | **Linux Foundations** | | | |
| | Process Model & Resource Investigation | 1 | 🟢 | `▓░░░░░░░░░` Running |
| | Log Investigation & Bash Automation | 2 | ⚪ | `░░░░░░░░░░` Pending |
| | Networking for Cloud Engineers | 3 | ⚪ | `░░░░░░░░░░` Pending |
| | Python for DevOps & Git | 4 | ⚪ | `░░░░░░░░░░` Pending |
| **MONTH 2** | **Containers, Docker & Cloud** | | | |
| | Docker Internals | 5 | ⚪ | `░░░░░░░░░░` Pending |
| | Kubernetes Architecture & Debugging | 6 | ⚪ | `░░░░░░░░░░` Pending |
| | Terraform Advanced & IaC Patterns | 7 | ⚪ | `░░░░░░░░░░` Pending |
| | CI/CD Pipelines & GitOps | 8 | ⚪ | `░░░░░░░░░░` Pending |
| **MONTH 3** | **Observability & Systems Math** | | | |
| | Prometheus & Metrics | 9 | ⚪ | `░░░░░░░░░░` Pending |
| | SLI/SLO/Error Budgets | 10 | ⚪ | `░░░░░░░░░░` Pending |
| | Distributed Tracing & OpenTelemetry | 11 | ⚪ | `░░░░░░░░░░` Pending |
| | Systems Math Deep Dive | 12 | ⚪ | `░░░░░░░░░░` Pending |
| **MONTHS 4–5** | **Failure Engineering & Migration** | | | |
| | Chaos Engineering | 13–14 | ⚪ | `░░░░░░░░░░` Pending |
| | Incident Response & Command | 15–16 | ⚪ | `░░░░░░░░░░` Pending |
| | Migration Patterns | 17–18 | ⚪ | `░░░░░░░░░░` Pending |
| | IAM Security & Cost Engineering | 19–20 | ⚪ | `░░░░░░░░░░` Pending |
| **MONTHS 6–7** | **Advanced Infra & Platform Eng** | | | |
| | Kubernetes Advanced (RBAC, Scheduling) | 21–22 | ⚪ | `░░░░░░░░░░` Pending |
| | Platform Engineering & Developer CLI | 23–24 | ⚪ | `░░░░░░░░░░` Pending |
| | Advanced Observability & Performance | 25–26 | ⚪ | `░░░░░░░░░░` Pending |
| | Multi-Region & High Availability | 27–28 | ⚪ | `░░░░░░░░░░` Pending |
| **MONTHS 8–9** | **Capstone & Career Launch** | | | |
| | Capstone Project (Multi-AZ Platform) | 29–32 | ⚪ | `░░░░░░░░░░` Pending |
| | Interview Preparation | 33–34 | ⚪ | `░░░░░░░░░░` Pending |
| | Career Positioning & Job Search | 35–36 | ⚪ | `░░░░░░░░░░` Pending |

> 🟢 Running &nbsp; 🟡 Queued &nbsp; 🔵 Complete &nbsp; ⚪ Pending

---

## `$ cat /proc/roadmap`

```
  MONTH 1          MONTH 2          MONTH 3          MONTHS 4–5
 ┌────────────┐   ┌────────────┐   ┌────────────┐   ┌────────────┐
 │  LINUX     │──▶│ CONTAINERS │──▶│OBSERVABILITY──▶│  FAILURE   │
 │ FOUNDATIONS│   │ DOCKER K8S │   │& SYSTEMS   │   │ENGINEERING │
 │            │   │ TERRAFORM  │   │   MATH     │   │& MIGRATION │
 │ Processes  │   │ CI/CD      │   │ Prometheus │   │ Chaos Eng  │
 │ Networking │   │ IaC        │   │ SLOs       │   │ Incidents  │
 │ Bash/Python│   │ GitOps     │   │ Tracing    │   │ IAM & Cost │
 └─────┬──────┘   └────────────┘   └────────────┘   └────────────┘
       │
    [HERE]

  MONTHS 6–7       MONTHS 8–9
 ┌────────────┐   ┌────────────┐
 │ ADVANCED   │──▶│  CAPSTONE  │
 │ INFRA &    │   │ & CAREER   │
 │ PLATFORM   │   │  LAUNCH    │
 │ K8s Adv    │   │ Multi-AZ   │
 │ Platform   │   │ Interviews │
 │ Multi-AZ   │   │ Job Search │
 └────────────┘   └────────────┘
```

---

## `$ kubectl get training-stack`

#### Currently studying

![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

#### On the training roadmap

![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![Helm](https://img.shields.io/badge/Helm-0F1689?style=for-the-badge&logo=helm&logoColor=white)
![ArgoCD](https://img.shields.io/badge/Argo-EF7B4D?style=for-the-badge&logo=argo&logoColor=white)

---

## `$ ls ~/repos`

| Repository | | Description |
|:-----------|:--:|:------------|
| [`sre-training`](https://github.com/donaldraph/sre-training) | 🟢 | Labs, debugging diaries, architecture decisions, and notes from my 9-month SRE playbook |
| `public-engineering-journal` | ⚪ | Incident writeups, failure investigations, and ADRs |
| `diagrams` | ⚪ | Architecture diagrams, system flows, and failure cascades |
| `dotfiles` | ⚪ | Shell configs, tool setups, and lab environment automation |

---

## `$ cat /var/log/writing.log`

I document the training process on [Dev.to](https://dev.to/donaldraph) — not as a teacher, but as someone figuring things out and writing down what I find.

**What I publish:**
- Debugging diaries — full investigation logs when things break
- Architecture decision records — why I chose X over Y, even at a beginner level
- Technical articles — explaining what I learn by building and breaking things
- Incident writeups — structured postmortems from lab failures

### Recent posts

<!-- BLOG-POST-LIST:START -->
*First posts coming soon — setting up now.*
<!-- BLOG-POST-LIST:END -->

<a href="https://dev.to/donaldraph">
  <img src="https://img.shields.io/badge/dev.to-0A0A0A?style=for-the-badge&logo=devdotto&logoColor=white" alt="Dev.to" />
</a>

---

## `$ journalctl -u youtube --latest`

I make videos about the same things I write about — cloud infrastructure, debugging, and building things from scratch. No hype, just the work.

<!-- YOUTUBE-CARDS:START -->
*First video in production.*
<!-- YOUTUBE-CARDS:END -->

<a href="https://youtube.com/@donaldraph">
  <img src="https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white" alt="YouTube" />
</a>

---

## `$ tail -1 /var/log/current-focus.log`

```
🟢 [2026-03-17] Week 1 — Process Model & Resource Investigation
   Linux processes, /proc, memory, CPU investigation, OOM kills, exit codes
```
*This section updates weekly.*

---

## `$ cat /etc/contact.conf`

<a href="https://linkedin.com/in/donaldraph">
  <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
</a>
<a href="https://dev.to/donaldraph">
  <img src="https://img.shields.io/badge/dev.to-0A0A0A?style=for-the-badge&logo=devdotto&logoColor=white" alt="Dev.to" />
</a>
<a href="https://youtube.com/@donaldraph">
  <img src="https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white" alt="YouTube" />
</a>

---

```
$ uptime
Started from zero. Building in public. No shortcuts.
```
