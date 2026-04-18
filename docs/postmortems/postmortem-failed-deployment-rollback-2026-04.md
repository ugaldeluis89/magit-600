# Postmortem: Failed Deployment and Rollback

## Summary

A deployment introduced instability and required rollback to restore service behavior.

## Impact

The incident caused degraded application behavior during a limited interval.

## Root cause

The change was introduced without sufficient validation coverage for an edge case in the deployment path.

## Resolution

The team rolled back to the previous stable version and monitored service recovery.

## Follow-up actions

- strengthen pull request validation criteria
- improve deployment checks
- update the relevant runbook
- document rollback expectations more clearly
