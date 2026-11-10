# Harini – Intern 4 | Stage 1 Technical Architecture

**Module:** Submissions, Judging and Organizer Operations  
**Status:** Stage 1 individual architecture draft  
**Owner:** Harini (Intern 4)

## Purpose
This folder documents the proposed architecture for Intern 4's module before implementation. It covers project submissions, judge assignments, evaluation criteria, evaluations, scoring and leaderboard generation.

> **Important:** This is an independently prepared draft. Shared identifiers, authentication conventions, final endpoint paths and integration details must be confirmed when the team is available. The proposed names and structures below are not represented as already-approved project standards.

## Contents
- `database-design.md` – proposed entities, fields, constraints and relationships
- `erd.mmd` – Mermaid ER diagram
- `api-contracts.md` – proposed API endpoints, request/response examples and access expectations
- `judging-and-scoring.md` – proposed evaluation workflow and scoring rules
- `submission-workflow.md` – submission lifecycle, validation and file-handling considerations
- `integration-assumptions.md` – independent assumptions and items to confirm later
- `stage1-checklist.md` – completion checklist for Stage 1

## Technology alignment
The project plan identifies Next.js/TypeScript/Tailwind CSS for the frontend and Python FastAPI, SQLite, SQLAlchemy and Alembic for the backend/database. This package is design documentation; it does not claim that the implementation has been completed.

## Suggested GitHub location
Place this folder in the shared repository, for example:

`docs/intern-4-stage-1/`

Suggested commit message:

`docs(intern-4): add stage 1 submissions and judging architecture`
