# Pet Daycare System - Client Meeting Preparation

## Project Context
- **Client**: Pet Daycare Business
- **Date**: September 26, 2025
- **Purpose**: Pre-meeting analysis and question preparation

## Problem Statement
Based on initial interviews, the following pain points were identified:

- **Owners**: Frustrated because onboarding new employees takes at least 3 months
- **Employees**: Frustrated because the process of onboarding a new client is complicated. Each individual employee also has their own "flavour" when processing the incoming client
- **Customers**: Frustrated because the onboarding flow is difficult to follow

---

## 1. Requirements Breakdown

### 1.1 Employee Onboarding Issues

#### Current State Analysis
The owner reports that employee onboarding takes 3+ months, which is significantly longer than industry standard (2-4 weeks for similar roles). This suggests systemic issues in training processes rather than inherent job complexity.

#### Root Cause Hypothesis
Based on the problem statement, potential root causes include:
- Lack of documented procedures and training materials
- Inconsistent training approaches across different trainers
- Complex or scattered systems requiring extensive learning time
- Interdependency with client onboarding complexity

#### Specific Requirements

**REQ-E001: Training Documentation**
- Comprehensive training manual covering all core operational procedures
- Standard operating procedures (SOPs) for daily tasks
- Visual aids and quick reference guides

**REQ-E002: Process Standardization**
- Document all operational workflows
- Establish single source of truth for procedures
- Eliminate variations in how tasks are performed

**REQ-E003: Structured Training Program**
- Define 30-60 day training curriculum with clear milestones
- Week-by-week learning objectives
- Competency assessments at key intervals

**REQ-E004: System Evaluation & Simplification**
- Audit current tools and software
- Identify opportunities for consolidation
- Assess user-friendliness and learning curve

**REQ-E005: Competency Tracking System**
- Create progress tracking mechanism
- Define "onboarded" criteria objectively
- Enable managers to monitor training completion

---

### 1.2 Client Onboarding Process Issues

#### Current State Analysis
Employees report that client onboarding is complicated and inconsistent, with each employee developing their own "flavour" of the process. This indicates lack of standardization and likely contributes to both employee frustration and customer confusion.

#### Root Cause Hypothesis
The phrase "their own flavour" suggests:
- No enforced standard operating procedure
- Employees creating workarounds for a broken process
- Lack of system support forcing manual/improvised solutions
- No accountability or quality control mechanism

#### Specific Requirements

**REQ-C001: Standardized Client Intake Workflow**
- Single, documented client onboarding process
- Step-by-step procedure all employees must follow
- Defined sequence and dependencies

**REQ-C002: Client Onboarding Checklist System**
- Mandatory checklist to ensure consistency
- Track completion of required steps
- Prevent steps from being skipped

**REQ-C003: Centralized Client Information Repository**
- Single system for storing all client/pet data
- Eliminate duplicate data entry
- Easy access for all staff members

**REQ-C004: Client Intake Form Standardization**
- Uniform forms and information collection
- Clear required vs. optional fields
- Digital form submission capability

**REQ-C005: Process Training & Enforcement**
- Train all employees on standard process
- Establish accountability for following procedures
- Regular audits for compliance

---

### 1.3 Customer Experience Issues

#### Current State Analysis
Customers find the onboarding flow difficult to follow. This is likely a direct result of the process inconsistency mentioned by employees - customers experience different processes depending on which employee assists them.

#### Root Cause Hypothesis
Customer confusion stems from:
- Inconsistent communication across different employees
- Unclear expectations about required steps
- Lack of self-service visibility into process status
- Too many back-and-forth interactions

#### Specific Requirements

**REQ-U001: Clear Customer-Facing Process Documentation**
- Step-by-step guide for customers
- Set clear expectations upfront
- Timeline and requirements transparency

**REQ-U002: Streamlined Information Collection**
- Minimize number of forms/steps
- Allow completion at customer's convenience
- Pre-populate information where possible

**REQ-U003: Progress Visibility**
- Customers can see where they are in the process
- Know what's completed vs. what's pending
- Automated status updates

**REQ-U004: Consistent Communication**
- Template-based communications
- Ensure all customers receive same information
- Professional, branded materials

**REQ-U005: Self-Service Capabilities**
- Online portal for form submission
- FAQ and help resources
- Reduce need for direct staff interaction

---

## 2. Assumptions & Validation Plan

The following assumptions have been made based on the initial problem statement. Each assumption requires validation during the client meeting.

