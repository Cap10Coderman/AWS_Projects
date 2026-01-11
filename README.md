# IAM Sentinel
## Automated IAM Policy Drift Detection & Remediation

### 📌 Overview

This project implements a real-time IAM security control that detects unauthorized IAM policy attachments and automatically remediates excessive privileges.

It addresses a common cloud security risk:

IAM privilege escalation caused by accidental or malicious policy attachment.

The solution uses event-driven security automation to enforce least privilege in AWS environments.

### 🎯 Problem Statement

In many AWS accounts:

IAM users or roles are granted additional policies without approval

High-risk policies like AdministratorAccess go unnoticed

Manual audits are slow and reactive

❌ Leads to privilege creep
❌ Increases blast radius
❌ Violates least-privilege principles

### ✅ Solution Summary

This project:

1. Detects IAM policy changes in real time

2. Notifies the security team instantly

3. Remediates unauthorized policy attachments automatically