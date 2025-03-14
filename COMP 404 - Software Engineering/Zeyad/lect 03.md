Below is a structured rewrite of the third provided lecture document on Software Engineering, focusing on Requirements. The content is organized into clear sections and subsections, preserving all original information from the OCR content without any omissions or alterations. The structure enhances readability while maintaining the page-by-page details and logical flow of the document.

---

# Software Engineering Lecture Notes (Part 3: Requirements)

## Table of Contents
1. Introduction to Requirements
2. Requirements Capture
3. Understanding the Current System
4. New System Requirements
   - Functional Requirements
   - Non-Functional Requirements (NFR)
   - Usability Requirements
5. Investigating Requirements (SQIRO Techniques)
6. Documenting Requirements
7. Self-Test Question

---

## 1. Introduction to Requirements (Page 1)
- **Three Categories:**
  - Requirements Capture
  - Requirements Analysis
  - Refining the Requirements Modelling

---

## 2. Requirements Capture (Page 2)
- **Introduction:**
  - The aim of developing a new system is to:
    - Find out from users what they require in the new system.
    - Ensure it meets the users' needs.
- **How?**
  - You must:
    - Have a clear understanding of both the overall objectives of the business and what individual users are trying to achieve in their jobs.
    - Avoid defects present in the current system.

---

## 3. Understanding the Current System

### Question (Page 3)
- Do you think a detailed understanding of the current system is necessary?
- Should an understanding of the current system be part of the requirements analysis process for the new system?
- Should we consider so-called legacy systems?
- **Legacy Systems:** Old, valuable systems that must be maintained and updated.

### Answer (Page 4)
- **Two Perspectives:**
  - **Yourdon (1989):** Argues it’s a waste of time to model the current system in great detail; focus should be on the behavior required of the new system.
  - **SSADM (Structured System Analysis and Design Method):** Advocates expending considerable time investigating and modeling the current system.

### SSADM Consideration (Page 5)
- Investigating and modeling the current system to:
  - Refine it to its logical essence.
  - Merge it with new requirements to produce a model of the required system that includes essentials of the existing system.

### SSADM Benefits (Page 6)
- Some functionality of the existing system will be required in the new system.
- Some data in the existing system is valuable and must be transferred to the new system.
- The existing system may have defects to avoid in the new system.
- Studying the existing system helps understand the organization in general.

### SSADM Benefits Continued (Page 7)
- Understanding how people currently do their jobs helps characterize future users of the new system.
- Gathering baseline information allows setting and measuring performance targets for the new system.
- Parts of the existing system may be retained, or interfaces with existing systems must be established.
- Technical documentation of existing systems may provide processing algorithms needed in the new system.

### Remark (Page 8)
- From SSADM benefits, an understanding of the current system should be part of the analysis process.
- However, analysts should not lose sight of the objective: developing new system requirements.

---

## 4. New System Requirements

### Overview (Page 9)
- **Three Categories:**
  - **Functional Requirements:** Describe what a system does or is expected to do (its functionality).
  - **Non-Functional Requirements:** (Not detailed here; see Page 12).
  - **Usability Requirements:** Ensure a good match between the system, its users, and their tasks.

### Building Usability into the System (Page 10)
- Information to gather:
  - Characteristics of the users.
  - Tasks users undertake, including their goals.
  - Situational factors describing potential situations during system use.

### Usability per ISO (Page 11)
- **ISO Definition:** The degree to which specific users can achieve specific goals within a particular environment—effectively, efficiently, comfortably, and acceptably.
- **Note:** Usability can be specified with measurable objectives (Human-Computer Interaction).

### Non-Functional Requirements (NFR) (Page 12)
- **Constraints on the System:** Describe how well the system provides functional requirements, including:
  - Performance criteria (e.g., desired response times for updating or retrieving data).
  - Anticipated data volumes (throughput or storage).
  - Security considerations.

### Functional Requirements (Page 13)
- Include:
  - Descriptions of required processing.
  - Details of inputs (e.g., paper forms, documents, telephone interactions, other systems).
  - Details of expected outputs (e.g., printed documents, reports, screen displays, transfers to other systems).
  - Details of data to be held in the system.

### Requirements as an Ongoing Problem (Page 14)
- Requirements encompass everything relevant stakeholders (internal and external, e.g., users, line management, senior management) want from a system in Information Systems (IS).
- Fixing errors at the requirements stage costs 80-100 times less than at the implementation stage.

### Requirements Continued (Page 15)
- **Two Types:**
  - **Functional Requirements:** Expressed as functions or behaviors the system should perform.
  - **Non-Functional Requirements (NFR):** Constraints or qualities related to system performance, interfaces, design, and software quality attributes.
- **Example:**
  - If functional requirements are met (e.g., transactions implemented correctly) but printing (order processing) is slow (NFR issue), users may still be dissatisfied.

### NFR Categories (Page 16)
- **Russell (2004) & IBM Developer Works Categories:**
  - **Categories #1:** Observable, easy to collect, potentially measurable, easier to test.
  - **Categories #2:** Non-observable, harder to gather and test.

