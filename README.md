```
$ whoami
```
# DonaldRaph — Building toward SRE from the ground up

```
donaldraph@localhost:~$ cat /etc/system-release
Training: Cloud Infrastructure → SRE
Status:   In progress
Started:  From zero
```

I'm not a cloud engineer yet. This GitHub is where I'm training to become one — every lab, every broken config, every debugging session, documented in real time.

---

## `$ systemctl status training`

```
● sre-training.service - 9-Month SRE Execution Playbook
     Active: active (running) since Week 1
      Phase: 1/3 — Linux & Cloud Foundations
   Progress: ████░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░ 3%
   
   ┌─────────────────────────────────────────────────┐
   │  PHASE 1  Months 1–3   Foundations        [NOW] │
   │  PHASE 2  Months 4–6   Reliability Engineering  │
   │  PHASE 3  Months 7–9   Mastery & Production     │
   └─────────────────────────────────────────────────┘
```

## `$ cat /proc/roadmap`

```
 ┌──────────────┐    ┌──────────────┐    ┌──────────────┐    ┌──────────────┐
 │    LINUX     │───▶│    CLOUD     │───▶│     SRE      │───▶│  OPEN SOURCE │
 │ FUNDAMENTALS │    │ ENGINEERING  │    │  PRACTICES   │    │ CONTRIBUTOR  │
 │              │    │              │    │              │    │              │
 │ Processes    │    │ Kubernetes   │    │ SLOs & Error │    │ CNCF PRs     │
 │ Networking   │    │ Terraform    │    │ Budgets      │    │ Tech Writing │
 │ Containers   │    │ CI/CD        │    │ Chaos Eng    │    │ Conferences  │
 │ Debugging    │    │ Observability│    │ Incidents    │    │ Mentorship   │
 └──────┬───────┘    └──────────────┘    └──────────────┘    └──────────────┘
        │
     [I AM HERE]
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

---

## `$ ls ~/repos`

| Repository | Description | Status |
|:-----------|:------------|:------:|
| [`sre-training`](https://github.com/donaldraph/sre-training) | Labs, debugging diaries, architecture decisions, and notes from my 9-month SRE playbook | `ACTIVE` |
| `public-engineering-journal` | Incident writeups, failure investigations, and ADRs written for public review | `PLANNED` |
| `diagrams` | Architecture diagrams, system flows, and failure cascade visualizations | `PLANNED` |
| `dotfiles` | Shell configs, tool setups, and lab environment automation | `PLANNED` |

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
[2026-03-17] Week 1 — Linux process model, /proc filesystem,
             memory investigation, containers as processes, OOM kills
```
*This section updates weekly.*

---

## `$ cat /etc/contact.conf`

```
linkedin  = https://linkedin.com/in/donaldraph
dev.to    = https://dev.to/donaldraph
youtube   = https://youtube.com/@donaldraph
```

---

```
$ uptime
Started from zero. Building in public. No shortcuts.
```