| ID | Assumption | Rationale | Validation Question | Priority |
|----|------------|-----------|---------------------|----------|
| A-001 | "Onboarding" for employees means time to full productivity, not just initial orientation | Industry standard distinguishes between orientation (days) and full onboarding (weeks) | "What does 'fully onboarded' mean to you? What can an employee do after 3 months that they couldn't do earlier?" | High |
| A-002 | The 3-month timeline is primarily due to lack of documentation and training structure, not job complexity | Similar roles typically take 2-4 weeks; excessive time suggests process issues | "Do you currently have documented procedures? How do new employees learn your processes?" | High |
| A-003 | "Client onboarding" refers to the process of registering new pet owners, not daily check-in procedures | Context suggests intake/registration rather than daily operations | "Walk me through your client onboarding process from first contact to first day of service" | High |
| A-004 | The employee "flavour" variation is significant enough to cause customer confusion | Customers notice the inconsistency, suggesting substantial variation | "Can you give me examples of how employees handle client onboarding differently?" | High |
| A-005 | Current process is primarily manual/paper-based or uses disconnected systems | Complexity and inconsistency often stem from lack of system support | "What systems or tools do you currently use for client onboarding?" | Medium |
| A-006 | The business lacks centralized documentation and SOPs | Would explain both employee training difficulty and process inconsistency | "Do you have written procedures or an operations manual?" | Medium |
| A-007 | Improving client onboarding will significantly reduce employee onboarding time | Learning a complex, inconsistent process likely contributes to long training time | "What percentage of new employee training focuses on client intake procedures?" | Medium |
| A-008 | The business is growing and onboarding is becoming a bottleneck | Otherwise, inefficiency might be tolerated | "How many new employees and new clients do you onboard monthly?" | Low |
| A-009 | Staff have attempted to create their own solutions/workarounds | "Flavour" suggests creativity in dealing with broken process | "Have employees developed their own tools or shortcuts? What do those look like?" | Low |

### Assumption Categories

**Critical Assumptions (Must Validate First):**
- A-001, A-002, A-003, A-004: Define the actual problem scope

**Important Assumptions (Validate for Solution Design):**
- A-005, A-006, A-007: Impact technical approach

**Nice-to-Know Assumptions (Provide Context):**
- A-008, A-009: Help prioritize and understand urgency

---

## 3. Questions for Client Meeting

### 3.1 Business Context & Scale

**Understanding the scope and impact:**

1. How many employees do you currently have? How many are customer-facing?
2. How many new employees do you typically onboard per year?
3. How many new clients do you onboard per month/year?
4. What's your current client capacity? Are you at capacity or growing?
5. How long has this business been operating?

### 3.2 Employee Onboarding Deep Dive

**Clarifying the 3-month problem:**

6. What does "fully onboarded" mean to you? What specific competencies or milestones define this?
7. Walk me through what a new employee does in their first week, first month, and first three months
8. Who is responsible for training new employees? Is there a dedicated trainer?
9. What do new employees struggle with most during onboarding?
10. Do you currently have any training materials, employee handbook, or documented procedures?
11. Have you tried anything to reduce the onboarding time? What worked or didn't work?
12. What systems, software, or tools do employees need to learn?

### 3.3 Client Onboarding Process Deep Dive

**Understanding the complications and inconsistencies:**

13. Walk me through your entire client onboarding process from first contact to the pet's first day at daycare
14. What information do you collect from new clients? (Forms, documents, requirements)
15. How many steps or touchpoints are involved in onboarding a client?
16. Can you give me specific examples of how different employees handle client onboarding differently? What are these "flavours"?
17. What systems or tools do you use for client onboarding? (Paper forms, spreadsheets, software, etc.)
18. How do you currently store client and pet information?
19. What are the most common bottlenecks or pain points in the current process?
20. How long does it typically take to onboard a new client from first contact to first service?

### 3.4 Customer Experience

**Understanding customer perspective:**

21. What feedback have you received from customers about the onboarding process?
22. At what point in the process do customers typically get confused or frustrated?
23. Do customers need to visit in person, or can anything be done remotely/online?
24. What causes customers to abandon the onboarding process before completing it?
25. How do customers currently communicate with you during onboarding? (Phone, email, in-person, etc.)

### 3.5 Current Systems & Tools

**Technical landscape assessment:**

26. What software or systems do you currently use? (Scheduling, billing, record-keeping, communication, etc.)
27. Are these systems integrated or do they work independently?
28. Do you have a website? If so, what functionality does it have?
29. How tech-savvy are your employees? Customers?
30. What's your budget range for potential solutions?

### 3.6 Requirements & Constraints

**Boundaries and priorities:**

31. Are there any regulatory or legal requirements for pet daycare in your area? (Vaccination records, liability waivers, etc.)
32. What would success look like for you? What's your ideal outcome?
33. If you could only fix one thing, what would have the biggest impact?
34. Are there any constraints we should be aware of? (Budget, timeline, resources, etc.)
35. Who will be involved in implementing any changes? Who are the key decision-makers?

### 3.7 Follow-Up Clarification Questions

**Questions that emerged from initial analysis:**

36. You mentioned employee onboarding takes 3 months - what percentage of that time is spent on learning client intake procedures vs. other aspects of the job?
37. When employees use their own "flavour" - have any employees developed particularly effective methods we should learn from?
38. Have you documented what the "ideal" client onboarding process should look like, even if it's not currently followed?
39. Do you track any metrics around onboarding? (Time to complete, error rates, customer satisfaction, etc.)
40. Are there seasonal variations in your workload that affect onboarding capacity?