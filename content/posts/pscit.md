---
weight: 1
title: "PSciT Library"
hlink: https://pscit.hungcq.xyz
cover:
  image: /images/pscit.png
github: https://github.com/hungcq/pscit
technologies: Golang, React.js, PostgreSQL, K8S, CI/CD (GitHub Actions), AWS, EFK, Prometheus, Grafana
summary: >
  PSciT is a physical library and web app I built to share curated books on philosophy, science, and technology,
  featuring a production-grade stack, all developed and deployed in just one week.
---

**PSciT** (Philosophy, Science, and Technology) is a physical library I founded and maintain in Hanoi, Vietnam.
As a lifelong skeptic and curious reader,
I built this collection to preserve and share books that have deeply influenced my thinking—primarily in philosophy,
science, and technology, along with select titles in history, sociology, fiction, and practical domains.
All books are handpicked and mostly read, with titles in both English and Vietnamese.

The accompanying website is a full-featured library management system that allows users to browse books,
explore authors and categories, request or approve reservations, and receive email notifications.
I built the core functionalities in just one week using **Cursor** for accelerated development.

Despite running on a cost-effective single-node Vultr instance,
the system is production-grade with **automated CI/CD**, **security**, **observability**, and **configurability** in mind.
It features:
- Backend: **Golang, PostgreSQL, Docker, Kubernetes, GitHub Actions, HAProxy**
- Observability: **Prometheus, Grafana, ElasticSearch, Kibana**
- Frontend: **React.js**, hosted on **AWS S3**, served via **AWS CloudFront**
- Domain Management: **AWS Route 53** and **AWS Certificate Manager**

This project combines my interests in software engineering, infrastructure, and knowledge-sharing.