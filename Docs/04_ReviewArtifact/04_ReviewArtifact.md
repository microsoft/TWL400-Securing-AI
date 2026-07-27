---
title: 'Exercise 04: Review the Defender XDR Investigation Artifact'
layout: default
nav_order: 5
---

# Exercise 04: Review the Defender XDR Investigation Artifact

## Introduction

You'll open the live Defender XDR incident, review its severity and involved assets, and inspect the related alert.

## Description

This exercise establishes the SOC's investigation starting point and identifies the users and applications connected to the Zava agent incident.

## Success criteria

- You confirmed the A365-LAB incident is Active with severity Medium.
- You identified two user entities, one of which is disabled.
- You identified three cloud application entities linked to the incident.
- You recognized this incident as a starting point that needs correlation with Agent365, Entra, SharePoint, and Purview findings.

## Steps

1. From the browser tab bar, select the **New tab** icon to open the Microsoft Defender.

1. From the left side bar, select **Show navigation**.

1. Select **Investigation & response**, then **Incidents & alerts**, and then **Incidents**.

1. From the incidents search bar, look for ++A365-LAB++.

1. From the result, open the **A365-LAB - Suspicious Zava Agent Access Pattern...** incident.

1. Review the incident's severity (Medium), status (Active), classification (Unclassified), active alerts (1/1), and assets (5).

1. Review the incident graph: two users (one of two disabled) and three cloud applications.

1. You can select the **Group similar nodes** toggle button to view details.

1. Select the **Alerts** tab and review its category (Suspicious activity), detection source (Manual), and impacted entities.