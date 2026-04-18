# Contributing Guide

## Purpose

This repository is used as a structured knowledge base demo for SRE practices.

## Content types

Contributions should fall into one of these categories:

- Runbooks
- Postmortems
- Standards
- Architecture notes
- Automation

## General rules

- Use clear and descriptive titles
- Keep content concise and operational
- Prefer step-by-step instructions for runbooks
- Document lessons learned in postmortems
- Follow the documentation standard in `docs/standards/documentation-standard.md`
- Open a pull request for every change

## Branch naming

Use one of the following patterns:

- `docs/runbook-<topic>`
- `docs/postmortem-<topic>`
- `docs/standard-<topic>`
- `automation/<topic>`

## Pull request expectations

Every pull request should:

- explain what was added or updated
- link the related issue when applicable
- follow the repository structure
- pass markdown and structure validation

## Sensitive information

Do not include:
- internal production details
- credentials
- customer data
- private infrastructure references
