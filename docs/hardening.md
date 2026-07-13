````markdown

---
layout: default
title: Security Hardening
nav_order: 3
---

# Security Hardening

The following controls are applied.

| Control | Status |
|----------|--------|
| SSH Root Login | Disabled |
| Firewall | Enabled |
| Auditd | Enabled |
| SELinux | Enforcing |

Example configuration

```bash
PermitRootLogin no
PasswordAuthentication no
```
