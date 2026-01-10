<!--
  Profile README for: Eric-Lebedenko
  Brand: Eric L. Morgan (ericlmorgan.com)
  Theme: Mission Control / Ops KB (Bottomless)
  Notes:
  - Put this file into a repo named exactly: Eric-Lebedenko
  - GitHub will render it on your profile automatically
-->

<p align="center">
  <img
    src="https://capsule-render.vercel.app/api?type=waving&color=gradient&height=190&section=header&text=Eric%20L.%20Morgan&fontSize=52&fontAlignY=36&desc=IT%20System%20Integration%20%C2%B7%20Automation%20%C2%B7%20Software%20Engineering&descAlignY=62&animation=fadeIn"
    alt="header"
  />
</p>

<p align="center">
  <a href="https://readme-typing-svg.demolab.com">
    <img
      src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=16&pause=900&center=true&vCenter=true&width=920&lines=Aspiring+Fachinformatiker+%E2%80%93+Systemintegration;Automation-first+ops.+Repeatable.+Observable.+Safe-by-default.;Linux+%E2%80%A2+Windows+%E2%80%A2+Networking+%E2%80%A2+Docker+%E2%80%A2+Scripting;Strategy+without+execution+is+hallucination."
      alt="typing"
    />
  </a>
</p>

<p align="center">
  <a href="https://img.shields.io/badge/Focus-System%20Integration-0b7285"><img src="https://img.shields.io/badge/Focus-System%20Integration-0b7285" alt="Focus"/></a>
  <a href="https://img.shields.io/badge/Focus-Automation-1c7ed6"><img src="https://img.shields.io/badge/Focus-Automation-1c7ed6" alt="Automation"/></a>
  <a href="https://img.shields.io/badge/Focus-Reliable%20Systems-6741d9"><img src="https://img.shields.io/badge/Focus-Reliable%20Systems-6741d9" alt="Reliable Systems"/></a>
</p>

<p align="center">
  <a href="https://ericlmorgan.com"><img src="https://img.shields.io/website?down_color=red&down_message=down&up_color=green&up_message=up&url=https%3A%2F%2Fericlmorgan.com" alt="Website"/></a>
  <a href="https://linkedin.com/in/Eric-Lebedenko"><img src="https://img.shields.io/badge/LinkedIn-Eric%20Lebedenko-0A66C2?logo=linkedin&logoColor=white" alt="linkedin"/></a>
  <a href="mailto:erik.lebedenko.888@gmail.com"><img src="https://img.shields.io/badge/Email-erik.lebedenko.888%40gmail.com-333333?logo=gmail&logoColor=white" alt="email"/></a>
  <a href="https://github.com/Eric-Lebedenko"><img src="https://img.shields.io/github/followers/Eric-Lebedenko?label=Followers&style=flat" alt="followers"/></a>
  <a href="https://github.com/Eric-Lebedenko?tab=repositories"><img src="https://img.shields.io/badge/Repos-GitHub-black" alt="repos"/></a>
</p>

---

# Mission
Aspiring **Fachinformatiker – Systemintegration** focused on **practical IT**, **automation**, and **reliable system design**.

> “Strategy without execution is hallucination.”

---

