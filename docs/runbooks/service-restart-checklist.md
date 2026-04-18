# Runbook: Service Restart Checklist

## Purpose

Provide a controlled checklist for restarting a service while reducing operational risk.

## Preconditions

- the affected service has been identified
- restart is permitted by the operational policy
- rollback path is understood
- relevant stakeholders are informed if required

## Steps

1. Confirm the reason for the restart.
2. Check whether there is customer-facing impact.
3. Review recent deployments or changes.
4. Capture the current health status.
5. Execute the restart using the approved procedure.
6. Monitor the service during stabilization.

## Validation

After the restart:

- confirm the service is healthy
- validate latency and error indicators
- verify dependent services are unaffected
- document the outcome

## Escalation

Escalate if the restart fails, if the service does not recover, or if impact expands to additional components.
