# Automated Sales & Operations System

This repository contains the documentation and system design for a scalable automation platform focused on sales, operations, and data-driven decision making.

## Objective
To build a system that automates:
- customer acquisition
- lead management
- quotation processes
- sales conversion
- operational workflows
- data analysis and KPIs

## Core Architecture (v3.0)
- **Respond.io** — central conversation platform (Meta BSP, unified inbox, contact CRM, messaging workflows, human agent escalation)
- **Claude API** — AI engine for quotations, lead qualification, and personalized responses
- **Claude Code + MCP** — intelligent builder that configures respond.io and n8n flows via natural language
- **n8n** — complementary tool for external system integrations (CRM, billing, inventory) when needed
- **Google Sheets** — initial CRM for orders, commissions, and KPIs

## Project Structure

- tools/ → tools and platforms used in the system
- project/ → planning, phases, and timeline
- flows/ → system workflows and automation logic
- clientes/negocios_cuanticos/ → client-specific documentation
- arquitectura/ → stack and architecture decisions

## Current Status
Phase: Analysis and system structuring (v3.0 — April 2026)

## What changed in v3.0
- Respond.io replaces Pancake.lat + WATI as the central conversation platform
- n8n moves from central engine to complementary integration tool
- Simplified architecture: one platform for conversations instead of three tools

## Next Steps
- configure respond.io for pilot business
- set up Claude API integration
- implement initial automation workflows
- define pilot business from Negocios Cuanticos portfolio
