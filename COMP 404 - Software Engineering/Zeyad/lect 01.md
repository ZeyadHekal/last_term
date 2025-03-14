Below is a structured rewrite of the provided lecture document on Software Engineering. The content is organized into clear sections and subsections, preserving all original information from the OCR content without any omissions or alterations. The structure follows the natural flow of the document, including page-by-page details, while enhancing readability with consistent formatting.

---

# Software Engineering Lecture Notes

## Table of Contents
1. Course Objectives
2. Software Engineering Concepts (Terminology)
3. Software Types
4. What is Software Engineering (SE)?
5. Why Software Engineering?
6. Software Engineering and Other Related Fields
7. Additional Topics
   - Attributes of Good Software
   - Key Challenges Facing Software Engineering
   - Accessibility, Usability, and User Experience
   - System Usability Scale (SUS)
   - Why Projects Fail
   - Software Engineering Goals
   - UML (Unified Modeling Language)
   - Self-Test Question and Activity

---

## 1. Course Objectives
**How to use Software Engineering concepts in order to:**
- Produce software products that satisfy the user's needs and meet their goals (budget, deadline, quality).
- Improve the quality of a software development effort.

**How? By:**
- Addressing problems in information systems development.
- Studying and understanding the software engineering process and different process models (Software Life Cycle).
- Studying the fundamental theories and techniques of software development methodologies.
- Developing a system design using UML notation.
- Studying tools and techniques for:
  - System Analysis and Design
  - Requirement specifications
  - Software metrics and planning
- Learning how to elicit requirements from a client and specify them.

---

## 2. Software Engineering Concepts (Terminology)

### Basic Terminology (Pages 4-5)
- **What is Software?**
  - Computer program codes and associated libraries and documentation.
- **What is Engineering?**
  - Developing products using well-defined, scientific principles, tools, and methods to find cost-effective solutions to problems.
- **What is Software Engineering?**
  - An engineering discipline concerned with all aspects of software products.
- **What is an Information System (IS)?**
  - An umbrella term for systems, people, and processes designed to create, store, manipulate, distribute, and disseminate information.
  - **Note:** All software need not be information system software, but information systems are always implemented as software.
  - **Example:** 
    - Anti-virus software is not an information system.
    - Company employee payroll systems and employee master files are information systems that let you access data.

### What is Software? (Page 6)
- Computer programs and associated documentation.
- Software products may be:
  - **Generic:** Developed to be sold to a range of different customers (e.g., word processing, drawing packages, anti-virus programs).
  - **Customized:** Developed for a particular customer according to their specifications (e.g., air traffic control software for an airport).

### What is Software Process? (Page 9)
- A set of activities whose goal is the development or evaluation of software.

### What is Software Process Model? (Page 9)
- A simplified representation of a software process.

### What are the Costs of Software Engineering? (Page 9)
- In most cases:
  - 60% of costs are for development.
  - 40% of costs are for testing.

---

## 3. Software Types

### Software Types (Page 7)
- **System Software:**
  - Software that acts as tools to help construct or support application software (e.g., compilers, operating systems).
- **Application Software:**
  - Software that helps perform directly useful tasks (e.g., games, ATM software, control software in an airplane, word processors).

### Application Software Categories (Page 8)
- Games
- Information Systems (e.g., airline seat reservation system)
- Real-time Systems (e.g., mobile phone software)
- Office Software (e.g., spreadsheets, email)
- Scientific Software (e.g., calculations, predictions, weather forecasting)

---

## 4. What is Software Engineering (SE)?

### Definition 1 (Page 10)
- Software Engineering (SE) is an engineering branch related to the evolution of software products using systematic, well-defined scientific principles, techniques, and procedures.
- Result: An effective and reliable software product.

### Definition 2 (Page 11)
- The methods, tools, and techniques used for developing software are called Software Engineering (SE).
- SE is an engineering discipline focused on developing cheaper, better, and faster software products (concerned with all aspects of software production).
- Software engineers are concerned with developing software products.
- SE involves:
  - **Modelling Activity**
  - **Problem-Solving Activity:** Formulate the problem, analyze it, search for solutions, choose the appropriate one, and specify it.
  - **Knowledge Acquisition Activity:** Collect data, organize it into information, and formalize it into knowledge.
- **Note:** An activity is a set of tasks performed toward a specific purpose.

---

## 5. Why Software Engineering?

### Software Engineers Should (Page 12)
- **Analyst & Programmer = Software Engineer**
- Adopt a systematic and organized approach to their work.
- Use appropriate tools and techniques depending on:
  - The problem to be solved.
  - The development constraints.
  - The resources available.

### Why is Software Engineering Required? (Page 13)
- To manage large software.
- For more scalability.
- Cost management.
- To manage the dynamic nature of software.
- For better quality management.

