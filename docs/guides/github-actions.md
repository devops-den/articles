---
title: GitHub Actions 101
layout: default
---

# GitHub Actions 101

Learn how to build a simple CI/CD pipeline using GitHub Actions.

## 🛠️ Key Concepts

- YAML workflows
- Runners
- Actions & Secrets

## 🚀 Example Workflow

```yaml
name: Build and Test
on: [push]
jobs:
  build:
    runs-on: ubuntu-latest
    steps:
    - uses: actions/checkout@v3
    - run: echo "Hello DevOps Den"
