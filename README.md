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

## Why is Requirement Analysis Important?

Requirement Analysis is a **cornerstone of the Software Development Lifecycle (SDLC)** because it ensures that the final product delivers real value, meets user needs, and is built efficiently. Without a solid requirement analysis phase, projects often suffer from scope creep, misaligned expectations, delays, or costly rework.

### Key Reasons

1. **Prevents Miscommunication and Misalignment**  

   - Establishes a shared understanding between stakeholders, business analysts, developers, and testers.  
   - Reduces ambiguity by clearly defining the system’s purpose, scope, and boundaries.  

2. **Saves Time and Cost**  

   - Fixing errors during requirement analysis is significantly cheaper than fixing them after development or deployment.  
   - Clear requirements reduce rework, avoid wasted resources, and ensure smoother project execution.  

3. **Guides Design, Development, and Testing**  

   - Provides a blueprint for developers to design solutions aligned with business goals.  
   - Helps QA teams create accurate test cases and acceptance tests.  
   - Ensures that the end product is both functional and reliable.  

4. **Supports Better Project Planning and Estimation**  

   - Well-defined requirements help in estimating timelines, budgets, and resources more accurately.  
   - Facilitates prioritization, so high-value features are developed first.  

5. **Ensures User Satisfaction and Business Value**  

   - Aligns system functionality with user needs and business objectives.  
   - Reduces the risk of delivering software that fails to solve the intended problem.  

---

## Key Activities in Requirement Analysis

Requirement Analysis is not a single step but a structured process made up of multiple activities that ensure the system requirements are **complete, accurate, and aligned** with stakeholder needs. The five key activities are:

- **Requirement Gathering**  

  - Collecting raw information about user needs, business goals, and constraints.  
  - Sources include stakeholders, existing systems, regulations, and market research.  
  - This forms the foundation for further analysis.  

- **Requirement Elicitation**  

  - Actively engaging with stakeholders to uncover detailed needs and expectations.  
  - Techniques: interviews, workshops, surveys, brainstorming sessions, prototyping, and observation.  
  - Helps clarify hidden or implicit requirements.  

- **Requirement Documentation**  

  - Translating gathered and elicited requirements into clear, structured documents.  
  - Outputs: Software Requirement Specification (SRS), Business Requirement Document (BRD), user stories, and use cases.  
  - Ensures requirements are traceable and easy to communicate across the team.  

- **Requirement Analysis and Modeling**  

  - Examining requirements to detect conflicts, redundancies, or gaps.  
  - Creating visual models (use case diagrams, data flow diagrams, UML models) to represent interactions and workflows.  
  - Helps both technical and non-technical stakeholders understand the system.  

- **Requirement Validation**  

  - Confirming that requirements are correct, complete, feasible, and testable.  
  - Techniques: reviews, walkthroughs, prototyping, and stakeholder sign-off.  
  - Ensures requirements truly reflect business objectives and user expectations.  

---

## Types of Requirements

### Functional Requirements

- The system shall allow users to search available rooms.
- The system shall allow users to book, modify, or cancel reservations.

### Non-Functional Requirements

- The system shall return search results within 2 seconds.
- The system shall maintain 99.9% uptime.

---

## Use Case Diagrams

**Use Case Diagrams** are a visual representation of the interactions between **actors** (users or external systems) and the system itself. They help in understanding **what the system should do** from the user’s perspective and provide a high-level overview of functional requirements.

### Benefits of Use Case Diagrams

- **Clarifies system scope:** Shows all major functionalities and their users.  
- **Improves communication:** Provides an easy-to-understand diagram for both technical and non-technical stakeholders.  
- **Supports documentation:** Helps in creating detailed use cases, test scenarios, and acceptance criteria.  
- **Identifies missing requirements:** Reveals gaps or overlaps in system functionality.

### Example: Booking Management System

**Actors:**  

- **User:** Can search, book, modify, or cancel reservations.  
- **Administrator:** Can manage room listings, monitor bookings, and generate reports.  
- **Payment Gateway:** Processes user payments securely.

**Use Cases:**  

- Search available rooms  
- Make a booking  
- Modify/cancel booking  
- Register/login  
- Receive booking confirmation  
- Manage room listings (admin)  
- Process payments  

### Diagram

Below is the use case diagram for the Booking Management System:  

![Booking Management System Use Case Diagram](alx-booking-uc.png)

---

## Acceptance Criteria

**Acceptance Criteria** are a set of predefined conditions or requirements that a software feature must satisfy to be considered complete and accepted by stakeholders. They act as a bridge between **requirements** and **testing**, ensuring that the system delivers what was agreed upon.  

### Importance in Requirement Analysis

- **Validates functionality:** Confirms that the feature works as intended.  
- **Provides clarity:** Sets clear expectations for developers, testers, and stakeholders.  
- **Facilitates testing:** Helps QA teams create accurate test cases.  
- **Reduces ambiguity:** Prevents misinterpretation of requirements.  
- **Supports prioritization:** Helps identify critical vs. optional conditions.  

### Example: Checkout Feature (Booking Management System)

**Feature:** Booking Checkout  

**Acceptance Criteria:**  

1. Given a user has selected a room and entered personal details, when the user clicks **Checkout**, then the system shall display a summary of the booking including room details, dates, and total cost.  
2. Given valid payment details, when the user confirms the payment, then the system shall process the payment and display a confirmation message.  
3. Given an invalid payment method, when the user attempts to pay, then the system shall display an error message without completing the booking.  
4. Given successful payment, the system shall send a confirmation email and SMS to the user within 5 minutes.  
5. The system shall prevent duplicate bookings for the same room and time slot.  

---