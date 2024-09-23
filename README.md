# Agile Principles and Mindset

## Introduction

Agile is a mindset that focuses on delivering products to customers in the required time with the best quality. It's not just a methodology, but a way of thinking that should be adopted by everyone in the team.

## Working in an Agile Environment

When we say we work in an Agile environment or with an Agile approach, we're referring to a specific set of principles and practices that guide our work.

## The Role of an Agile Coach

An Agile coach, often certified in Agile methodologies, is the best person to explain and implement Agile practices. In many cases, the Scrum Master serves as the Agile coach for the team.

## Work Agreement and Agile Principles

Before starting work together, teams often establish a work agreement that includes key Agile principles. These principles should be applied throughout the project:

### 1. Commitment

When a team lead assigns a task, team members should commit to completing it. This principle ensures reliability and builds trust within the team.

### 2. Courage

```mermaid
graph TD
    A[Courage] --> B[Take Risks]
    A --> C[Try New Things]
    A --> D[Choose Challenging Tasks]
    B --> E[Growth and Innovation]
    C --> E
    D --> E
```

Courage in Agile means:
- Being willing to take risks
- Not always choosing the easiest path
- Having the bravery to work on new and challenging tasks
- Stepping out of your comfort zone to learn and grow

### 3. Focus

Focus is crucial throughout the project lifecycle:

- Start by thoroughly reading and understanding the Software Requirements Specification (SRS)
- Maintain focus during implementation to meet all business requirements
- Pay attention to each step, practicing separation of concerns
- Invest time in reading documentation and learning new technologies

> "Minutes spent reading documentation are better than hours spent not knowing how to implement."

### 4. Openness

```mermaid
graph TD
    A[Openness] --> B[Accept Others' Opinions]
    A --> C[Listen to Feedback]
    A --> D[Share Ideas]
    B --> E[Collaborative Environment]
    C --> E
    D --> E
```

An open mindset involves:
- Accepting and considering others' opinions
- Being receptive to feedback
- Sharing your own ideas freely

### 5. Respect

Respect is a fundamental principle in Agile and should be the default behavior for all team members. It fosters a positive work environment and enhances collaboration.

## Conclusion

Adopting these Agile principles helps teams deliver high-quality products efficiently. Remember, Agile is not just about following a set of rules, but about embracing a mindset that values flexibility, collaboration, and continuous improvement.


## Common Agile Myths

There are several myths about Agile that need to be addressed:

1. **Customers know exactly what they want**: While customers know their business, they may not always know the exact details of what they need in a software solution.

2. **Developers know exactly what they're building**: Developers may have a good understanding of the technical aspects, but may not always grasp all the business implications.

3. **Nothing will change along the way**: Change is inevitable in most projects. The Agile approach helps create projects that can accept change requests at any time without causing major problems.

## Agile Process: IRKIWIEI

IRKIWIEI stands for "I'll Really Know It When I Experience It". This concept is central to the Agile approach, emphasizing the importance of iterative development and feedback.

## Project Lifecycle

In an Agile project, we divide the work into modules and services. Each service goes through four main processes:

1. **Development (DEV)**
2. **Quality Assurance/Quality Control (QA/QC)**
3. **Staging/User Acceptance Testing (UAT)**
4. **Production (PROD)**

```mermaid
graph LR
    A[Development] --> B[QA/QC]
    B --> C[Staging/UAT]
    C --> D[Production]
    D --> A
```

### Detailed Workflow

1. **Business Requirements**:
   - Business consultants document requirements in SRS (Software Requirements Specification) or RD (Requirements Document).
   - This document is delivered to development and testing teams.

2. **Development**:
   - Frontend and backend developers start working on implementation.
   - Testers begin writing test cases based on business requirements.

3. **Testing**:
   - Developers deploy the service to the testing server.
   - Testers execute test cases (manually or through automation).

4. **Smoke Testing**:
   - Developers create a "smoke" work item to indicate a service is ready for testing.
   - This is managed through platforms like Azure DevOps or Jira.

5. **Bug Tracking and Fixing**:
   - Testers create bug work items for issues found.
   - Developers fix bugs and redeploy.
   - Critical bugs may stop the smoke testing process.

6. **Staging and UAT**:
   - Service is deployed to the staging server.
   - Business consultants demonstrate the service to the customer.
   - Customer provides feedback (UAT comments or Change Requests).

7. **Production**:
   - If everything is approved, the service goes live in production.

## Tools and Platforms

- Azure DevOps or Jira are commonly used for managing Agile workflows.
- These platforms allow creation of work items like tasks, bugs, and smoke tests.
- They facilitate communication between team members and track project progress.

## Conclusion

The Agile approach, with its iterative processes and emphasis on communication, helps teams navigate the complexities of software development. It acknowledges that requirements may change and encourages adaptability throughout the project lifecycle.