### NFR Categories #1 (Page 17)
- **Performance:** Responsiveness (e.g., response time).
- **Security:** Capability to prevent unauthorized use.
- **Availability:** Proportion of time the system is available.
- **Reliability:** Consistent functionality and recovery from failure.
- **Capacity:** Ability to handle resources, volume, and growth.
- **Usability:** Ease of use matching user abilities.

### NFR Categories #2 (Page 18)
- **Maintainability:** Ease of system changes.
- **Portability:** Ease of porting to alternative environments.
- **Integrity:** Preservation of transactions accurately and persistently.
- **Scalability:** Ease of handling increased volumes.
- **Manageability:** Ease of management during operation.
- **Safety:** Capability to avoid harm to users or others.
- **Efficiency:** Effective resource utilization.

### Why NFRs Are Difficult to Discover (Page 19)
- People don’t naturally think in terms of NFRs; they’re seen as developers’ concerns.
- Difficult to evaluate.
- Compete with functional requirements, often overshadowed.
- Fewer tools, techniques, and methods exist for NFRs compared to functional requirements.

### Remark (Page 20)
- NFRs are among the most difficult and expensive to correct if not identified early.
- Recommended to gather NFRs alongside functional requirements early in development.

### Differentiating NFR and Functional Requirements (Page 21)
- **Functional Requirements:** Phrased in noun-verb form (e.g., “The system prints the transaction,” “The customer credit rating is checked”).
- **NFRs:** Expressed with adverbs or adverbial clauses (e.g., “The system prints the transaction quickly,” “The system checks the credit rating securely”).

---

## 5. Investigating Requirements (SQIRO Techniques)

### How to Investigate Requirements (Page 22)
- **Five Fact-Finding Techniques (SQIRO):**
  - Background Reading
  - Interviewing
  - Observation
  - Document Sampling
  - Questionnaires
- **Note:** Sometimes referred to as SOIRO (Sampling, Questionnaires, Interviewing, Reading/Research, Observation).

### Remark (Page 23)
- SQIRO techniques studied in terms of:
  - Information gained.
  - Advantages and disadvantages.
  - Appropriate situations.

### Background Reading (Page 24)
- **Sources:** Company reports, organization charts, policy manuals, job descriptions, reports, and documentation of existing systems.
- **Advantages:**
  - Helps analysts understand the organization before meeting staff.
  - Prepares analysts for other fact-finding (e.g., knowing business objectives).
  - Existing system documentation may provide formally defined information requirements.
- **Disadvantages:**
  - Documents may not reflect reality (outdated or differing from practice).

### Background Reading (Appropriate Situations) (Page 25)
- Useful when the analyst is unfamiliar with the organization.
- Valuable in initial investigation stages.

### Interviewing (Page 26)
- **Definition:** A structured meeting between the analyst and a staff member of the organization.
- **Advantages:**
  - Produces high-quality information.
  - Allows in-depth probing of work details.
  - Can be terminated if the interviewee has nothing to say.
- **Disadvantages:**
  - Time-consuming.
  - Requires post-interview work (e.g., writing notes).
  - Conflicting information from interviewees can be hard to resolve.

### Interviewing (Appropriate Situations) (Page 27)
- Appropriate for most projects.
- Provides in-depth information about the existing system and new system requirements.

### Observation (Page 28)
- Watching people work naturally provides better job understanding than interviews.
- Allows analysts to see information used and follow processes from start to finish.
- Can be open-ended (noting what happens) or closed (using a schedule/form for specific aspects).

### Observation (Advantages) (Page 29)
- Offers first-hand experience of current system operations.
- Collects real-time data.
- Verifies information from other sources or identifies exceptions.
- Gathers baseline performance data.

### Observation (Disadvantages) (Page 30)
- People may behave differently under observation, affecting validity.
- Requires a trained, skilled observer for effectiveness.
- Ethical issues may arise with sensitive data (e.g., doctor’s surgery).

### Observation (Appropriate Situations) (Page 31)
- Essential for gathering quantitative job data.
- Best for following items through processes from start to finish.

### Document Sampling (Page 32)
- **Two Uses:**
  1. Collecting blank and completed documents during interviews/observations to determine information used and process inputs/outputs.
  2. Statistical analysis to identify data patterns (e.g., header and detail lines in order forms).

### Document Sampling Example (Agate Case Study) (Page 33)
- **Example:**
  - Date: 23rd February 2005
  - Client: Yellow Partridge, Park Road Workshops, Jewellery Quarter, Birmingham B2 3DT, U.K.
  - Campaign: Spring Collection 2005
  - Billing Currency: GBP £
  - Table:
    | Item | Curr | Amount | Rate | Billing Amount |
    |------|------|--------|------|----------------|
    | Advert preparation: photography, artwork, layout, etc. | GBP £ | 15,000.00 | 1 | 15,000.00 |
    | Placement French Vogue | EUR € | 6,500.00 | 1.47 | 4,421.77 |
    | Placement Portuguese Vogue | EUR € | 5,500.00 | 1.47 | 3,741.50 |
    | Placement US Vogue | USD $ | 17,000.00 | 1.77 | 9,604.52 |
    | **Total** | | | | **32,767.79** |
  - Note: Not a VAT invoice; a detailed VAT invoice will be provided separately.