### Why Use Software Engineering? (Pages 14-17)
- **Reason 1 (Page 14):**
  - Complex and large-scale software is made by teams, not individuals.
  - Software engineering is about teams participating in solving complex or large problems that a single developer cannot solve alone.
  - Teams include developers, testers, architects, system engineers, customers, project managers, etc.
  - Software projects can be so large that careful planning is required.
- **Reason 2 (Page 15):**
  - Implementation is not just writing code but also:
    - Following guidelines.
    - Writing documentation.
    - Writing unit tests.
  - Finishing coding does not mean the project is complete:
    - For large projects, maintaining software can keep many people busy for a long time.
  - Need to learn about project management and its drawbacks.
- **Reason 3 (Page 16):**
  - Teaches us to see the big picture (patterns), providing a higher level of abstraction.
  - A fantastic way to learn from seniors, essential for designing large software systems.
  - Good software engineers need tools, and we must know about them.
- **Reason 4 (Page 17):**
  - Produces high-quality software systems.
  - **Complexity:** Many sources, but size is key:
    - UNIX contains 4 million lines of code.
    - Windows 2000 contains 10⁸ lines of code.
  - Software engineering is about managing this complexity.

### Importance of Software Engineering (Page 18)
- Reduced complexity.
- Minimize software cost.
- Decrease time.
- Handling big projects.

---

## 6. Software Engineering and Other Related Fields

### Software Reliability & Effectiveness (Page 19)
- **Software Reliability:** The probability that the software will execute for a particular period without failure.
- **Effectiveness:** Getting the desired results/doing the right thing.

### IS Design (Page 20)
- **IS Analysis & Design (ISAD):**
  - Software System Development Methodology (SSDM) (IS Development).
  - Involves:
    - Software Engineering
    - Project Management
    - Human-Computer Interaction
    - Total Quality Assurance
  - Goals:
    - High-quality software product.
    - Deliver the project on schedule.
    - Within budget.
    - Meets user requirements.

### Difference Between Software Engineering and System Engineering (Page 21)
- **System Engineering:**
  - Concerned with all aspects of computer-based systems development, including:
    - Hardware
    - Software
    - Process engineering
  - System engineers are involved in:
    - System specification
    - Architectural design
    - Integration and deployment
- **Software Engineering:**
  - Part of system engineering.
  - Concerned with developing the software infrastructure, control, applications, and databases in the system.

---

## 7. Additional Topics

### Attributes of Good Software

#### Overview (Page 22)
- The software should deliver the required functionality and performance to the user and should be:
  - Maintainable
  - Dependable
  - Usable

#### Detailed Attributes (Page 23)
- **Maintainability:** Software must evolve to meet changing needs.
- **Dependability:** Software must be trustworthy.
- **Efficiency:** Software should not waste system resources.
- **Usability:** Software must be usable by the users for whom it was designed (i.e., easy to use).

### Key Challenges Facing Software Engineering

#### Overview (Page 22)
- Coming with increasing diversity.
- Demands for reduced delivery times.

#### 21st Century Challenges (Page 30)
- **Legacy Systems:** Old, valuable systems must be maintained and updated.
- **Heterogeneity:** Systems are distributed and include a mix of hardware and software.
- **Delivery:** Increasing pressure for faster delivery of software.

### Accessibility, Usability, and User Experience

#### Definitions (Page 24)
- **User Experience:** The degree of satisfaction the end user has with the system or service after using it.
- **Accessibility:** The system is available and can be easily accessed by a normal person or even a disabled person.
- **Usability:** The product is easy to use.
- **Usability Testing:** Focuses on measuring the ease at which a system can be used.

#### Accessibility (Page 25)
- The condition that environments, services, processes, and objects must meet, being understandable and usable by the broadest range of people, regardless of their capabilities.

#### User Experience (Page 26)
- Meaningful and valuable when a product, service, or system is:
  - Useful (original content that satisfies a need).
  - Usable (easy to use).
  - Desirable (produces positive emotions via image, identity, brand, and design).
  - Locatable (accessible to people with disabilities).
  - Credible (users have confidence in the product).
  - Valuable (generates added value).

### System Usability Scale (SUS)

#### Overview (Page 27)
- The SUS questionnaire contains 10 questions about:
  - Ease of learning
  - Efficiency
  - Ease of memorization
  - Occurrence of execution errors
  - Level of satisfaction
- Each question uses a five-point scale (1 = totally disagree, 5 = totally agree).
- SUS provides a score from 0 to 100:
  - 85 or higher = exceptional usability.
  - Below 70 = unacceptable usability.

