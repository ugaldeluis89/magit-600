---
title: API Latency Spike
parent: Postmortems
nav_order: 1
---

# Postmortem: API Latency Spike

## Summary

An API latency spike affected request performance during a peak traffic period.

## Impact

Users experienced slower response times for a limited period.

## Root cause

The main contributing factor was elevated database pressure combined with insufficient early detection of degradation.

## Resolution

The team applied short-term mitigation and stabilized the service.