### Document Sampling (Advantages and Disadvantages) (Page 34)
- **Advantages:**
  - Gathers quantitative data (e.g., average invoice lines).
  - Identifies error rates in paper documents.
- **Disadvantages:**
  - If the system changes dramatically, existing documents may not reflect the future.

### Document Sampling (Appropriate Situations) (Page 35)
- First type (collecting documents) is almost always appropriate; provides evidence for interviews/observations.
- Statistical approach suits large data volume processing.

### Questionnaires (Page 36)
- Series of written questions with limited reply options designed by the questionnaire creator.

### Questionnaire Types (Page 37)
- **YES/NO Questions:** Two options.
- **Multiple Choice Questions:** Factual answers with multiple options.
- **Scaled Questions:** Subjective answers with a scale.
- **Open-Ended Questions:** No fixed responses; respondents write freely.

### Example (Page 38)
- **YES/NO:** “Do you print reports from the existing system?” (Ring Yes/No).
- **Multiple Choice:** “How many new clients do you obtain in a year?” (Tick one: a) 1-10, b) 11-20, c) 21-30, d) 31+).
- **Scaled:** “How satisfied are you with the response time of the stock update?” (Ring one: 1. Very Satisfied, 2. Satisfied, 3. Dissatisfied, 4. Very Dissatisfied).
- **Open-Ended:** “What additional reports would you require from the system?”

### Questionnaires (Advantages and Disadvantages) (Page 39)
- **Advantages:**
  - Economical for large groups.
  - Well-designed results are easily analyzed (possibly by computer).
- **Disadvantages:**
  - Difficult to construct effectively.
  - No automatic follow-up/probing (though interviews can supplement).
  - Postal questionnaires have low response rates.

### Questionnaires (Appropriate Situations) (Page 40)
- Useful for large or geographically dispersed groups (e.g., companies with many branches).
- Appropriate for systems used by the public, to understand user types and usage.

### Remark (Page 41)
- First task in fact-finding: Draw up a plan outlining:
  - Information sought.
  - Techniques used.
  - Involved parties.
  - Duration of fact-finding.
- See the next Case Study Example.

### Case Study Example (Page 42)
| Objective | Technique | Subject(s) | Time Commitment |
|-----------|-----------|------------|-----------------|
| Get background on the company and advertising industry | Background Reading | Company reports, trade journals | 0.5 day |
| Establish business objectives, agree likely scope of new system, check non-UK office involvement | Interview | Two directors | 2 × 1 hour each |
| Understand roles of each department, check line management and team structure in Creative dept., agree likely interviewees | Interview | Department heads (1 account manager) | 2 × 1 hour each |
| Find out how core business operates | Interview | 1 account manager, 1 graphic designer, 1 copywriter, 1 editor | 1.5 hours each |
| Follow up development of business understanding | Observation | 2 creative staff | 0.5 day each |

### Case Study Example Continued (Page 43)
| Objective | Technique | Subject(s) | Time Commitment |
|-----------|-----------|------------|-----------------|
| Determine role of support/admin staff and relationship to core business | Interview | 2 admin staff (based on experience) | 1.5 hours each |
| Establish what records and resources are kept | Interview/Document Sampling | Filing clerk, Resource librarian | 2 × 1 hour each |
| Determine use of current computer system (functionality) | Interview | Computer manager | 2 × 1 hour |
| Establish additional requirements for new system | Interview | 2 account managers, 3 Creative Dept. staff | 3 × 1 hour each |
| Establish accounting requirements for new system | Interview | Accountant, Credit controller, 1 purchasing assistant, 1 accounts clerk | 1.5 hours each |

---

## 6. Documenting Requirements

### Overview (Page 44)
- Information systems professionals must record facts about the organization and its requirements.
- As soon as fact-gathering begins, documentation is needed.
- UML produces graphical models from different perspectives, but other documents may not fit the UML framework.

### Details (Page 45)
- Analysts need to record and store facts/requirements for retrieval.
- Paper-based documentation is ineffective.
- **How to Model and Document:**
  - Use UML (e.g., Use Case diagrams) for system models from various perspectives.
  - Use CASE tools to draw diagrammatic models.

---

## 7. Self-Test Question (Page 46)
1. **Name the five fact-finding techniques and list one advantage and one disadvantage of each.**
2. **Explain the difference between functional and non-functional requirements.**
3. **Identify functional, non-functional, and usability requirements in this description:**
   - “When operatives arrive at work, they will have to clock in. Their staff no., name, and the date and time of arrival must be recorded. The information should be available immediately to the Production Control staff. If they were recorded as sick for the previous working day, then the system should notify Production Planning. It should not take more than 10 seconds for an individual to clock in. New staff should be able to learn the system easily. Ideally, it should be so obvious that they can use it straight away. There should be no more than one error in a hundred entries.”

---

**End of Lecture Notes**

This structured version preserves all content from the original document, organized for clarity and ease of reference, without altering or omitting any details. Let me know if you'd like further refinements!