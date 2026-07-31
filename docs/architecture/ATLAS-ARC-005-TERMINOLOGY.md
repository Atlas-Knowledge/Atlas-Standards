---
id: ATLAS-ARC-005
title: Terminology
version: 1.0.0
status: Draft
category: Architecture
owner: Atlas Architecture Group
created: 2026-07-31
last_updated: 2026-07-31
reviewers: []
depends_on:
  - ATLAS-ARC-001
  - ATLAS-ARC-002
  - ATLAS-ARC-003
referenced_by: []
tags:
  - architecture
  - terminology
  - glossary
---

# Terminology

## Purpose

This document defines the official terminology used throughout the Atlas ecosystem.

Every specification, standard, policy, implementation, and discussion MUST use these terms consistently.

---

# Core Principles

- One concept MUST have one official term.
- One term MUST have one official definition.
- Avoid synonyms in specifications.
- Definitions take precedence over informal interpretations.

---

# Core Terms

## Atlas

The complete platform consisting of specifications, repositories, runtime components, tools, and services.

---

## Specification

A normative document that defines required behavior, structure, interfaces, or constraints.

Specifications define **what must be implemented**, not how.

---

## Standard

A document defining conventions or best practices shared across Atlas repositories.

Standards promote consistency but may not always be normative.

---

## Policy

A governance document defining mandatory project rules.

Policies specify what contributors and repositories are required to follow.

---

## Architecture

The high-level design and organization of Atlas.

Architecture describes components, relationships, responsibilities, and boundaries.

---

## Repository

An independently versioned source code or documentation project.

Repositories communicate through well-defined contracts.

---

## Component

A modular implementation unit with a clearly defined responsibility.

Examples:

- Kernel
- Runtime
- Registry
- Storage

---

## Module

A logical subdivision within a component.

Modules are not independently versioned repositories.

---

## Contract

A formal agreement defining how two components interact.

Contracts include:

- APIs
- Schemas
- Events
- Interfaces

---

## Entity

A uniquely identifiable object defined by Atlas specifications.

Entities possess:

- Identity
- Metadata
- Lifecycle
- Relationships

---

## Relationship

A formal connection between two or more entities.

---

## Event

A record describing something that has occurred within the system.

Events are immutable.

---

## Metadata

Structured descriptive information associated with an entity or document.

---

## Schema

A formal definition describing structure, constraints, and validation rules.

---

## Registry

A service responsible for discovering, registering, or resolving Atlas resources.

---

## Runtime

The execution environment responsible for operating Atlas components.

---

## Node

An independently operating participant within the Atlas ecosystem.

---

## Federation

The architectural model allowing autonomous nodes to cooperate without centralized ownership.

---

## Compatibility

The ability of different versions or components to work together according to documented contracts.

---

# Reserved Terms

The following identifiers are reserved by Atlas:

- Atlas
- Kernel
- Runtime
- Registry
- Federation
- Specification
- Standard
- Policy
- ADR
- RFC

Future documents may extend this list.

---

# References

- ATLAS-ARC-001 Architecture Constitution
- ATLAS-ARC-003 Repository Model
- ATLAS-SPEC-001 Entity (planned)

---

# Revision History

## Version 1.0.0

Initial release.
