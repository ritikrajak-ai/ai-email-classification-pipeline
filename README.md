# AI Email Classification Pipeline

An AI-powered email classification pipeline that uses an LLM API to convert unstructured customer emails into structured information for downstream automation.

## Project Status

**V0.1 — Basic AI Classification Pipeline**

🚧 Work in Progress

## Current Workflow

```text
Incoming Email
      ↓
Email Data Preparation
      ↓
HTTP / LLM API
      ↓
Structured AI Output
      ↓
Output Validation
```

## Current Capabilities

* Accept email content as input
* Send email data to an LLM through an API
* Classify the email using a defined schema
* Generate structured JSON output
* Validate the returned AI output

## Current Classification Fields

The classifier currently works with fields such as:

* `intent`
* `confidence`
* `order_id`
* `action_note`

## Technology

* n8n
* HTTP APIs
* LLM API
* Structured JSON
* Output validation

## Development Roadmap

### V0.1 — Basic AI Classification

* [x] LLM API integration
* [x] Structured output
* [x] Basic validation

### V0.2 — Reliable Classification

* [ ] Confidence-based handling
* [ ] Invalid-output handling
* [ ] Human review path

## Project Status

This project is actively being developed. The current version focuses on building the core AI classification pipeline before adding reliability and production-oriented capabilities.
