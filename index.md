---
title: 'Introduction'
layout: home
nav_order: 1
---

# Securing AI with Agent365

## Introduction

In this lab, you investigate Zava's Agent365 estate using live Microsoft 365 security and governance surfaces. You will correlate agent inventory, usage, ownership, identity permissions, sensitive data access, and Microsoft Defender XDR incident evidence to build a governance picture of Zava's AI agents.

Primary surfaces used: Agent365 / Microsoft 365 admin center, Microsoft Defender XDR, Microsoft Entra, SharePoint Online, and Microsoft Purview.

## Objectives
 
By the end of this lab, you will be able to:
 
- Inventory an organization's AI agent estate in Agent365 and interpret status, risk, and usage metrics.
- Investigate agent ownership and identity to identify accountability gaps, such as agents owned by disabled accounts.
- Review Microsoft Graph permissions on agent app registrations and assess whether access scope matches business purpose.
- Evaluate SharePoint sensitivity labels and site permissions to identify overexposed data repositories.
- Validate data exposure findings using a low-privileged account rather than relying on admin-level visibility alone.
- Correlate a Defender XDR incident with agent, identity, and data findings to build a unified investigation.
- Assess whether agent governance and lifecycle controls are operating effectively across ownership, permissions, usage, and monitoring.
- Translate technical findings into a prioritized, executive-ready risk briefing.


## Before you begin: your investigation worksheet

This lab produces four artifacts that build toward the module's **Proof Through Scenario** - the executive-ready deliverable you hand off at the end. To help you capture these as you go, download the **[Learner Investigation Notes](media/Zava_Agent365_Learner_Findings_Template.docx)** worksheet now.

Each exercise below has a matching section in the worksheet. Fill it in as you complete each step - your notes from Exercises 01-03 are the raw material for the Proof Through Scenario you assemble in Exercise 04.

### Duration

**Estimated Time:** 25 minutes

---

## Disclaimer

This presentation, demonstration, and demonstration model are for informational purposes only and (1) are not subject to SOC 1 and SOC 2 compliance audits, and (2) are not designed, intended, or made available as a medical device(s) or as a substitute for professional medical advice, diagnosis, treatment, or judgment. Microsoft makes no warranties, express or implied, in this presentation, demonstration, and demonstration model. Nothing in this presentation, demonstration, or demonstration model modifies any of the terms and conditions of Microsoft’s written and signed agreements. This is not an offer, and applicable terms and the information provided are subject to revision and may be changed at any time by Microsoft.

This presentation, demonstration, and demonstration model do not give you or your organization any license to any patents, trademarks, copyrights, or other intellectual property covering the subject matter in this presentation, demonstration, and demonstration model.

The information contained in this presentation, demonstration, and demonstration model represents the current view of Microsoft on the issues discussed as of the date of presentation and/or demonstration, for the duration of your access to the demonstration model. Because Microsoft must respond to changing market conditions, it should not be interpreted to be a commitment on the part of Microsoft, and Microsoft cannot guarantee the accuracy of any information presented after the date of presentation and/or demonstration and for the duration of your access to the demonstration model.

No Microsoft technology, nor any of its component technologies, including the demonstration model, is intended or made available as a substitute for the professional advice, opinion, or judgment of (1) a certified financial services professional, or (2) a certified medical professional. Partners or customers are responsible for ensuring the regulatory compliance of any solution they build using Microsoft technologies.

## Copyright

© 2026 Microsoft Corporation. All rights reserved. 

By using this demo/lab, you agree to the following terms:

The technology/functionality described in this demo/lab is provided by Microsoft Corporation for purposes of obtaining your feedback and to provide you with a learning experience. You may only use the demo/lab to evaluate such technology features and functionality and provide feedback to Microsoft. You may not use it for any other purpose. You may not modify, copy, distribute, transmit, display, perform, reproduce, publish, license, create derivative works from, transfer, or sell this demo/lab or any portion thereof.

COPYING OR REPRODUCTION OF THE DEMO/LAB (OR ANY PORTION OF IT) TO ANY OTHER SERVER OR LOCATION FOR FURTHER REPRODUCTION OR REDISTRIBUTION IS EXPRESSLY PROHIBITED.

THIS DEMO/LAB PROVIDES CERTAIN SOFTWARE TECHNOLOGY/PRODUCT FEATURES AND FUNCTIONALITY, INCLUDING POTENTIAL NEW FEATURES AND CONCEPTS, IN A SIMULATED ENVIRONMENT WITHOUT COMPLEX SET-UP OR INSTALLATION FOR THE PURPOSE DESCRIBED ABOVE. THE TECHNOLOGY/CONCEPTS REPRESENTED IN THIS DEMO/LAB MAY NOT REPRESENT FULL FEATURE FUNCTIONALITY AND MAY NOT WORK THE WAY A FINAL VERSION MAY WORK. WE ALSO MAY NOT RELEASE A FINAL VERSION OF SUCH FEATURES OR CONCEPTS. YOUR EXPERIENCE WITH USING SUCH FEATURES AND FUNCITONALITY IN A PHYSICAL ENVIRONMENT MAY ALSO BE DIFFERENT.

