# Uday Kandyanam

Senior Software Engineer working on platform engineering and applied AI. Based in Newark, Delaware.

I operate Kubernetes platforms on AWS and Azure and build the tooling around them: CI/CD for hundreds of microservices, internal platform APIs, and LLM agents that help platform teams triage incidents and find answers in their own documentation.

## Current work

At UnitedHealth Group I work on the platform team. Recent work includes Go and Python automation for Kubernetes operations (manual operations down 70%), an LLM-based agent that diagnoses platform issues inside Microsoft Teams, a knowledge assistant that answers platform questions from internal documentation and runbooks, and an event-driven pipeline that keeps the internal developer dashboard current. The fuller write-up, with the engineering decisions behind three of those systems, is on my portfolio: [udaykandyanam.com](https://udaykandyanam.com).

## Projects here

[KubePulse](https://github.com/UdayKandyanam/kubepulse): a Go CLI that reads a Kubernetes cluster snapshot and reports what is wrong, the evidence for it, and the next step to take. Diagnose only, nothing in it changes a cluster.

[Runbook Assistant](https://github.com/UdayKandyanam/runbook-assistant): a Python tool that answers platform questions from a folder of runbooks and cites the file and section behind each answer. When the runbooks do not cover a question, it says so instead of guessing.

[Developer Intelligence](https://github.com/UdayKandyanam/developer-intelligence): an event-driven pipeline that ingests GitHub webhook events, normalizes them into a store, and serves a services and activity API.

[Platform API](https://github.com/UdayKandyanam/platform-api): a Go self-service platform API with API key auth, team-scoped namespaces, audit logging, and dry run mode on every write.

[Incident Investigator](https://github.com/UdayKandyanam/incident-investigator): a read-only Python investigator for Kubernetes incidents. It scores the likely root cause, cites runbook sections, marks every proposed action as needing human approval, and is scored against an evaluation set of synthetic incidents.

[Portfolio site](https://github.com/UdayKandyanam/udaykandyanam.github.io): the source for udaykandyanam.com, a single page site built with plain HTML and CSS.

## Stack I use day to day

Platform: Kubernetes, Docker, Helm, Argo CD, Istio
Cloud: AWS (EKS, ECS, Lambda, RDS), Azure (AKS, Key Vault, Azure Monitor)
Automation: Go, Python, Terraform, Ansible, GitHub Actions, Jenkins, Azure DevOps
Reliability: Grafana, Dynatrace, Splunk, Prometheus, OpenTelemetry, SLOs and error budgets
AI tooling: LLM agents, LangChain, LangGraph, retrieval-augmented generation, MCP

## Contact

Portfolio: [udaykandyanam.com](https://udaykandyanam.com)
LinkedIn: [linkedin.com/in/udaykandyanam](https://www.linkedin.com/in/udaykandyanam/)
Email: kandyanam.uday@gmail.com

For roles, a short note about the team and the stack is plenty to start.
