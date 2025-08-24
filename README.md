# Requirement Analysis in Software Development

## Introduction

This repository documents the **Requirement Analysis** phase for a booking management system.  
The goal is to provide a comprehensive foundation for software development by analyzing, documenting, and structuring requirements.  

It simulates a real-world project environment and emphasizes clarity, precision, and structure in defining requirements.  
Through this repository, you will find detailed documentation, diagrams, and acceptance criteria, all following industry-standard practices.  

## Project Objective

- Understand and apply requirement analysis methodologies in the Software Development Lifecycle (SDLC).  
- Identify and document **functional** and **non-functional** requirements.  
- Create visual representations (use case diagrams, requirement models).  
- Define clear acceptance criteria for project success.  

## Repository Structure

- `README.md` → Introduction and project overview  
- `/diagrams` → Visual diagrams created using Draw.io (or similar tools)  
- `/docs` → Detailed requirement documentation  
- `/use-cases` → Use case definitions and acceptance criteria  

---

This project is part of the **Requirement Analysis Learning Project**, focusing on a **Booking Management System**.

## What is Requirement Analysis?

**Requirement Analysis** is the structured process of discovering, clarifying, documenting, and validating what a software system must do and how well it must do it. It translates business needs into clear, testable, and prioritized requirements that guide design, implementation, and testing. In short, it bridges the gap between a **business problem** and a **technical solution**.

### Why it matters in the SDLC

- **Sets the foundation:** Informs architecture, design, estimations, and planning.
- **Prevents scope creep:** Establishes clear boundaries and priorities.
- **Reduces rework & cost:** Finds ambiguities and conflicts early when they are cheaper to fix.
- **Aligns stakeholders:** Creates a shared understanding of goals and success criteria.
- **Enables verification:** Produces testable acceptance criteria for QA and UAT.
- **Supports compliance & governance:** Improves traceability from business goals to delivered features.

### Core activities

1. **Elicitation:** Gather inputs via interviews, workshops, observation, surveys, document reviews.
2. **Analysis & Modeling:** Resolve conflicts, clarify assumptions, and model flows (e.g., use cases, activity diagrams).
3. **Specification:** Document requirements (e.g., SRS/BRD, user stories) clearly and unambiguously.
4. **Validation & Verification:** Check correctness with stakeholders and testability with QA.
5. **Prioritization:** Rank requirements (e.g., MoSCoW) to focus on highest value first.
6. **Management & Traceability:** Versioning, change control, and linking requirements to design, code, and tests.

### Types of requirements

- **Functional Requirements:** What the system should do (features, behaviors, workflows).
- **Non-Functional Requirements (Quality Attributes):** How well it should perform (performance, security, reliability, usability, scalability).
- **Constraints & Assumptions:** Technical, regulatory, budget, or timeline limitations and known assumptions.

### Good requirement qualities

- **Clear & unambiguous**
- **Testable & measurable**
- **Atomic (one idea per requirement)**
- **Consistent & feasible**
- **Prioritized & traceable**

### Common techniques & tools

- **Techniques:** Interviews, workshops, shadowing, surveys, prototyping, wireframes, use cases, user stories, UML/BPMN.
- **Tools:** Draw.io/diagrams.net, Jira/Linear, Confluence/Notion, GitHub for versioned documentation.

### Key deliverables

- Requirement documents (SRS/BRD), **use case diagrams**, user stories with **acceptance criteria**, glossary, and a **requirements traceability matrix (RTM)**.

### Mini example (Booking Management System)

- **Functional:** “The system shall allow a user to search available rooms by date range, location, and capacity.”
- **Non-Functional:** “Search results shall return within **2 seconds** for 95% of requests under normal load.”
- **Acceptance Criteria (sample):**
  - Given valid dates and location, when the user clicks **Search**, then only rooms available in that period are listed.
  - When no rooms are available, the system displays a clear ‘No availability’ message and suggests alternative dates.

