# Architecture

## V0.1 — Basic AI Classification Pipeline

The workflow converts unstructured email content into structured information using an LLM API.

### Flow

```text
Email Input
    ↓
Prepare Email Data
    ↓
HTTP / LLM API
    ↓
Structured Output
    ↓
Validation
```

## Architectural Principle

The LLM is responsible for interpreting the email and producing structured information.

The automation workflow is responsible for validating that output before it is used by downstream logic.

This creates a boundary between probabilistic AI behavior and deterministic workflow logic.

## Current Scope

The current version focuses on:

* LLM API integration
* Structured classification
* Output validation

More advanced reliability and routing mechanisms will be added in future versions.
