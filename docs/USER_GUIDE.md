# User Guide

This guide provides detailed instructions for end users on how to use the application effectively.

For an overview of the project, check the main [Readme](../README.md), and if you are a developer and want to contribute to the project, review the [Development Guide](DEVELOPMENT_GUIDE.md).

## Customization

This section guides you step by step to adapt the template to any type of project, following a structured 3-phase process.

```
┌───────────┐    ┌───────────────┐    ┌────────────┐
│ Proposal  │ -> │  Planning     │ -> │ Development│
└───────────┘    └───────────────┘    └────────────┘
```

### 1. Proposal

To get started, clone the template and organize its structure following the instructions in the [Readme](../README.md). This step is key to separating the original template documentation and laying a clean foundation for your project.

Once the environment is set up, use the template documents as a reference to create your own project documentation.

Now that you have prepared the environment, it's time to conceptualize the core idea of your project. At this stage, you will focus on clearly defining the problem to solve, the solution you propose and the scope of implementation.

- **[Proposal](PROPOSAL.md)**: Create this document to define the problem you solve, the proposed solution and the project scope. It is the starting point that validates whether the idea makes sense and is worth developing.
- **[License](../LICENSE)**: Decide which license to use for your project. The template includes MIT by default, but you can change it according to your needs.

Before continuing, it is essential that the development team reviews, actively participates and approves the proposal to ensure its technical feasibility and alignment with project objectives.

### 2. Planning

Once the proposal is validated, organize the project and establish how it will be executed and success measured.

- **[Action Plan](ACTION_PLAN.md)**: Defines the phases, milestones, required resources and project schedule. Establishes how you will measure success and what criteria you will use to validate the results.
- **[Tasks](tasks/)**: Break down the work into specific and manageable tasks. Each task should have clear acceptance criteria and time estimates.
- **[Validation](VALIDATION.md)**: Define acceptance criteria and the process to verify that the results meet the objectives established in the proposal.

Continue with the rest of the template tasks. If you have followed the previous steps, the initial setup tasks will already be completed.

- **[Credits](CREDITS.md)**: Acknowledge project contributions, tools used and acknowledgements.
- **[README.md](../README.md)**: Create the main document of your project that explains what it does, how to install it and how to use it. This will be the first document users see.
- **[Code of Conduct](CODE_OF_CONDUCT.md)**: Establish behavior and coexistence standards for the project community.
- **[Security Guide](SECURITY.md)**: Define security policies, how to report vulnerabilities and response procedures.
- **[Contribution Guide](CONTRIBUTING.md)**: Define how other developers can contribute to your project, including code standards and review process.
- **[User Guide](USER_GUIDE.md)**: Document how end users should use your application or product, including practical examples and use cases.
- **[Project Structure](STRUCTURE.md)**: Document the architecture and organization of files and folders of your project.
- **[Development Guide](DEVELOPMENT_GUIDE.md)**: Establish technical standards, code conventions and development methodology for the team.

It is essential that the entire team reviews and collectively validates the action plan, including the defined tasks, success criteria and validation methodology, as well as all created documentation. This collaborative review ensures technical feasibility, confirms alignment with project objectives and guarantees commitment from all members before proceeding to the next phase.

### 3. Development

You can now start with the custom tasks you have added to the [Action Plan](ACTION_PLAN.md).

Remember that documentation is a living component of the project. Each time significant changes are made to documentation and code, it is good practice to review and update all relevant documents, to ensure that information remains accurate and useful for the entire team.

Keep the [Readme](../README.md), [Action Plan](ACTION_PLAN.md) and [Tasks](tasks/) log updated.

[Validation](VALIDATION.md) is executed when the project is completed or when releasing a stable version (release), typically in version 1.0.0. This document helps ensure that all objectives and acceptance criteria defined initially have been successfully met.

When you no longer need the template files, you can safely delete them.

## Frequently Asked Questions

**Can I use this template for any programming language?**
Yes! The template is language agnostic. Simply start adding your code to the `src/` folder.

**What do I do if I determine the project is not viable?**
If you conclude that the project is not viable, you can stop its development at any time. Use the **[Proposal](PROPOSAL.md)** document to document the analysis and decision, keeping a clear record for the team.

**In what order should I create the documents?**
Follow the 3 phases: first the Proposal, then Planning and create all documentation before Development.

**Can I skip any of the 3 phases?**
We recommend following all phases, but you can adapt the process according to the size and complexity of your project.

**What if I don't want all the documentation?**
You can delete or modify the documents you don't need. However, we recommend keeping at least `README.md`, `LICENSE` and `CONTRIBUTING.md` to have a well-documented project.

**Which documents are mandatory vs optional?**
`README.md` and `LICENSE` are essential. You can adapt the rest according to your project's needs.

**How do I report a problem or suggest an improvement for the template?**
You have several options to report problems or suggest improvements:

- **Issues**: Open an [issue](https://github.com/sergio-ridaura/project-kickstart/issues) to report bugs or request features
- **Contributions**: Check the [Contribution Guide](CONTRIBUTING.md) for the complete collaboration process
- **Vulnerabilities**: For security issues, review the [Security Document](SECURITY.md)

Thank you for using Project Kickstart! We hope it helps you build amazing projects.
