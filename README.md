# Sample CI App

[![CI Pipeline](https://github.com/Alibras257/sample-ci-app/actions/workflows/ci.yml/badge.svg)](https://github.com/Alibras257/sample-ci-app/actions/workflows/ci.yml)

## Overview

A production-ready GitHub Actions CI/CD demonstration project.

## Features

- GitHub Actions CI
- Matrix Builds
- Docker Build & Push
- Docker Hub Integration
- Artifact Upload
- Dependency Caching
- Scheduled Workflows
- Manual Workflow Dispatch
- Reusable Workflows
- Dependabot
- Security Best Practices

## Workflow

The pipeline automatically runs on:

- Push to `main`
- Pull Requests
- Manual dispatch
- Weekly scheduled execution

## Docker Image

Images are published automatically to Docker Hub after successful builds on the `main` branch.

## Project Structure

```text
.
├── .github
│   ├── workflows
│   └── dependabot.yml
├── logs
├── Dockerfile
├── SECURITY.md
├── WORKFLOW_GUIDE.md
└── README.md
```

## Author

Ibraheem Aloyinlapa