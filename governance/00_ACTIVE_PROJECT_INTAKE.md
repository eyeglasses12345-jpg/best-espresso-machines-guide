# 00_ACTIVE_PROJECT_INTAKE.md

# Active Project Intake System

# Purpose

This file controls:
# project selection, project creation, and project isolation.

The purpose of this system is to ensure:
- projects never contaminate each other
- niche-specific data stays isolated
- Codex always loads the correct client/category context
- reusable governance remains stable
- production mistakes are minimized

This file must be read:
# BEFORE any production work begins.

---

# MASTER RULE

Codex must NEVER:
- assume the active project
- mix project information
- reuse taxonomy from another niche
- reuse product roles from another project
- generate pages without confirming the active project

If no active project is confirmed:
# STOP.

---

# PROJECT ARCHITECTURE

The repository contains:

```text
/governance
/templates
/projects