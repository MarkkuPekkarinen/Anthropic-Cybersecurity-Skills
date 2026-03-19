---
name: detecting-oauth-token-theft
description: >
  Detect OAuth access token theft and misuse by analyzing sign-in logs for
  impossible travel, new device patterns, token replay from unusual IPs,
  and anomalous scope requests via Microsoft Graph and Okta APIs.
domain: cybersecurity
subdomain: identity-security
tags: [oauth, token-theft, identity-attacks, impossible-travel]
version: "1.0"
author: mahipal
license: Apache-2.0
---

# Detecting OAuth Token Theft

Analyze OAuth sign-in telemetry for indicators of token theft including
impossible travel, device fingerprint changes, and token replay attacks.


## When to Use

- When investigating security incidents that require detecting oauth token theft
- When building detection rules or threat hunting queries for this domain
- When SOC analysts need structured procedures for this analysis type
- When validating security monitoring coverage for related attack techniques

## Prerequisites

- Familiarity with identity security concepts and tools
- Access to a test or lab environment for safe execution
- Python 3.8+ with required dependencies installed
- Appropriate authorization for any testing activities
