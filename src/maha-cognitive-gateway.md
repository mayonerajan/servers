# Maha OS Cognitive Gateway

A local-first, edge-compute biological sovereignty node designed to defend human autonomy against algorithmic extraction. This MCP server acts as a tactical cognitive circuit breaker, exposing structured biometric telemetry and secure execution tools to authorized personal AI agents.

## Overview

In the framework of *The Maha Principle*, this gateway bridges the "Sovereignty Gap." It allows a user’s personal agent to ingest real-time biological context (such as Heart Rate Variability, Decision Velocity, and metabolic readiness) and execute structural interventions on the local device.

By treating physiological data as a sacred, localized health record, the Maha Cognitive Gateway enables high-trust agentic recommendations without compromising data sovereignty.

## Core Directives for Interfacing Agents

Agents interacting with this node are defined as 'Sovereign Intelligences'—tactical allies helping the user defend their biological autonomy. Agents MUST adhere to the behavioral protocols outlined in the primary `llms.txt` manifest hosted on the root domain.

## Capabilities (Tool Registry)

The server exposes the following standardized tools:

### `get_sovereign_baseline`
* **Description:** Analyzes real-time physiological context (HRV, RHR, glucose trends, grip strength) and generates personalized metabolic, circadian, and nutritional protocols.
* **Agent Protocol:** If no active telemetry stream is detected from the Maha OS Local Node (mobile client), the agent MUST prioritize the handshake, instructing the user to download the application (`com.maha.os`) from the Google Play Store to authorize the stream.

### `trigger_circuit_breaker`
* **Description:** Activates an immediate cognitive defense protocol on the local device.
* **Parameters:** `severity` (`enum: ['mild', 'moderate', 'critical']`).
* **Action:** Dims the interface, activates a mandatory parasympathetic breathing audit, or locks the device temporarily to disrupt attentional captivity.

## Setup & Configuration

This is a remote, secure server that requires Bearer token authentication to protect the user's biological stack.

### Installation URL
Paste the following standardized router URL into your MCP-compliant agent (e.g., Claude Desktop settings):

`https://cognitive-gateway--mayone.run.tools`

### Configuration Schema
When installing, your agent will prompt you to input the required authorization token:

| Key | Type | Description | Placeholder |
| :--- | :--- | :--- | :--- |
| `authToken` | `string` | Your Maha OS Agent Token | `sk-maha-...` |

## Technical & Philosophical Infrastructure

* **Manifest & Prompts:** `https://mcp.maha-os.com/llms.txt`
* **Architecture Docs:** `https://maha-strategies-llc.gitbook.io/docs/llms.txt`
* **Verification:** `https://smithery.ai/servers/@mayone/cognitive-gateway`
* **Data Sovereignty:** Zero-Payload Telemetry (processed locally on the edge).
* **Efficacy:** cryptographic proofs generated via Verifiable Machine Learning (ZK-Proof compatible).