#### Detailed SUS Metrics (Page 28)
- **Efficiency:** How fast the user can accomplish a task after learning the interface.
- **Ease of Memorization:** How easily a user can re-establish competence after a period of no use.
- **Minimization of Errors:** Level of seriousness of mistakes and ease of recovery.
- **Satisfaction:** How pleasant the interface is to use.
- **Ease of Learning:** How easy it is to perform simple tasks the first time.

#### SUS Questions (Page 29)
1. I needed to learn a lot of things before I could get going with this system.
2. I felt very confident using the system.
3. I found the system very cumbersome to use.
4. I would imagine that most people would learn to use this system very quickly.
5. I thought there was too much inconsistency in this system.
6. I found the various functions in this system were well integrated.
7. I think that I would need the support of a technical person to be able to use this system.
8. I thought the system was easy to use.
9. I found the system unnecessarily complex.
10. I think that I would like to use this system frequently.

### Why Projects Fail?

#### Statistics (Page 31)
- 42% of all corporate IS projects were abandoned before completion.
- 53% of all U.S. government IS projects were abandoned.
- Many systems that aren’t abandoned are:
  - Delivered significantly late.
  - Cost far more than planned.
  - Have fewer features than originally planned.
- Generally, over 50% of projects are either canceled or over 100% late.
- Even Microsoft has a history of failures and overdue projects (e.g., Windows 1.0, Windows 95).

#### Causes of Failure (Page 32)
- Unrealistic schedules.
- Inappropriate staffing.
- Changing requirements.
- Poor quality work.

#### Flynn Approach to IS Project Failures (Page 33)
- **Two Types:**
  - **Quality Problems:**
    - Quality means fitness for purpose or meeting all user requirements.
  - **Productivity Problems:**
    - Will the product be delivered?
    - Will it be delivered in time to be useful?
    - Will it be affordable?
- **Flynn Suggestion:** (Not detailed in the document)

#### Quality Problem Reasons (Page 34)
- The wrong problem is addressed (no clear requirements).
- Wider influences are neglected (e.g., organizational culture).
- Analysis is carried out incorrectly (poor skilled team).
- Project undertaken for the wrong reason.

#### Productivity Problem Reasons (Page 35)
- Users change their minds (requirements).
- External events change the environment.
- Implementation is not feasible (too late).
- Poor project control (poor managers).

### Software Engineering (SE) Goals

#### Primary Goals (Page 36)
- Meeting user’s needs (Requirements analysis or requirements engineering):
  - Find out what the customer or user needs.
  - Establish clearly what the user wants.
- Low cost of production.
- High performance (efficiency).

#### Continued Goals (Page 37)
- **Portability:**
  - Transferring the software product from one type of computer to another with minimum effort.
- **Low Cost of Maintenance:**
  - Any effort put into software after it has been written and put into operation.
  - **Maintenance Types:**
    - **Remedial Maintenance:** Fixing bugs (correcting faults in the software).
    - **Adaptive Maintenance:** Altering software due to changed user needs, computer, OS, or programming language.
  - Maintenance is a consequence of inadequate testing.

#### Continued Goals (Page 38)
- **Delivery on Time.**
- **High Reliability:**
  - Software works and continues to work without crashing or doing something undesirable.
  - **Bug Types:**
    - **Error:** A wrong decision made during software development.
    - **Fault:** A problem that may cause software to depart from its intended behavior.
    - **Failure:** An event when software departs from its intended behavior.
    - **Relationship:** An error causes one or more faults; a fault can cause one or more failures.

#### Maintenance vs. Reliability (Page 39)
- (Content appears incomplete in the original document, filled with repeated "α" symbols.)

### Software Engineering Blueprints (Page 40)
- Specifying software problems and solutions is like cartoon strip writing.
- Most of us are not artists, so we use UML symbols instead.

### UML (Unified Modeling Language)

#### Introduction (Page 41)
- Teams need a language to communicate effectively (UML).
- Previous courses taught languages like Java or C++ to turn ideas into code, but ideas are independent of language.
- UML describes code independently of language and teaches thinking at a higher level of abstraction.
- UML is an invaluable communication and documentation tool.

#### System Components (Page 42)
- **Actors:** Agents external to the system that interact with it.
- **Concepts/Objects:** Agents working inside the system to make it function.
- **Use Cases:** Scenarios for using the system.

### Self-Test Question (Page 43)
- Flynn categorizes project failures into productivity and quality problems. Indicate which type applies to each reason:
  a) The user changes the requirements → **Productivity**
  b) The wrong problem is addressed → **Quality**
  c) Analysis is carried out incorrectly → **Quality**
  d) Poor project control → **Productivity**
  e) Implementation is not feasible → **Productivity**

### Activity #1 (Page 44)
- (No further details provided in the document.)

---

**End of Lecture Notes**

This structured version retains all content from the original document, organized for clarity and ease of reference, without altering or omitting any details. Let me know if you'd like further refinements!