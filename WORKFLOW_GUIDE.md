# GitHub Actions Workflow Guide

## Overview

This repository uses GitHub Actions to automate:

- Build
- Testing
- Docker image creation
- Docker Hub publishing

## Workflow Triggers

- Push to main
- Pull Requests
- Manual workflow_dispatch
- Weekly scheduled cron

## Maintenance

- Review workflow runs regularly.
- Keep GitHub Actions up to date.
- Review Dependabot pull requests.
- Remove stale artifacts.
- Monitor Docker image builds.

## Security

- Secrets are managed through GitHub Secrets.
- Workflow permissions follow least privilege.
- Docker authentication uses repository secrets.