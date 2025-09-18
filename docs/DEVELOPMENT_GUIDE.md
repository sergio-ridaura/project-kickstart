# Development Guide

This guide explains how to contribute to the project development effectively, covering from initial setup to the complete workflow for developers.

For an overview of the project, check the main [Readme](../README.md), and if you want to contribute to the project, check the [Contribution Guide](CONTRIBUTING.md).

## Development Methodology

This project uses an adapted agile methodology for small teams or individual developers, focused on clarity, planning and quality. The development life cycle is divided into 4 phases.

```
┌───────────┐    ┌───────────────┐    ┌────────────┐    ┌────────────┐
│ Proposal  │ -> │  Planning     │ -> │ Development│ -> │ Validation │
└───────────┘    └───────────────┘    └────────────┘    └────────────┘
```

### 1. Proposal

Initial phase where the problem to solve is defined, a solution is proposed and the project scope is established. The objective is to validate the feasibility of an idea before investing resources in its development.

- **[Proposal](PROPOSAL.md)**: Create this document to define the problem you solve, the proposed solution and the project scope. It is the starting point that validates whether the idea makes sense and is worth developing.
- **[License](../LICENSE)**: Decide which license to use for your project.

Before continuing, it is essential that the development team reviews, actively participates and approves the proposal to ensure its technical feasibility and alignment with the project objectives.

### 2. Planning

Once the proposal is approved, the work is broken down into concrete tasks. A detailed action plan is created, acceptance criteria are defined and deadlines and resources are estimated.

- **[Action Plan](ACTION_PLAN.md)**: Defines the phases, milestones, required resources and project schedule. Establishes how you will measure success and what criteria you will use to validate the results.
- **[Tasks](tasks/)**: Break down the work into specific and manageable tasks. Each task should have clear acceptance criteria and time estimates.
- **[Validation](VALIDATION.md)**: Define acceptance criteria and the process to verify that the results meet the objectives established in the proposal.

Continue with the rest of the documents to establish development rules:

- **[Credits](CREDITS.md)**: Acknowledge contributions, tools used and project acknowledgements.
- **[README.md](../README.md)**: Create the main document of your project that explains what it does, how to install it and how to use it. This will be the first document users see.
- **[Code of Conduct](CODE_OF_CONDUCT.md)**: Establish behavior and coexistence standards for the project community.
- **[Security Guide](SECURITY.md)**: Define security policies, how to report vulnerabilities and response procedures.
- **[Contribution Guide](CONTRIBUTING.md)**: Define how other developers can contribute to your project, including code standards and review process.
- **[User Guide](USER_GUIDE.md)**: Document how end users should use your application or product, including practical examples and use cases.
- **[Project Structure](STRUCTURE.md)**: Document the architecture and organization of files and folders of your project.
- **[Development Guide](DEVELOPMENT_GUIDE.md)**: Establish technical standards, code conventions and development methodology for the team.

### 3. Development

Implementation phase where the team writes code, updates documentation and performs necessary configurations, following defined standards and plan.

Remember that documentation is a living component of the project. Each time significant changes are made to documentation and code, it is good practice to review and update all relevant documents, to ensure that information remains accurate and useful for the entire team.

Keep the [Readme](../README.md), [Action Plan](ACTION_PLAN.md) and [Tasks](tasks/) log updated.

### 4. Validation

Final stage where it is verified that the result meets all acceptance criteria and project objectives. In this phase, the results are also analyzed to learn from both successes and failures, in order to improve in future iterations. This process is performed before a major release or at the end of the project.

## Technical Standards and Guides

To ensure consistency, quality and efficiency in project development, it is essential to adhere to the standards and workflows defined in the following specialized documents. This section acts as an index and reminder of the fundamental technical guides.

- **Environment Setup:** For a quick and correct setup of your local workspace, check the **[Quick Start section of README.md](../README.md#quick-start)**. Here you will find detailed instructions to start developing.

- **Project Structure:** Understanding the internal organization of the project is key. The **[Structure Guide](STRUCTURE.md)** details the arrangement of directories, files and main components, facilitating navigation and maintenance.

- **Contribution Workflow:** The process for making contributions to the project, from branch creation to Pull Request management, is exhaustively described in the **[Contribution Guide](CONTRIBUTING.md)**. This document also covers the branch strategy, commit message conventions and review cycle.

  The `develop` branch is used by internal developers and derives from the `staging` branch. This branch is intended for more flexible and experimental development, allowing the integration of new features and initial testing before consolidation. In addition, it facilitates a comfortable working environment for communication and development in the native language.

- **Code Quality and Standards:** To maintain clean, readable and consistent code, formatting guidelines and static analysis tools (`linting`) are specified in the "Code Quality" section of the **[Contribution Guide](CONTRIBUTING.md#code-quality)**. Compliance with these is vital for integrating new features.

Rigorous adherence to these guides is a fundamental pillar for the success and sustainability of the project.

## Feedback and Improvements

This guide is a living document that evolves with the project. If you have suggestions for improving it, feel free to open an [issue](https://github.com/sergio-ridaura/project-kickstart/issues) to discuss it with the team.
