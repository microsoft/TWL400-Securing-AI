---
title: 'Exercise 06: Prepare the CISO Briefing'
layout: default
nav_order: 7
---

# Exercise 06: Prepare the CISO Briefing

## Introduction

You'll organize your findings into a risk table and draft a short executive summary of the top risks and recommended priorities.

## Description

This exercise translates the technical investigation into a business-ready briefing that communicates risk and priority to leadership.

## Success criteria

- You produced a risk table covering ownership, permissions, sensitive data exposure, lifecycle/usage, and SOC visibility.
- You assigned a recommended priority to each risk.
- You wrote a short briefing summary connecting the evidence to a business recommendation for leadership.

### Reference: risk summary

| Risk | Evidence | Business impact | Recommended priority |
|---|---|---|---|
| Ownership and accountability gap | Agent365 shows Zava-Unknown Operations Agent owner/creator = former.employee. Entra shows former.employee is blocked. | An available agent without an active accountable owner creates lifecycle, approval, and incident response risk. | High |
| Excessive permissions / least privilege | Associated app registrations show broad permissions such as Sites.Read.All, Files.Read.All, User.Read.All, Group.Read.All, and Mail.Read. | Broad permissions increase blast radius if an associated identity or application is misused. | High |
| Sensitive data exposure | Customer Records is Confidential and readable by A365 Lab Student Readers. Low-privileged reader can access Customer Records but is denied on Finance and Legal. | Customer escalation and risk data may be exposed to a broader audience than intended. | High |
| Lifecycle and usage review | Agent365 shows usage for all six agents. Procurement and Unknown Operations show lower sessions than the other Zava agents. | Lower-usage available agents should have documented business purpose, owner, and review cadence. | Medium |
| SOC visibility and correlation | Defender XDR incident links users and cloud applications, including one disabled user indicator. | The SOC has a starting point, but analysts must correlate evidence across tools. | Medium |

## Steps

1. Review the evidence you gathered on ownership, permissions, sensitive data exposure, usage/lifecycle, and SOC visibility.
2. Organize your findings into a risk table with columns for **Risk**, **Evidence**, **Business impact**, and **Recommended priority**. Use the reference table above as a guide.
3. Draft 2-3 short paragraphs summarizing the priority risks and your recommended next steps for leadership.
