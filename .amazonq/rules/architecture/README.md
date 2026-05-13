# Architecture Overview

## Full Architecture Guide

Complete architecture documentation: `docs/dev/architecture.md`

This is an example folder to show AI-consumable rule extracts focused on enforcement and guidance.

---

## Rule Files

### CRITICAL Rules

**critical-example.md**
- Bullets that distill and explain the purpose of rules in the file

### IMPORTANT Rules

**important-example.md**
- Bullets that distill and explain the purpose of rules in the file

### GUIDANCE

**guidance-example.md**
- Bullets that distill and explain the purpose of rules in the file


---

## Example Architecture - NOTES

Rules, notes and guidelines on architecture in use


---

## Key Architectural Principles

1. **Domains are first-class** — each domain is a top-level folder in `src/`
2. **UI layers are explicit** — pages, components, global UI, and domain UI are separate
3. **Folders and packages exist only when they earn their existence** — no unnecessary hierarchy

---

## Quick Reference

### <Category> Domain Structure
```
DomainName/
    DomainFile1.ts          — REQUIRED  #Where File1 is something the domain needs
    DomainTypes.ts          — REQUIRED  #Any Objects, constants or types used by the domain
    __tests__/              — REQUIRED  #tests live close to the code when possible, depending on language
```

List other Domain Categories, and folder structures with `###` header blocks

---

## Special Folders

### Read-Only
- list archive and generated folder paths with a description

Use `###` Header Blocks and bullet list any other folders with special names, with a description
