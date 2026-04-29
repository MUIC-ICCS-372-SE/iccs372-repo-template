# Project Brief

The project brief is your team’s first structured proposal for the system you plan to build. It should show that your team understands the case, can define a realistic MVP, and can justify early scope and technical decisions.

Keep the brief focused and practical. It does not need to be a complete design document, but it should be clear enough that another person can understand what problem you are solving, who the system is for, what your team plans to build, and what you are intentionally not building.

Recommended length: **about 3 pages, A4 format**.\
Use the topics below to write your Project Brief Document.

---

## 1. Problem Statement

Describe the core problem your system is trying to solve.

Your answer should explain:
- what is currently happening in the case
- who is affected by the problem
- what pain points or inefficiencies exist
- why the problem is worth solving

Focus on the real situation described in the case brief. Do not jump directly into features before explaining the problem.

---

## 2. Stakeholders and User Roles

Identify the key stakeholders and user roles for your system.

For each role, briefly explain:
- who they are
- what they need from the system
- how the current problem affects them

Example format:

- **Customer** — someone who submits a request, booking, inquiry, or order.
- **Staff** — someone who reviews, updates, or manages requests.
- **Owner/Manager** — someone who wants clearer operations and better visibility.

You do not need many roles. Choose the roles that matter most for your MVP.

---

## 3. User Needs

Describe the main needs your system should address.

These should connect directly to the problem statement and user roles.

For example:
- Customers need a clearer way to submit requests.
- Staff need a single place to review and update request status.
- The owner needs better visibility into active work.

Keep this section short and focused. Avoid listing every possible wish.

---

## 4. MVP Scope / In-Scope Functionality

List the high-level functionality your team plans to deliver in the MVP.

Each item should be realistic within the project timeline and should later connect to one or more user stories.

Focus on the core workflow first. For example:
- submit a request
- view request details
- update request status
- store records persistently
- view a basic list or dashboard

Do not overpromise. A small, working, well-explained MVP is better than a large unfinished system.

---

## 5. Out-of-Scope Functionality

List features, integrations, or complexities your team will intentionally not build.

This section is important because it prevents scope creep and shows that your team understands the limits of the project.

Examples:
- real payment gateway integration
- advanced analytics
- native mobile app
- complex scheduling optimization
- full commercial deployment
- automated final decision-making by AI

Your out-of-scope items should make sense for your chosen case.

---

## 6. Assumptions

List the assumptions your team is making at the start of the project.

Assumptions are things you believe to be true for planning purposes, but which would normally need to be clarified with the client in a real project.

Examples:
- Users have internet access.
- Staff can use a simple web-based interface.
- The MVP can use mock data.
- External integrations can be mocked.
- The system only needs to support a small number of users for demo purposes.

Be honest. If an assumption turns out to be wrong, it may affect your scope, timeline, or design.

---

## 7. Constraints

Identify constraints that limit your project.

Constraints may include:
- time available
- team size and skill level
- technology familiarity
- lack of real client data
- need to keep the system simple
- limited deployment or hosting options
- course requirements

Explain how these constraints affect your MVP decisions.

---

## 8. Risks

Identify risks that could affect your project delivery or the usefulness of the system.

For each risk, briefly explain:
- what might go wrong
- why it matters
- how your team may reduce or manage the risk

Example format:

| Risk | Why it matters | Possible mitigation |
|---|---|---|
| Team overscopes the MVP | The system may not be finished | Prioritize one core workflow first |
| AI output is unreliable | Staff may not trust the system | Require human review before action |
| Database design changes late | Rework may delay implementation | Start with a simple data model |

You do not need a long risk list. Focus on the most important risks.

---

## 9. Success Criteria / Definition of “Valuable”

Define what a successful first version looks like.

Your success criteria should connect back to the problem statement. They should describe the value your MVP provides to users or stakeholders.

Good success criteria are specific enough to judge.

Examples:
- Customers can submit a request with the required information.
- Staff can view and update request status from one place.
- Important records are stored and can be retrieved later.
- The system reduces confusion compared with the current manual process.
- The demo shows one complete core workflow end to end.

---

## 10. Initial Technical Direction

Briefly describe the technical direction your team currently plans to take.

Include:
- type of system, for example web app, API + front end, mobile-friendly web app
- front-end technology
- back-end technology
- database or storage choice
- demo or hosting approach
- any major libraries, frameworks, or tools

If your case includes an AI-assisted element, also include:
- AI/chatbot approach
- what information the AI is allowed to use
- what AI outputs are stored or reviewed
- where human review is required

These choices do not need to be final, but they should be realistic for your team and suitable for the MVP. If your team later changes a major technical choice, explain the reason in an ADR.