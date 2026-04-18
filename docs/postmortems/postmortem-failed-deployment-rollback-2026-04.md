---
title: Failed Deployment and Rollback
parent: Postmortems
nav_order: 2
---

# Postmortem: Failed Deployment and Rollback

## Summary

A deployment introduced instability and required rollback to restore service behavior.

## Impact

The incident caused degraded application behavior during a limited interval.

## Root cause

The change was introduced without sufficient validation coverage for an edge case in the deployment path.

## Follow-up actions

- strengthen pull request validation criteria
- improve deployment checks
- update the relevant runbook
