---
title: High CPU Incident Response
parent: Runbooks
nav_order: 1
---

# Runbook: High CPU Incident Response

## Purpose

Provide a structured response procedure for incidents involving sustained high CPU usage in a service or component.

## When to use this runbook

Use this runbook when:

- CPU usage remains high for an extended period
- application performance is degraded
- latency or error rate increases and CPU is suspected
- alerts indicate abnormal resource consumption

## Initial checks

1. Confirm the affected service or component.
2. Validate whether the issue is isolated or widespread.
3. Check recent changes:
   - deployments
   - configuration changes
   - scheduled jobs
4. Review logs, metrics, and traces if available.
5. Confirm whether the issue is customer-facing.

## Containment actions

1. Reduce incoming load if possible.
2. Restart the affected process only if restart is low-risk and approved by policy.
3. Roll back recent changes if evidence points to a recent deployment.
4. Scale resources temporarily if operationally justified.

## Validation steps

After containment:

1. Verify CPU has returned to acceptable levels.
2. Confirm service latency and error rates have stabilized.
3. Check for recurrence within the next observation window.
4. Document what action was taken.

## Escalation criteria

Escalate when:

- CPU remains high after containment steps
- there is impact across multiple services
- customer impact is significant
- root cause is not identifiable within a reasonable time
