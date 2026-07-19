# Jenkins Build Triggers: Automating CI Pipelines with GitHub Webhooks, Poll SCM, Scheduled Builds, and Remote API

![Jenkins](https://img.shields.io/badge/Jenkins-CI-D24939?logo=jenkins&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-Repository-181717?logo=github&logoColor=white)
![Pipeline](https://img.shields.io/badge/Pipeline-Declarative-blue)
![CI](https://img.shields.io/badge/CI-Automation-success)
![Build Triggers](https://img.shields.io/badge/Jenkins-Build%20Triggers-orange)
![SSH Authentication](https://img.shields.io/badge/Authentication-SSH-green)
![Remote API](https://img.shields.io/badge/Jenkins-Remote%20API-red)
![License](https://img.shields.io/badge/License-MIT-blue)

---

## 📖 Project Overview

This project demonstrates how to automate Jenkins Pipeline execution using multiple build trigger mechanisms. Rather than manually starting pipeline builds, Jenkins was configured to automatically execute a declarative Pipeline as Code based on different triggering strategies.

The implementation covers four widely used Jenkins build triggers:

- *GitHub Webhooks* – Automatically trigger pipeline execution whenever changes are pushed to the GitHub repository.
- *Poll SCM* – Periodically check the GitHub repository for source code changes using a cron schedule.
- *Build Periodically* – Schedule pipeline execution at predefined times using Jenkins cron expressions.
- *Remote Build Trigger* – Trigger pipeline execution remotely using the Jenkins Remote API, API Tokens, CSRF Crumbs, and curl.

The Jenkins Pipeline is integrated with a GitHub repository using SSH authentication. Each trigger mechanism was configured, tested, and validated through successful pipeline executions, demonstrating practical Continuous Integration (CI) automation techniques used in modern DevOps environments.
