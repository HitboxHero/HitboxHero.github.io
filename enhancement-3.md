# Alex Kastigar | CS 499 ePortfolio

[Professional Self-Assessment](./index.md) | [Code Review](./code-review.md) | [Enhancement 1](./enhancement-1.md) | [Enhancement 2](./enhancement-2.md) | [Enhancement 3](./enhancement-3.md) | [Artifacts & Downloads](./artifacts.md)

---

## Enhancement 3: Databases

### Artifact Description

The artifact for this enhancement is the same **SecureRastrear** application based on my original **CS 465 full-stack project**. I continued using the same artifact because it already included MongoDB and a working Mongoose data model, which made it a strong candidate for deeper database improvements.

### Why I Included This Artifact

I chose this artifact for the database category because it gave me a practical way to improve how data is structured, validated, and tracked within a working system. Earlier enhancements focused more on the software workflow and logic of the application. This enhancement focused more directly on what happens under the surface when data is stored, updated, deleted, and retrieved over time.

### Enhancement Implemented

For this enhancement, I strengthened the incident schema, kept the incident-oriented fields more consistent, and added **audit-history tracking** for create, update, and delete actions. I also added a protected history route so change records can be retrieved later. These changes moved the application away from being just a simple CRUD project and made it feel more like a system designed for accountability and structured record management. I also improved validation and indexing so the database layer better supported the SecureRastrear use case.

### Skills Demonstrated

This enhancement demonstrated my ability to:
- improve a MongoDB schema for a more realistic operational use case
- use validation, defaults, and indexing to strengthen data handling
- design database support for record tracking and accountability
- connect backend controller logic to more structured database behavior

### Course Outcome Alignment

This enhancement most strongly supports:
- **Outcome 4**, because it shows practical use of database tools and techniques to improve the system
- **Outcome 5**, because it focuses on trustworthy data handling, protected routes, and better change tracking
- **Outcome 2**, because the enhancement had to be clearly explained even though many of the most important improvements happened behind the scenes

### Reflection

One of the biggest things I learned from this enhancement was that database improvements are often some of the most important changes in a system even when they are not the most visible. Earlier milestones changed what the application looked like and how it behaved in a more obvious way, but this milestone improved the structure and accountability of the system underneath. I also learned that storing data is only part of database design. A stronger system also needs validation, consistency, and a useful history of changes over time. The main challenge was improving the database layer while keeping the application stable and compatible with the earlier milestones.

## Artifact Access

- [Download Original Artifact](./downloads/SecureRastrear-Original-Artifact.zip)
- [Download Enhanced Artifact](./downloads/SecureRastrear-Enhanced-Artifact.zip)
- [Download Enhancement 3 Narrative](./downloads/CS-499-Milestone-4-Narrative-Kastigar.docx)
