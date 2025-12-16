---
title: Introduction
layout: home
nav_order: 1
---

# TechWorkshop L200: Agents at work

## Course Objective:
Enable solution owners, AI COE members, and makers to design, configure, and operate Microsoft Copilot–based agents that connect to real enterprise systems (Azure DevOps, SAP, and HR data) using both prebuilt connectors and Model Context Protocol (MCP)–based integrations, and to publish those agents into Microsoft 365 for secure, repeatable use.


## Learning objectives

At the end of this workshop, you will be able to:

- Explain how Microsoft 365 Copilot, Agent Builder, Copilot Studio, connectors, and MCP work together in an agentic architecture.
- Identify when to use Agent Builder vs Copilot Studio for a given business scenario.
- Differentiate between prebuilt Copilot Studio connectors and MCP-based integrations, and know when each approach is appropriate.
- Configure connectors and MCP tools to bring in data from Azure DevOps, SAP, and a custom HR system.
- Design agent instructions, prompts, and capabilities so agents stay grounded in enterprise data instead of general knowledge.
- Publish and share Copilot Studio agents to Teams and Microsoft 365, using appropriate availability options and connection approval patterns.

## Customer scenario

Zava Retail Group is a retailer with both physical stores and a growing e-commerce business. To support its growth, Zava has launched an AI Center of Excellence (COE) focused on using agents and copilots to streamline work across departments.

Three immediate needs have emerged:
 
 - The Executive Office wants real-time visibility into project health without digging through Azure DevOps boards or asking project leads for manual updates.
 - The Operations team needs proactive inventory monitoring tied to SAP, so low-stock items are detected early and store managers are alerted in time to restock.
 - The HR team wants a simple, conversational way to search, add, and update candidate records, reducing manual data entry and speeding up hiring workflows.

To address these needs, Zava is piloting a set of copilots and agents built with Agent Builder and Copilot Studio, integrated with Azure DevOps, SAP (via MCP and API Management), Outlook, and a custom HR backend exposed through MCP.

In this lab, you play the role of a member of Zava’s AI COE. You will:
 - Build an executive project-status agent grounded in Azure DevOps work items.
 - Build an inventory management agent that uses MCP to access SAP inventory and sends targeted email alerts to store managers.
 - Build an HR candidate-management agent that uses MCP tools to manage a candidate list and is published into Microsoft 365 for access via Teams and Copilot.

Together, these exercises show how to use Microsoft Copilot, Copilot Studio, and MCP to deliver practical, end-to-end agentic solutions on top of real enterprise data.