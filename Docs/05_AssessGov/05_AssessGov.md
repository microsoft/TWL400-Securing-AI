---
title: 'Exercise 05: Assess Governance and Lifecycle Controls'
layout: default
nav_order: 6
---

# Exercise 05: Assess Governance and Lifecycle Controls

## Introduction

You'll revisit the Agent365 registry and Defender XDR incident to combine usage, ownership, permission, and SOC findings into a single governance view.

## Description

This exercise evaluates whether Zava's agent ownership, lifecycle, permissions, and monitoring controls are operating effectively by correlating evidence gathered in the earlier exercises.

## Success criteria

- You confirmed Unknown Operations has invalid ownership.
- You identified Procurement and Unknown Operations as having lower session counts, warranting lifecycle review.
- You confirmed Contract Review, CRM Update, and Executive Research have broad associated permission evidence.
- You confirmed Customer Records is overexposed.
- You connected the Defender XDR incident as a live SOC investigation starting point.

## Steps

1. From the browser tab bar, select the first tab - **Agents - Microsoft 365 admin center**.
1. Review the live **Active users** and **Total sessions** values for all six Zava agents.
1. Confirm all six agents have visible usage telemetry and at least one active user.
1. Note that Procurement and Unknown Operations show lower sessions than the other four agents.
1. Combine the usage data with the ownership and permission findings from Exercise 2.
1. Return to Defender XDR and review the A365-LAB incident as the SOC correlation point.