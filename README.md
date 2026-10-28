<div align="center">

# Soufian Zaouam

**OpenStack in production — Day-2 operations, stability and governance of mission-critical private cloud platforms.**

*Deployment is where the operational journey begins.*

[![LinkedIn](https://img.shields.io/badge/LinkedIn-soufian--zaouam-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/soufian-zaouam)
[![Book](https://img.shields.io/badge/Book-OpenStack%2C%20the%20Day%20After%20Tomorrow-2ea44f?style=flat-square)](https://github.com/soufian-zaouam/openstack-the-day-after-tomorrow)
[![OzarLand](https://img.shields.io/badge/Community-OzarLand-f59e0b?style=flat-square)](https://github.com/OzarLand)

</div>

---

🛠️ I have worked on OpenStack platforms since 2016 and, for more than five years, on their operation in production:
deployment and administration, incident management, monitoring and log management, upgrades, and the organisation
that has to exist around a platform once a business depends on it. As a consultant, I have carried out these
missions for banks and public administrations in France.

🎯 My interest is less in getting OpenStack to work than in keeping it under control afterwards — visibility,
stability, recoverability, and the decisions that preserve them.

## 🗺️ How my public work fits together

```mermaid
flowchart LR
    B["📘 The book<br/><i>why control erodes,<br/>how to keep it</i>"]
    G["📗 Short Guide<br/><i>the way in</i>"]
    P["🚨 Production Guide<br/><i>checks and cases<br/>during an incident</i>"]
    O["OzarLand<br/><i>operators share runbooks,<br/>patterns and a quick lab</i>"]
    S["🤖 Operator Skills<br/><i>Claude reasons like a<br/>senior operator</i>"]
    B --> G
    B --> P
    B --> O
    O --> S
    classDef book fill:#dcfce7,stroke:#16a34a,color:#14532d
    classDef practice fill:#dbeafe,stroke:#2563eb,color:#1e3a8a
    classDef community fill:#fef3c7,stroke:#d97706,color:#78350f
    class B,G book
    class P practice
    class O,S community
```

## 📚 Public work

| | What it is | Read it for |
| --- | --- | --- |
| 📘 **[OpenStack, the Day After Tomorrow](https://github.com/soufian-zaouam/openstack-the-day-after-tomorrow)** | Free book (PDF, 116 pages, 20 chapters, CC BY-NC-ND 4.0) | The reasoning: why control over a platform erodes, how to assess it, how to keep it while the platform, its workloads and its people change |
| 📗 **[Short Guide](https://github.com/soufian-zaouam/openstack-the-day-after-tomorrow-guide)** | The book's ideas in 18 illustrated pages | A first read, or a shared reference for managers, sponsors and platform leads |
| 🚨 **[OpenStack Production Guide](https://github.com/soufian-zaouam/openstack-production-guide)** | Troubleshooting by symptom, command and error message; the *One Command, One Investigation* series (20 episodes); six anonymised incident RCAs; change and rollback methodology | The practice, during an incident |

The book explains *why*; the Production Guide gives the checks, commands and cases for *when it is already
happening*; the Short Guide is the way in.

## OzarLand

**[OzarLand](https://github.com/OzarLand)** is the open community I started in October 2026: an early-stage,
independent space where OpenStack operators share what they learn running it. Every page names its source and says
how much it was checked.

| | Repository | What it holds |
|:-:|---|---|
| | [ozarland](https://github.com/OzarLand/ozarland) | Start here: newcomer path, community rules, Discussions |
| 🔧 | [openstack-vm-runbooks](https://github.com/OzarLand/openstack-vm-runbooks) | Symptom-driven runbooks for instance problems |
| 🏗️ | [kolla-ansible-deployment-patterns](https://github.com/OzarLand/kolla-ansible-deployment-patterns) | How platforms are deployed with Kolla-Ansible, and what each choice implies |
| 🧪 | [openstack-quick-lab](https://github.com/OzarLand/openstack-quick-lab) | A disposable all-in-one OpenStack on one VM, with exercises |
| 🤖 | [openstack-operator-skills](https://github.com/OzarLand/openstack-operator-skills) | Claude Agent Skills for incidents, changes, maintenance and troubleshooting, with the validation status of every procedure |

## 🧰 Areas of work

**OpenStack in production** — deployment and administration with Kolla-Ansible; Day-2 operations, incident and
problem management, recovery, upgrades and lifecycle

![OpenStack](https://img.shields.io/badge/OpenStack-ED1944?style=flat-square&logo=openstack&logoColor=white)
![Kolla-Ansible](https://img.shields.io/badge/Kolla--Ansible-EE0000?style=flat-square&logo=ansible&logoColor=white)
![Ansible](https://img.shields.io/badge/Ansible-EE0000?style=flat-square&logo=ansible&logoColor=white)

**Observability** — log management and correlation for production platforms

![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)
![Elasticsearch](https://img.shields.io/badge/Elasticsearch-005571?style=flat-square&logo=elasticsearch&logoColor=white)
![Fluentd](https://img.shields.io/badge/Fluentd-0E83C8?style=flat-square&logo=fluentd&logoColor=white)

**Platform foundations**

![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![CentOS](https://img.shields.io/badge/CentOS-262577?style=flat-square&logo=centos&logoColor=white)
![RHEL](https://img.shields.io/badge/RHEL-EE0000?style=flat-square&logo=redhat&logoColor=white)
![QEMU / KVM](https://img.shields.io/badge/QEMU%20%2F%20Libvirt%20%2F%20KVM-FF6600?style=flat-square&logo=qemu&logoColor=white)
![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=flat-square&logo=rabbitmq&logoColor=white)
![MariaDB / Galera](https://img.shields.io/badge/MariaDB%20%2F%20Galera-003545?style=flat-square&logo=mariadb&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Shell](https://img.shields.io/badge/Shell-4EAA25?style=flat-square&logo=gnubash&logoColor=white)

<details>
<summary><b>Earlier work</b></summary>

Cloud Foundry / BOSH on OpenStack, Kubernetes on IBM Cloud, Elasticsearch cluster engineering

![Cloud Foundry](https://img.shields.io/badge/Cloud%20Foundry-0C9ED5?style=flat-square&logo=cloudfoundry&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![IBM Cloud](https://img.shields.io/badge/IBM%20Cloud-1261FE?style=flat-square&logo=ibmcloud&logoColor=white)

</details>

## 🎓 Background

| | |
|:-:|---|
| 🎓 | Master's degree in computer science (data analysis and optimisation), University of Caen Normandy, 2016 |
| 🎓 | Bachelor's degree in computer science (software development), University of Caen Normandy, 2014 |
| 🌍 | Arabic, English, French |

## 📬 Contact

- 💼 Professional enquiries: [LinkedIn](https://www.linkedin.com/in/soufian-zaouam)
- 📝 Questions, corrections and suggestions about the book or the guides: open an issue in the corresponding repository
- OpenStack questions and field reports: [OzarLand Discussions](https://github.com/OzarLand/ozarland/discussions)
