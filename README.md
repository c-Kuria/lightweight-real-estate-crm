# Real Estate Sales Automation & Lightweight CRM

## Overview
This repository contains a **lightweight sales tracking and automation system** designed to support day-to-day sales operations for a single real estate development.

The system focuses on **organizing sales data**, **automating repetitive follow-ups**, and **maintaining basic visibility** across sub-agents, clients, and site visits. It is intentionally simple and built using readily available tools rather than a full enterprise CRM.

The project serves both as:
- A practical solution to a real operational problem, and
- A learning exercise in system design, automation, and data modeling.

---

## Problem Context
In small real estate sales setups, especially where:
- One internal sales agent manages multiple external sub-agents
- Sales activity is tracked manually across messages, calls, and spreadsheets
- Follow-ups depend heavily on memory

it becomes difficult to:
- Keep track of who has been contacted and when
- Ensure contracts are sent and acknowledged
- Follow up consistently with agents and clients
- Maintain a clear picture of ongoing site visits and leads

This often results in missed follow-ups, duplicated effort, and poor visibility into sales activity.

---

## Purpose of This System
The goal of this project is to provide a **minimal structure** that helps:

- Keep all sales-related information in one place
- Reduce repetitive manual work
- Introduce consistency into follow-ups
- Make sales activity easier to track and review over time

It is not intended to replace a full CRM, nor to support multiple users or teams.

---

## What the System Covers

### Sub-Agent Tracking
- Stores basic sub-agent information
- Tracks contract status and basic activity
- Helps identify which agents are active or inactive

### Contract Distribution
- Sends signed contracts via email
- Records when contracts are sent
- Triggers simple follow-up reminders

### Client Tracking
- Records client details and interest level
- Links clients to the responsible sub-agent
- Tracks progress from initial contact to site visit

### Follow-Up Reminders
- Identifies overdue follow-ups
- Generates simple task lists for calls or messages
- Reduces reliance on memory or ad-hoc notes

### Site Visit Tracking
- Records scheduled site visits
- Tracks visit outcomes
- Prompts post-visit follow-ups

---

## Design Approach
- Keep the system small and understandable
- Prefer simple automation over complex workflows
- Use tools that are easy to modify and maintain
- Store data in a structured, auditable format
- Avoid unnecessary abstractions

---

## Scope and Limitations
- Designed for a single sales operator
- Uses spreadsheets as the primary data store
- Automations are batch-based, not real-time
- Messaging is limited to email (with WhatsApp handled manually)

These limitations are intentional and aligned with the project’s goals.

---

## Why This Project Exists
This project exists to:
- Improve day-to-day sales organization
- Reduce avoidable administrative effort
- Practice building a small, maintainable automation system
- Serve as a reference for future improvements or similar use cases

---

## Data Privacy
All sensitive company and client data has been removed.  
This repository contains only structure, logic, and example data.

---

## License
This project is provided for personal, educational and reference use.