# Navigation (scroll-friendly)
- [Now](#now)
- [Ops Dashboard](#ops-dashboard)
- [System Map](#system-map)
- [Tech Stack](#tech-stack-practical)
- [Projects](#projects)
- [Operational Systems](#operational-systems)
- [Runbooks & Playbooks](#runbooks--playbooks)
- [Incident Museum](#incident-museum)
- [Homelab](#homelab)
- [Security Posture](#security-posture)
- [Learning Matrix](#learning-matrix)
- [Cheatsheets](#cheatsheets)
- [Contact](#contact)

---

## Now
**What I’m doing currently**
- Preparing for Ausbildung (Systemintegration)
- Building small infra-related projects
- Practicing Linux/Windows administration, networking basics, Docker
- Writing automation scripts (repeatable, idempotent, documented)

**What I’m looking for**
- Ausbildung / internship opportunities where I can contribute with: documentation, automation, troubleshooting, clean ops.

---

## Ops Dashboard
### Core focus areas
| Domain | Capabilities | Status |
|---|---|---|
| Linux Admin | users/permissions, services, logs, troubleshooting | L → A |
| Windows Admin | basics, services, troubleshooting, fundamentals | L |
| Networking | TCP/IP, DNS, DHCP, VLAN basics, diagnostics | L → A |
| Containers | Docker fundamentals, compose patterns | L |
| Automation | scripting, CLI tooling, repeatable tasks, mini-pipelines | A |
| Security | least privilege, updates, secrets hygiene, baseline checks | L |

### Operating principles (I actually use)
- **Automate the second time**: if done twice → script it.
- **Make it observable**: logs first; then opinions.
- **Safe defaults**: least privilege, explicit configs, secrets discipline.
- **Docs are production**: runbooks are part of the deliverable.

---

## System Map
```mermaid
flowchart LR
  U[User / Client] -->|Requests| S[Services]
  S --> A[Automation Layer]
  A --> L[Logs & Observability]
  A --> I[Infrastructure]
  I --> N[Networking: DNS/DHCP/VLAN]
  I --> C[Containers: Docker]
  I --> W[Windows/Linux Hosts]
  L --> R[Runbooks & RCA]
```

---

## Tech Stack (practical)
**Languages:** Python · C++ · C# · JavaScript  
**Web/Markup:** HTML5 · CSS3  
**Tools:** Git/GitHub · Linux (basic) · Docker (learning) · SQL (basic)  
**Concepts:** system integration · automation · scripting · infrastructure basics

<p>
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=python,cpp,cs,js,html,css,linux,docker,git,github,sqlite&perline=11" alt="skills" />
  </a>
</p>

---

## Projects
| Project | Why it exists | Stack |
|---|---|---|
| **[Telegram-bot-DVAG](https://github.com/Eric-Lebedenko/Telegram-bot-DVAG)** | automated partner/client sourcing & intake, structured flows | Python, aiogram |
| **Finance Tools (private/soon)** | analytics toolkit (CAPM, factor views), API-first thinking | Python, Pandas, FastAPI |
| **Investment Calculator (soon)** | ROI & DCF web app for practical decision support | Python, Streamlit |

---

## Operational Systems
This is a “systems-first” section: even if projects are small, I document them like production.

<details>
  <summary><b>System catalog template (copy/paste)</b></summary>

**System name:**  
**Purpose:**  
**Users:**  
**Interface:** CLI / Web / Bot / API  
**Runtime:** Linux / Windows / Docker  
**Data:** where stored, backup policy  
**Secrets:** how stored (never in repo)  
**Observability:** logs/metrics/alerts  
**SLO (training):** e.g. 99% weekly availability, RTO/RPO targets  
**Runbook:** link  
**Change log:** link/notes

</details>

<details>
  <summary><b>Example SLOs (training-grade but realistic)</b></summary>

- **Availability:** 99.0% per week (allowed downtime ~1h 40m/week)
- **RTO:** 60 minutes (restore service within 1 hour)
- **RPO:** 24 hours (lose at most 1 day of data)
- **MTTR target:** under 30–60 minutes for common incidents

</details>

---

# Runbooks & Playbooks
Ниже — “бездна”: раскрывающиеся разделы, как внутренний wiki/KB.

<details>
  <summary><b>Runbook template (copy/paste)</b></summary>

**Purpose**  
- What this system does, for whom, and what “healthy” looks like.

**Dependencies**  
- External services, credentials, ports, DNS entries.

**Start/Stop**  
- Start:
- Stop:
- Restart:

**Health Checks**  
- `systemctl status ...`
- `journalctl -u ... -n 200 --no-pager`
- Endpoint check:
- Disk/CPU/RAM checks:

**Common Incidents**  
- Symptom → likely cause → fix steps

**Rollback**  
- How to revert safely

**Owner**  
- Who maintains this and escalation path

</details>

<details>
  <summary><b>Incident report template (RCA)</b></summary>

**Title:**  
**Severity:** SEV-1/2/3  
**Start:**  
**End:**  
**Impact:** Who/what was affected

**Timeline**
- T0:
- T+5:
- T+30:
- Resolution:

**Root Cause**
- Primary cause:
- Contributing factors:

**Corrective actions**
- Immediate fix:
- Preventative tasks (automation/monitoring/docs):

**Lessons learned**
- What worked:
- What failed:
- What to improve:

</details>

<details>
  <summary><b>Checklists (Ops)</b></summary>

### Pre-change checklist
- [ ] Backup / snapshot exists
- [ ] Rollback steps written
- [ ] Maintenance window defined (if needed)
- [ ] Monitoring in place (at least logs)
- [ ] Risk assessed (blast radius)

### Post-change checklist
- [ ] Smoke tests passed
- [ ] Logs clean (no new errors)
- [ ] Metrics stable (CPU/RAM/disk/network)
- [ ] Documentation updated

</details>

<details>
  <summary><b>Automation catalog (what I like to automate)</b></summary>

- provisioning: users, packages, configs
- service lifecycle: start/stop/restart/health checks
- log parsing + alerts
- backups + verification
- “one command” environment bootstrap

**Rule:** automation must be:
- idempotent (safe to run repeatedly)
- readable (future-me can debug it)
- logged (you can prove what happened)

</details>

<details>
  <summary><b>Diagnostics playbook (default workflow)</b></summary>

1. **Confirm impact**: who/what is affected, scope, severity  
2. **Check health**: service status, ports, disk, memory, CPU  
3. **Check logs**: last 200 lines + correlate timestamps  
4. **Reproduce**: minimal reproduction steps (if possible)  
5. **Isolate layer**: network → host → container/service → app  
6. **Fix safely**: smallest reversible change  
7. **Verify**: smoke test + log sanity  
8. **Document**: incident note + prevention task

</details>

---

# Incident Museum
Failure stories (even in lab) are proof of real ops thinking.

<details>
  <summary><b>Example: Service won't start after config change</b></summary>

**Symptoms:** `systemctl restart ...` fails, exit code non-zero  
**Hypothesis:** invalid config syntax or permission issue  
**Checks:**
- `systemctl status SERVICE --no-pager`
- `journalctl -u SERVICE -n 200 --no-pager`
- config lint / validation command (if available)

**Fix:**
- rollback config to last known good
- validate and re-apply change in small steps

**Prevention:**
- add config validation to script/CI
- keep a backup of config + timestamped change log

</details>

<details>
  <summary><b>Example: Docker container loses data after restart</b></summary>

**Symptoms:** data disappears after redeploy  
**Root cause (typical):** no volume mounted (data stored in container FS)  
**Fix:** create named volume or bind mount  
**Prevention:** template Compose files with explicit volume mapping + backup job

</details>

---

# Homelab
<details>
  <summary><b>Homelab blueprint (concept)</b></summary>

**Goal:** a repeatable mini-infrastructure that mimics real ops:
- DNS/DHCP simulation
- a couple of services (web/api/bot)
- logging + basic monitoring
- backups + restore tests
- documented runbooks

**Topology (example)**
- router / gateway
- one Linux host (services, docker)
- one Windows VM (admin practice)
- VLAN (optional): mgmt / services / client

</details>

<details>
  <summary><b>“Build log” format I use</b></summary>

Each lab experiment gets:
- **Objective**
- **Steps**
- **Verification**
- **Issues encountered**
- **Fix**
- **Runbook snippet**
- **What I’d improve next time**

</details>

---

# Security Posture
<details>
  <summary><b>Baseline security habits</b></summary>

- least privilege mindset (minimum permissions)
- updates & patch hygiene
- secrets never committed to git
- environment variables / secret stores (where possible)
- logging for accountability (audit mindset)

</details>

<details>
  <summary><b>Hardening checklist (starter)</b></summary>

- [ ] disable unused services
- [ ] firewall rules explicit
- [ ] SSH keys preferred over passwords (where applicable)
- [ ] backups encrypted (where applicable)
- [ ] log rotation configured
- [ ] principle of least privilege applied

</details>

<details>
  <summary><b>Secrets discipline</b></summary>

- `.env` files are gitignored
- credentials rotated when leaked
- prefer per-service tokens with minimal permissions
- store secrets in env vars or secret managers (when available)

</details>

---

# Learning Matrix
<details>
  <summary><b>Ausbildung prep roadmap (2026)</b></summary>

- **Q1**: Linux fundamentals + subnetting + DNS essentials  
- **Q2**: Windows admin + DHCP/DNS labs + troubleshooting routine  
- **Q3**: Docker/Compose + monitoring basics + backups  
- **Q4**: a “production-like” infra project (docs + runbook + hardening checklist)

Deliverables that matter:
- clean README + diagrams
- scripts safe + idempotent
- “how to operate it” docs

</details>

<details>
  <summary><b>Skill proof strategy (how I demonstrate competence)</b></summary>

For each skill:
- small project + README
- commands used + reasoning
- failure cases + fixes
- short runbook
- minimal demo video/gif (optional)

</details>

<details>
  <summary><b>Day-1 value (Ausbildung-ready contributions)</b></summary>

Things I can reliably help with from day one:
- writing/cleaning documentation (runbooks, checklists, SOPs)
- automating repetitive tasks (scripts, wrappers, small tools)
- basic troubleshooting with a structured method
- log collection, reproduction steps, and concise incident notes
- Git hygiene: issues, PRs, changelogs, clear README

</details>

---

# Cheatsheets
<details>
  <summary><b>Networking essentials</b></summary>

**DNS**
- A/AAAA: host → IPv4/IPv6  
- CNAME: alias → canonical name  
- MX: mail routing  
- TXT: verification / SPF / DKIM / misc notes  

**DHCP**
- leases, reservations, options (router/DNS), scope design

**VLAN**
- segmentation for security + blast radius reduction  
- typical split: mgmt / services / clients / guest

**Troubleshooting quick**
- `ip a`, `ip r`, `ping`, `traceroute`, `dig`, `nslookup`
- `ss -tulpn` (list listeners)

</details>

<details>
  <summary><b>Linux (systemd + logs)</b></summary>

- service status: `systemctl status NAME --no-pager`
- restart: `sudo systemctl restart NAME`
- enable at boot: `sudo systemctl enable NAME`
- logs: `journalctl -u NAME -n 200 --no-pager`
- follow logs: `journalctl -u NAME -f`

</details>

<details>
  <summary><b>Docker essentials</b></summary>

- running containers: `docker ps -a`
- logs: `docker logs --tail 200 -f CONTAINER`
- exec shell: `docker exec -it CONTAINER sh`
- volumes: `docker volume ls`
- compose: `docker compose up -d`, `docker compose logs -f`

</details>

---

# Contact
- Email: **erik.lebedenko.888@gmail.com**
- LinkedIn: https://linkedin.com/in/Eric-Lebedenko
- Website: https://ericlmorgan.com

---

<sub>© Ericlmorgan.com (Erik Lebedenko). All rights reserved.</sub>

<p align="center">
  <img
    src="https://capsule-render.vercel.app/api?type=rect&color=gradient&height=90&section=footer&text=Build%20systems%20that%20survive%20Mondays&fontSize=18&fontAlignY=70"
    alt="footer"
  />
</p>
