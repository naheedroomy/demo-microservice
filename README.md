# Demo Microservice

This is the "Application Repo" for the Autonomous Resilience Demo.

It contains a intentionally fragile deployment (`manifests/deployment.yaml`) that is monitored by the system.
The AI agent will detect issues (like OOMKilled) and automatically open PRs against this repository to fix them.
