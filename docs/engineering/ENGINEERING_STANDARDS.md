# Engineering Standards

Version: 1.0

Status: Accepted

---

# Purpose

This document defines the engineering standards for the Northstar project.

Every contributor, including AI coding assistants, must follow these standards.

---

# Technology Stack

Frontend

- Next.js
- React
- TypeScript
- Tailwind CSS

Backend

- Next.js Route Handler
- REST API

Database

- PostgreSQL
- Prisma ORM

Deployment

- Vercel

Version Control

- GitHub

---

# Coding Principles

## Readability First

Code should be easy to understand.

Never write clever code that is difficult to maintain.

---

## Small Components

Each component should have a single responsibility.

---

## Type Safety

Avoid using "any".

Use TypeScript types whenever possible.

---

## Reusability

Avoid duplicate code.

Extract reusable logic into shared modules.

---

## Documentation

Public functions should include comments when necessary.

Complex business logic must be documented.

---

# Git Branch Strategy

main

Production-ready code.

develop

Integration branch.

feature/*

New features.

bugfix/*

Bug fixes.

hotfix/*

Emergency fixes.

---

# Commit Message Convention

feat:

New feature.

fix:

Bug fix.

docs:

Documentation.

refactor:

Code restructuring.

style:

Formatting only.

test:

Testing.

chore:

Maintenance.

---

# Pull Request Checklist

Before merging:

- Project builds successfully.
- No TypeScript errors.
- No ESLint errors.
- Documentation updated.
- Code reviewed.

---

# AI Development Rules

AI can:

- Generate code.
- Suggest refactoring.
- Improve documentation.

AI cannot:

- Merge code without review.
- Change architecture decisions.
- Remove documentation.

---

# Definition of Done

A task is completed only when:

- Code works.
- Documentation updated.
- Tests pass.
- Review completed.
